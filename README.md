# SOPPG

**Source-Oriented Persona Prompt Generator, which isn't.**

```text
Start with:
    a character you want to represent

SOPPG develops:
    research artifacts
    evidence model
    core character model
    target-specific adaptation
    deployment persona
    test / audit material
```

Naturally, because I wanted to create a believable AI waifu.

The immediate goal was simple enough: take a character with a substantial body of source material and produce a persona that could sustain convincing interaction with a language model. The complication was that “believable” quickly stopped meaning “sounds vaguely like the character.” It meant that the resulting behavior should remain recognizably grounded in what the source material actually supports, including its ambiguities, contradictions, limitations, and context.

That turned out to be a rather different problem from writing a good prompt.

SOPPG concerns the process between the source material and the final persona: researching and organizing sources, extracting and qualifying evidence, modeling characterization, handling uncertainty and constraints, adapting the result to a particular target, and finally compiling it into a deployable form.

The final prompt is only one artifact.

## The Problem

A direct persona-generation request might produce something like:

> **Personality**
>
> * Observant
> * Analytical
> * Blunt
> * Pragmatic
> * Curious
> * Self-controlled

followed by instructions for speech, knowledge, relationships, humor, emotional expression, and roleplay behavior.

For example, a one-shot Maomao prompt might continue with:

> **Reasoning Style**
>
> When solving a mystery:
>
> 1. Observe the available evidence.
> 2. Separate facts from assumptions.
> 3. Identify contradictions.
> 4. Generate several plausible explanations.
> 5. Determine which explanation best fits the evidence.

There is nothing inherently wrong with this. It is useful, recognizable, and often good enough to produce a plausible character.

But notice what has happened. The character, the interpretation of the character, the instructions for reproducing the character, and the protections against likely model failures have all been compressed into the same artifact.

SOPPG starts from a different premise.

A compiled Maomao persona might instead describe her like this:

> Maomao approaches problems by gathering information, checking assumptions, and comparing explanations against observable evidence.
>
> When information is incomplete, she does not need to pretend certainty.
>
> Her expertise does not make her omniscient. She can make mistakes, misjudge things, lack information, or discover that a previous assumption was wrong.

The difference is not simply that one prompt is longer or more detailed. The two approaches use a different unit of representation.

The first primarily describes **properties and instructions**: be observant, be analytical, speak this way, react that way, do not do these things.

The second describes **behavioral mechanisms and constraints**: how Maomao approaches a problem, how she handles uncertainty, and how competence coexists with fallibility. Its voice is similarly expressed through recurring and conditional interactional tendencies rather than mandatory mannerisms.

More importantly, it reaches its description through **observable process and artifacts**. Character claims are derived from source material, recorded as evidence, modeled, qualified where necessary, and only then translated into the final deployment representation.

## A Small Example

Consider the difference between saying:

> **Maomao is observant.**

and representing something more like:

```text
Evidence:
    Repeatedly notices small physical, environmental, and behavioral details.

Mechanism:
    Gathers information before committing to an explanation.

Modulation:
    Investigates unusual details when they appear consequential or interesting,
    but does not treat every anomaly as a mystery that must be solved.

Constraint:
    Observation does not imply certainty; new information can change the conclusion.
```

The second representation is not necessarily more verbose when deployed. In fact, much of it may disappear during compilation.

What matters is that the intermediate representation makes explicit **why** a particular characterization was chosen and **where its limits are**.

This makes it possible to distinguish, for example:

* what the sources directly establish;
* what is a reasonable interpretation;
* what remains uncertain;
* what is specific to a relationship or context;
* what is a property of the deployment environment rather than of the character;
* and what may simply be a tendency of the target model.

That distinction becomes difficult to recover once everything has already been flattened into prose instructions.

## Workflow

SOPPG therefore uses a staged workflow:

```text
Source Material
      ↓
Source Research
      ↓
Evidence Model
      ↓
Core Character Model
      ↓
Specialization / Adaptation
      ↓
Persona Compilation
      ↓
Deployment
```

The stages are deliberately separated and produce relatively verbose process artifacts so that both the LLM and the user can inspect, question, correct, and refine the work before it is compressed into a final persona.

The verbosity is not the goal. **Externalization is.**

The intermediate artifacts exist because they are useful places to catch unsupported assumptions, contradictions, missing evidence, accidental reinterpretations, and model-specific contamination before those things disappear into a polished final prompt.

## The Artifacts

### Source Research

Establish what material is being used, where it came from, what coverage it provides, and where the gaps are.

### Evidence Model

Record observations with provenance and scope, while distinguishing direct evidence from inference and speculation. Conflicts and uncertainty remain visible rather than being silently resolved.

### Core Character Model

Turn the evidence into a stable characterization that can survive changes in context. The Core is a semantic character specification, not a finished deployment persona. It captures recurring mechanisms, meaningful modulation, voice, embodiment, persistent character facts, and relevant uncertainties.

### Specialization

Adapt the Core for a particular medium, relationship, language, domain, or deployment environment. Specialization changes how the character is realized; it should not silently redefine the character.

### Persona Compilation

Translate the resulting model into a target-specific persona suitable for the chosen model and environment.

### Deployment and Audit

Put the compiled persona to use, test it against ordinary and adversarial situations, and distinguish failures of characterization from failures introduced by the model, prompt, context, or deployment configuration.

## Why Keep the Intermediate Work?

Because the final persona is necessarily compressed.

Compression is useful for deployment, but dangerous as a place to perform reasoning.

A final prompt might need only a few concise mechanisms to preserve a large amount of characterization. The research and modeling process, however, needs enough detail to show how those mechanisms were established.

This creates a deliberate asymmetry:

```text
development artifacts:
    expansive
    inspectable
    qualified
    revisable

deployment artifact:
    compact
    target-specific
    operational
```

The project is therefore not trying to preserve every research note in the final prompt. It is trying to preserve the **useful consequences of that research**.

## From Character Model to Persona

This separation also makes different kinds of adaptation easier to reason about.

A source may establish a recurring behavior. Another source may qualify it. A relationship may change how that behavior is expressed without changing the underlying character. A deployment environment may provide capabilities that the fictional character could not plausibly possess.

Those things should not all become permanent character facts merely because they happen to occur in the same prompt.

For example, a deployment may provide modern information access, multilingual interaction, or a particular relationship with the user. These can be implemented as target-specific realization choices while leaving the underlying character specification intact.

Likewise, a model may have a strong prior toward excessive agreement, romance, omniscience, or helpfulness. Such behavior should not automatically be “fixed” by adding another permanent character trait. SOPPG explicitly treats model behavior and character behavior as potentially different sources of failure.

## The Compiler Intuition

At this point the compiler analogy is less metaphorical than it first sounds.

```text
source material
      ↓
analysis
      ↓
evidence
      ↓
character IR
      ↓
transformation / specialization
      ↓
target-specific realization
      ↓
deployment
```

The Core is an intermediate representation.

Specialization is a transformation pass.

The deployment persona is a target-specific artifact.

The adapter hand-off is an interface between stages.

And the final prompt is not the source of truth for the character. It is a compiled representation of one.

This is why the project is called what it is — **SOPPG**.

I am deliberately naming this project with an acronym of its embryonic form. **No, SOPPG is not a Prompt Generator.**

That is, among other things, a small nod to LLVM.

**Build the character first. Then build the prompt.**
