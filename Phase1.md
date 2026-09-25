# SOPPG — PHASE 1
## Source Research & Evidence Modeling

---

# 0. PHASE CONTRACT

## PURPOSE

Collect, verify, organize, and calibrate evidence from the **selected Phase 0 source corpus** so that Phase 2 can construct an evidence-grounded Core Character Model.

Phase 1 answers:

> **What does the selected source material actually show?**

Phase 1 does **not** construct the character model.

---

## LANGUAGE SETS AND PROCESS LANGUAGE

Keep these language sets distinct:

- **WORKING LANGUAGE** — default to the language of the user's initial target-character request, considered by language rather than by the character name or source title. Use it for user-facing process narration and explanations unless the user specifies another language. If materially multilingual and unclear, ask or state a minimal, reversible assumption.
- **SPECIFICATION LANGUAGE** — the language in which this phase's rules and canonical schema are written (English in this specification). Preserve canonical section names, field names, IDs, and controlled values exactly as defined by the Phase specification. Explain them in the Working Language as needed; translation must not change the procedure or evidence standard.
- **SOURCE LANGUAGE(S)** — the original language(s) of works and evidence sources. Record per source where known; retain original excerpts and identify translations or glosses as such.
- **TARGET-REALIZATION LANGUAGE(S)** — intended persona/deployment language(s), determined separately. The Working Language does not set the target voice.

Research and present evidence accessibly in the Working Language while preserving its original wording, provenance, and scope. Do not treat translation, localization, or a language choice by itself as character behavior; assess such effects as presentation or version evidence where relevant.

---

## INPUTS

Required:

- Phase 0 source registry
- Phase 0 prioritized source handoff
- Phase 0 corpus state / user edits

Optional:

- user-added sources
- specific research questions
- source-scope restrictions
- explicitly marked user observations

Do not silently add unselected sources.

Do not invent missing constraints.

---

## OUTPUTS

Produce these artifact classes in this order:

1. RESEARCH HEADER
2. SELECTED SOURCE CORPUS
3. EVIDENCE LEDGER
4. EVIDENCE COVERAGE
5. COUNTEREVIDENCE / CONFLICTS
6. SOURCE-SCOPE NOTES
7. VOICE EVIDENCE
8. RELATIONSHIP EVIDENCE
9. TEMPORAL / VERSION EVIDENCE
10. RESEARCH HYPOTHESES
11. RESEARCH AUDIT
12. PHASE 1 STATUS

All listed sections are part of the canonical grammar.

**Section presence does not imply that entries must exist.**

---

# 1. SHARED ARTIFACT GRAMMAR

## 1.1 SECTION RULE

A canonical section must appear in the specified order.

If a section has no meaningful entries, keep it structurally present and write:

`NONE ESTABLISHED`

Do not invent content merely to populate the section.

## 1.2 ENTRY RULE

Entries are conditional.

Create an entry only when the selected corpus provides materially useful information.

Do not create placeholder entries.

## 1.3 FIELD RULE

Fields are:

- **REQUIRED** — necessary for the artifact to be meaningful
- **OPTIONAL** — include only when useful
- **FORBIDDEN** — content outside Phase 1 scope

Optional fields may be omitted.

## 1.4 OMISSION RULE

Do not fill an optional field with filler such as:

- none
- not applicable
- no evidence
- no counterevidence

unless the absence itself is analytically relevant.

Otherwise omit the field.

## 1.5 ID RULE

Use phase-qualified, zero-padded IDs. `P1-` identifies Phase 1 IDs; use the established type prefix after it.

### Evidence

`P1-E001`, `P1-E002`, `P1-E003` ...

### Conflicts

`P1-X001`, `P1-X002`, ...

### Scope notes

`P1-N001`, `P1-N002`, ...

### Voice evidence

`P1-V001`, `P1-V002`, ...

### Relationship evidence

`P1-R001`, `P1-R002`, ...

### Temporal / version evidence

`P1-TV001`, `P1-TV002`, ...

### Research hypotheses

`P1-H001`, `P1-H002`, ...

Do not reuse IDs.

## 1.6 SOURCE REGISTRY RULE

Phase 0 owns the canonical source IDs.

Use inherited Phase 0 `P0-SRC` IDs exactly as supplied.

Do not silently rename, reclassify, or replace Phase 0 sources.

If a source classification genuinely appears incorrect, record the issue explicitly in `SOURCE-SCOPE NOTES` or `RESEARCH AUDIT`.

## 1.7 EVIDENCE REFERENCE RULE

When an artifact refers to evidence, reference existing Phase 1 `P1-E` IDs exactly.

Do not create a new evidence ID merely to support an interpretation.

## 1.8 PROVENANCE RULE

Use only:

- DIRECT
- REPRODUCED
- SECONDARY
- INFERENCE
- SPECULATION

Do not silently upgrade provenance.

## 1.9 INTERPRETATION RULE

Phase 1 may include a brief interpretive note when it helps Phase 2 locate a research issue.

It must not become a finished personality judgment.

---

# 2. GOVERNING PRINCIPLES

## 2.1 Evidence Before Characterization

Do not decide what the character is and then collect confirming evidence.

Research the selected corpus first.

Character modeling comes in Phase 2.

## 2.2 Observe Before Abstracting

Prefer:

> what happened

over:

> what it means.

For example:

Weak:

> The character is caring.

Better:

> When another character is struggling, she repeatedly notices the problem and takes practical action without being asked.

The second provides evidence from which Phase 2 may construct a mechanism.

## 2.3 Fixed Grammar, Variable Occupancy

The output structure must remain recognizable across characters.

The quantity and detail of entries may vary naturally.

## 2.4 Unknown Is Valid

Accept:

- insufficient evidence
- not observable
- conflicting evidence
- unclear provenance
- inaccessible source
- outside current scope

Do not manufacture certainty.

## 2.5 Salience Is Not Centrality

A famous line, iconic scene, meme, visual gag, dramatic failure, or heavily repeated summary is not automatically representative.

Seek recurrence, variation, and ordinary behavior.

## 2.6 One Example Is Not a Rule

A single observation can establish that something can occur.

It does not automatically establish:

- frequency
- centrality
- permanence
- typicality

Record scope where relevant.

## 2.7 Contradiction Is Evidence

Conflicting observations may reveal:

- context dependence
- relationship dependence
- development
- adaptation differences
- presentation effects
- an incorrect interpretation

Preserve conflicts instead of smoothing them away.

---

# 3. RESEARCH HEADER

## RESEARCH HEADER

### REQUIRED

- CHARACTER:
- RESEARCH SCOPE:
- SOURCE LANGUAGES:
- SOURCE / WORK:
- CONTINUITY / VERSION:
- CORPUS STATE:
- RESEARCH STATUS:

### OPTIONAL

- WORKING LANGUAGE:

Record it when explicitly selected, different from the default, or materially relevant to user-facing research presentation. It does not change the source corpus or source-language evidence.

### SOURCE / WORK RULE

Use the selected Phase 0 scope.

Do not silently broaden the corpus.

`CORPUS STATE` should identify whether the source set was:

- DEFAULT-ACCEPTED
- USER-SELECTED
- USER-MODIFIED

`RESEARCH STATUS` begins as:

`OPEN`

---

# 4. SELECTED SOURCE CORPUS

This is a **registry reference**, not a second source-discovery phase.

## SELECTED SOURCE CORPUS

### INCLUDED

- P0-SRC001
- P0-SRC002
- P0-SRC003

### DISCOVERY ONLY

- P0-SRC010

### EXCLUDED

- P0-SRC004

### USER ADDITIONS

- [user-provided source, if any]

### USER EXCLUSIONS

- [source IDs removed by user, if any]

Use the Phase 0 source descriptions as authoritative.

Do not duplicate full source descriptions here.

If the corpus includes an explicit user-added source not present in Phase 0, assign it a new `P0-SRC` ID and record its minimal registry information.

---

# 5. EVIDENCE LEDGER

This is the primary Phase 1 artifact.

## EVIDENCE LEDGER

### P1-E001 — [SHORT DESCRIPTION]

### REQUIRED

- OBSERVATION:
- CONTEXT:
- EVIDENCE:
- PROVENANCE:

### OPTIONAL

- FREQUENCY:
- CHARACTER SCOPE:
- QUALIFIER:
- INTERPRETIVE NOTE:
- CONFIDENCE:

### FIELD RULES

`OBSERVATION`

Describe the relevant behavior, speech, decision, reaction, or explicit characterization concretely.

Prefer observable events over generalized labels.

`CONTEXT`

Include only context needed to interpret the observation.

`EVIDENCE`

Use a quotation, paraphrase, transcript reference, scene reference, or other recoverable support.

Reference the source with its Phase 0 `P0-SRC` ID where useful.

`PROVENANCE`

Use exactly one:

- DIRECT
- REPRODUCED
- SECONDARY
- INFERENCE
- SPECULATION

Phase 1 should normally rely on DIRECT, REPRODUCED, and SECONDARY evidence.

Use INFERENCE or SPECULATION only for explicitly marked research leads.

`FREQUENCY`

Only record when repetition is materially established.

Use qualitative descriptions such as:

- recurring
- occasional
- rare
- one observed instance
- unknown

Do not invent numerical frequencies.

`CHARACTER SCOPE`

Use only when necessary to distinguish:

- baseline
- situational
- relationship-specific
- version-specific
- developmental
- exceptional

`QUALIFIER`

Use for a limitation that materially changes interpretation.

`INTERPRETIVE NOTE`

Optional research guidance for Phase 2.

It must not become a finished character conclusion.

`CONFIDENCE`

Optional.

Use:

- HIGH
- MEDIUM
- LOW
- UNKNOWN

Confidence should be attached only when it adds useful information.

---

# 6. EVIDENCE QUALITY

Do not create a quality card for every observation unless necessary.

Assess important evidence using:

- directness
- specificity
- recurrence
- context
- corroboration
- counterevidence

Do not create false precision.

---

# 7. EVIDENCE GROUPING

Group observations when doing so helps Phase 2 identify patterns.

Useful grouping questions:

- Which observations appear related?
- Which occur under similar conditions?
- Which conflict?
- Which are relationship-specific?
- Which are version-specific?
- Which concern presentation rather than behavior?
- Which concern voice rather than behavior?

Do not create a character model here.

---

# 8. EVIDENCE COVERAGE

This section maps **what kinds of evidence are available**, not what the character “is.”

## EVIDENCE COVERAGE

### COVERED

### Optional entry

- AREA:
- EVIDENCE:
- COVERAGE:

### WEAK / MISSING

### Optional entry

- AREA:
- REASON:
- IMPACT:

Useful areas may include:

- ordinary behavior
- goals / priorities
- competence
- mistakes
- uncertainty
- social interaction
- humor
- conflict
- disagreement
- embarrassment
- failure
- recovery
- agency
- independence
- dependence
- affection
- boundaries
- information behavior
- surprise
- relationships
- voice
- development

Do not attempt to fill every area.

Do not use this section to infer personality.

---

# 9. COUNTEREVIDENCE / CONFLICTS

Record meaningful evidence that challenges, qualifies, or conflicts with an emerging interpretation.

## COUNTEREVIDENCE / CONFLICTS

### P1-X001 — [ISSUE]

### REQUIRED

- CLAIM / INTERPRETATION AT RISK:
- CONFLICTING EVIDENCE:
- CONTEXT:

### OPTIONAL

- POSSIBLE EXPLANATIONS:
- RESOLUTION:
- REMAINING UNCERTAINTY:

Possible explanations must remain hypotheses.

Do not force resolution.

---

# 10. SOURCE-SCOPE NOTES

Record boundaries that Phase 2 needs to know.

## SOURCE-SCOPE NOTES

### P1-N001 — [SCOPE NOTE]

### REQUIRED

- ISSUE:
- SCOPE:
- HANDLING:

Examples:

- behavior appears only in one adaptation
- internal thoughts exist only in a novel
- apparent speech pattern may be localization-specific
- player-controlled actions cannot be cleanly attributed
- characterization changes over time
- a Phase 0 source classification appears questionable

These are evidence boundaries, not personality traits.

---

# 11. VOICE EVIDENCE

Collect source-grounded linguistic evidence without constructing the target-language voice.

## VOICE EVIDENCE

### P1-V001 — [FEATURE]

### REQUIRED

- OBSERVATION:
- CONTEXT:
- EVIDENCE:
- PROVENANCE:

### OPTIONAL

- FREQUENCY:
- VARIATION:
- SOURCE / VERSION:

Possible features:

- register
- sentence rhythm
- vocabulary
- politeness
- pronouns
- verbal habits
- emotional expression
- hesitation
- rhetorical style
- sentence length
- humor

Do not create synthetic dialogue here.

---

# 12. RELATIONSHIP EVIDENCE

Record observed relationship-specific behavior without constructing the deployment relationship.

## RELATIONSHIP EVIDENCE

### P1-R001 — [RELATIONSHIP / BEHAVIOR]

### REQUIRED

- OTHER PERSON:
- RELATIONSHIP:
- OBSERVATION:
- CONTEXT:
- EVIDENCE:
- PROVENANCE:

### OPTIONAL

- VARIATION:
- SOURCE / VERSION:
- QUALIFIER:

Do not infer:

- intimacy from importance
- romance from affection
- dependence from trust
- obedience from authority

unless the evidence supports it.

---

# 13. TEMPORAL / VERSION EVIDENCE

Use only when meaningful changes occur across time or source versions.

## TEMPORAL / VERSION EVIDENCE

### P1-TV001 — [CHANGE]

### REQUIRED

- PERIOD / VERSION:
- BEFORE:
- AFTER:
- EVIDENCE:
- PROVENANCE:

### OPTIONAL

- POSSIBLE CAUSE:
- CONFIDENCE:

`POSSIBLE CAUSE` is a hypothesis, not an established fact.

---

# 14. RESEARCH HYPOTHESES

Use only for useful unresolved questions that Phase 2 should examine.

## RESEARCH HYPOTHESES

### P1-H001 — [HYPOTHESIS]

### REQUIRED

- QUESTION:
- SUPPORTING EVIDENCE:
- STATUS:

### OPTIONAL

- CONTRARY EVIDENCE:

`STATUS` may be:

- OPEN
- WEAK
- PLAUSIBLE
- UNSUPPORTED
- RESOLVED BY EVIDENCE

This is a research aid, not part of the character model.

---

# 15. RESEARCH STRATEGY

When the selected corpus leaves important gaps, use the Phase 0 source map to determine whether:

- an included source can be mined further;
- a discovery-only source can locate additional primary material;
- a user-added source is needed;
- another Phase 0 discovery pass is warranted.

Do not silently expand the evidentiary corpus.

When a genuinely valuable new source is discovered, record it as:

> **NEW SOURCE CANDIDATE — RETURN TO PHASE 0**

unless the user has explicitly permitted Phase 1 discovery.

---

# 16. SOURCE-LANGUAGE RESEARCH

When reasonably accessible, prefer original-language evidence for original-language works.

For Japanese-origin material, investigate Japanese evidence where practical.

For other languages, apply the same principle.

Use translated or English-language material for:

- discovery
- cross-checking
- accessibility
- supplementary context

Do not allow a translation to overwrite original-language evidence when the original is available.

---

# 17. PRESENTATION VS CHARACTER EVIDENCE

Where the medium introduces presentation effects, distinguish:

- CHARACTER
- PRESENTATION
- MIXED
- UNKNOWN

Possible effects include:

- comedic exaggeration
- editing
- reaction shots
- voice-performance emphasis
- gameplay repetition
- player control
- visual shorthand
- narrator framing
- localization
- adaptation compression

Do not discard presentation evidence automatically.

---

# 18. EXTERNAL / REAL-WORLD MATERIAL

When external source material is relevant, separate:

- external fact
- fictional source material
- fictional characterization
- later interpretation

External fact is not automatically character evidence.

---

# 19. RESEARCH AUDIT

## RESEARCH AUDIT

### REQUIRED CHECKS

- SOURCE CORPUS FIDELITY:
- SOURCE ACCESS HONESTY:
- PRIMARY EVIDENCE:
- PROVENANCE DISCIPLINE:
- EVIDENCE COVERAGE:
- COUNTEREVIDENCE SEARCH:
- CONTEXT PRESERVATION:
- VERSION / CONTINUITY DISCIPLINE:
- PRESENTATION / CHARACTER DISTINCTION:
- PREMATURE CHARACTERIZATION:
- UNSUPPORTED CLAIMS:

Each uses:

`PASS`, `WARNING`, or `FAIL`

followed by one concise explanation.

Do not turn the audit into another analysis section.

---

# 20. PHASE 1 STATUS

## PHASE 1 STATUS

### REQUIRED

- STATUS:
- SELECTED SOURCES:
- EVIDENCE ENTRIES:
- MAJOR COVERAGE GAPS:
- MAJOR CONFLICTS:

### OPTIONAL

- OPEN RESEARCH QUESTIONS:
- NEW SOURCE CANDIDATES:
- HANDOFF NOTE:

`STATUS` may be:

- OPEN
- READY FOR PHASE 2

`READY FOR PHASE 2` means the evidence is sufficiently usable to attempt modeling.

It does not mean uncertainty has disappeared.

---

# 21. HANDOFF RULE

Phase 1 passes:

> **selected source corpus + evidence ledger + evidence coverage + conflicts + scope notes + relevant specialized evidence views**

to Phase 2.

Phase 1 does not pass a rewritten character as authoritative characterization.

The canonical Phase 2 input remains:

> **SOURCE COMPILATION / CORPUS + EVIDENCE LEDGER + COVERAGE + CONFLICTS + SCOPE NOTES**

Phase 2 reconstructs the behavioral model from that evidence.

---

# 22. EXECUTION RULE

When executing Phase 1:

1. Read the selected Phase 0 corpus before extracting evidence.
2. Respect the corpus selection and exclusions.
3. Use inherited Phase 0 `P0-SRC` IDs exactly.
4. Collect concrete evidence before abstracting traits.
5. Seek variation and counterevidence.
6. Preserve context.
7. Preserve contradictions.
8. Distinguish provenance.
9. Keep relationship-specific evidence scoped.
10. Keep voice evidence separate from target-language realization.
11. Record important gaps rather than filling them.
12. Do not silently add sources.
13. Do not construct the Core.
14. Complete the audit.
15. Mark `READY FOR PHASE 2` only when the evidence base is reasonably usable.

---

# 23. OUTPUT DISCIPLINE

Begin directly with:

`# PERSONA BUILDER — PHASE 1`

Follow the canonical section order.

Do not add free-form top-level sections.

Do not append general commentary after `PHASE 1 STATUS`.

The Phase 1 artifact is the deliverable.
