# SOPPG — PHASE 0
## Source Discovery & Research Planning

---

# 0. PHASE CONTRACT

## PURPOSE

Discover and evaluate potentially useful sources for researching the target character.

Phase 0 answers:

> **What sources exist that could materially improve the research?**

It does **not** answer:

> What does the character's evidence prove?

and does **not** construct:

> a character model or persona.

Phase 0 produces the **candidate source registry and prioritized research queue** for Phase 1.

---

## LANGUAGE SETS AND PROCESS LANGUAGE

Keep these language sets distinct:

- **WORKING LANGUAGE** — the language of the user's initial target-character request, considered by language rather than by the character name or source title. Use it for user-facing process narration and explanations unless the user specifies another language. If the request is materially multilingual and no working language is clear, ask or state a minimal, reversible assumption.
- **SPECIFICATION LANGUAGE** — the language in which this phase's rules and canonical schema are written (English in this specification). Preserve canonical section names, field names, IDs, and controlled values exactly. Explain them in the Working Language as needed; do not translate away or weaken their requirements.
- **SOURCE LANGUAGE(S)** — the original language(s) of the work and each source. Record per source where known. Preserve original-language evidence; mark translations as translations or glosses.
- **TARGET-REALIZATION LANGUAGE(S)** — the language(s) intended for a later persona or deployment. This is independent of the Working Language and Source Language(s); do not infer it from either.

Phase 0 may use multiple languages for discovery. Search original-language sources where practical and use other languages for discovery or cross-checking without confusing source language with process language or eventual output language.

---

## INPUTS

Required:

- target character
- source / work / property

Optional:

- known adaptation / version
- source language
- specific research interest
- preferred source restrictions
- already-known sources

Do not require model, deployment, relationship, or target-language information unless it materially affects source discovery.

---

## OUTPUTS

Produce these artifact classes in this order:

1. RESEARCH HEADER
2. PRIMARY SOURCES
3. SECONDARY / RESEARCH SOURCES
4. SOURCE ROLE MAP
5. PRIORITIZED SOURCE HANDOFF
6. SOURCE GAPS
7. PHASE 0 AUDIT
8. PHASE 0 STATUS

All listed sections are part of the canonical grammar.

Sections may contain zero entries where nothing useful is found.

---

# 1. SHARED ARTIFACT GRAMMAR

## 1.1 SECTION RULE

A canonical section must appear in the specified order.

If a section has no meaningful entries, keep it and write:

`NONE ESTABLISHED`

Do not invent content to populate it.

## 1.2 ENTRY RULE

Create an entry only when a source is materially useful or materially informative about the research landscape.

Do not list sources merely because they exist.

## 1.3 FIELD RULE

Fields are:

- **REQUIRED** — necessary for the source entry to be useful
- **OPTIONAL** — include when materially informative
- **FORBIDDEN** — content outside Phase 0 scope

Optional fields may be omitted.

## 1.4 OMISSION RULE

Do not use filler.

Do not create empty descriptions simply because a field exists.

## 1.5 ID RULE

Use phase-qualified, zero-padded IDs:

`P0-SRC001`, `P0-SRC002`, `P0-SRC003` ...

The `P0-` namespace identifies Phase 0. Do not reuse an ID within the artifact.

## 1.6 AUTHORITY / VALUE RULE

Always distinguish:

**AUTHORITY**

from:

**RESEARCH VALUE**

A source may be weak as canon authority but highly useful for locating scenes, organizing character stories, mapping relationships, or identifying recurring behavior.

Do not collapse these into a single quality score.

## 1.7 PRIORITY RULE

Priority means:

> **expected usefulness to Phase 1 given the current research goal and the other sources already found.**

Priority does not mean:

> “How canonical is this source?”

A secondary source may have very high research priority.

## 1.8 SOURCE REGISTRY RULE

Phase 0 owns the canonical description of discovered sources.

Later phases inherit these source IDs and source classifications.

A later phase must not silently change:

- source identity
- authority classification
- access status
- source role

If a classification genuinely needs correction, record the change explicitly.

---

# 2. RESEARCH HEADER

## RESEARCH HEADER

### REQUIRED

- CHARACTER:
- SOURCE / WORK:
- SOURCE LANGUAGES:
- DISCOVERY SCOPE:
- STATUS:

### OPTIONAL

- WORKING LANGUAGE:
- CONTINUITY / VERSION:
- KNOWN USER SOURCES:

Record `WORKING LANGUAGE` when it is explicitly selected, differs from the default, or materially affects how the source register will be presented. It is process context, not a source-language claim.

`STATUS` begins as:

`OPEN`

---

# 3. SOURCE DISCOVERY PRINCIPLE

Search for sources according to **what they can contribute to character research**, not merely according to general reputation.

Look for:

- primary canon
- official character material
- story / episode archives
- dialogue / transcript sources
- character-focused analyses
- relationship analyses
- development / chronology resources
- adaptation comparisons
- terminology / reference databases
- unusually detailed secondary sources
- community resources useful for scene discovery

Do not stop after finding a generic character profile.

Pay particular attention to unusually information-dense secondary sources that organize:

- character stories
- recurring scenes
- relationships
- dialogue
- development
- behavioral patterns
- cross-references to primary material

---

# 4. PRIMARY SOURCES

Identify accessible primary or official sources first.

## PRIMARY SOURCES

### P0-SRC001 — [SOURCE NAME]

### REQUIRED

- TYPE:
- ACCESS:
- COVERAGE:
- CONTENT:
- RESEARCH VALUE:
- AUTHORITY:

### OPTIONAL

- LIMITATIONS:
- SOURCE LANGUAGE:
- VERSION / DATE:
- DIRECT ACCESS METHOD:

`TYPE` may include:

- OFFICIAL CHARACTER MATERIAL
- ORIGINAL WORK
- SCRIPT / TRANSCRIPT
- OFFICIAL STORY MATERIAL
- OFFICIAL EPISODE / CHAPTER INDEX
- OTHER PRIMARY

`ACCESS` may include:

- VERIFIED
- PARTIALLY VERIFIED
- INACCESSIBLE

`CONTENT` describes what is actually available.

Do not perform Phase 1 evidence extraction here.

---

# 5. SECONDARY / RESEARCH SOURCES

Search deliberately for high-value secondary material.

## SECONDARY / RESEARCH SOURCES

### P0-SRC010 — [SOURCE NAME]

### REQUIRED

- TYPE:
- ACCESS:
- COVERAGE:
- CONTENT:
- RESEARCH VALUE:
- AUTHORITY:

### OPTIONAL

- LIMITATIONS:
- SOURCE LANGUAGE:
- CROSS-REFERENCES:
- BEST USED FOR:

Possible `TYPE` values:

- CHARACTER ANALYSIS
- STORY / SCENE ARCHIVE
- DIALOGUE / QUOTE ARCHIVE
- RELATIONSHIP ANALYSIS
- CHARACTER DATABASE
- DEVELOPMENT / CHRONOLOGY
- ADAPTATION COMPARISON
- COMMUNITY REFERENCE
- OTHER SECONDARY

A detailed secondary source may have high research value even when its canon authority is limited.

---

# 6. SOURCE CONTENT DESCRIPTION

For every source surfaced for user consideration, describe **what the researcher can actually obtain from it**.

Prefer:

> Four-part character-story analysis covering major story events, relationships, trainer interactions, and later development.

over:

> Good character analysis.

Prefer:

> Episode archive with plot summaries but little original dialogue.

over:

> Useful anime website.

The purpose is to let the user decide whether the source deserves research budget.

Do not perform full characterization analysis here.

---

# 7. RESEARCH VALUE

Evaluate sources by useful research function.

Possible dimensions:

- CANON VALUE
- BEHAVIORAL VALUE
- VOICE VALUE
- RELATIONSHIP VALUE
- DEVELOPMENT VALUE
- DISCOVERY VALUE

Use concise descriptions.

Do not create numeric scores unless explicitly requested.

Examples:

> High behavioral value; moderate canon authority.

> Low primary authority; high discovery value.

> High voice value; limited relationship coverage.

---

# 8. SOURCE ROLE MAP

Map sources by research function.

## SOURCE ROLE MAP

### CANON / PRIMARY

- [P0-SRC IDs]

### BEHAVIOR

- [P0-SRC IDs]

### VOICE / DIALOGUE

- [P0-SRC IDs]

### RELATIONSHIPS

- [P0-SRC IDs]

### DEVELOPMENT / TEMPORAL

- [P0-SRC IDs]

### ADAPTATION / VERSION

- [P0-SRC IDs]

### DISCOVERY / SCENE NAVIGATION

- [P0-SRC IDs]

A source may appear in multiple roles.

Do not force a source into a role it does not serve.

---

# 9. PRIORITIZED SOURCE HANDOFF

This is the primary Phase 0 handoff.

The objective is to give the user a **practical, editable research queue**.

Group sources by research role.

Within each group, order sources from highest to lowest expected research usefulness.

Do not produce one undifferentiated global ranking.

## PRIORITY GROUPS

Use the following groups when applicable:

### P1 — PRIMARY / CANON FOUNDATION

Official or primary sources that should normally form the evidentiary base.

### P2 — HIGH-VALUE CHARACTER RESEARCH

Secondary sources that provide substantial behavioral, story, relationship, or developmental material.

This is where unusually useful sources such as detailed character-story analyses should be surfaced prominently.

### P3 — VOICE / DIALOGUE

Sources particularly useful for original dialogue, transcripts, speech patterns, or linguistic evidence.

### P4 — RELATIONSHIP / DEVELOPMENT

Sources especially useful for relationship behavior or changes over time.

### P5 — SCENE DISCOVERY / NAVIGATION

Sources whose primary value is locating relevant scenes, chapters, episodes, stories, or primary evidence.

### P6 — VERSION / ADAPTATION

Sources useful for distinguishing continuities, adaptations, localization, or version-specific characterization.

### P7 — SUPPLEMENTARY / LOW PRIORITY

Useful material that adds value after higher-priority sources are covered.

Do not create a group merely to fill the structure.

---

## 9.1 SOURCE ENTRY FORMAT

Each source in the handoff uses:

### P0-SRC001 — [SOURCE NAME]

- KEEP / REMOVE:
- PRIORITY:
- TYPE:
- COVERAGE:
- CONTENT:
- WHY USEFUL:
- AUTHORITY:
- ACCESS:

Optional:

- OVERLAP:
- LIMITATION:
- BEST PHASE 1 USE:
- DEPENDENCIES:

### `KEEP / REMOVE`

This is a **user-editing marker**, not a claim that the source must be included.

Default it to:

`KEEP`

for sources recommended for the initial corpus.

Use:

`REMOVE`

for sources the model considered but does not recommend for the initial corpus.

A source marked `REMOVE` may still be useful for discovery or later expansion.

---

# 10. HANDOFF EDITING MODEL

The user should be able to modify the Phase 0 result using simple operations.

Supported conceptual edits:

### KEEP

Retain the source for Phase 1.

### REMOVE

Exclude the source from Phase 1.

### ADD

Add a user-provided source.

### DISCOVERY ONLY

Permit the source to help locate evidence, but do not treat its claims as evidentiary support unless independently verified.

### PRIMARY ONLY

Restrict the Phase 1 corpus to primary / official material.

### TRUNCATE

Use only the sources through a chosen priority group or stopping point.

### EXPAND

Continue discovery before Phase 1.

The user does not need to rewrite source descriptions.

---

# 11. DEFAULT CORPUS

When the user provides no explicit editing instruction, recommend:

> **Primary / Canon Foundation + the highest-value complementary secondary sources.**

Treat discovery-only sources as navigation aids rather than primary evidence.

The default should favor **complementarity** over source count.

---

# 12. SOURCE COMPLEMENTARITY

Prefer a source set that covers different research needs.

For example:

```text
Official character page
→ canon baseline

Detailed character-story analysis
→ behavioral variation

Dialogue archive
→ voice

Relationship analysis
→ relational behavior

Episode / chapter index
→ scene discovery
```

Do not recommend several sources that merely repeat the same basic profile.

When sources overlap substantially, identify the overlap so the user can prune them easily.

---

# 13. SOURCE GAPS

Identify important research needs for which no strong source was found.

## SOURCE GAPS

### P0-GAP001 — [RESEARCH NEED]

### REQUIRED

- NEED:
- CURRENT COVERAGE:
- IMPACT:

### OPTIONAL

- POSSIBLE NEXT SEARCH:
- REASON NO STRONG SOURCE WAS FOUND:

Do not manufacture gaps merely because a category exists.

---

# 14. SOURCE CONFLICTS

Phase 0 may identify obvious disagreements between sources.

Do not resolve them into characterization.

## SOURCE CONFLICTS

### P0-C001 — [CONFLICT]

### REQUIRED

- SOURCES INVOLVED:
- SUBJECT:
- DESCRIPTION:

### OPTIONAL

- LIKELY CAUSE:
- RESEARCH HANDLING:

Possible causes include:

- continuity difference
- adaptation difference
- translation
- localization
- source incompleteness
- community interpretation

Phase 1 evaluates the evidence.

---

# 15. PHASE 0 BOUNDARY

Do not:

- construct Core mechanisms
- declare personality traits
- infer hidden motivations
- resolve characterization conflicts
- construct relationship dynamics
- construct target-language voice
- design deployment prompts
- generate synthetic dialogue
- rank character interpretations

Phase 0 describes:

> **available sources + source usefulness + recommended research order**

It does not characterize the person.

---

# 16. SOURCE HONESTY

For every source:

- verify accessibility where possible;
- distinguish existence from inspected content;
- distinguish source claims from the model's assessment;
- mark partial or inaccessible access;
- do not invent titles, URLs, pages, quotations, or contents.

When source content cannot be verified, say so.

---

# 17. DISCOVERY STRATEGY

When external research is available, search broadly enough to find **unusually useful sources**, not merely the most prominent results.

Search combinations may include:

- character name + character analysis
- character name + story analysis
- character name + dialogue
- character name + transcript
- character name + relationship
- character name + development
- character name + chronology
- character name + episode analysis
- character name + scene archive
- character name + official
- character name + original language
- character name + quote / speech
- character name + adaptation

When the work originates in a non-English language:

- search the original language;
- prioritize original-language discovery where practical;
- use English-language sources for supplementary discovery and cross-checking.

Do not assume search-engine ranking reflects source quality.

---

# 18. DISCOVERY RULE: FIND THE UNUSUALLY USEFUL SOURCE

The primary objective is not to find the most famous source.

It is to find sources that substantially improve Phase 1.

Give particular attention to sources that:

- organize character stories
- index recurring scenes
- document character interactions
- preserve dialogue
- compare versions
- trace development
- explain obscure but recurring behavior
- link primary evidence across chapters, episodes, stories, or routes

When such a source exists, surface it prominently in `P2 — HIGH-VALUE CHARACTER RESEARCH` or the appropriate more specialized group.

Explain its usefulness concretely.

---

# 19. SOURCE DUPLICATION

Avoid recommending several sources that merely reproduce the same basic profile.

When substantial overlap exists:

- identify the overlap;
- retain the source with greater research value;
- retain multiple sources only when each adds meaningful coverage or provenance.

Do not inflate the apparent quality of the corpus by counting duplicates.

---

# 20. PHASE 0 AUDIT

## PHASE 0 AUDIT

### REQUIRED CHECKS

- DISCOVERY BREADTH:
- PRIMARY SOURCE COVERAGE:
- HIGH-VALUE SECONDARY DISCOVERY:
- SOURCE CONTENT ACCURACY:
- ACCESS HONESTY:
- AUTHORITY / VALUE DISTINCTION:
- SOURCE COMPLEMENTARITY:
- DUPLICATION CONTROL:
- SOURCE GAP IDENTIFICATION:
- USER EDITABILITY:
- CHARACTERIZATION BOUNDARY:

Each uses:

`PASS`, `WARNING`, or `FAIL`

followed by one concise explanation.

The audit evaluates the **research landscape**, not the character.

---

# 21. PHASE 0 STATUS

## PHASE 0 STATUS

### REQUIRED

- STATUS:
- CANDIDATE SOURCES:
- RECOMMENDED SOURCES:
- CORPUS STATE:

### OPTIONAL

- IMPORTANT SOURCE GAPS:
- SCOPE NOTE:

`STATUS` may be:

- OPEN
- READY FOR PHASE 1

`CORPUS STATE` may be:

- CANDIDATE
- USER-SELECTED
- USER-MODIFIED
- DEFAULT-ACCEPTED

`READY FOR PHASE 1` means a usable corpus has been identified.

The corpus does not need to be exhaustive.

---

# 22. HANDOFF RULE

Phase 0 passes:

> **prioritized source groups + source registry + source roles + research-use notes + corpus state**

to Phase 1.

The **selected corpus becomes authoritative for Phase 1**.

Phase 1 must not silently add discovered sources.

If Phase 1 identifies a potentially valuable unlisted source, it should record it as a research gap / new candidate rather than silently incorporating it.

A source marked:

`DISCOVERY ONLY`

may be used to locate additional material but should not silently become evidentiary support.

Phase 0 does not pass a character summary as authoritative interpretation.

---

# 23. EXECUTION RULE

When executing Phase 0:

1. Identify the target character and source/work.
2. Discover relevant primary sources.
3. Search deliberately for unusually useful secondary research sources.
4. Describe what each source actually contains.
5. Distinguish authority from research value.
6. Map sources by research role.
7. Group and prioritize sources for easy editing.
8. Prefer complementary sources over duplicates.
9. Mark discovery-only sources clearly.
10. Identify important source gaps.
11. Do not construct the character model.
12. Do not resolve characterization questions prematurely.
13. Keep inaccessible or unverified material clearly marked.
14. Apply any explicit user source preferences.
15. Complete the audit.
16. Mark `READY FOR PHASE 1` when a usable corpus exists.

---

# 24. OUTPUT DISCIPLINE

Begin directly with:

`# PERSONA BUILDER — PHASE 0`

Follow the canonical section order.

Do not add free-form top-level sections.

Do not append general commentary after `PHASE 0 STATUS`.

The Phase 0 artifact is the deliverable.
