# SOPPG run manifests

A run manifest is the receipt for one bounded SOPPG production or evaluation run. It records what was used, what was produced, the model and runtime details that are known, and where each artifact came from. Each `plog` is intended as a mostly one-time, singular record, so the scheme does not require artifact hashing. The manifest is metadata about the run; the original logs, prompts, reports, and conversation captures remain their own files.

## Layout

```text
manifests/
  README.md
  runs.yaml                 # small index of run IDs and manifest paths
  template.yaml             # copy for each new run
  plog0001.yaml             # legacy run receipt
  plog0002.yaml             # legacy run receipt
logs/
  plog0001/
    process-log.md
    process-report.md
    conversation.md
    conversation-report.md
  plog0002/
    process-log.md
    gem-log.md             # optional
    conversation.md
    conversation-report.md
DeployedPrompts/             # flat: one final prompt product per run
```

Keep one directory per run under `logs/`. Use role-based filenames (`process-log.md`, `process-report.md`, optional `gem-log.md`, `conversation.md`, `conversation-report.md`) so each file's purpose is clear. `DeployedPrompts/` stays flat: save one exact final prompt product per run as `plogNNNN-<subject>.md`.

## IDs and lifecycle

- Assign a stable, never-reused run ID. Reuse an existing `plogNNNN` ID when extending that production lineage; otherwise use the next available `plogNNNN` ID.
- Save the receipt as `manifests/<run-id>.yaml` and add it to `runs.yaml`.
- One manifest describes one bounded run. If a later evaluation uses a deployed prompt, give it a separate run ID and refer to the prompt's earlier run in `inputs`.
- Treat a finalized manifest as a historical receipt. If metadata is corrected, update it with a `revision` increment and a short `change_note`; keep the same run ID. Use artifact paths, roles, and notes to identify materials; do not add hashes.
- Record timestamps in UTC using ISO 8601. Local dates in legacy filenames are not assumed to be UTC.

## What to record

Record exact values when exposed by the platform or runtime. For unavailable values use an explicit state, so missing data is distinguishable from an omitted field:

```yaml
temperature:
  status: unknown
  reason: provider_did_not_expose
```

Allowed `status` values are `known`, `unknown`, `not_applicable`, and `not_recorded`. Use `not_recorded` only for a receipt created after the run when the value might once have been available. `unknown` means the run was inspected and the value could not be established. `not_applicable` is for settings the platform does not use. Never infer settings from a model name or from typical defaults.

For hosted models, capture provider/platform, model name and exposed version/revision, API or UI mode, inference settings, enabled tools, and relevant session context. For open-weight models, additionally capture the model file name or locator, source revision, quantization, runtime/version, sampler settings, context/batch parameters, seed, and hardware when available. Secrets, API keys, cookies, and private credentials must never be included.

Use repository-relative paths with `/` separators. For external inputs, record a stable URL or locator and enough source/version/context information to identify what was consulted. Git history can show later edits to files in the repository.

## Artifact roles

Use `process_log` for the Phase 0–4 production trace; `process_report` for retrospective analysis of that production process; `gem-log` for an optional Gem Adapter / Gem Builder run record, including the deployed Gem process when retained; `conversation_log` for the deployment interaction with the resulting persona prompt; and `conversation_report` for analysis of that interaction. Include a `gem-log` entry only when that optional workflow was used and its log is available. Use `deployed_prompt` for the exact prompt sent to a model, and `research`, `evidence`, `core`, `adapter`, `deployment`, or `audit` for staged SOPPG outputs. A file can have one primary role and free-form notes. Link a conversation report and its source conversation separately.

## Legacy receipts

`plog0001.yaml` and `plog0002.yaml` inventory the existing checked-in files and capture only facts stated in those files. They are marked `legacy` and `partial`; they do not claim to be complete production receipts. Missing model settings remain explicitly unknown. New runs should use `template.yaml` before execution where possible.

## Validation checklist

Before closing a run, verify that every listed repository artifact exists, every prompt is the actual deployed prompt (not merely a later edited copy), model/runtime facts have a source, and the manifest is committed alongside the artifacts.

