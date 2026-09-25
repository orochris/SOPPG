# PERSONA BUILDER — PHASE 3
## Specialization, Reconciliation & Compilation
### v0.6 — Character Specification → Targeted RP Realization → Specialized Persona Prompt

---

# 0. PHASE CONTRACT

## PURPOSE

Transform a **frozen Phase 2 Character Specification** into a target-context persona by applying explicit specialization lenses, reconciling their interactions, and compiling the accepted result into a **standalone deployment-ready persona prompt**.

Phase 2 now supplies both semantic behavioral mechanisms and stable character specification such as source-grounded voice, embodiment, and persistent canonical facts. Phase 3 realizes that character for the target context without becoming a runtime state manager.

Phase 3 answers:

> **How should the frozen character be realized under these specific conditions?**

Phase 3 does **not** reconstruct the Core.

Phase 3 does **not** silently rewrite the Core.

Phase 3 treats the frozen Core as an authoritative characterization contract and produces explicit, typed specialization deltas around it.

---

## INPUTS

### Required

- Phase 2 FROZEN CHARACTER SPECIFICATION
- target specialization requirements, where applicable

### Specialization inputs may include

- target media / adaptation
- target domain / activity context
- target relationship
- target language
- target deployment environment
- explicit user constraints
- explicit user preferences for realization

### Upstream source material

For a Phase 3 execution following Phase 1, the following are the authoritative upstream research layers and should be available:

- Phase 1 Evidence Ledger
- Phase 1 Voice Evidence
- Phase 1 Relationship Evidence
- Phase 1 Temporal / Version Evidence
- Phase 1 Source-Scope Notes
- Phase 0 source registry and selected corpus

Phase 3 may also inspect the **underlying contents of the already-selected Phase 0 sources**, where access is available, when specialization requires concrete realization details.

### Optional

- accepted Phase 2 hypotheses
- explicitly marked user observations

Phase 3 uses upstream material in two distinct ways:

1. **Evidence verification** — check scope, provenance, continuity, or a claim already present in Phase 1.
2. **Realization mining** — inspect selected source material to recover concrete dialogue patterns, interactional moves, recurring quirks, variation, and example-worthy behavior that Phase 2 necessarily compressed.

For interactive RP targets, `REALIZATION MINING` is a required part of the process whenever the selected corpus contains usable source material.

Phase 3 must not:

- silently expand the selected source corpus;
- reopen Phase 1 as a new unrestricted research phase;
- perform a fresh whole-character modeling pass from raw evidence;
- use upstream evidence to silently replace the frozen Character Specification;
- treat Phase 1 summaries as a substitute for source inspection when the underlying selected source is accessible and concrete realization matters.

If a specialization reveals a material problem in the frozen Character Specification, record it explicitly as `REVISE` or `VERSION-SPLIT`.

Revision of the frozen Core or other character specification belongs to a subsequent Phase 2 execution.

---

## FROZEN CHARACTER SPECIFICATION RULE

The Phase 2 Character Specification is authoritative.

It contains:

- Core behavioral mechanisms;
- Behavioral Modulation;
- Functional Behavior;
- source-grounded Voice Baseline;
- source-grounded Embodiment Baseline;
- Persistent Character Specification.

Phase 3 may realize these elements for the target. It must not convert runtime state into a character fact merely because the RP currently exhibits it.

### RUNTIME STATE BOUNDARY

Phase 3 may describe **how the character tends to respond when runtime conditions occur**, because those conditional tendencies belong to the character specification. It must not store or prescribe the actual current runtime condition.

Do not compile as character state:

- current mood;
- current scene location or activity unless explicitly part of the target setup;
- accumulated trust or relationship state from an ongoing RP;
- active unresolved events or promises;
- episodic memories created during deployment;
- current emotional state;
- turn-by-turn continuity.

These belong to the RP frontend / runtime layer.

If:

> `CORE STATUS: FROZEN`

then Phase 3 may:

- preserve behavioral mechanisms and their modulation;
- qualify or adapt their expression;
- realize source-grounded voice for the target language;
- realize source-grounded embodiment and persistent character facts for RP;
- add target-specific context;
- identify a possible upstream modeling problem;
- mark a version split;
- reject an incompatible specialization;
- impose technical realization constraints.

Phase 3 may **not** silently replace the Character Specification.

A substantive disagreement with the frozen Character Specification must be represented explicitly as a typed delta or unresolved issue.

---

## SINGLE-EXECUTION RULE

Phase 3 is a **single specialization and compilation pass** over the frozen character specification.

The specialization lenses are not serial character rewrites.

They are analytical views over the same frozen Character Specification.

A lens does not automatically replace the input to another lens.

Cross-lens dependencies are resolved during `CROSS-LENS RECONCILIATION`.

---

# OUTPUTS

Produce these artifact classes in this order:

1. PHASE 3 HEADER
2. FROZEN CHARACTER SPECIFICATION REFERENCE
3. SPECIALIZATION TARGET
4. SPECIALIZATION LENSES
5. CROSS-LENS RECONCILIATION
6. PERSONA COMPILATION
7. SINGLE AUDIT
8. PHASE 3 STATUS

All listed sections are part of the canonical grammar.

Section presence does not imply that entries must exist.

`COMPILATION TRACE` is conditional and belongs inside `PERSONA COMPILATION` when needed.

`FINAL PERSONA PROMPT` is the principal deployment artifact.

---

# 1. SHARED ARTIFACT GRAMMAR

## 1.1 SECTION RULE

A canonical section must appear in the specified order.

If a section has no meaningful entries, keep it structurally present and write:

`NONE ESTABLISHED`

Do not invent content merely to populate the section.

---

## 1.2 ENTRY RULE

Entries are conditional.

Create an entry only when it materially contributes to specialization, reconciliation, compilation, or audit.

Do not create placeholder entries.

---

## 1.3 FIELD RULE

Fields are:

- **REQUIRED** — necessary for the artifact to be meaningful
- **OPTIONAL** — include only when materially useful
- **FORBIDDEN** — content outside Phase 3 scope

Optional fields may be omitted.

---

## 1.4 OMISSION RULE

Do not fill optional fields with filler such as:

- none
- not applicable
- no evidence
- no conflict

unless the absence itself materially affects the decision.

Otherwise omit the field.

---

## 1.5 ID RULE

Use zero-padded IDs.

### Specialization deltas

`D001`, `D002`, `D003` ...

### Reconciliation issues

`RX001`, `RX002`, `RX003` ...

### Compilation trace entries

`CP001`, `CP002`, `CP003` ...

Do not reuse IDs.

---

## 1.6 REFERENCE RULE

All references to the Core must point to existing Phase 2 identifiers where applicable.

All references to evidence must point to existing Phase 1 evidence IDs where applicable.

Do not invent upstream IDs.

---

## 1.7 DELTA STATUS RULE

Use the shared typed delta vocabulary:

- `KEEP`
- `REFINE`
- `QUALIFY`
- `REVISE`
- `ADAPT`
- `VERSION-SPLIT`
- `TECHNICAL`
- `UNKNOWN`
- `REJECT`

### Meanings

`KEEP`

The Core mechanism or existing realization transfers without material change.

`REFINE`

The specialization supplies a more precise expression without changing the underlying Core mechanism.

`QUALIFY`

The specialization establishes a boundary, condition, or exception to prevent overgeneralization.

`REVISE`

The specialization exposes a potentially material mismatch in the Core.

A `REVISE` delta does **not** rewrite the frozen Core.

It records an issue for possible future Core revision.

`ADAPT`

The underlying characterization remains intact, but its surface realization changes for the target.

`VERSION-SPLIT`

The target cannot be represented safely as one undifferentiated realization because continuity, adaptation, or version differences materially matter.

`TECHNICAL`

The change exists because of deployment or implementation constraints rather than because the character itself differs.

`UNKNOWN`

The available basis is insufficient to determine the correct specialization.

`REJECT`

The proposed specialization would improperly alter, contradict, or contaminate the Core and is therefore not accepted.

---

## 1.7 REALIZATION MATERIAL RULE

Phase 3 may generate **realization material** that demonstrates how accepted characterization should sound or behave in the target deployment.

Realization material may include:

- dialogue patterns;
- example voice lines;
- behavioral-quirk examples;
- contrastive examples showing common failure modes.

These are **compiled demonstrations, not new evidence**. They must be derived from the frozen Core, accepted specialization deltas, accepted reconciliation decisions, or explicit technical requirements.

Do not present generated examples as canon quotations unless they are explicitly sourced and marked as such.

Examples demonstrate a behavioral rule; they do not become rigid scripts.

---

# 2. PHASE 3 HEADER

## PHASE 3 HEADER

### REQUIRED

- CHARACTER:
- CHARACTER SPECIFICATION VERSION:
- CORE STATUS:
- SPECIALIZATION SCOPE:
- PHASE 3 STATUS:

### OPTIONAL

- TARGET DEPLOYMENT:

`CORE STATUS` must confirm:

`FROZEN`

If the supplied Core is not frozen, Phase 3 must not treat it as an immutable characterization contract.

`PHASE 3 STATUS` begins as:

`OPEN`

---

# 3. FROZEN CHARACTER SPECIFICATION REFERENCE

This is a **minimal reference layer**, not a rewritten character specification.

## FROZEN CHARACTER SPECIFICATION REFERENCE

### REQUIRED

- SPECIFICATION SOURCE:
- RELEVANT CORE MECHANISMS:
- RELEVANT MODULATION:
- RELEVANT CHARACTER SPECIFICATION:

### OPTIONAL

- MATERIAL CORE UNCERTAINTIES:
- RELEVANT VOICE BASELINE:
- RELEVANT EMBODIMENT BASELINE:
- RELEVANT PERSISTENT CHARACTER SPECIFICATION:
- RELEVANT FUNCTIONAL BEHAVIOR:

Only include Character Specification material necessary to interpret the specialization.

Do not restate the entire specification unless required for traceability.

Do not modify Core meaning for convenience.

---

## 3.1 CHARACTER SPECIFICATION INVARIANT RULE

Identify the aspects of the frozen character specification that specialization must preserve.

Typical invariants may include:

- recurring behavioral mechanisms;
- meaningful boundaries;
- agency;
- characteristic decision patterns;
- established fallibility;
- established uncertainty;
- source-grounded voice properties;
- persistent embodiment;
- persistent canonical facts;
- meaningful modulation.

Do not manufacture invariants.

---

## 3.2 CHARACTER SPECIFICATION UNCERTAINTY RULE

Carry forward material Phase 2 uncertainties affecting the character specification.

Do not convert unresolved Core uncertainty into certainty merely because a usable target persona is desired.

Phase 3 may narrow uncertainty only when the specialization conditions or existing evidence actually justify doing so.

---

# 4. SPECIALIZATION TARGET

This section defines the conditions under which the Core will be realized.

## SPECIALIZATION TARGET

### REQUIRED

- MEDIA:
- DOMAIN:
- RELATIONSHIP:
- LANGUAGE:
- DEPLOYMENT:

### OPTIONAL

- TARGET CONTINUITY / VERSION:
- USER ROLE:
- TASK TYPE:
- OUTPUT FORMAT:
- SPECIAL CONSTRAINTS:

An input may be:

- explicit;
- inherited from a known target;
- unresolved.

Do not invent missing target conditions.

---

## 4.1 TARGET SCOPE RULE

The target specification describes the **condition of realization**.

It is not evidence that the character inherently possesses traits associated with that condition.

For example:

> a professional domain may change what the character talks about

without proving:

> the character is professionally oriented by nature.

Likewise:

> a close relationship may permit more explicit affection

without proving:

> the Core is fundamentally dependent or romantic.

---

# 5. SPECIALIZATION LENSES

## 5.0 LENS RULE

Analyze each applicable specialization against:

> **the same frozen Core**

not against another lens's rewritten character.

The lenses may inform one another.

They do not overwrite one another.

Every substantive specialization must produce a typed delta.

Not every lens requires a substantive delta.

---

## 5.0A SOURCE-INFORMED REALIZATION PASS

Before compiling an interactive RP persona, perform a **targeted realization pass over the selected upstream corpus**.

This is not a new Phase 1.

Its purpose is to recover source-level detail that may have been lost when Phase 1 was compressed into the evidence ledger and Phase 2 into the frozen Character Specification.

### REQUIRED PROCESS

1. Start from the frozen Character Specification and target conditions.
2. Identify which Core mechanisms need concrete conversational realization.
3. Locate the relevant Phase 1 evidence entries.
4. Follow those entries back to the selected `SRC` sources.
5. Inspect the underlying source material when accessible.
6. Extract only material useful for specialization and live realization.
7. Preserve original provenance and scope.
8. Distinguish ordinary/recurrent behavior from salient one-off scenes.
9. Seek variation, counterexamples, and natural stopping behavior.
10. Compile the result into dialogue patterns, example voice lines, behavioral-quirk examples, and contrastive boundaries where useful.

### SOURCE-INSPECTION PRIORITY

Prefer, in order of usefulness to realization:

- direct primary dialogue and scenes;
- faithful transcripts or reproductions of primary dialogue;
- Phase 1 evidence summaries when underlying material is inaccessible;
- secondary interpretation only when it contributes something not otherwise recoverable.

Do not silently upgrade provenance.

### REALIZATION MINING QUESTIONS

Ask:

- What does this mechanism sound like in an actual turn?
- How does she typically open or extend an interaction?
- How does she react when surprised?
- How does she challenge or disagree?
- What does agreement look like?
- How does curiosity intensify?
- What makes her stop pursuing a topic?
- What recurring small behaviors or verbal habits distinguish her from a generic version of the archetype?
- Which physical or visual features are persistent and useful to mention in RP?
- Which established attire, accessories, possessions, or canonical facts should remain stable across scenes?
- Which physical reactions are conditional behaviors rather than persistent appearance?
- Which behaviors vary by context, relationship, or developmental state?

### SCOPE RULE

Mine the corpus **for realization**, not for a new personality verdict.

Do not reopen questions already settled by the frozen Character Specification merely because a source contains an interesting alternative interpretation.

If raw source material appears to materially contradict the frozen Character Specification, record a `REVISE` or `VERSION-SPLIT` issue rather than silently changing the model.

### ORDINARY-BEHAVIOR PRIORITY

When selecting demonstration material, prefer ordinary, recurring, interaction-rich scenes where possible.

Do not build the realization layer primarily from:

- iconic scenes;
- maximum-drama scenes;
- isolated jokes;
- one-time emotional peaks;
- fan-favorite quotations.

Salient material may still be used when it captures a genuinely recurring mechanism.

### REALIZATION EVIDENCE RECORD

When realization material materially affects the compiled persona, record a concise internal basis using existing `SRC` and Phase 1 `E` references.

Do not create fake new evidence IDs merely because a source was inspected again.

---

## 5.1 MEDIA LENS

The Media lens determines whether medium, adaptation, performance, editing, gameplay, narration, or presentation materially affect realization.

### MEDIA SPECIALIZATION

### D001 — [DELTA]

### REQUIRED

- CORE REFERENCE:
- CHANGE:
- STATUS:
- BASIS:
- SCOPE:

### OPTIONAL

- EXPRESSION:
- VERSION:
- PRESENTATION EFFECT:
- DEPENDENCY:
- LIMITATION:

### RULES

Distinguish:

- character evidence;
- medium-specific presentation;
- adaptation behavior;
- performance effects;
- gameplay effects;
- editorial effects;
- localization effects.

Do not convert a medium convention into an intrinsic character mechanism.

A media delta may determine:

> **how an established Core mechanism is represented**

without determining:

> **what the mechanism fundamentally is.**

---

## 5.2 DOMAIN LENS

The Domain lens determines how the target activity, setting, professional context, specialized task, or knowledge domain changes expression.

### DOMAIN SPECIALIZATION

### D002 — [DELTA]

### REQUIRED

- CORE REFERENCE:
- CHANGE:
- STATUS:
- BASIS:
- SCOPE:

### OPTIONAL

- EXPRESSION:
- DOMAIN CONDITION:
- DEPENDENCY:
- LIMITATION:
- COUNTEREVIDENCE:

### RULES

Domain specialization may alter:

- subject matter;
- terminology;
- examples;
- task behavior;
- contextual priorities;
- practical expression of established competencies;
- interaction patterns required by the domain.

Do not derive personality merely from the domain role.

Do not convert:

> domain competence

into:

> universal competence.

Do not convert:

> task familiarity

into:

> omniscience.

Do not allow domain conventions to overwrite the Core.

---

## 5.3 RELATIONSHIP LENS

The Relationship lens determines how the target relationship changes expression of the frozen Character Specification.

### RELATIONSHIP SPECIALIZATION

### D003 — [DELTA]

### REQUIRED

- CORE REFERENCE:
- CHANGE:
- STATUS:
- BASIS:
- SCOPE:

### OPTIONAL

- RELATIONSHIP CONDITION:
- EXPRESSION:
- RECIPROCITY:
- BOUNDARY:
- DEPENDENCY:
- LIMITATION:

### RULES

Relationship specialization may alter:

- openness;
- disclosure;
- warmth;
- teasing;
- guardedness;
- directness;
- trust expression;
- conflict expression;
- practical support;
- conversational assumptions.

Do not infer:

- romance from affection;
- dependence from trust;
- obedience from authority;
- intimacy from importance;
- possessiveness from protectiveness;

unless the target relationship specification and evidence support the distinction.

A relationship delta must remain relationship-scoped.

Do not convert target-specific expression into Core personality.

---

## 5.4 LANGUAGE LENS

The Language lens determines how the frozen characterization should be realized in the target language.

### LANGUAGE SPECIALIZATION

### D004 — [DELTA]

### REQUIRED

- CORE REFERENCE:
- CHANGE:
- STATUS:
- BASIS:
- FUNCTION:

### OPTIONAL

- REGISTER:
- PRAGMATIC REALIZATION:
- RHYTHM:
- LEXICAL REALIZATION:
- POLITENESS:
- PRONOUN / ADDRESS:
- RELATIONSHIP INTERACTION:
- LIMITATION:

### RULES

The Language lens adapts expression, not underlying character mechanisms.

Preserve where supported:

- communicative function;
- degree of directness;
- emotional restraint;
- rhetorical behavior;
- social stance;
- interactional boundaries;
- meaningful voice distinctions.

Target-language realization may change:

- pronouns;
- register;
- politeness;
- syntax;
- rhythm;
- lexical choice;
- discourse markers;
- address forms.

These are realization choices unless evidence shows otherwise.

Do not introduce target-language habits merely because they are common stereotypes.

Where source-language voice evidence exists, use it as the semantic and pragmatic basis for realization.

---

## 5.5 EMBODIMENT & PERSISTENT CHARACTER REALIZATION LENS

The Embodiment & Persistent Character Realization lens determines **how source-grounded physical appearance, attire, visual markers, and persistent canonical character facts should appear in the target realization**, especially for interactive RP.

This lens realizes **static character specification**. It does not manage dynamic scene state, current emotion, or turn-by-turn continuity.

### D005 — [DELTA]

### REQUIRED

- CHARACTER SPECIFICATION REFERENCE:
- CHANGE:
- STATUS:
- BASIS:
- SCOPE:

### OPTIONAL

- APPEARANCE REALIZATION:
- ATTIRE REALIZATION:
- PHYSICAL / VISUAL CUES:
- PERSISTENT FACT REALIZATION:
- CONTEXTUAL VARIATION:
- RP FUNCTION:
- LIMITATION:

### RULES

For interactive RP, include appearance statements when they materially improve character fidelity or scene grounding.

Where the frozen specification establishes them, preserve relevant:

- physical characteristics;
- hair / face / eyes;
- height / build where useful;
- characteristic attire;
- persistent accessories;
- distinctive visual markers;
- persistent possessions, affiliations, roles, or other canonical facts.

Distinguish three things:

```text
PERSISTENT CHARACTER FEATURE
→ what remains true of the character.

CONTEXTUAL REALIZATION
→ how that feature is presented in this target situation.

RUNTIME EVENT / STATE
→ what is happening to the character right now.
```

Only the first two belong in Phase 3.

Dynamic physical behavior may be realized when it is an established or accepted conditional character behavior, such as a recurring gesture, posture shift, facial reaction, or ear/tail movement. Do not encode the current occurrence of that behavior as persistent state.

Do not invent appearance from genre convention, visual stereotypes, or unsupported art assumptions.

Do not compile a current outfit, current location, current expression, current injury, or similar transient fact as persistent characterization unless the target explicitly establishes it as fixed context.

### RP EMBODIMENT REALIZATION

For interactive RP, the final prompt may state concise scene-facing guidance such as:

> Include established appearance and attire naturally when scene description makes them relevant; do not repeat a character sheet mechanically every turn.

> Let established physical cues support emotional realization when the relevant state or behavior is actually triggered; do not force them on every turn.

The purpose is to make the character **embodied**, not to make every response visually descriptive.

---

## 5.6 DIALOGUE & BEHAVIORAL REALIZATION LENS

The Dialogue & Behavioral Realization lens determines **how the specialized character's stable behavioral repertoire should actually sound and behave in live interaction**, without becoming a runtime state manager or creating a new Core.

It exists because a semantically correct Core may still be under-specified for an interactive language model. Concrete dialogue patterns, examples, selective quirks, and conditional realizations may therefore be needed to make the intended repertoire reproducible.

The lens may describe **recoverable modes or conditional registers** when those are established in the frozen specification, but it must specify them as character capabilities or tendencies rather than as currently active state.

For interactive RP targets, this lens must be informed by the `SOURCE-INFORMED REALIZATION PASS` whenever selected source material is accessible. Do not derive the dialogue layer solely from Phase 2 abstractions or generic knowledge of the character.

### D006 — [DELTA]

### REQUIRED

- CORE REFERENCE:
- CHANGE:
- STATUS:
- BASIS:
- SCOPE:

### OPTIONAL

- ORIGIN:
- SOURCE BASIS:
- DIALOGUE PATTERNS:
- EXAMPLE VOICE LINES:
- BEHAVIORAL QUIRKS:
- SELECTIVITY / VARIATION:
- CONTRASTIVE BOUNDARIES:
- LIMITATION:

### RULES

The realization lens may specify:

- recurrent conversational moves;
- preferred turn shapes;
- characteristic ways of reacting, questioning, teasing, agreeing, disagreeing, or following up;
- representative example lines;
- selective recurring quirks that deepen an existing Core mechanism;
- conditions under which a quirk appears, intensifies, or stops.

`ORIGIN` may distinguish:

- `EVIDENCE-GROUNDED` — directly supported by upstream material;
- `TARGET-INFERRED` — a narrow realization inference supported by the target conditions;
- `USER-SUGGESTED` — explicitly proposed by the user;
- `THEORIZED` — a model-generated hypothesis or extrapolation.

`SOURCE BASIS` should identify the relevant Phase 1 `E` IDs and/or selected `SRC` IDs when the realization feature was materially informed by upstream source inspection.

A final example may be synthetic, but the **behavioral function it demonstrates should be source-grounded or explicitly identified as a target inference or theorized realization**.

A `THEORIZED` or `TARGET-INFERRED` quirk is not canon evidence. It may be accepted as a target realization only when it clearly amplifies the frozen Core, remains bounded, and is marked as extrapolative in the analysis layer.

#### DIALOGUE PATTERNS

A dialogue pattern describes an **interactional sequence**, not a mandatory template.

Useful pattern forms include:

```text
observation → reaction → personal addition → conversational return
claim → playful challenge → example or counterexample → shared conclusion or continued disagreement
surprise → self-correction → renewed interest → follow-up
shared reference → association → brief detour → return to the original topic
interesting anomaly → optional rabbit hole → natural stopping point
```

Patterns should be used selectively. Do not force a pattern on every turn.

#### EXAMPLE VOICE LINES

Use a small number of short, diverse lines that demonstrate the intended voice in context.

Examples should demonstrate **function and texture**, not become catchphrases to repeat mechanically.

Where multiple target languages are required, examples may be provided separately for each language, preserving equivalent pragmatic function rather than literal translation.

Do not use mixed-language examples merely to demonstrate multilingual capability unless mixed-language speech is itself an accepted specialization.

#### BEHAVIORAL QUIRKS

A behavioral quirk should preferably be specified as:

> **trigger → tendency → optional escalation → natural stopping condition**

Prefer quirks that amplify an existing Core mechanism rather than introducing a new personality trait.

A quirk is a selective tendency, not a permanent gimmick.

When a realization feature depends on a runtime condition, describe the **trigger and characteristic response**, not the claim that the character is presently in that condition. Runtime activation belongs to the deployment layer.

For example:

```text
CHARACTER SPECIFICATION:
meaningful failure can trigger childish refusal and sulking.

RUNTIME STATE:
the character is currently upset about today's failed attempt.
```

Only the first belongs in the persona prompt.

#### SELECTIVITY / VARIATION

Realization should preserve **attention gradients and behavioral variance**.

A character may:

- notice something without pursuing it;
- pursue an interesting detail briefly and then stop;
- become deeply engaged when a detail is unusually unresolved;
- agree without needing to challenge;
- disagree when disagreement creates useful discovery;
- be surprised and revise an assumption;
- respond ordinarily when nothing especially distinctive is happening.

Do not turn a recurring mechanism into a universal response rule.

#### CONTRASTIVE BOUNDARIES

When useful, state a likely failure mode beside the intended realization.

For example:

```text
NOT: challenge every opinion
INSTEAD: challenge when the disagreement opens an interesting question

NOT: know every obscure fact
INSTEAD: enjoy discovering unfamiliar information

NOT: turn every curiosity into a major investigation
INSTEAD: sometimes follow the rabbit hole, sometimes let it go
```

These contrasts are guardrails, not negative personality definitions.

#### INTERACTIVE RP COMPLETENESS

For conversational LLM roleplay, when the realization lenses are materially applicable, the compiler should ordinarily include the useful subset of these four components:

- concise embodiment / appearance guidance;
- dialogue patterns;
- example voice lines;
- behavioral-quirk or conditional-reaction examples.

They need not be numerous. Prefer a small, diverse set that covers distinct interactional situations and makes the character easy to portray rather than merely easy to describe.

Omit a component only when it would add no useful information, conflict with the target, or exceed a justified deployment budget. Do not satisfy this guidance through redundant examples.

### REALIZATION SAFEGUARDS

Do not allow realization material to:

- overwrite the frozen Core;
- become mandatory response templates;
- collapse the character into a catchphrase;
- imply universal enthusiasm;
- equate disagreement with personality;
- turn quirks into constant gimmicks;
- convert generated examples into purported canon evidence;
- introduce unsupported psychology.

---

## 5.7 DEPLOYMENT LENS

The Deployment lens is a **technical realization lens**, not a new characterization layer.

It determines how the already-specialized character can be represented under the constraints of the target system.

### DEPLOYMENT SPECIALIZATION

### D007 — [DELTA]

### REQUIRED

- CORE / SPECIALIZATION REFERENCE:
- CHANGE:
- STATUS:
- TECHNICAL FUNCTION:

### OPTIONAL

- BASIS:
- MODEL CONSTRAINT:
- CONTEXT / MEMORY CONSTRAINT:
- FORMAT:
- GENERATION CONSTRAINT:
- LIMITATION:

### RULES

Deployment specialization may alter:

- prompt representation;
- instruction structure;
- context allocation;
- memory cues;
- formatting;
- verbosity;
- output constraints;
- explicitness;
- technical safeguards;
- model-specific implementation.

Deployment constraints must not silently become characterization.

Do not encode:

> model weakness

as:

> character weakness.

Do not encode:

> context-window limitation

as:

> forgetfulness.

Do not encode:

> generation instability

as:

> emotional inconsistency.

Do not encode:

> prompt formatting requirements

as:

> personality rules.

Deployment is a realization constraint.

---

# 6. CROSS-LENS RECONCILIATION

This section resolves interactions among specialization deltas.

It does not revise the Core directly.

## CROSS-LENS RECONCILIATION

### RX001 — [ISSUE]

### REQUIRED

- DELTAS INVOLVED:
- ISSUE:
- RECONCILIATION:
- STATUS:

### OPTIONAL

- DEPENDENCY:
- CONFLICT TYPE:
- REASON:
- REMAINING UNCERTAINTY:

---

## 6.1 RECONCILIATION QUESTIONS

Check whether specialization lenses introduce:

- contradictions;
- scope collisions;
- incompatible assumptions;
- accidental propagation;
- duplicate adaptations;
- language choices mistaken for behavior;
- deployment fixes mistaken for characterization;
- adaptation differences mistaken for canon;
- relationship behavior generalized beyond the target relationship;
- domain assumptions generalized into personality;
- presentation effects generalized into the character.

---

## 6.2 NON-AVERAGING RULE

Do not resolve incompatible evidence or deltas by averaging them into an artificial middle.

When conflict remains:

- narrow the scope;
- preserve the distinction;
- version-split;
- mark unknown;
- reject the unsupported delta;
- or flag the Core for future revision.

---

## 6.3 PRECEDENCE RULE

When resolving conflicts, use this order:

### 1. Frozen Character Specification integrity

A specialization cannot silently overwrite the frozen Character Specification.

### 2. Explicit target specification

Explicit user-provided target conditions take precedence over inferred conditions.

### 3. Scoped evidence

A narrow, context-specific claim should not be generalized beyond its demonstrated scope.

### 4. Stronger provenance

Where relevant, direct or appropriately verified evidence takes precedence over weaker secondary interpretation.

### 5. Minimal necessary change

Prefer the smallest specialization necessary to satisfy the target conditions.

### 6. Explicit uncertainty

When no defensible resolution exists, preserve uncertainty.

---

## 6.4 PROPAGATION RULE

Track a delta as:

- `LOCAL`
- `DEPENDENT`
- `CROSS-LENS`
- `TECHNICAL`

where this distinction materially affects reconciliation.

Do not allow a contextual implication to become a global character rule without justification.

---

## 6.5 UPSTREAM EVIDENCE RULE

Phase 3 may return to Phase 1 evidence only to:

- verify a specialization claim;
- resolve a scope question;
- distinguish source/version behavior;
- support a delta already under consideration.

It must not use upstream evidence to conduct a new character-modeling pass.

If upstream material appears to invalidate a frozen Core mechanism, record:

`REVISE`

or:

`VERSION-SPLIT`

and preserve the frozen Character Specification.

---

# 7. PERSONA COMPILATION

The compiler produces the final target persona from:

> **FROZEN CHARACTER SPECIFICATION + ACCEPTED SPECIALIZATION DELTAS + REALIZATION MATERIAL + RECONCILIATION DECISIONS + TECHNICAL DEPLOYMENT CONSTRAINTS**

## PERSONA COMPILATION

### REQUIRED

- SOURCE CHARACTER SPECIFICATION:
- ACCEPTED DELTAS:
- REJECTED / DEFERRED DELTAS:
- REALIZATION MATERIAL:
- FINAL PERSONA PROMPT:

### OPTIONAL

- PRESERVED CORE FEATURES:
- TARGET-SPECIFIC REALIZATION:
- DIALOGUE PATTERNS:
- EXAMPLE VOICE LINES:
- BEHAVIORAL QUIRKS:
- TECHNICAL REALIZATION:
- UNRESOLVED LIMITATIONS:

---

## 7.1 FINAL PERSONA PROMPT RULE

`FINAL PERSONA PROMPT` is the **standalone deployment artifact**.

Unless another format is explicitly requested, produce it as **Markdown persona-prompt text** suitable for direct insertion into the target deployment system.

The final prompt must:

- function independently of the Phase 3 analysis;
- contain the necessary target-specific realization;
- preserve the semantic Core and relevant character specification;
- incorporate accepted specialization;
- incorporate necessary embodiment / appearance realization and persistent character facts for the target when relevant;
- incorporate necessary deployment instructions;
- avoid requiring the downstream system to reconstruct the Phase 3 reasoning.

For interactive RP, the final prompt describes the character's **stable repertoire and scene-facing realization**, not the character's current runtime state.

It may say how the character tends to react when embarrassed, excited, disappointed, or otherwise triggered. It must not state that such a state is currently active unless the target setup explicitly establishes it.

Do not include:

- Phase 3 deliberation;
- delta ledgers;
- audit commentary;
- internal research notes;
- unsupported explanatory material

inside the final prompt unless such material is itself required for deployment.

---

## 7.2 COMPILATION RULE

The compiler must preserve the semantic Core and relevant stable character specification while realizing accepted specialization.

It may:

- reorganize information;
- shorten information;
- expand information;
- change ordering;
- convert semantic mechanisms into deployment instructions;
- realize target-language voice;
- incorporate relationship-specific behavior;
- incorporate source-grounded embodiment and persistent character facts;
- incorporate domain-specific context;
- incorporate medium-specific framing;
- encode technical deployment constraints.

It must not:

- silently remove meaningful Core mechanisms;
- silently add unsupported personality;
- generalize contextual behavior into baseline behavior;
- convert language realization into character mechanism;
- convert deployment behavior into personality;
- turn hypotheses into established facts;
- erase material uncertainty;
- replace the frozen Character Specification with a newly interpreted character.

---

## 7.3 REALIZATION COMPILATION RULE

For interactive text RP, the final persona should normally contain a compact **demonstration layer** when it materially improves behavioral reproducibility.

The demonstration layer may include:

- concise embodiment / appearance guidance;
- dialogue patterns;
- a small set of example voice lines;
- a small set of behavioral-quirk examples;
- conditional mode / register examples where materially useful;
- concise contrastive boundaries for common failure modes.

For interactive RP, prefer the full three-part set when applicable, while keeping it compact and diverse.

Use the demonstration layer to answer:

> **What does this character tend to do or sound like in an actual turn?**

while the frozen Core answers:

> **What underlying behavior must remain invariant?**

Demonstrations must remain:

- short;
- behaviorally diverse;
- semantically traceable;
- non-prescriptive;
- free of unsupported canon claims.

Do not create so many examples that the prompt becomes a script or encourages phrase imitation. When space is limited, preserve **behavioral diversity over example count**.

Do not compile `THEORIZED` or `TARGET-INFERRED` material as if it were independently established canon. Keep the distinction visible through wording, selectivity, or compilation trace as needed.

---

## 7.4 MINIMALITY RULE

Use the smallest sufficient compiled prompt.

Do not preserve every upstream research artifact in the deployment prompt.

The compiler should preserve:

> **semantic necessity**

rather than:

> **documentary volume.**

---

## 7.5 LOSSLESS-SEMANTICS RULE

Compression is permitted.

Semantic loss is not.

If a compressed prompt cannot preserve a material Core mechanism, retain enough explicit information to preserve it.

---

## 7.6 EXPRESSION / MECHANISM RULE

Preserve the distinction between:

> underlying mechanism

and:

> target-specific expression.

For example:

```text
CORE MECHANISM
→ deliberate processing before response

LANGUAGE REALIZATION
→ measured target-language phrasing

RELATIONSHIP REALIZATION
→ greater explicitness with trusted person

DEPLOYMENT REALIZATION
→ implementation instructions that preserve the mechanism
```

Do not collapse these into one undifferentiated personality statement.

---

## 7.7 COMPILATION TRACE

Use only when the final persona contains material transformations whose provenance would otherwise be difficult to inspect.

### CP001 — [COMPILED ELEMENT]

### REQUIRED

- FINAL ELEMENT:
- BASIS:
- REASON:

### OPTIONAL

- RECONCILIATION:
- COMPRESSION NOTE:

Do not create a trace entry for every sentence or instruction.

Do not reproduce the upstream artifacts.

---

## 7.8 TRACEABILITY RULE

Every substantive final-persona element must be traceable to at least one of:

- frozen Core mechanism;
- accepted specialization delta;
- accepted realization material;
- accepted reconciliation decision;
- technical deployment requirement.

Unsupported additions are defects.

---

# 8. SINGLE AUDIT

The audit evaluates the completed specialization and compilation as one system.

## SINGLE AUDIT

### REQUIRED CHECKS

- CORE PRESERVATION:
- DELTA TRACEABILITY:
- UPSTREAM SOURCE REVIEW:
- SOURCE-LEVEL REALIZATION BASIS:
- REALIZATION TRACEABILITY:
- EMBODIMENT / PERSISTENT CHARACTER PRESERVATION:
- DIALOGUE / VOICE DEMONSTRATION QUALITY:
- QUIRK SELECTIVITY:
- THEORIZED-MATERIAL BOUNDARY:
- SPECIALIZATION SCOPE:
- CROSS-LENS PROPAGATION:
- MEDIA CONTAMINATION:
- DOMAIN CONTAMINATION:
- RELATIONSHIP CONTAMINATION:
- LANGUAGE CONTAMINATION:
- DEPLOYMENT CONTAMINATION:
- TECHNICAL / CHARACTER SEPARATION:
- COUNTEREVIDENCE / UNCERTAINTY:
- PSYCHOLOGICAL OVERREACH:
- UNSUPPORTED ADDITIONS:
- INTERNAL CONTRADICTION:
- SEMANTIC LOSS:
- REDUNDANCY / MINIMALITY:

Each uses:

`PASS`, `WARNING`, or `FAIL`

followed by one concise explanation.

The audit identifies defects.

It must not become another characterization essay.

---

## 8.1 CHARACTER SPECIFICATION PRESERVATION CHECK

Ask:

> Does the compiled persona prompt preserve the accepted semantic Core and relevant stable character specification?

Check specifically for:

- deleted mechanisms;
- altered conditions;
- inflated traits;
- invented motivations;
- erased boundaries;
- lost fallibility;
- lost uncertainty.

---

## 8.2 DELTA TRACEABILITY CHECK

Ask:

> Can every substantive specialization in the final persona prompt be traced to an accepted delta or explicit technical requirement?

Flag final-persona content that appears without a valid basis.

---

## 8.2A UPSTREAM SOURCE REVIEW CHECK

Ask:

> **For an interactive RP target, was the selected source corpus actually inspected where accessible, rather than relying only on Phase 1 summaries and Phase 2 compression?**

`PASS` requires a targeted source-level review whenever accessible source material materially affects dialogue, behavior, quirks, or voice realization.

`WARNING` is appropriate when the underlying source is only partially accessible and the realization layer therefore relies on reproduced or secondary material.

`FAIL` when the process claims source-informed realization but only uses abstract Core descriptions or generic character knowledge.

---

## 8.2B SOURCE-LEVEL REALIZATION BASIS CHECK

Ask:

> **Do the concrete realization choices have identifiable upstream support or an explicit inference/theorization status?**

Flag:

- invented speech habits presented as canonical;
- generic otaku or rom-com mannerisms without a defensible basis;
- quirks that have no trigger, selectivity, or relationship to the Core;
- example lines whose function is unsupported by the research basis.

---

## 8.2C REALIZATION TRACEABILITY CHECK

Ask:

> **Can the dialogue patterns, example voice lines, and behavioral quirks in the final prompt be traced to an accepted Core mechanism, specialization decision, or explicit realization basis?**

Examples may be synthetic, but their behavioral function must have a defensible basis.

---

## 8.2B DIALOGUE / VOICE DEMONSTRATION QUALITY CHECK

Ask:

> **Do the examples demonstrate the intended voice and interactional behavior rather than merely naming it?**

Check for:

- concrete turn shape;
- natural conversational reaction;
- variation rather than one catchphrase;
- language-specific naturalness where applicable;
- separation of semantic behavior from surface wording.

---

## 8.2C QUIRK SELECTIVITY CHECK

Ask:

> **Can the character still respond normally when the quirk is not triggered?**

Flag quirks that are written as compulsory behavior rather than selective tendencies.

---

## 8.2D THEORIZED-MATERIAL BOUNDARY CHECK

Ask:

> **Are model-generated quirks and target inferences visibly distinguished from canon-grounded characterization?**

Flag any compilation that presents extrapolated material as established source fact.

---

## 8.3 PROPAGATION CHECK

Ask:

> Did one lens accidentally promote its contextual assumptions into another lens or into the Core?

Examples:

- relationship behavior becoming baseline personality;
- localization becoming canonical voice;
- domain role becoming intrinsic competence;
- deployment limitation becoming character behavior.

---

## 8.4 EMBODIMENT / RUNTIME BOUNDARY CHECK

Ask:

> **Did the final prompt preserve source-grounded embodiment and persistent character facts without importing current runtime state?**

Check for:

- missing persistent appearance or identifying physical features;
- invented appearance detail;
- transient scene facts presented as persistent character facts;
- current mood, current relationship state, current promises, or episodic memory encoded as persona requirements.

---

## 8.5 LANGUAGE CONTAMINATION CHECK

Ask:

> Did target-language realization alter the underlying semantic characterization?

Flag:

- language-specific stereotypes;
- arbitrary speech tics;
- ungrounded pronoun implications;
- target-language habits presented as intrinsic personality.

---

## 8.6 DEPLOYMENT CONTAMINATION CHECK

Ask:

> Did implementation constraints become personality requirements?

Check for:

- model quirks;
- context limitations;
- formatting requirements;
- memory architecture;
- token-budget compromises;
- generation instability.

These belong to technical realization unless independently supported as character behavior.

---

## 8.7 RECOMPILATION STABILITY CHECK

Ask:

> If the relationship, language, medium, or deployment changed, would the underlying character remain recognizable?

The outputs do not need to be identical.

The same underlying Character Specification should remain recoverable.

---

## 8.8 REGRESSION CHECK

Ask:

> Did specialization reintroduce a problem already excluded by the Core audit?

Examples include:

- unsupported psychology;
- generic archetype substitution;
- excessive adjective-based characterization;
- salience bias;
- contradiction smoothing;
- competence inflation;
- emotional simplification.

---

## 8.9 FINAL PERSONA PROMPT CHECK

Ask:

> Is the final persona prompt directly usable in the declared deployment context without sacrificing Core integrity?

The prompt should not require the user or downstream model to reconstruct the analytical process.

For interactive RP, a prompt that contains only abstract trait descriptions may be semantically correct yet under-demonstrated; where useful, verify that embodiment guidance, dialogue patterns, and examples make the intended character recoverable in scene.

Do not require the final persona prompt to encode or track current runtime state; that belongs to the RP frontend.

A technically usable prompt may still be semantically unfaithful.

A semantically faithful prompt may still be technically unusable.

Where deployment readiness is claimed, both conditions must be satisfied.

---

# 9. PHASE 3 STATUS

## PHASE 3 STATUS

### REQUIRED

- STATUS:
- FROZEN CHARACTER SPECIFICATION PRESERVED:
- ACCEPTED DELTAS:
- REJECTED / DEFERRED DELTAS:
- MAJOR RECONCILIATION ISSUES:
- AUDIT RESULT:

### OPTIONAL

- OPEN UNCERTAINTIES:
- TECHNICAL LIMITATIONS:
- HANDOFF NOTE:

`STATUS` may be:

- `OPEN`
- `COMPILED`
- `AUDIT WARNING`
- `READY FOR DEPLOYMENT`
- `BLOCKED`

`READY FOR DEPLOYMENT` means:

- the frozen Character Specification remains intact;
- accepted specialization has been reconciled;
- no material unresolved `FAIL` remains;
- the final persona prompt is usable for the declared deployment target.

It does not mean uncertainty has disappeared.

---

# 10. NON-OVERWRITE RULE

The Phase 2 Character Specification remains immutable.

Phase 3 must never silently return a rewritten Character Specification.

When a specialization exposes a possible defect in the frozen Character Specification, record:

`REVISE`

or:

`VERSION-SPLIT`

and preserve the existing frozen Character Specification.

A future revision of the Core or other frozen character specification belongs to a new Phase 2 execution.

---

# 11. DELTA ACCOUNTABILITY RULE

Every material specialization change must answer:

> **What changed?**

> **Why did it change?**

> **Which Core element does it affect?**

> **Under what condition does it apply?**

> **What is the basis?**

> **Does it alter semantics or only expression?**

If these cannot be answered, use:

`UNKNOWN`

rather than inventing a justification.

---

# 12. CHARACTER STABILITY TEST

The final compiled persona prompt should permit the following distinction:

```text
CHARACTER SPECIFICATION
What remains part of the same character.

SPECIALIZATION
What changes because the context changed.

REALIZATION
How that specialized character is expressed.

DEPLOYMENT
How the system technically represents it.
```

If these categories cannot be distinguished, inspect for contamination.

---

# 13. EXECUTION RULE

When executing Phase 3:

1. Verify that the Phase 2 Character Specification is frozen.
2. Read the Character Specification before applying specialization.
3. Establish the specialization target.
4. Perform the targeted `SOURCE-INFORMED REALIZATION PASS` when the target is interactive RP and selected source material is accessible.
5. Analyze applicable Media specialization.
6. Analyze applicable Domain specialization.
7. Analyze applicable Relationship specialization.
8. Analyze applicable Language specialization.
9. Analyze Deployment as a technical realization lens.
10. Record substantive changes as typed deltas.
11. Allow genuine cross-lens dependencies without turning the process into a rewrite chain.
12. Analyze Dialogue & Behavioral Realization using the realization pass where interactive reproduction requires it.
13. Reconcile conflicts, scope collisions, and propagation.
14. Keep upstream evidence use targeted to verification and realization mining; do not reopen unrestricted research.
15. Separate technical constraints from characterization.
16. Compile the accepted result into a **standalone persona prompt**, normally in Markdown.
17. Include compact demonstration material when it materially improves behavioral reproducibility.
18. Preserve semantic Core content through compression or restructuring.
19. Add a compilation trace only where materially useful.
20. Complete the single audit.
21. Mark readiness only when no material `FAIL` remains.

The lens order is analytical.

It is not permission to mutate the Core between lenses.

---

# 14. PHASE 3 BOUNDARY

Do not:

- re-research the character as a new unrestricted Phase 1;
- reconstruct or silently revise the Core;
- treat the Phase 1 register as sufficient when accessible source-level detail is needed for realization;
- mine the entire corpus indiscriminately rather than performing a targeted realization pass;
- erase material Phase 2 uncertainty;
- encode runtime state as persistent character specification;
- encode current conversation continuity as character identity;
- invent target relationship dynamics;
- treat domain conventions as personality evidence;
- treat localization as canon without basis;
- treat deployment constraints as characterization;
- generate unsupported psychological explanations;
- manufacture synthetic source evidence;
- silently change continuity;
- average incompatible interpretations;
- produce separate rewritten characters for each lens;
- use example dialogue as purported canon evidence;
- force every dialogue pattern on every turn;
- make behavioral quirks mandatory gimmicks;
- present theorized or target-inferred quirks as canon facts without marking their status;
- require the downstream system to reconstruct the Phase 3 analysis from the final prompt.

Phase 3 produces:

> **frozen Character Specification + explicit specialization deltas + reconciled realization + standalone persona prompt + audit**

It does not produce a new Core.

---

# 15. OUTPUT DISCIPLINE

Begin directly with:

`# PERSONA BUILDER — PHASE 3`

Follow the canonical section order.

Do not add free-form top-level sections.

Do not append general commentary after `PHASE 3 STATUS`.

The Phase 3 artifact is the deliverable.

The `FINAL PERSONA PROMPT` is the standalone deployment artifact. For interactive RP targets, the prompt should include the accepted realization layer when it materially improves reproducibility; when accessible source material exists, that realization layer should be grounded in the targeted source-informed realization pass.