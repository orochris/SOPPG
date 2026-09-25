# SOPPG — PHASE 3
## Specialization, Reconciliation & Compilation

---

# 0. PHASE CONTRACT

## PURPOSE

Transform a **frozen Phase 2 Character Specification** into a target-context persona by applying explicit specialization, realizing the character for the target, reconciling the resulting choices, and compiling a **standalone deployment-ready persona prompt**.

Phase 3 is a target-realization and compilation phase, not a new character-modeling phase. It answers:

> **How should the frozen character be realized under these specific conditions?**

It must not silently rewrite the frozen Character Specification. Material disagreement is recorded as `REVISE` or `VERSION-SPLIT` for a later Phase 2 revision.

---

## LANGUAGE SETS AND PROCESS LANGUAGE

Keep these language sets distinct:

- **WORKING LANGUAGE** — default to the language of the user's initial target-character request, considered by language rather than by the character name or source title. Use it for user-facing process narration and explanations unless the user specifies another language. If materially multilingual and unclear, ask or state a minimal, reversible assumption.
- **SPECIFICATION LANGUAGE** — the language in which this phase's rules and canonical schema are written (English in this specification). Preserve canonical section names, field names, IDs, controlled values, and requirements exactly as defined here. Explain them in the Working Language as needed without changing their meaning.
- **SOURCE LANGUAGE(S)** — the original language(s) supporting the frozen specification and realization evidence. Preserve original text where useful and label translations or glosses.
- **TARGET-REALIZATION LANGUAGE(S)** — the explicitly required language(s) for the persona's generated speech. Determine these independently of both the Working Language and Source Language(s); do not infer them from either.

The compiled prompt may be translated or reorganized for the target language, but must preserve the frozen characterization and interactional function. For multiple target languages, specify each realization separately where needed; do not assume literal translation yields equivalent voice. A multilingual instruction prompt does not by itself authorize multilingual character output.

---

## INPUTS

### Required

- Phase 2 FROZEN CHARACTER SPECIFICATION
- target specialization requirements, where applicable

### Target conditions may include

- media / adaptation
- domain / activity context
- relationship
- language
- deployment environment
- explicit user constraints
- explicit user realization preferences

### Upstream research material

When following Phase 1, the authoritative upstream material includes:

- Phase 1 Evidence Ledger
- Phase 1 Voice Evidence
- Phase 1 Relationship Evidence
- Phase 1 Temporal / Version Evidence
- Phase 1 Source-Scope Notes
- Phase 0 source registry and selected corpus

Phase 3 may inspect the already-selected source contents when concrete realization requires detail that Phase 1/2 compressed.

For interactive RP, perform `REALIZATION MINING` when usable selected source material is accessible.

Use upstream material only for:

1. **Evidence verification** — scope, provenance, continuity, or claims already under consideration.
2. **Realization mining** — concrete dialogue, interactional behavior, quirks, variation, embodiment, and example-worthy material.

Do not silently expand the corpus, reopen unrestricted Phase 1 research, or perform a fresh whole-character modeling pass.

### Optional

- accepted Phase 2 hypotheses
- explicitly marked user observations

---

## FROZEN CHARACTER SPECIFICATION RULE

The Phase 2 Character Specification is authoritative. It contains:

- Core behavioral mechanisms;
- Behavioral Modulation;
- Functional Behavior;
- source-grounded Voice Baseline;
- source-grounded Embodiment Baseline;
- Persistent Character Specification.

Phase 3 may realize these elements for the target, but may not replace them silently.

### RUNTIME STATE BOUNDARY

Phase 3 may describe **conditional character tendencies** such as how the character responds when embarrassed or disappointed. It must not encode the live state of an ongoing RP as character specification.

Do not compile as character state:

- current mood or emotional state;
- current scene state;
- current relationship state or accumulated trust;
- active unresolved events or promises;
- episodic deployment memories;
- turn-by-turn continuity;
- transient physical condition unless fixed by the target setup.

These belong to the RP frontend / runtime layer.

---

## SINGLE-EXECUTION RULE

Phase 3 is a **single specialization and compilation pass** over the frozen Character Specification. Lenses are analytical views, not serial character rewrites. Cross-lens interactions are resolved in `CROSS-LENS RECONCILIATION`.

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

Use phase-qualified, zero-padded IDs. `P3-` identifies Phase 3 IDs; use the established type prefix after it.

### Specialization deltas

`P3-D001`, `P3-D002`, `P3-D003` ...

### Reconciliation issues

`P3-RX001`, `P3-RX002`, `P3-RX003` ...

### Compilation trace entries

`P3-CP001`, `P3-CP002`, `P3-CP003` ...

Do not reuse IDs.

---

## 1.6 REFERENCE RULE

All references to the Core must point to existing Phase 2 `P2-` identifiers where applicable.

All references to evidence must point to existing Phase 1 `P1-E` IDs and Phase 0 `P0-SRC` IDs where applicable.

Do not invent upstream IDs.

### External realization packages

An optional Gem Reconciliation & Realization Corpus may be supplied as a separate realization package. Preserve its `GRC-*` identifiers as package-local references; they are not Phase 0–2 identifiers, canonical evidence IDs, or approved upstream findings. A Gem Builder routing recommendation does not itself authorize propagation.

Use an inspected and relevant `GRC-M` item as a realization reference only after checking its source, inspected material, locator, continuity, scope, and relationship to the frozen Core. Keep canonical evidence references (`P1-E` / `P0-SRC`) separate. If the package would add or change a characterization claim, conflicts materially with the Core, or lacks enough provenance to support the intended use, record the issue and route it for the appropriate SOPPG phase review; do not silently absorb it into Phase 3.

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

- WORKING LANGUAGE:
- TARGET DEPLOYMENT:

`WORKING LANGUAGE` is for the process discussion and explanations. `LANGUAGE` under `SPECIALIZATION TARGET` means the target language(s) of persona generation; never substitute one for the other.

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

`LANGUAGE` means the target-realization language(s) for generated character speech and any other persona output. Identify multiple languages explicitly. It does not mean the process Working Language or the Source Language(s).

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

For interactive RP, perform a **targeted realization pass over the selected upstream corpus** when usable source material is accessible. Its purpose is to recover concrete source detail that Phase 1/2 compression may have lost, not to remodel the character.

### REQUIRED PROCESS

1. Start from the frozen Character Specification and target.
2. Identify mechanisms, modulation, voice, embodiment, or persistent facts needing concrete realization.
3. Locate the relevant Phase 1 evidence and selected sources.
4. Inspect the underlying source material where accessible.
5. Extract concrete dialogue, interactional moves, physical presentation, quirks, variation, and example-worthy behavior.
6. Preserve provenance, scope, and counterevidence.
7. Prefer ordinary/recurrent interaction over isolated spectacle.
8. Compile only the smallest useful realization set.

### SOURCE PRIORITY

Prefer:

- direct primary scenes/dialogue;
- faithful transcripts/reproductions;
- Phase 1 evidence summaries when sources are inaccessible;
- secondary interpretation only when it contributes unrecoverable realization detail.

Do not silently upgrade provenance or create new evidence IDs merely because a source was inspected again.

### REALIZATION QUESTIONS

Ask only those useful to the target, including:

- What does the mechanism sound like in an actual turn?
- How does the character react, agree, disagree, or self-correct?
- What recurring quirks or small behaviors distinguish the character?
- Which appearance, attire, accessories, or physical cues should persist?
- Which physical reactions are conditional rather than persistent?
- How does behavior vary by context or relationship?
- What makes the character stop, recover, or return to baseline?

### SCOPE

Do not reopen settled characterization questions merely because a source contains another interpretation. If source material appears to contradict the frozen specification, record `REVISE` or `VERSION-SPLIT` rather than changing it.
## 5.1 MEDIA LENS

The Media lens determines whether medium, adaptation, performance, editing, gameplay, narration, or presentation materially affect realization.

### MEDIA SPECIALIZATION

### P3-D001 — [DELTA]

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

### P3-D002 — [DELTA]

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

### P3-D003 — [DELTA]

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

### P3-D004 — [DELTA]

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

### P3-D005 — [DELTA]

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

### P3-D006 — [DELTA]

### REQUIRED

- CORE REFERENCE:
- CHANGE:
- STATUS:
- BASIS:
- SCOPE:

### OPTIONAL

- ORIGIN:
- SOURCE BASIS:
- GEM CORPUS REFERENCES:
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

`SOURCE BASIS` should identify the relevant Phase 1 `P1-E` IDs and/or selected Phase 0 `P0-SRC` IDs when the realization feature was materially informed by upstream source inspection.

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

### P3-D007 — [DELTA]

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

This section resolves interactions among specialization deltas without revising the frozen Character Specification.

## CROSS-LENS RECONCILIATION

### P3-RX001 — [ISSUE]

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

### RECONCILIATION RULES

Check for:

- contradictions or scope collisions;
- accidental propagation across lenses;
- duplicate adaptations;
- language choices mistaken for behavior;
- domain/relationship/media assumptions generalized into personality;
- presentation or deployment effects mistaken for character facts.

Do not average incompatible evidence or deltas. Instead narrow scope, preserve the distinction, version-split, mark unknown, reject the unsupported delta, or flag `REVISE`.

### PRECEDENCE

Resolve conflicts in this order:

1. frozen Character Specification integrity;
2. explicit target conditions;
3. scoped evidence;
4. stronger provenance where relevant;
5. smallest necessary change;
6. explicit uncertainty when unresolved.

### PROPAGATION

A delta may be `LOCAL`, `DEPENDENT`, `CROSS-LENS`, or `TECHNICAL`. Do not promote a contextual implication into a global character rule without justification.

### UPSTREAM EVIDENCE

Return to Phase 1 evidence or selected sources only to verify a specialization, resolve scope/version questions, or perform targeted realization mining. If this exposes a material Core problem, preserve the frozen specification and record `REVISE` or `VERSION-SPLIT`.

# 7. PERSONA COMPILATION

The compiler produces:

> **FROZEN CHARACTER SPECIFICATION + ACCEPTED SPECIALIZATION DELTAS + REALIZATION MATERIAL + RECONCILIATION DECISIONS + TECHNICAL DEPLOYMENT CONSTRAINTS**

## PERSONA COMPILATION

### REQUIRED

- SOURCE CHARACTER SPECIFICATION:
- ACCEPTED DELTAS:
- REJECTED / DEFERRED DELTAS:
- REALIZATION MATERIAL:
- FINAL PERSONA PROMPT:

### OPTIONAL

- PRESERVED CHARACTER FEATURES:
- TARGET-SPECIFIC REALIZATION:
- TECHNICAL REALIZATION:
- UNRESOLVED LIMITATIONS:

## 7.1 FINAL PERSONA PROMPT

The final prompt is a **standalone deployment artifact**. It must:

- preserve the semantic Character Specification;
- incorporate accepted specialization;
- include necessary target-language, relationship, domain, media, deployment, embodiment, and RP realization;
- function without requiring reconstruction of Phase 3 reasoning;
- remain usable at the declared deployment budget.

For interactive RP, describe the character's **stable repertoire and conditional tendencies**, not live runtime state.

Do not include internal research notes, delta ledgers, audit commentary, or unsupported explanatory material unless directly required for deployment.

## 7.2 REALIZATION COMPILATION

For interactive RP, include a compact demonstration layer when it materially improves reproducibility. Use the smallest useful subset of:

- appearance / embodiment guidance;
- dialogue patterns;
- example voice lines;
- behavioral-quirk or conditional-reaction examples;
- conditional mode/register examples;
- contrastive boundaries for common failure modes.

Examples must be short, diverse, synthetic unless explicitly sourced, and non-prescriptive. Prefer behavioral diversity over example count. Do not turn examples into catchphrases or scripts.

Concrete realization must preserve the behavioral function and scope of the underlying source/model. `THEORIZED` and `TARGET-INFERRED` material must not be presented as canon evidence.

## 7.3 COMPILATION RULES

The compiler may reorganize, shorten, expand, reorder, or translate the established specification into target-facing instructions. It may realize language, embodiment, relationship expression, domain/media context, and technical constraints.

It must not:

- delete a material mechanism, modulation, persistent character feature, boundary, fallibility, or uncertainty;
- generalize contextual behavior into baseline behavior;
- convert language/deployment choices into character traits;
- turn hypotheses into facts;
- overwrite the frozen specification.

## 7.4 TRACEABILITY AND MINIMALITY

Every substantive final-persona element must trace to the frozen Character Specification, an accepted specialization delta, accepted realization material, a reconciliation decision, or an explicit technical requirement.

Use a `COMPILATION TRACE` only where a material transformation would otherwise be difficult to inspect.

Compression is encouraged; semantic loss is not. Preserve **semantic necessity**, not documentary volume.

## 7.5 EXPRESSION / MECHANISM

Keep distinct:

```text
underlying character mechanism
→ target realization
→ deployment representation
```

Do not collapse them into one undifferentiated personality instruction.

# 8. SINGLE AUDIT

The audit evaluates the completed specialization and compilation as one system.

## SINGLE AUDIT

### REQUIRED CHECKS

- CHARACTER SPECIFICATION PRESERVATION:
- SPECIALIZATION / DELTA TRACEABILITY:
- SOURCE-INFORMED REALIZATION:
- REALIZATION QUALITY:
- EMBODIMENT / RUNTIME BOUNDARY:
- SCOPE / PROPAGATION:
- LANGUAGE / DEPLOYMENT SEPARATION:
- UNCERTAINTY / COUNTEREVIDENCE:
- UNSUPPORTED / THEORIZED MATERIAL:
- INTERNAL CONSISTENCY:
- SEMANTIC LOSS / MINIMALITY:
- DEPLOYMENT USABILITY:

Each uses `PASS`, `WARNING`, or `FAIL` followed by one concise explanation.

### AUDIT INTERPRETATION

**CHARACTER SPECIFICATION PRESERVATION** checks that material mechanisms, modulation, persistent character features, boundaries, fallibility, and uncertainty survive compilation.

**SPECIALIZATION / DELTA TRACEABILITY** checks that target changes are scoped, justified, and traceable to accepted deltas or explicit target conditions.

**SOURCE-INFORMED REALIZATION** checks that interactive RP realization used accessible selected source material rather than only generic knowledge or abstract Core descriptions; partial access may warrant `WARNING`.

**REALIZATION QUALITY** checks that dialogue patterns, examples, quirks, conditional modes, and embodiment guidance demonstrate behavior rather than merely naming it, without becoming scripts or mandatory gimmicks.

**EMBODIMENT / RUNTIME BOUNDARY** checks that persistent appearance and canonical facts are retained without importing current mood, scene state, relationship state, episodic memory, or transient conditions.

**SCOPE / PROPAGATION** checks for relationship, domain, media, presentation, or contextual assumptions leaking into baseline character.

**LANGUAGE / DEPLOYMENT SEPARATION** checks that target-language and technical choices remain realization constraints rather than new characterization.

**UNCERTAINTY / COUNTEREVIDENCE** checks that unresolved or conflicting upstream material has not been silently erased or averaged away.

**UNSUPPORTED / THEORIZED MATERIAL** checks that synthetic examples remain demonstrations and that `THEORIZED` / `TARGET-INFERRED` material is not presented as canon.

**INTERNAL CONSISTENCY** checks for contradictions among accepted deltas, realization rules, and the final prompt.

**SEMANTIC LOSS / MINIMALITY** checks that compression has removed redundancy rather than required meaning.

**DEPLOYMENT USABILITY** checks that the final prompt is standalone and technically usable for the declared target.

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

The Phase 2 Character Specification remains immutable. A material disagreement is recorded as `REVISE` or `VERSION-SPLIT`; it does not silently rewrite the frozen input.

---

# 11. DELTA ACCOUNTABILITY RULE

Every material delta must identify:

- what changed;
- why it changed;
- affected Character Specification element;
- applicable condition/scope;
- basis;
- whether the change affects semantics or expression.

Use `UNKNOWN` when the basis is insufficient.

`GEM CORPUS REFERENCES` may list relevant package-local `GRC-M` and `GRC-S` IDs. These references support realization selection and traceability; they do not replace `SOURCE BASIS` or establish canonical evidence status.

---

# 12. CHARACTER STABILITY TEST

Across changes of relationship, language, medium, or deployment, the same underlying Character Specification should remain recoverable even when its expression changes.

---

# 13. EXECUTION RULE

When executing Phase 3:

1. Verify the frozen Phase 2 Character Specification.
2. Establish target conditions.
3. For interactive RP, perform targeted source-informed realization when accessible source material exists; where an optional Gem corpus is supplied, inspect only relevant items and preserve their package-local provenance.
4. Apply relevant specialization lenses as views over the same frozen input.
5. Record substantive changes as typed deltas.
6. Reconcile cross-lens interactions.
7. Compile the standalone persona prompt with sufficient realization material.
8. Complete the single audit.
9. Mark readiness only when no material `FAIL` remains.

The lens order is analytical, not a rewrite chain.

---

# 14. PHASE 3 BOUNDARY

Do not:

- reopen Phase 1 as unrestricted research;
- reconstruct or silently revise the frozen Character Specification;
- invent source evidence;
- promote contextual behavior into baseline personality;
- encode runtime state or turn-by-turn continuity as character specification;
- treat localization or deployment constraints as character traits;
- force examples, quirks, or dialogue patterns as scripts;
- present theorized material as canon;
- require the downstream system to reconstruct Phase 3 analysis.
- treat a Gem corpus routing recommendation or package-local `GRC` reference as SOPPG approval, canonical evidence, or permission to revise the frozen Core.

Phase 3 produces:

> **frozen Character Specification + explicit specialization deltas + reconciled realization + standalone persona prompt + audit**

It does not produce a new Core or a runtime state store.

---

# 15. OUTPUT DISCIPLINE

Begin directly with `# PERSONA BUILDER — PHASE 3` and follow the canonical section order.

Do not add free-form top-level sections or commentary after `PHASE 3 STATUS`.

The Phase 3 artifact is the deliverable; the `FINAL PERSONA PROMPT` is the standalone deployment artifact.
