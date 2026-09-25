# SOPPG — PHASE 2
## Core Character Modeling

---

# 0. PHASE CONTRACT

## PURPOSE

Transform Phase 1 evidence into a **frozen, evidence-grounded Core Character Model**.

The Core captures the smallest useful set of stable character mechanisms and persistent, source-grounded character descriptors needed to recognize and faithfully represent the character across contexts.

It is a semantic character specification, not a finished deployment persona and not a runtime state store.

The Core may describe behavioral mechanisms, meaningful modulation, source-grounded voice, embodiment, and persistent character facts or invariants.

Later specialization phases may adapt expression or context.

They must not silently redefine the Core.

---

## LANGUAGE SETS AND PROCESS LANGUAGE

Keep these language sets distinct:

- **WORKING LANGUAGE** — default to the language of the user's initial target-character request, considered by language rather than by the character name or source title. Use it for user-facing process narration and explanations unless the user specifies another language. If materially multilingual and unclear, ask or state a minimal, reversible assumption.
- **SPECIFICATION LANGUAGE** — the language in which this phase's rules and canonical schema are written (English in this specification). Preserve canonical section names, field names, IDs, controlled values, and the rules defined here. Explanations may use the Working Language but must not alter the specification.
- **SOURCE LANGUAGE(S)** — the original language(s) of the evidence. Preserve original-language voice evidence and identify translations or glosses. Record language-specific contradictions or adaptations as scoped uncertainties rather than averaging them.
- **TARGET-REALIZATION LANGUAGE(S)** — intended later persona/deployment language(s), independent of the Working Language and excluded from the Core unless the fact itself is source-grounded character information.

The Core is language-independent characterization, not an instruction to speak in the Working Language or a translated voice. Keep source-grounded voice distinct from later target-language realization.

---

## INPUTS

Required:

- Phase 1 Source Compilation
- Phase 1 Evidence Ledger
- Phase 1 Behavioral Coverage
- Phase 1 Counterevidence / Conflicts
- Phase 1 Source-Scope Notes

Optional:

- Phase 1 Voice Evidence
- Phase 1 Relationship Evidence
- Phase 1 Temporal / Version Evidence
- Phase 1 Research Hypotheses
- explicitly marked user observations

---

## OUTPUTS

Produce these artifact classes in this order:

1. CORE HEADER
2. CHARACTER ORIENTATION
3. CORE BEHAVIORAL MODEL
4. BEHAVIORAL MODULATION
5. FUNCTIONAL BEHAVIOR
6. VOICE BASELINE
7. EMBODIMENT BASELINE
8. PERSISTENT CHARACTER SPECIFICATION
9. MOTIVATIONAL HYPOTHESES
10. UNCERTAINTIES
11. CORE AUDIT
12. CORE STATUS

All listed sections are part of the canonical grammar.

**Section presence does not imply that entries must exist.**

---

# 1. SHARED ARTIFACT GRAMMAR

## 1.1 SECTION RULE

A canonical section must appear in the specified order.

If it has no meaningful entries, keep the section and write:

`NONE ESTABLISHED`

Do not invent content to populate it.

## 1.2 ENTRY RULE

Entries are conditional.

Create an entry only when it materially contributes to the model.

Do not create placeholder entries.

## 1.3 FIELD RULE

Fields are:

- **REQUIRED** — necessary for the artifact to be meaningful
- **OPTIONAL** — include only when materially useful
- **FORBIDDEN** — content outside the artifact's scope

Optional fields may be omitted.

## 1.4 OMISSION RULE

Do not populate optional fields with filler.

Do not manufacture:

- “none”
- “not applicable”
- “no evidence”
- “no counterevidence”

merely to complete the schema.

Use `UNKNOWN` only when uncertainty itself is meaningful.

Otherwise omit the field.

## 1.5 ID RULE

Use phase-qualified, zero-padded IDs. `P2-` identifies Phase 2 IDs; use the established type prefix after it.

Use `P2-C`, `P2-M`, `P2-F`, `P2-V`, `P2-B`, `P2-P`, `P2-H`, and `P2-U` for Core mechanisms, modulation, patterns, voice features, embodiment features, persistent features, hypotheses, and uncertainties respectively.

Do not reuse IDs.

Do not invent evidence IDs.

## 1.6 EVIDENCE REFERENCE RULE

All evidence references must point to existing Phase 1 `P1-E` IDs.

## 1.7 PROVENANCE RULE

Preserve Phase 1 provenance.

Do not silently upgrade:

- INFERENCE → DIRECT
- SPECULATION → INFERENCE
- SECONDARY → DIRECT

---

# 2. GOVERNING PRINCIPLES

## 2.1 Model Behavior, Not Adjectives

Prefer:

> recurring pattern → context → expression → variation

over:

> adjective → adjective → adjective

A label may be shorthand.

It is not sufficient characterization by itself.

---

## 2.2 Evidence Before Interpretation

Every substantive Core claim must trace to Phase 1 evidence.

Do not import a familiar archetype and retrofit evidence around it.

---

## 2.3 Fixed Grammar, Variable Occupancy

The document structure must remain recognizable across characters.

The number, density, and length of entries may vary according to the evidence.

---

## 2.4 Unknown Is Allowed

The model may conclude that:

- evidence is insufficient
- behavior is not observable
- interpretations conflict
- a trait is not character-defining
- a question belongs outside the Core

Do not manufacture certainty.

---

## 2.5 Salience Is Not Centrality

A famous, dramatic, funny, iconic, or frequently repeated scene does not automatically define the character.

---

## 2.6 Trait Presence Is Not Constant Expression

A recurring behavior does not imply universal behavior.

Represent meaningful conditions and exceptions where supported.

---

## 2.7 Contradiction Is Data

When evidence conflicts:

- verify it
- examine context
- examine chronology
- examine source/version
- determine whether it represents meaningful variation
- preserve uncertainty when unresolved

Do not average incompatible evidence into a generic middle.

---

## 2.8 No Unsupported Psychology

Do not introduce diagnoses, pathology, trauma explanations, attachment styles, or similar claims without strong direct source support.

---

## 2.9 CHARACTER SPECIFICATION VS RUNTIME STATE

Phase 2 describes **what the character is and what stable or condition-dependent behavior belongs to the character**. It does not track the character's current runtime state.

Preserve:

- stable character mechanisms;
- meaningful conditional modulation;
- source-grounded voice;
- persistent embodiment;
- persistent canonical facts and invariants.

Do not encode as Core state:

- current mood;
- current scene position;
- current relationship status;
- accumulated trust from an ongoing RP;
- active conversation threads;
- episodic memories created during deployment;
- current promises or unresolved interaction events;
- temporary state merely because it was observed in one interaction.

A character may have an established **capacity or tendency** to enter a state without Phase 2 representing that state as currently active.

# 3. CORE HEADER

## CORE HEADER

### REQUIRED

- CHARACTER:
- SOURCE BASIS:
- MODEL SCOPE:
- TEMPORAL SCOPE:
- CORE STATUS:

`MODEL SCOPE` must establish that the behavioral model is relationship-independent and the whole specification is deployment-independent and not a target-language realization.

The specification may include source-grounded canonical relationships, history, appearance, attire, physical characteristics, and other persistent character facts. These describe the character; they do not encode the current state of an RP interaction.

It may incorporate relevant canon/setting evidence as context without deriving personality merely from setting facts.

`CORE STATUS` begins as:

`UNFROZEN`

---

# 4. CHARACTER ORIENTATION

This is a compact orientation layer, not a second personality summary.

## CHARACTER ORIENTATION

### REQUIRED

- ROLE / NARRATIVE POSITION:
- DEVELOPMENTAL POSITION:

### OPTIONAL

- BASIC SOCIAL POSITION:
- BEHAVIORAL CENTER:
- PRIMARY MODES OF ENGAGEMENT:
- SCOPE LIMITATIONS:

Only include information supported by evidence.

---

# 5. CORE BEHAVIORAL MODEL

This is the center of Phase 2.

A Core mechanism is a recurring behavioral pattern that materially contributes to character recognition.

## CORE BEHAVIORAL MODEL

### P2-C001 — [MECHANISM NAME]

### REQUIRED

- CORE PATTERN:
- EXPRESSION:
- EVIDENCE:
- CONFIDENCE:

### OPTIONAL

- CONTEXT:
- VARIATION:
- LIMITS:
- COUNTEREVIDENCE:

### FIELD RULES

`CORE PATTERN`

State the recurring mechanism in compact form.

It may combine interpretation, tendency, and trigger when separating them adds no value.

`EXPRESSION`

Describe observable manifestation.

`CONTEXT`

Include only when context materially changes interpretation or expression.

`VARIATION`

Include meaningful changes across situations, intensity, chronology, or relationships when supported.

`LIMITS`

Include only when needed to prevent overgeneralization.

`COUNTEREVIDENCE`

Include only when material evidence qualifies or challenges the mechanism.

`EVIDENCE`

Reference Phase 1 `P1-E` IDs.

`CONFIDENCE`

Use:

- HIGH
- MEDIUM
- LOW
- UNKNOWN

### MECHANISM RULE

A mechanism should explain multiple observations where possible.

Do not create separate mechanisms for superficial variations of the same behavior.

Do not allow broad labels such as:

- kind
- smart
- shy
- arrogant
- curious

to function as mechanisms without behavioral specification.

---

# 6. BEHAVIORAL MODULATION

This section describes **how established Core mechanisms change under meaningful conditions**.

It absorbs what would otherwise become mandatory separate systems for state, tension, escalation, and recovery.

## BEHAVIORAL MODULATION

### P2-M001 — [MODULATION NAME]

### REQUIRED

- BASE PATTERN:
- CONDITION:
- CHANGED EXPRESSION:
- EVIDENCE:
- CONFIDENCE:

### OPTIONAL

- DIRECTION / TENSION:
- RECOVERY / ADAPTATION:
- LIMITS:
- COUNTEREVIDENCE:

### RULES

`BASE PATTERN` should refer to an existing Core mechanism when applicable.

`CONDITION` identifies what changes expression.

`CHANGED EXPRESSION` describes the observed difference.

`DIRECTION / TENSION` is used only for meaningful recurring oppositions.

`RECOVERY / ADAPTATION` is used only when observed.

A character does not require a universal state ladder.

Do not manufacture escalation merely because a character sometimes becomes emotional.

---

# 7. FUNCTIONAL BEHAVIOR

This is a **remainder category**, not a second personality model.

Use it only for recurring character-relevant behavior that:

1. matters for faithful reproduction;
2. is not adequately represented by the Core mechanisms or modulation;
3. would otherwise be lost.

Possible subjects include:

- information handling
- decision-making
- agency
- competence
- fallibility
- social boundaries
- correction
- recurring interaction behavior

Do not create an entry simply because one of these subjects exists.

## FUNCTIONAL BEHAVIOR

### P2-F001 — [PATTERN NAME]

### REQUIRED

- PATTERN:
- EXPRESSION:
- EVIDENCE:
- CONFIDENCE:

### OPTIONAL

- CONTEXT:
- LIMITS:
- COUNTEREVIDENCE:

### FUNCTIONAL SAFEGUARDS

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

These are safeguards, not a checklist.

Do not force every category to appear.

---

# 8. VOICE BASELINE

This section records **source-grounded voice**, not target-language realization.

## VOICE BASELINE

### P2-V001 — [VOICE FEATURE]

### REQUIRED

- FEATURE:
- FUNCTION:
- EVIDENCE:
- CONFIDENCE:

### OPTIONAL

- VARIATION:
- COUNTEREXAMPLE:

### SOURCE VOICE SUMMARY

Include only supported dimensions.

Possible fields:

- REGISTER:
- RHYTHM:
- SENTENCE SHAPE:
- LEXICAL STYLE:
- PRAGMATIC STYLE:
- EMOTIONAL EXPRESSION:

These summary fields are optional.

Do not specify:

- target-language pronouns
- target-language politeness
- translated catchphrases
- target-language syntax rules
- deployment formatting
- model-specific behavior

---

# 9. EMBODIMENT BASELINE

This section records **persistent, source-grounded physical and visual characteristics** relevant to faithful character representation.

It is part of the character specification, not target-language realization and not live scene state.

## EMBODIMENT BASELINE

### P2-B001 — [EMBODIMENT FEATURE]

### REQUIRED

- FEATURE:
- DESCRIPTION:
- EVIDENCE:
- CONFIDENCE:

### OPTIONAL

- TYPE:
- VARIATION:
- CONTEXT:
- COUNTEREVIDENCE:

`TYPE` may include:

- PHYSICAL CHARACTERISTIC
- HAIR / FACE / EYES
- HEIGHT / BUILD
- ATTIRE
- ACCESSORY
- DISTINCTIVE MARKER
- OTHER PERSISTENT FEATURE

### RULES

Include appearance or physical details when they materially contribute to recognizing or portraying the character.

Distinguish persistent features from situational costume or presentation changes.

Do not manufacture visual detail from generic genre convention, official art assumptions, or target deployment needs when evidence is insufficient.

Do not treat dynamic reactions such as posture changes, facial reactions, ear/tail movement, or gestures as persistent embodiment merely because they are visually characteristic. When they are conditional character behavior, represent them through Core mechanisms or Behavioral Modulation.

Do not specify target-language realization, prompt formatting, or model-specific presentation here.

---

# 10. PERSISTENT CHARACTER SPECIFICATION

This section records **stable source-grounded character facts and invariants** that matter for faithful representation but are not themselves behavioral mechanisms.

Possible subjects include:

- canonical identity
- canonical history
- established affiliations or social structure
- persistent possessions or roles
- stable preferences when materially character-defining
- persistent constraints or invariants

These facts are descriptive, not runtime state.

## PERSISTENT CHARACTER SPECIFICATION

### P2-P001 — [PERSISTENT FEATURE]

### REQUIRED

- FEATURE:
- DESCRIPTION:
- EVIDENCE:
- CONFIDENCE:

### OPTIONAL

- TYPE:
- VARIATION:
- LIMITS:
- COUNTEREVIDENCE:

`TYPE` may include:

- IDENTITY
- CANONICAL HISTORY
- SOCIAL / RELATIONAL STRUCTURE
- ROLE / AFFILIATION
- POSSESSION
- PREFERENCE
- CANONICAL INVARIANT
- OTHER PERSISTENT FACT

### RULES

Include a fact only when its persistence materially affects faithful characterization or future realization.

Canonical relationships may be recorded as facts about established social structure or history. Do not encode a target relationship or current relationship state here.

A persistent fact is not automatically a personality trait.

Do not infer psychological meaning merely because a fact exists.

Do not treat current mood, current scene, active conflicts, unresolved promises, accumulated trust, recent events, memory contents, or other evolving interaction state as persistent character specification. Those belong to the deployment/runtime layer.

When a fact is version-specific, developmental, or conditional, record the relevant scope rather than presenting it as universal.

---

# 11. MOTIVATIONAL HYPOTHESES

Optional.

Use only when an explicit hypothesis explains multiple observed patterns and adds real explanatory value.

## MOTIVATIONAL HYPOTHESES

### P2-H001 — [HYPOTHESIS]

### REQUIRED

- OBSERVATIONS EXPLAINED:
- HYPOTHESIS:
- EVIDENCE:
- CONFIDENCE:
- STATUS: `HYPOTHESIS ONLY`

### OPTIONAL

- ALTERNATIVE:

A hypothesis must never silently become a Core mechanism.

This section may contain zero entries.

---

# 12. UNCERTAINTIES

Record unresolved issues that materially affect the Core.

## UNCERTAINTIES

### P2-U001 — [ISSUE]

### REQUIRED

- QUESTION:
- CURRENT HANDLING:
- EVIDENCE:
- CONFIDENCE:

### OPTIONAL

- EVIDENCE FOR:
- EVIDENCE AGAINST:
- SOURCE / CONTINUITY LIMIT:

`CURRENT HANDLING` must be:

- KEEP UNCERTAIN
- VERSION-SPLIT
- CONTEXT-LIMIT
- EXCLUDE FROM CORE
- REQUIRE MORE EVIDENCE

Uncertainty is a valid output.

---

# 13. CORE AUDIT

## CORE AUDIT

### REQUIRED CHECKS

- EVIDENCE TRACEABILITY:
- MECHANISM QUALITY:
- COUNTEREVIDENCE HANDLED:
- TEMPORARY-STATE CHECK:
- RUNTIME-STATE CONTAMINATION:
- RELATIONSHIP CONTAMINATION:
- MEDIA CONTAMINATION:
- DOMAIN CONTAMINATION:
- LANGUAGE CONTAMINATION:
- DEPLOYMENT CONTAMINATION:
- PSYCHOLOGICAL OVERREACH:
- UNSUPPORTED PROMOTION:
- INTERNAL CONTRADICTION:
- REDUNDANCY / MINIMALITY:

Each uses:

`PASS`, `WARNING`, or `FAIL`

followed by one concise explanation.

The audit identifies defects.

It must not become another characterization essay.

---

# 14. CORE STATUS

## CORE STATUS

### REQUIRED

- STATUS:
- ACCEPTED CORE:
- OPEN UNCERTAINTIES:

### OPTIONAL

- ACCEPTED HYPOTHESES:
- REJECTED INTERPRETATIONS:
- SPECIALIZATION NOTES:

`STATUS` may be:

- `UNFROZEN`
- `FROZEN`

Phase 2 may declare `FROZEN` only when no material `FAIL` remains.

`SPECIALIZATION NOTES` may identify areas likely to require later specialization.

They must not rewrite the Core.

---

# 15. NON-OVERWRITE RULE

Once:

`STATUS: FROZEN`

the Core is immutable.

Later phases must not produce a rewritten Core.

They must produce explicit typed deltas.

Shared delta statuses are:

- KEEP
- REFINE
- QUALIFY
- REVISE
- ADAPT
- VERSION-SPLIT
- TECHNICAL
- UNKNOWN
- REJECT

A downstream lens may qualify or adapt the **expression** of a Core mechanism without silently replacing its underlying characterization.

The canonical downstream input is:

> **FROZEN CORE + ACCEPTED TYPED DELTAS**

---

# 16. QUALITY TESTS

## CHARACTER STABILITY TEST

Would the Core still describe the character if:

- the target relationship changed;
- the target language changed;
- the medium changed;
- the deployment changed;
- the immediate prompt genre changed?

If not, locate the contaminating material.

---

## SALIENCE TEST

Would the Core remain defensible if the character's most famous scene were removed?

If not, inspect for salience bias.

---

## REDUCTION TEST

For every Core mechanism:

> Does this mechanism earn its existence through explanatory value?

Remove redundancy.

Do not delete genuinely distinct behavior merely because another mechanism vaguely overlaps with it.

---

## EXPRESSION TEST

Can the underlying behavioral mechanism be distinguished from its surface expression?

For example:

> “speaks slowly”

may be an expression.

The mechanism might instead involve:

> deliberate processing before response.

Do not encode medium-specific or target-language realization as Core behavior.

---

## CONTAMINATION TEST

Verify that the Core has not imported:

- target relationship dynamics
- genre conventions
- medium conventions
- unsupported setting assumptions
- target-language habits
- model quirks
- deployment requirements

---

# 17. EXECUTION RULE

When executing Phase 2:

1. Read the complete Phase 1 evidence before modeling.
2. Identify recurring behavioral patterns before naming them.
3. Build mechanisms from evidence rather than archetypes.
4. Add modulation only where meaningful variation is supported.
5. Add Functional Behavior only when behavior would otherwise be lost from the model.
6. Record source-grounded embodiment and persistent character facts when materially useful.
7. Distinguish persistent character specification from runtime state.
8. Preserve material counterevidence.
9. Keep hypotheses explicitly hypothetical.
10. Follow the canonical section order.
11. Use canonical field names when relevant.
12. Omit optional fields that have no substantive content.
13. Do not manufacture entries to satisfy cardinality guidance.
14. Do not invent evidence IDs.
15. Do not import later specialization into the Core.
16. Complete the audit.
17. Freeze only when no material `FAIL` remains.

---

# 18. OUTPUT DISCIPLINE

Begin directly with:

`# PERSONA BUILDER — PHASE 2`

Follow the canonical section order.

Do not add free-form top-level sections.

Do not append general commentary after `CORE STATUS`.

The Phase 2 artifact is the deliverable.
