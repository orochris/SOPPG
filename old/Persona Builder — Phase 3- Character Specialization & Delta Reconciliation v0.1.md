# PERSONA BUILDER — PHASE 3
## Character Specialization & Delta Reconciliation
### v0.1 — Core → Bounded Specialization

---

# 0. PHASE CONTRACT

## PURPOSE

Transform the frozen Phase 2 Core into a **contextually specialized but still character-faithful model** by applying bounded Media, Domain / Canon, and Relationship specialization.

Phase 3 answers:

> **How should the established character model manifest under the specific source, world, continuity, and central relationship of the intended roleplay?**

Phase 3 does **not** rebuild the character.

It produces:

> **FROZEN CORE + ACCEPTED SPECIALIZATION DELTAS → RECONCILED MODEL**

The Core remains authoritative and immutable.

---

## INPUTS

### REQUIRED

- Phase 2 frozen Core Character Model
- Phase 2 Core Audit
- Phase 2 Uncertainties
- Phase 1 relevant specialized evidence views
- intended source / medium scope
- intended domain / canon scope
- central relationship premise

### OPTIONAL

- Media / Source Adapter findings
- Domain / Canon Adapter findings
- Relationship Adapter findings
- explicitly marked user requirements
- adaptation / continuity constraints
- deployment goal, when needed only to define relationship scope

Phase 3 may use relevant Phase 1 evidence to evaluate a specialization.

It must not silently conduct a new research phase.

If material evidence is missing:

> **RETURN TO PHASE 1**

Do not manufacture evidence during reconciliation.

---

# 1. PHASE BOUNDARY

Phase 3 specializes the character through:

- source / medium
- domain / canon
- continuity
- central relationship

It does not perform:

- target-language realization
- target-language dialogue construction
- model-specific prompt engineering
- generation configuration
- final persona compression

Those belong to later phases.

### Boundary rule

> **Specialize the expression and conditions of the Core before specializing its language or deployment.**

---

# 2. GOVERNING ARCHITECTURE

Phase 3 operates as a **delta system**, not a chain of rewritten personas.

The authoritative structure is:

```text
FROZEN CORE
   │
   ├── MEDIA DELTAS
   ├── DOMAIN DELTAS
   └── RELATIONSHIP DELTAS
            │
            └── DEPENDENCY CHECK
                    │
                    ▼
              RECONCILIATION
                    │
                    ▼
           RECONCILED MODEL
```

Permitted information flow does not imply permission to overwrite upstream artifacts.

A downstream lens may inspect an upstream delta.

It may not silently convert that delta into:

- Core evidence
- a universal character rule
- a different lens's conclusion

---

# 3. CORE IMMUTABILITY

The Phase 2 Core is frozen.

Do not modify:

- `C` mechanism text
- Core confidence
- Core scope
- Core evidence references

without an explicit **Core Revision Event**.

A specialization normally acts by adding:

> **condition + contextual expression**

rather than replacing the underlying mechanism.

Example:

```text
CORE:
C003 — Deliberate preparation before commitment

SPECIALIZATION:
Under a trusted authority relationship, the character may disclose
more of her reasoning before acting.
```

Do not rewrite `C003` into:

> “The character explains her reasoning to trusted people.”

The latter has changed the Core itself.

---

# 4. SPECIALIZATION THEORY

## 4.1 Core vs Specialization

Treat:

> **CORE**

as what remains character-defining across ordinary contextual changes.

Treat:

> **SPECIALIZATION**

as how the Core is expressed under defined conditions.

A specialization should answer:

1. Which Core mechanism is involved?
2. What condition activates the specialization?
3. What actually changes?
4. What does not change?
5. What evidence or explicit requirement justifies the change?
6. What is the scope of the change?

---

## 4.2 Delta Types

Every substantive specialization must be classified.

### CONTEXTUALIZE

The Core remains unchanged, but its expression becomes more specific.

### QUALIFY

The scope of an interpretation must be narrowed.

### VERSION-SPLIT

Different continuities, adaptations, or temporal scopes require distinct versions.

### ADAPT

A deployment-specific or requested contextual change is introduced without claiming that it is canon.

### REVISE

A specialized evidence review reveals that an existing interpretation is materially insufficient.

Use sparingly.

### TECHNICAL

A change concerns representation or interoperability rather than characterization.

This should normally be deferred to Language or Deployment.

### UNKNOWN

The issue cannot currently be resolved.

### REJECT

The proposed change is unsupported, contaminating, redundant, or out of scope.

Do not create deltas merely because a lens has nothing to contribute.

---

# 5. DELTA ACCEPTANCE

A proposed delta has two distinct dimensions:

### ACTION

What kind of change is being proposed?

Use:

- KEEP
- CONTEXTUALIZE
- QUALIFY
- VERSION-SPLIT
- ADAPT
- REVISE
- TECHNICAL
- UNKNOWN
- REJECT

### DECISION

What happens to the proposal?

Use:

- ACCEPT
- REJECT
- DEFER
- RETURN TO PHASE 1
- USER DECISION

Do not confuse:

> `REVISE`

with:

> `ACCEPTED`.

A delta can propose revision and still be rejected.

---

# 6. DELTA SCHEMA

Each substantive delta uses:

### D001 — [DELTA NAME]

### REQUIRED

- LENS:
- AFFECTS:
- ACTION:
- DECISION:
- BASIS:
- SCOPE:
- PROPOSED EFFECT:
- EVIDENCE / JUSTIFICATION:
- NON-OVERWRITE CONSTRAINTS:

### OPTIONAL

- CONDITION:
- DEPENDS ON:
- COUNTEREVIDENCE:
- ALTERNATIVE:
- VERSION:
- IMPACT:

### FIELD RULES

`LENS`

Use:

- MEDIA
- DOMAIN
- RELATIONSHIP

`AFFECTS`

Reference:

- Core mechanism IDs
- modulation IDs where applicable
- specialized evidence views
- defined contextual structures

Do not invent new Core IDs.

`BASIS`

Distinguish among:

- CORE
- PHASE 1 EVIDENCE
- CANON / DOMAIN EVIDENCE
- RELATIONSHIP EVIDENCE
- USER REQUIREMENT
- DEPLOYMENT REQUIREMENT
- INFERENCE
- UNKNOWN

Do not silently upgrade an adaptation requirement into canon evidence.

`SCOPE`

State whether the delta applies to:

- universal
- source-specific
- version-specific
- relationship-specific
- context-specific
- developmental
- deployment-specific

A specialization should be as narrow as the evidence permits.

---

# 7. MEDIA LENS

## PURPOSE

Determine how the source medium or adaptation changes the observable or usable expression of the Core.

Ask:

- What does the medium directly reveal?
- What does it hide?
- What does it exaggerate?
- What may be a presentation artifact?
- Which behaviors are version-specific?
- Which behaviors remain stable?

### MEDIA QUESTIONS

For each relevant Core mechanism:

- directly observable?
- indirectly inferred?
- presentation-amplified?
- presentation-suppressed?
- adaptation-specific?
- genuinely character-relevant?

Do not convert:

> animation exaggeration

into:

> permanent emotional intensity.

Do not convert:

> gameplay repetition

into:

> obsessive behavior.

Do not convert:

> player-selected action

into:

> autonomous character preference.

### MEDIA OUTPUT

Produce only Media DELTAS.

Do not rewrite the Core.

---

# 8. DOMAIN / CANON LENS

## PURPOSE

Determine which world, franchise, continuity, or domain facts materially affect the expression of the established character.

Ask:

> If this world fact were removed, would the character plausibly behave differently?

If no:

> keep it outside the specialized character model.

### DOMAIN DISTINCTIONS

Keep separate:

- world fact
- character knowledge
- character belief
- character assumption
- audience knowledge
- character experience

Do not turn lore knowledge into omniscience.

Do not turn canonical relationships into emotional intimacy automatically.

Do not turn a fictional institution into a personality trait.

### DOMAIN OUTPUT

Produce only Domain DELTAS.

Do not rewrite the Core.

---

# 9. RELATIONSHIP LENS

## PURPOSE

Determine how the established character behaves toward the intended central person.

The relationship is a **context applied to the Core**, not a replacement for the Core.

### RELATIONSHIP DIMENSIONS

Consider where relevant:

- trust
- authority
- independence
- cooperation
- disclosure
- disagreement
- affection
- vulnerability
- intimacy
- boundaries
- conflict
- repair
- reliance
- initiative

### REQUIRED DISTINCTIONS

Preserve:

- trust ≠ obedience
- care ≠ control
- affection ≠ romance
- intimacy ≠ dependence
- authority ≠ submission
- support ≠ caretaking
- vulnerability ≠ helplessness

### RELATIONSHIP SPECIALIZATION

Prefer:

> existing mechanism + relationship-specific expression

over:

> new relationship-specific personality trait.

Example:

```text
CORE:
C002 — Protects personal autonomy in important decisions.

RELATIONSHIP DELTA:
In a trusted collaboration, the character may seek advice openly
while retaining final agency over decisions.
```

Do not rewrite the Core as:

> “The character needs the other person's advice.”

### RELATIONSHIP OUTPUT

Produce only Relationship DELTAS.

---

# 10. LENS INTERACTION

A lens may inspect another lens's accepted delta when dependency requires it.

### Typical dependency pattern

```text
CORE
 │
 ├── MEDIA
 │
 ├── DOMAIN
 │
 └── RELATIONSHIP
       ↑
 MEDIA / DOMAIN context may be relevant
```

The later lens must preserve the earlier delta's:

- ACTION
- DECISION
- SCOPE
- BASIS

unless the new evidence explicitly warrants a separate delta.

Do not mutate an existing delta.

Create a new delta that states the dependency.

---

# 11. NO TELEPHONE-GAME RULE

Never pass a rewritten prose baseline from one specialization lens to another as the canonical character representation.

Incorrect:

```text
Core
→ Media rewrites persona
→ Domain rewrites Media persona
→ Relationship rewrites Domain persona
```

Correct:

```text
Core
→ Media delta
→ Domain delta
→ Relationship delta

Then:

Core + accepted deltas
→ reconciliation
→ reconciled model
```

Lens summaries are explanatory artifacts.

They are not authoritative substitutes for the Core or delta ledger.

---

# 12. NEW EVIDENCE RULE

Phase 3 is not allowed to create fresh evidentiary claims merely because a specialization seems plausible.

If a proposed change requires evidence not present in Phase 1:

1. mark the delta `RETURN TO PHASE 1`;
2. identify the missing evidence;
3. do not incorporate the proposed characterization into the Reconciled Model.

User-specified deployment requirements may be recorded separately from evidence.

They are not canon evidence.

---

# 13. PROMOTION RULE

A specialized observation must not automatically become a Core property.

The following promotion is forbidden:

```text
relationship-specific behavior
→ universal character trait
```

```text
setting-specific behavior
→ universal personality rule
```

```text
adaptation-specific behavior
→ composite canon
```

```text
deployment requirement
→ character psychology
```

To promote anything into the Core requires a separate Core Revision Event and explicit re-evaluation against Phase 1 evidence.

---

# 14. VERSION AND SCOPE CONTROL

When behavior differs by:

- adaptation
- continuity
- source version
- relationship
- developmental period
- contextual trigger

do not average the behaviors.

Represent the distinction explicitly.

Examples:

```text
C004
→ MEDIA DELTA: Anime version
```

```text
C004
→ RELATIONSHIP DELTA: Central partner
```

```text
C004
→ DOMAIN DELTA: Institutional setting
```

One character may therefore have multiple valid expressions of the same Core mechanism.

---

# 15. DELTA CONFLICTS

When two deltas affect overlapping material:

### Check

1. Do they concern the same Core mechanism?
2. Do they have compatible scopes?
3. Do they require incompatible behavior?
4. Does one depend on the other?
5. Is the conflict real or merely apparent?
6. Can the difference be represented conditionally?
7. Is one proposal unsupported?
8. Is one a technical constraint rather than characterization?

Do not average conflicting deltas.

Do not privilege the newest delta merely because it appears later.

---

# 16. RECONCILIATION RULES

After all specialization lenses have produced their proposals:

### STEP 1 — VALIDATE

Check:

- affected IDs
- evidence references
- scope
- basis
- lens ownership
- dependency declarations

### STEP 2 — REMOVE REJECTED MATERIAL

Exclude deltas with:

`DECISION: REJECT`

### STEP 3 — CHECK EVIDENCE

For each accepted characterization delta ask:

> What is the evidentiary or explicit requirement basis?

### STEP 4 — CHECK PROMOTION

Ensure no delta has silently become universal characterization.

### STEP 5 — CHECK CONTAMINATION

Test for:

- media → character contamination
- domain → personality contamination
- relationship → Core contamination
- deployment → character contamination
- user premise → canon contamination

### STEP 6 — CHECK CONFLICTS

Identify:

- direct contradiction
- scope overlap
- incompatible version claims
- mutually exclusive assumptions

### STEP 7 — PRESERVE CONDITIONALITY

When two deltas are compatible under different conditions, retain both with explicit conditions.

### STEP 8 — PRESERVE UNKNOWN

Do not force resolution when the evidence does not permit one.

### STEP 9 — PRODUCE RECONCILED MODEL

Compile the accepted deltas against the frozen Core.

---

# 17. RECONCILED MODEL

The Reconciled Model is a **derived semantic artifact**.

It is not a rewritten Core.

## RECONCILED MODEL

### CORE REFERENCES

List accepted Core mechanisms unchanged by reference.

### MEDIA SPECIALIZATION

List accepted Media deltas.

### DOMAIN SPECIALIZATION

List accepted Domain deltas.

### RELATIONSHIP SPECIALIZATION

List accepted Relationship deltas.

### CONDITIONAL EXPRESSIONS

State important interactions in the form:

> CORE MECHANISM + CONDITION → SPECIALIZED EXPRESSION

### VERSION / SCOPE MAP

Identify behavior that changes by:

- source
- version
- relationship
- context
- development

### PRESERVED UNCERTAINTIES

Retain unresolved issues from Phase 2 and Phase 3.

### EXCLUDED MATERIAL

List rejected or deliberately unpromoted interpretations when they protect against future contamination.

Do not rewrite Core mechanisms here.

---

# 18. SPECIALIZATION AUDIT

## SPECIALIZATION AUDIT

### REQUIRED CHECKS

- CORE IMMUTABILITY:
- DELTA TRACEABILITY:
- LENS BOUNDARY:
- EVIDENCE / REQUIREMENT DISTINCTION:
- SCOPE DISCIPLINE:
- CONDITIONALITY:
- MEDIA CONTAMINATION:
- DOMAIN CONTAMINATION:
- RELATIONSHIP CONTAMINATION:
- CROSS-LENS CONTAMINATION:
- UNSUPPORTED PROMOTION:
- VERSION / CONTINUITY DISCIPLINE:
- CONFLICT HANDLING:
- UNKNOWN PRESERVATION:
- TELEPHONE-GAME PREVENTION:

Each uses:

`PASS`, `WARNING`, or `FAIL`

followed by one concise explanation.

The audit evaluates the specialization process.

It must not become another character essay.

---

# 19. PHASE 3 STATUS

## PHASE 3 STATUS

### REQUIRED

- STATUS:
- CORE STATUS:
- ACCEPTED DELTAS:
- REJECTED DELTAS:
- DEFERRED / RETURNED ITEMS:
- MAJOR SPECIALIZATION CONFLICTS:

### OPTIONAL

- VERSION NOTES:
- RELATIONSHIP SCOPE:
- HANDOFF NOTE:

`STATUS` may be:

- OPEN
- READY FOR PHASE 4

`CORE STATUS` must remain:

`FROZEN`

Phase 3 cannot unfreeze the Core merely because a specialization is inconvenient.

`READY FOR PHASE 4` means the Reconciled Model is internally usable for Language and/or subsequent specialization.

---

# 20. HANDOFF RULE

Phase 3 passes:

> **FROZEN CORE + ACCEPTED MEDIA DELTAS + ACCEPTED DOMAIN DELTAS + ACCEPTED RELATIONSHIP DELTAS + RECONCILED MODEL + OPEN UNCERTAINTIES**

to Phase 4.

Do not pass a rewritten persona as the authoritative source.

The next phase should compile from the Reconciled Model rather than from whichever lens ran last.

---

# 21. EXECUTION RULE

When executing Phase 3:

1. Read the frozen Phase 2 Core completely.
2. Read the relevant Phase 1 specialized evidence views.
3. Establish the intended medium, domain, continuity, and relationship scope.
4. Run the Media lens.
5. Run the Domain / Canon lens.
6. Run the Relationship lens.
7. Record substantive changes as explicit DELTAS.
8. Distinguish evidence from user requirements.
9. Preserve Core immutability.
10. Preserve delta scope.
11. Record dependencies between deltas.
12. Detect cross-lens conflicts.
13. Reject unsupported promotions.
14. Preserve unresolved uncertainty.
15. Produce the Reconciled Model.
16. Complete the specialization audit.
17. Mark `READY FOR PHASE 4` only when the model is internally consistent enough for downstream realization.

---

# 22. OUTPUT DISCIPLINE

Begin directly with:

`# PERSONA BUILDER — PHASE 3`

Follow the canonical section order.

Do not add free-form top-level sections.

Do not append general commentary after `PHASE 3 STATUS`.

The Phase 3 artifact is the deliverable.