# SOPPG — Phase 4 
## Sample Generation Assessment-Driven Audit

---

# 0. PHASE CONTRACT

## PURPOSE

Assess how a compiled and deployed persona is realized in actual model generation.

Phase 4 answers:

> **What does the supplied generation material actually show about the deployed artifact and its runtime realization?**

Phase 4 does **not** automatically answer:

> What is the character?

and does **not** automatically modify:

> the Phase 2 Core Character Model, Phase 3 compilation, or deployed artifact.

Phase 4 produces:

> **runtime assessment + audit findings + propagation / disposition**

Candidate revision or adapter work is produced only where the audit identifies an actionable intervention supported by the available evidence.

Phase 4 is optional.

---

## LANGUAGE SETS AND PROCESS LANGUAGE

Keep these language sets distinct:

- **WORKING LANGUAGE** — default to the language of the user's initial target-character request, considered by language rather than by the character name or source title. Use it for user-facing assessment and explanations unless the user specifies another language. If materially multilingual and unclear, ask or state a minimal, reversible assumption.
- **SPECIFICATION LANGUAGE** — the language in which this phase's rules and canonical schema are written (English in this specification). Preserve canonical section names, field names, IDs, disposition values, and audit labels exactly as defined here. Explain them in the Working Language without changing their requirements.
- **SOURCE LANGUAGE(S)** — languages of the deployed prompt's supporting sources, where consulted. Keep source quotations and their translations distinguishable.
- **TARGET-REALIZATION LANGUAGE(S)** — language(s) actually intended and represented in the supplied generation sample. Assess that realization in context; do not treat the Working Language or source language as the deployed output language unless independently established.
- **PROMPT LANGUAGE** — language(s) used by the compiled instructions. It defaults to English for general-user workflows unless the user explicitly selected another language. Treat this separately from the sample's target output language.

When a user cue, prompt, and generation use different languages, record which language each uses when it materially affects interpretation. Assess observable meaning and pragmatic function, including localization effects where relevant, rather than judging equivalence by literal translation alone. A mismatch with the English prompt default is not itself a runtime defect when the user explicitly requested another Prompt Language.

---

## INPUTS

### ESSENTIAL

- Phase 3 deployment artifact
- bounded sample generation set
- runtime / deployment context

### OPTIONAL

- relevant earlier Phase artifacts
- user cue / prompt context
- existing assessment report
- comparative samples
- runtime diagnostic material
- prior Phase 4 assessments
- explicit audit question / scope

Do not load or reassess upstream artifacts automatically.

---

# 1. SHARED ARTIFACT GRAMMAR

## 1.1 SECTION RULE

A canonical section must appear in the specified order.

If a section has no meaningful entries, keep it structurally present and write:

`NONE ESTABLISHED`

Do not invent content merely to populate the section.

## 1.2 ENTRY RULE

Create an entry only when the supplied runtime evidence provides materially useful information.

Do not create placeholder findings.

## 1.3 FIELD RULE

Fields are:

- **REQUIRED** — necessary for the artifact to be meaningful
- **OPTIONAL** — include only when materially useful
- **FORBIDDEN** — content outside Phase 4 scope

Optional fields may be omitted.

## 1.4 OMISSION RULE

Do not fill optional fields with filler.

Do not manufacture:

- none
- not applicable
- no evidence
- no counterevidence

merely to complete the structure.

Use `UNKNOWN` only when uncertainty itself is meaningful.

Otherwise omit the field.

## 1.5 ID RULE

Use phase-qualified, zero-padded IDs. `P4-` identifies Phase 4 IDs; use the established type prefix after it.

### Runtime findings

`P4-RF001`, `P4-RF002`, `P4-RF003` ...

### Runtime patterns

`P4-RP001`, `P4-RP002`, `P4-RP003` ...

### Disposition items

`P4-D001`, `P4-D002`, `P4-D003` ...

Do not reuse IDs.

## 1.6 EVIDENCE REFERENCE RULE

Runtime findings must reference the supplied sample or other supplied runtime material.

When earlier Phase artifacts are consulted, use their existing IDs exactly.

Do not invent upstream evidence IDs.

## 1.7 INHERITED EVIDENCE DISCIPLINE

Apply the existing Phase 0–1 terminology, distinctions, and epistemic discipline throughout Phase 4.

In particular:

- preserve provenance;
- preserve context and scope;
- distinguish observation from interpretation;
- preserve contradiction and uncertainty;
- distinguish character evidence from presentation effects;
- do not silently upgrade provenance or certainty;
- do not treat one observation as establishing frequency, centrality, permanence, or typicality.

Do not introduce a parallel evidence taxonomy for runtime assessment.

---

# 2. GOVERNING PRINCIPLES

## 2.1 EVIDENCE BEFORE INTERPRETATION

Begin with what is actually present in the supplied generation material.

Prefer:

> observable behavior, wording, action, omission, contradiction, or recurring pattern

over:

> inferred motive, personality explanation, or narrative significance.

## 2.2 CONTEXT PRESERVATION

Preserve enough surrounding prompt, conversation, sample sequence, and runtime context to interpret an observation correctly.

## 2.3 CONTRADICTION IS EVIDENCE

Conflicting runtime observations may indicate:

- context dependence
- cue dependence
- character-model ambiguity
- specialization effects
- host-model variation
- runtime instability
- an incorrect interpretation

Preserve conflicts instead of smoothing them away.

## 2.4 UNKNOWN IS VALID

Accept:

- insufficient evidence
- unclear cause
- not observable
- conflicting evidence
- unresolved attribution
- outside current scope

Do not manufacture certainty.

## 2.5 PRESENTATION VS CHARACTER DISTINCTION

Where generation behavior may reflect narration, roleplay convention, stylistic prompting, model prose habits, or other presentation effects, distinguish these from character evidence.

Do not treat prose presentation automatically as character behavior.

---

# 3. RUNTIME EVIDENCE SET

Aim for no more than approximately **5,000 words of sample text**, with an approximate upper limit of **6,000** per assessment. Count all supplied user and model turns cumulatively across samples, conversations, segments, and passes. Where whitespace word counts poorly represent text volume, use a rough character-count equivalent. This is a workload guide, not a token limit. Keep runtime context, cues, and diagnostics concise. If the material exceeds the practical limit, select a representative subset or conduct separately scoped assessments; do not use segmentation to bypass the cumulative limit or imply that a subset represents the full transcript.

The set may contain:

- continued turns
- discontinued turns
- samples from one conversation
- samples from multiple conversations

Approximately four turns may provide a useful default sample shape, but sample count itself is not the controlling constraint.

Prefer representative and diagnostically useful material over exhaustive transcript coverage.

The audit is not required to explain every line.

---

# 4. SAMPLE GENERATION ASSESSMENT

This is the primary Phase 4 evidence artifact.

## SAMPLE GENERATION ASSESSMENT

Record only significant observations.

### P4-RF001 — [SHORT FINDING]

### REQUIRED

- OBSERVATION:
- CONTEXT:
- EVIDENCE:
- PROVENANCE:

### OPTIONAL

- FREQUENCY:
- SCOPE:
- QUALIFIER:
- INTERPRETIVE NOTE:
- CONFIDENCE:

### FIELD RULES

`OBSERVATION`

Describe what actually occurred in the supplied generation.

Prefer concrete description over generalized character judgment.

`CONTEXT`

Include only context necessary to interpret the observation.

When materially different, identify the language of the user cue, deployed instruction, and generated sample. `WORKING LANGUAGE` remains the language used for the assessment discussion; it is not evidence of the target-realization language.

`EVIDENCE`

Use a recoverable excerpt, paraphrase, turn reference, or sample identifier.

Do not invent quotations.

`PROVENANCE`

Record the evidentiary basis of the claim, using inherited Phase 0–1 terminology where applicable. For example, the occurrence visible in a supplied sample is `DIRECT`; a claim about its cause or likely locus is `INFERENCE` unless independently established. Provenance applies to the claim being made, not to the sample as a whole. A `DIRECT` runtime observation remains runtime evidence and does not become canonical character evidence.

`FREQUENCY`

Record only when repetition is materially established.

Possible values include:

- recurring
- occasional
- rare
- one observed instance
- unknown

Do not invent numerical frequencies.

`SCOPE`

Use when necessary to distinguish:

- sample-specific
- conversation-specific
- cue-dependent
- deployment-specific
- host-specific
- runtime-specific

`QUALIFIER`

Record a limitation that materially changes interpretation.

`INTERPRETIVE NOTE`

May identify a possible implication for later audit work.

It must not become a finished character judgment.

`CONFIDENCE`

Optional.

Use:

- HIGH
- MEDIUM
- LOW
- UNKNOWN

Only where useful.

---

# 5. RUNTIME PATTERN AUDIT

Synthesize significant runtime findings without repeating the Sample Generation Assessment.

Group findings where this helps establish recurrence, variation, contradiction, scope, or likely attribution.

## RUNTIME PATTERN AUDIT

### P4-RP001 — [PATTERN]

### REQUIRED

- FINDINGS:
- PATTERN:
- CONTEXT / SCOPE:
- ASSESSMENT:
- LIKELY LOCUS:

### OPTIONAL

- CONTRARY FINDINGS:
- PROVENANCE / EVIDENCE NOTE:
- POSSIBLE CONTRIBUTING FACTORS:
- CONFIDENCE:

### ASSESSMENT RULE

Do not elevate an isolated finding into a recurring pattern without sufficient support.

Possible assessments include:

- recurring runtime pattern
- context-dependent pattern
- cue-dependent pattern
- isolated observation
- contradictory evidence
- insufficient evidence

### LIKELY LOCUS

Consider:

- Core Character Model
- Phase 3 compilation
- specialization / adapter
- host model
- user cue
- runtime / context
- presentation effect
- insufficient evidence

Multiple contributing loci may be recorded.

Do not force attribution when the evidence does not support it.

`POSSIBLE CONTRIBUTING FACTORS` remain hypotheses unless directly established.

Do not repeat individual findings except where necessary to establish a pattern or resolve a conflict.

---

# 6. UPSTREAM ARTIFACT REVIEW GATE

Determine whether the runtime findings justify consulting relevant upstream artifacts.

## UPSTREAM ARTIFACT REVIEW

### REQUIRED

- STATUS:
- FINDINGS:
- JUSTIFICATION:

`STATUS` may be:

- `NOT JUSTIFIED`
- `JUSTIFIED`

`FINDINGS` lists the relevant `P4-RF` and/or `P4-RP` IDs only. Keep `JUSTIFICATION` to the reason upstream material is needed.

Review may be justified when, for example:

- an established Core element appears to have been lost;
- the deployment artifact appears internally inconsistent;
- specialization may have altered established characterization;
- runtime behavior materially conflicts with the established artifact;
- the finding cannot be adequately assessed from deployment evidence alone.

`JUSTIFIED` means:

> there is sufficient reason to inspect relevant upstream material.

It does **not** mean:

> revise the upstream artifact.

When justified, inspect only the relevant artifact(s) necessary to answer the audit question.

Do not automatically reassess the full pipeline.

---

# 7. PROPAGATION / DISPOSITION

This is the formal boundary between runtime observation and changes to other artifacts.

## PROPAGATION / DISPOSITION

### P4-D001 — [FINDING / PATTERN]

### REQUIRED

- FINDING:
- DISPOSITION:
- TARGET:
- RATIONALE:

`DISPOSITION` may be:

- `PROPAGATE UPSTREAM`
- `ADAPT DOWNSTREAM`
- `RECORD ONLY`
- `REJECT / DO NOT PROPAGATE`
- `INSUFFICIENT EVIDENCE`

The target may be:

- Phase 2
- Phase 3
- adapter / specialization
- deployment configuration
- host profile
- Phase 4 record only
- no target

Reference `P4-RF` / `P4-RP` IDs. A single disposition may cover a pattern and its linked findings; an isolated finding may receive `RECORD ONLY`.

Do not reproduce the full assessment.

---

# 8. CANDIDATE REVISION / ADAPTER NOTES

Produced **only where the audit identifies an actionable intervention supported by the available evidence**.

Possible outputs include:

- candidate Phase 3 revision
- candidate adapter / specialization change
- deployment-level mitigation
- host-model-specific guidance
- additional testing or evidence requirement

These notes are proposals.

They do not modify upstream or deployment artifacts automatically.

---

# 9. UPDATED RUNTIME / HOST PROFILE

Produced only where the evidence supports a reusable host-specific or runtime-specific finding.

Such findings must remain separate from canonical characterization.

---

# 10. PHASE 4 AUDIT

## PHASE 4 AUDIT

### REQUIRED CHECKS

- EVIDENCE / PROVENANCE / CONTEXT:
- RECURRENCE / CONTRADICTION / SCOPE:
- CHARACTER / PRESENTATION / ATTRIBUTION:
- REVIEW / PROPAGATION DISCIPLINE:
- OUTPUT / WORKLOAD DISCIPLINE:

Each grouped check covers the corresponding safeguards already specified above and uses:

`PASS`, `WARNING`, or `FAIL`

followed by one concise explanation.

Do not turn the audit into another analysis section.

---

# 11. PHASE 4 STATUS

## PHASE 4 STATUS

### REQUIRED

- STATUS:
- SAMPLES ASSESSED:
- RUNTIME FINDINGS:
- RUNTIME PATTERNS:
- UPSTREAM REVIEW:
- DISPOSITIONS:

### OPTIONAL

- CANDIDATE INTERVENTIONS:
- HOST / RUNTIME PROFILE UPDATE:
- REMAINING UNCERTAINTIES:
- HANDOFF NOTE:

`STATUS` may be:

- `OPEN`
- `AUDITED`
- `AUDITED — NO ACTIONABLE INTERVENTION`

`AUDITED` means the supplied runtime evidence has been assessed and significant findings have received disposition.

`SAMPLES ASSESSED` must identify the sample(s) or transcript range actually assessed; do not imply full-transcript coverage when only a subset was reviewed.

`AUDITED — NO ACTIONABLE INTERVENTION` means the phase completed without identifying an evidence-supported intervention requiring further work.

---

# 12. EXECUTION RULE

When executing Phase 4:

1. Read the supplied deployment artifact and bounded runtime evidence first.
2. Confirm the runtime / deployment context.
3. Preserve sample context.
4. Record significant observations before interpreting them.
5. Apply the existing Phase 0–1 evidence terminology and epistemic discipline.
6. Preserve provenance, scope, contradiction, and uncertainty.
7. Seek recurrence and variation where the evidence permits.
8. Distinguish character realization from presentation, cueing, host behavior, and runtime effects.
9. Do not convert isolated runtime behavior into a character rule.
10. Assess likely attribution without forcing certainty.
11. Determine whether upstream artifact review is justified.
12. If justified, inspect only the relevant upstream material.
13. Assign significant findings an explicit disposition.
14. Produce candidate revision / adapter notes only where an actionable intervention is supported.
15. Do not silently modify upstream or deployment artifacts.
16. Complete the audit.
17. Mark `AUDITED` or `AUDITED — NO ACTIONABLE INTERVENTION`.

---

# 13. OUTPUT DISCIPLINE

When essential inputs are valid:

- initialize concisely;
- proceed directly to assessment;
- do not restate the phase specification;
- do not enumerate already-satisfied requirements;
- do not consume substantial output space on phase bootstrap.

The information flow should be:

> **sample evidence → runtime assessment → pattern synthesis → disposition**

Later artifacts should reference earlier findings rather than reproduce their prose.

Prioritize significant and diagnostically useful findings over exhaustive commentary.

A valid run may terminate without upstream review, candidate revision, or host-profile update.

Do not append general commentary after `PHASE 4 STATUS`.

The Phase 4 artifact is the deliverable.
