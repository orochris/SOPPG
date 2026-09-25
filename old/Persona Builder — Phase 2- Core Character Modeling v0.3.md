# PERSONA BUILDER — PHASE 2
## Core Character Modeling
### v0.3 — Lean Core Architecture

---

# 0. PHASE CONTRACT

## PURPOSE

Transform Phase 1 evidence into a **frozen, evidence-grounded Core Character Model**.

The Core should capture the smallest useful set of recurring behavioral patterns needed to recognize and reproduce the character across contexts.

It is a **semantic model**, not a finished persona.

Later specialization phases may adapt its expression, context, relationship, language, or deployment.

They must not silently redefine it.

---

## INPUTS

Required:

- Phase 1 Source Compilation
- Phase 1 Evidence Ledger
- Phase 1 uncertainty / counterevidence

Optional:

- source dialogue / transcripts
- chronological evidence
- adaptation comparisons
- explicitly marked user observations

---

## OUTPUTS

Produce these artifact classes in this order:

1. CORE HEADER
2. CORE BEHAVIORAL MODEL
3. BEHAVIORAL MODULATION
4. FUNCTIONAL BEHAVIOR
5. VOICE BASELINE
6. UNCERTAINTIES
7. CORE AUDIT
8. CORE STATUS

Do not add other top-level sections.

Sections may contain zero entries where the evidence does not support them.

---

# 1. GOVERNING PRINCIPLES

## 1.1 Model Behavior, Not Adjectives

Prefer:

> recurring pattern → context → expression → variation

over:

> adjective → adjective → adjective

A label may be used as shorthand, but the model must describe observable behavior.

---

## 1.2 Fixed Grammar, Variable Occupancy

The output structure must remain recognizable across different characters.

However:

> **A field is not a request to invent content.**

Optional fields are included only when they provide materially useful information.

Do not populate empty fields with filler.

Do not write:

- “none”
- “not applicable”
- “no evidence”
- “no counterevidence”

merely to complete a template.

---

## 1.3 Evidence Before Interpretation

Every substantive claim must trace to Phase 1 evidence.

Use the Phase 1 provenance categories without modification:

- DIRECT
- REPRODUCED
- SECONDARY
- INFERENCE
- SPECULATION

Do not silently upgrade an inference into fact.

---

## 1.4 Salience Is Not Centrality

A famous, dramatic, funny, iconic, or frequently discussed scene does not automatically represent the character's general behavior.

Consider recurrence, context, variation, chronology, and counterevidence.

---

## 1.5 Trait Presence Is Not Constant Expression

A character can possess a recurring tendency without displaying it continuously.

Do not turn:

> “can become frightened”

into:

> “is always frightened.”

Do not turn:

> “sometimes acts arrogantly”

into:

> “is fundamentally arrogant in every situation.”

---

## 1.6 Contradiction Is Data

When evidence conflicts:

1. verify the evidence;
2. examine context;
3. examine chronology;
4. examine source / adaptation differences;
5. determine whether the difference is meaningful variation;
6. preserve uncertainty when it cannot be resolved.

Do not average incompatible evidence into a vague middle.

---

## 1.7 Unknown Is Allowed

The model is permitted to conclude that something is unknown, weakly supported, or not character-defining.

Do not infer traits from absent evidence.

---

## 1.8 No Unsupported Psychology

Do not introduce diagnoses, pathology, trauma explanations, attachment styles, or similar psychological claims without strong direct source support.

A motivational explanation may appear only as an explicitly marked hypothesis.

---

# 2. ID CONVENTIONS

Use zero-padded IDs.

- Core mechanisms: `C001`, `C002`, ...
- Modulation patterns: `M001`, `M002`, ...
- Functional behavior patterns: `F001`, `F002`, ...
- Voice observations: `V001`, `V002`, ...
- Motivational hypotheses: `H001`, `H002`, ...
- Uncertainties: `U001`, `U002`, ...

Do not reuse IDs.

Do not invent Phase 1 evidence IDs.

---

# 3. CARDINALITY RULES

These are guidance, not quotas.

### Core mechanisms

Normally 3–6.

Use fewer when fewer are genuinely supported.

### Modulation patterns

0–5.

### Functional behavior patterns

0–6.

### Voice observations

Normally 2–6 when dialogue evidence exists.

### Motivational hypotheses

0–3.

### Uncertainties

0–5.

Never create an entry simply to reach a number.

---

# 4. CORE HEADER

## CORE HEADER

- CHARACTER:
- SOURCE BASIS:
- MODEL SCOPE:
- TEMPORAL SCOPE:
- CORE STATUS:

`MODEL SCOPE` must state that the model is:

> relationship-independent, deployment-independent, and not a target-language realization.

It may incorporate canon / setting evidence as context, but must not derive personality traits merely from the existence of the setting.

`CORE STATUS` remains `UNFROZEN` until the final audit is complete.

---

# 5. CORE BEHAVIORAL MODEL

This is the center of Phase 2.

Each entry represents a recurring behavioral mechanism that materially contributes to character recognition.

## CORE BEHAVIORAL MODEL

### C001 — [MECHANISM NAME]

- CORE PATTERN:
- EXPRESSION:
- EVIDENCE:
- CONFIDENCE:

Optional:

- CONTEXT:
- VARIATION:
- LIMITS:
- COUNTEREVIDENCE:

Repeat as needed.

### FIELD MEANINGS

`CORE PATTERN`

The recurring behavioral rule in compact form.

It may combine interpretation, tendency, and typical trigger when separating them would add no useful information.

`EXPRESSION`

What the pattern looks like in observable behavior.

`CONTEXT`

Include only when context materially affects expression.

`VARIATION`

Include only when meaningful variation exists across situations, intensity, chronology, or other conditions.

`LIMITS`

Include only when necessary to prevent overgeneralization.

`COUNTEREVIDENCE`

Include only when relevant evidence materially qualifies or challenges the interpretation.

`EVIDENCE`

Reference Phase 1 evidence IDs.

`CONFIDENCE`

Use only:

- HIGH
- MEDIUM
- LOW
- UNKNOWN

### MECHANISM RULE

A mechanism should explain multiple observations where possible.

Do not create separate mechanisms for superficial variations of the same underlying behavior.

Do not force broad labels such as:

- kind
- smart
- shy
- arrogant
- curious

to function as mechanisms without behavioral specification.

---

# 6. BEHAVIORAL MODULATION

This section captures **how the Core behaves differently under meaningful conditions**.

It replaces separate mandatory systems for “state,” “tension,” and “recovery.”

A modulation entry may represent:

- a recurring behavioral tension;
- pressure-related change;
- context-dependent expression;
- failure response;
- recovery;
- adaptation;
- a persistent shift across time.

## BEHAVIORAL MODULATION

### M001 — [MODULATION NAME]

- BASE PATTERN:
- CONDITION:
- CHANGED EXPRESSION:
- EVIDENCE:
- CONFIDENCE:

Optional:

- DIRECTION / TENSION:
- RECOVERY / ADAPTATION:
- LIMITS:
- COUNTEREVIDENCE:

### RULES

`BASE PATTERN` must refer to an existing Core mechanism when applicable.

`CONDITION` identifies what changes the expression.

`CHANGED EXPRESSION` describes what actually changes.

`DIRECTION / TENSION` may describe opposing tendencies when that tension is genuinely recurring.

`RECOVERY / ADAPTATION` is used only when the evidence shows what happens afterward.

A character does not need a formal emotional-state ladder.

Do not manufacture dramatic escalation merely because the character occasionally becomes emotional.

---

# 7. FUNCTIONAL BEHAVIOR

This section captures recurring behavioral functions that may not be adequately represented by the headline mechanisms.

Possible areas include:

- information handling
- knowledge and uncertainty
- social behavior
- boundaries
- agency
- competence
- failure
- correction
- decision-making
- interaction patterns

Do not create separate entries for every area.

Create an entry when the behavior is character-relevant and not already adequately represented by a Core mechanism.

## FUNCTIONAL BEHAVIOR

### F001 — [PATTERN NAME]

- PATTERN:
- EXPRESSION:
- EVIDENCE:
- CONFIDENCE:

Optional:

- CONTEXT:
- LIMITS:
- COUNTEREVIDENCE:

### FUNCTIONAL DISTINCTIONS

Preserve relevant distinctions such as:

- confidence ≠ correctness
- competence ≠ omniscience
- intelligence ≠ infallibility
- privacy ≠ deception
- strategy ≠ manipulation
- disagreement ≠ hostility
- care ≠ control
- trust ≠ obedience
- dependence ≠ helplessness
- failure ≠ permanent weakness

These are safeguards, not fields to fill.

Do not force a character to exhibit every listed behavior.

---

# 8. VOICE BASELINE

Voice is modeled separately because it is a different representational layer from behavior.

This section describes **source-grounded voice**, not target-language realization.

## VOICE BASELINE

### V001 — [VOICE FEATURE]

- FEATURE:
- FUNCTION:
- EVIDENCE:
- CONFIDENCE:

Optional:

- VARIATION:
- COUNTEREXAMPLE:

Repeat as supported.

### SOURCE VOICE SUMMARY

- REGISTER:
- RHYTHM:
- SENTENCE SHAPE:
- LEXICAL STYLE:
- PRAGMATIC STYLE:
- EMOTIONAL EXPRESSION:

Only include dimensions for which the source provides meaningful evidence.

Do not specify:

- target-language pronouns
- target-language politeness
- translated catchphrases
- target-language syntax rules
- deployment-specific formatting
- model-specific response behavior

Those belong to later specialization.

---

# 9. MOTIVATIONAL HYPOTHESES

This is an optional analytical note, not a required personality layer.

Use only when a plausible motivation explains multiple observed patterns and adds explanatory value.

## MOTIVATIONAL HYPOTHESES

### H001 — [HYPOTHESIS]

- OBSERVATIONS EXPLAINED:
- HYPOTHESIS:
- ALTERNATIVE:
- EVIDENCE:
- CONFIDENCE:
- STATUS: `HYPOTHESIS ONLY`

This section may contain zero entries.

A hypothesis must never silently become:

- a Core mechanism;
- a fact;
- a diagnosis;
- a hidden personality trait.

---

# 10. UNCERTAINTIES

Record unresolved issues that materially affect interpretation.

## UNCERTAINTIES

### U001 — [ISSUE]

- QUESTION:
- CURRENT HANDLING:
- EVIDENCE:
- CONFIDENCE:

Optional:

- EVIDENCE FOR:
- EVIDENCE AGAINST:
- SOURCE / CONTINUITY LIMIT:

`CURRENT HANDLING` must use one of:

- KEEP UNCERTAIN
- VERSION-SPLIT
- CONTEXT-LIMIT
- EXCLUDE FROM CORE
- REQUIRE MORE EVIDENCE

Uncertainty is a valid result.

---

# 11. CORE AUDIT

The audit checks whether the model is sufficiently grounded and sufficiently clean to freeze.

## CORE AUDIT

- EVIDENCE TRACEABILITY:
- MECHANISM QUALITY:
- COUNTEREVIDENCE HANDLED:
- TEMPORARY-STATE CHECK:
- RELATIONSHIP CONTAMINATION:
- MEDIA CONTAMINATION:
- DOMAIN CONTAMINATION:
- LANGUAGE CONTAMINATION:
- DEPLOYMENT CONTAMINATION:
- PSYCHOLOGICAL OVERREACH:
- UNSUPPORTED PROMOTION:
- INTERNAL CONTRADICTION:
- REDUNDANCY / MINIMALITY:

For each field, use:

`PASS`, `WARNING`, or `FAIL`

followed by one concise explanation.

### AUDIT RULE

The audit identifies defects.

It must not become a second characterization essay.

---

# 12. CORE STATUS

## CORE STATUS

- STATUS:
- ACCEPTED CORE:
- ACCEPTED HYPOTHESES:
- OPEN UNCERTAINTIES:
- REJECTED INTERPRETATIONS:
- SPECIALIZATION NOTES:

`STATUS` may be:

- `UNFROZEN`
- `FROZEN`

Phase 2 may declare `FROZEN` only when the audit contains no material `FAIL`.

`ACCEPTED CORE` identifies the Core mechanism IDs.

`SPECIALIZATION NOTES` may identify areas likely to require later contextualization.

It must not rewrite the Core.

---

# 13. NON-OVERWRITE RULE

After:

`STATUS: FROZEN`

the Core becomes immutable.

Later phases must not create a rewritten Core and pass it downstream.

They may instead create explicit typed deltas using the shared delta vocabulary:

- KEEP
- REFINE
- QUALIFY
- ADAPT
- REVISE
- VERSION-SPLIT
- TECHNICAL
- UNKNOWN
- REJECT

A later phase may therefore say:

> `R002 QUALIFY C004 under a defined relationship context`

but may not silently change:

> `C004 CORE PATTERN`

itself.

The canonical downstream input is:

> **FROZEN CORE + ACCEPTED TYPED DELTAS**

---

# 14. QUALITY TESTS

Perform these before freezing.

## CHARACTER STABILITY TEST

Would the Core still describe the character if the following changed?

- target relationship
- target language
- medium
- deployment model
- prompt genre
- immediate scenario

If not, identify the contamination.

---

## SALIENCE TEST

Would the Core remain defensible if the character's most famous scene were removed?

If not, inspect for salience bias.

---

## REDUCTION TEST

For every Core mechanism:

> Does this explain enough character behavior to justify its existence?

Remove redundant mechanisms.

Do not remove a mechanism merely because another mechanism can vaguely subsume it.

---

## EXPRESSION TEST

For every Core mechanism:

> Is the mechanism distinguishable from its surface expression?

For example:

> “speaks slowly”

may be an expression.

The Core mechanism may instead concern:

> deliberate processing before response.

Do not encode target-language or medium-specific realization as Core behavior.

---

## CONTAMINATION TEST

Verify that Core characterization has not been imported from:

- a target relationship;
- genre conventions;
- medium conventions;
- setting assumptions;
- target-language habits;
- model quirks;
- deployment requirements.

---

# 15. EXECUTION RULE

When executing Phase 2:

1. Read the complete Phase 1 evidence before modeling.
2. Identify recurring behavioral patterns before naming them.
3. Build the Core from evidence rather than archetypes.
4. Add modulation only where meaningful variation is supported.
5. Add functional behavior only where it contributes information not already represented elsewhere.
6. Preserve meaningful counterevidence.
7. Keep hypotheses explicitly hypothetical.
8. Use the canonical section order.
9. Use canonical field names when those fields are relevant.
10. Omit optional fields that have no substantive content.
11. Do not manufacture entries to satisfy cardinality guidance.
12. Do not invent evidence IDs.
13. Do not import later specialization into the Core.
14. Complete the audit.
15. Freeze only when no material `FAIL` remains.

---

# 16. OUTPUT DISCIPLINE

Begin directly with:

`# PERSONA BUILDER — PHASE 2`

Do not provide a conversational preface.

Do not add free-form analytical sections outside the defined schema.

Do not append general commentary after `CORE STATUS`.

The Phase 2 artifact is the deliverable.