# Conventions

**Status:** Working draft  
**Purpose:** Naming, notation, formatting, and usage conventions for The Triadic Integrity Framework.

---

## 1. Purpose of this file

This file defines the current conventions for the `triadic-integrity` repository.

Use it as the authority for:

- project names,
- layer names,
- core terminology,
- symbol usage,
- register usage,
- diagnostic language,
- file naming,
- and Markdown formatting.

When another file conflicts with this one, assume this file is more current unless explicitly noted otherwise.

---

## 2. Preferred repository description

Use this description when a short explanation is needed:

> The Triadic Integrity Framework is a working grammar for noticing what is happening, understanding stuckness, and choosing a better next move. It organizes experience through three layers: structural primitives, mechanical systems, and human-facing registers. The repository is written so that both humans and AI agents can read, test, and apply the framework.

Avoid describing the framework as a finished theory, clinical tool, spiritual system, or universal explanation.

---

## 3. Project names

### Framecraft

**Framecraft** is the broader umbrella project for building, testing, and expressing conceptual frameworks.

### The Triadic Integrity Framework

**The Triadic Integrity Framework** is the formal name of the framework in this repository.

### Tri Everything

**Tri Everything** is an informal nickname.

Use it sparingly in canonical files.

### The Three Pulls

**The Three Pulls** was the early/original/formative language of the project.

In the current architecture:

- The whole framework is **The Triadic Integrity Framework**.
- The canonical Layer 1 System 1 is **The Three Forces**.
- **The Three Pulls** is treated as a Layer 2 Human Register.

---

## 4. The Three Articulation Layers

The framework is organized into three articulation layers.

```text
Layer 0 → Layer 1 → Layer 2
structure → mechanism → human language
```

### Layer 0: The Structural Layer

Layer 0 names the basic structural primitives:

- **Quality**
- **Contact**
- **Continuity**

Layer 0 also includes the dyads and Triadic Integration.

Layer 0 is abstract, descriptive, and non-diagnostic.

### Layer 1: The Mechanical Layer

Layer 1 translates the structural primitives into mechanical systems:

- **The Three Forces**
- **The Three Capacities**
- **The Three Operations**

Layer 1 is the main diagnostic layer.

### Layer 2: Human Registers

Layer 2 translates the framework into human-facing language for specific domains, audiences, or use cases.

Registers are translations, not separate frameworks.

---

## 5. Layer 0 terminology

Use these Layer 0 terms consistently.

| Term | Meaning |
|---|---|
| **Quality** | Felt salience, tone, vividness, character, or intensity. |
| **Contact** | Encounter, friction, relation, reality, or actual meeting. |
| **Continuity** | Pattern, persistence, memory, recognizability, stability, or form. |

The three Layer 0 dyads are:

- **Quality–Contact**
- **Contact–Continuity**
- **Quality–Continuity**

**Triadic Integration** is the emergent coherence produced when Quality, Contact, and Continuity are mutually related.

Triadic Integration is not a fourth primitive.

---

## 6. Layer 1 systems

Use these as the canonical Layer 1 system names.

| System | Core question |
|---|---|
| **The Three Forces** | What is trying to happen? |
| **The Three Capacities** | What can the system actually hold? |
| **The Three Operations** | What move is available? |

Preferred summary:

> Forces generate movement. Capacities determine what the system can bear. Operations tune the system toward responsive integrity.

---

## 7. Layer 1 component structure

Each Layer 1 system contains seven components:

```text
3 elements + 3 relations + 1 emergent formation
```

Use the following terms in canonical Layer 1 files:

- **Element**
- **Relation**
- **Emergent Formation**

The older term **Alliance** may still appear in historical or human-facing material, but in canonical Layer 1 contexts prefer **Relation**.

The older term **Emergent Triangle** may still appear in human-facing material, but in canonical Layer 1 contexts prefer **Emergent Formation**.

---

## 8. Canonical Layer 1 names

### The Three Forces

Elements:

- **Qualitative Force**
- **Contact Force**
- **Continuity Force**

Relations:

- **Quality–Contact Force Relation**
- **Contact–Continuity Force Relation**
- **Quality–Continuity Force Relation**

Emergent formation:

- **Force Formation**

---

### The Three Capacities

Elements:

- **Bodily/Regulatory Capacity**
- **Social/Structural Capacity**
- **Form/Integrity Capacity**

Relations:

- **Bodily/Regulatory–Social/Structural Capacity Relation**
- **Social/Structural–Form/Integrity Capacity Relation**
- **Bodily/Regulatory–Form/Integrity Capacity Relation**

Emergent formation:

- **Capacity Formation**

---

### The Three Operations

Elements:

- **Explore Operation**
- **Coordinate Operation**
- **Stabilize Operation**

Relations:

- **Explore–Coordinate Operation Relation**
- **Coordinate–Stabilize Operation Relation**
- **Explore–Stabilize Operation Relation**

Emergent formation:

- **Operation Formation**

---

## 9. Diagnostic language

The framework uses three diagnostic distortions and one well-formed condition.

| Term | Meaning |
|---|---|
| **Slack** | Too little activation, support, contact, structure, force, relation, or form. |
| **Tight** | Too much pressure, rigidity, constraint, control, force, or over-formation. |
| **Misdirected** | Force, support, relation, or operation aimed at the wrong thing. |
| **Coherent Formation** | The well-formed condition in which the system holds together responsively. |

Important distinction:

```text
Slack, Tight, and Misdirected are distortions.
Coherent Formation is the well-formed condition.
```

In human-facing contexts, **healthy emergence** may be used as a softer phrase.

In canonical files, prefer **Coherent Formation**.

---

## 10. Symbol usage

Symbols are useful for precision, but they should not become a barrier.

Use symbols most consistently in:

- canonical framework files,
- quick reference files,
- tables,
- data files,
- agent-readable materials.

Use symbols more sparingly in:

- README files,
- human-facing registers,
- worked examples,
- practical prompts,
- public-facing explanations.

Plain language is preferred when clarity matters more than precision.

---

## 11. Core symbols

Layer 0 symbols:

| Symbol | Term |
|---|---|
| **★** | Quality |
| **●** | Contact |
| **■** | Continuity |

Layer 1 system symbols:

| Symbol | System |
|---|---|
| **⟶** | The Three Forces |
| **⬡** | The Three Capacities |
| **↻** | The Three Operations |

Component symbols:

| Symbol | Component type |
|---|---|
| **○** | Element |
| **⟷** | Relation |
| **△** | Emergent Formation |

Diagnostic symbols:

| Symbol | Diagnostic state |
|---|---|
| **∿** | Slack |
| **≡** | Tight |
| **↯** | Misdirected |
| **✓** | Coherent Formation |

These are internal framework symbols. Do not imply that they are standard outside this project.

---

## 12. Icon-first convention

When using symbols in canonical files, put the symbol first.

Preferred:

```text
★ Quality
● Contact
■ Continuity
⟶ The Three Forces
∿ Slack
✓ Coherent Formation
```

Avoid:

```text
Quality ★
Contact ●
Continuity ■
The Three Forces ⟶
Slack ∿
Coherent Formation ✓
```

In human-facing files, it is acceptable to omit symbols for readability.

---

## 13. Dense notation

Use compact notation only where it helps.

Examples:

```text
⟶○★ Qualitative Force
⬡○● Social/Structural Capacity
↻○■ Stabilize Operation
```

Dense notation is appropriate in:

- tables,
- structured references,
- data files,
- diagnostic matrices,
- agent-readable lookup material.

Avoid dense notation in:

- introductions,
- examples,
- reflective prose,
- human-facing register explanations,
- practical advice.

The notation should support thought, not replace it.

---

## 14. Human Register conventions

A Human Register is a Layer 2 translation of the framework.

Each register should make clear:

- what domain it serves,
- what audience or use case it is for,
- how it translates Forces,
- how it translates Capacities,
- how it translates Operations,
- and what kinds of situations it helps interpret.

Current or emerging registers include:

- **The Three Pulls Register**
- **The Working Register**
- **The Embodied Register**
- **The Kid Register**
- **Proposed Registers**

Registers should preserve the underlying Layer 1 structure, but they do not need to show full symbolic notation in every section.

---

## 15. The Three Pulls Register

The Three Pulls Register preserves the original formative language of the framework.

Use this mapping:

| Canonical Layer 1 | Three Pulls Register |
|---|---|
| **The Three Forces** | The Three Pulls |
| **Qualitative Force** | Pull 1: Aliveness |
| **Contact Force** | Pull 2: Coordination / Encounter |
| **Continuity Force** | Pull 3: Stability / Steadiness |
| **Force Formation** | Wholesome Triangle |

Use **The Three Forces** for canonical structure.

Use **The Three Pulls** for human-facing practical reflection.

---

## 16. Expression Formats

Expression Formats are the forms the framework takes so it can be stored, displayed, taught, navigated, reused, or executed.

Examples:

- GitHub Markdown repository
- printable PDF
- diagram
- structured data file
- public website
- AI agent prompt
- physical model
- table or grid

Key distinction:

```text
Human Registers = how the framework speaks.
Expression Formats = how the framework appears, circulates, and operates.
```

---

## 17. Agent-readable writing

This repository is intended to be readable by both humans and AI agents.

Write Markdown so that it is:

- clear,
- structured,
- explicit,
- easy to parse,
- consistent in headings and terms.

Prefer:

- short definitions,
- stable terminology,
- clean headings,
- simple tables,
- concrete examples.

Avoid:

- compressed Markdown,
- long tangled paragraphs,
- unexplained notation,
- inconsistent names,
- and excessive conceptual sprawl.

Use caution with the phrase **AI-native**.

Prefer:

```text
human-and-agent-readable
```

or:

```text
structured so that both humans and AI agents can read, test, and apply the framework
```

---

## 18. Peirce references

Peirce may be mentioned as background resonance, especially around Quality, Contact, and Continuity.

Do not present the framework as a formal Peircean system.

Preferred wording:

```text
The framework has loose resonance with Peircean themes such as quality, encounter, and continuity.
```

Avoid:

```text
This is a Peircean system.
The framework is derived from Peirce.
The framework is Peircean in structure.
```

This repository is not a Peirce scholarship project.

---

## 19. Markdown style

Use clean Markdown with real line breaks.

Preferred:

```markdown
# Title

Intro paragraph.

## Section

- Bullet
- Bullet
- Bullet
```

Avoid compressed Markdown where headings, paragraphs, bullets, and tables run together on the same physical line.

Tables should be readable in raw Markdown.

---

## 20. File naming

Use lowercase kebab-case for file names.

Preferred:

```text
layer-0-structural-layer.md
working-register.md
worked-case-template.md
```

Avoid:

```text
Layer0StructuralLayer.md
Working Register.md
worked_case_template.md
```

---

## 21. Canon vs experiment

Use clear status labels where helpful.

Suggested labels:

```text
Canonical working draft
Exploratory
Proposed
Archived
Deprecated
```

Canonical files may still change, but they should be treated as the current working reference.

Exploratory files may contain experiments, unresolved possibilities, or alternate language.

Deprecated material should be preserved only when historically useful.

---

## 22. Development principle

The framework should grow vertically before it grows horizontally.

This means:

- deepen one register before adding many more,
- add worked examples before adding more abstract elaboration,
- test distinctions before multiplying terms,
- prefer demonstrated usefulness over conceptual elegance.

The central question is:

```text
Does this help someone see and respond more clearly?
```
