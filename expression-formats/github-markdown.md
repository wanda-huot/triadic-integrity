# GitHub Markdown Repository

**Status:** Active  
**Expression Format:** GitHub Markdown Repository  
**Framework:** The Triadic Integrity Framework  
**Author:** Gwendolyn Huot with ChatGPT  

---

## 1. Purpose

The GitHub Markdown repository is the first active **Expression Format** of The Triadic Integrity Framework.

Its purpose is to make the framework:

- public
- navigable
- versionable
- readable by humans
- usable by AI agents
- easy to revise
- easy to extend
- suitable as a source for future formats

This repository is not only a storage place.

It is a working expression of the framework.

---

## 2. Why Markdown?

Markdown is useful because it can hold both prose and structure.

It works well for:

- conceptual definitions
- layer files
- register files
- bridge notes
- expression-format documentation
- tables
- maps
- prompts
- quick references
- structured examples

Markdown is plain enough to stay portable, but structured enough to support future formats such as:

- websites
- PDFs
- AI agent prompts
- structured data
- diagrams
- teaching materials

Markdown is the current working form of the framework.

Other expression formats can grow from it later.

---

## 3. Repository role

This repository currently serves as:

```text
canonical working reference + public draft + human-and-agent-readable source
```

It is not final.

It is not just private notes.

It is a minimum viable public structure for developing the framework in a disciplined way.

The repository should help answer:

```text
What is the current framework?
What is canonical?
What is experimental?
What is a Human Register?
What is a Bridge?
What is an Expression Format?
How should an AI agent read and use this material?
```

---

## 4. Main sections

The repository is organized around these major sections:

```text
framework/             = the framework itself
registers/             = Human Registers
bridges/               = comparative translation documents
expression-formats/    = ways the framework appears and operates
agents/                = future AI-agent materials
data/                  = future machine-readable canon
archive/               = old, retired, or experimental material
```

Not all future directories need to exist yet.

Each section should have a clear purpose.

If a file does not clearly belong somewhere, that is a sign the repository architecture may need adjustment.

---

## 5. Framework files

The `framework/` directory contains the core architecture.

Current core files:

```text
framework/layer-0-structural-layer.md
framework/layer-1-mechanical-layer.md
framework/layer-2-human-registers.md
```

Future framework file:

```text
framework/diagnostic-matrix.md
```

The framework files should define the structure itself.

They should avoid becoming:

- examples
- applications
- journal entries
- register-specific essays
- bridge comparisons
- expression-format notes

The framework files are the main reference layer.

---

## 6. Register files

The `registers/` directory contains **Layer 2 Human Registers**.

Current working register files:

```text
registers/three-pulls-register.md
registers/kid-register.md
registers/working-register.md
registers/embodied-register.md
registers/proposed-registers.md
```

A register file translates the framework into a specific kind of human language.

A register should make clear:

- who or what it is for
- what vocabulary it uses
- how it maps back to Layer 1
- how it maps back to Layer 0
- how the diagnostic overlay appears in that register
- how it helps in practice

A register file should not become a separate framework.

It should remain traceable back to:

- **Layer 0: The Structural Layer**
- **Layer 1: The Mechanical Layer**
- **Layer 2: Human Registers**

---

## 7. Bridge files

The `bridges/` directory contains **Bridges**.

A Bridge is a comparative translation document.

It connects The Triadic Integrity Framework with an external framework, theory, tradition, modality, or vocabulary.

Current file:

```text
bridges/README.md
```

Possible future Bridge files:

```text
bridges/peirce-bridge.md
bridges/active-inference-bridge.md
bridges/four-e-cognition-bridge.md
bridges/act-bridge.md
bridges/ifs-bridge.md
bridges/self-determination-theory-bridge.md
bridges/relevance-realization-bridge.md
```

Bridge files should identify:

- useful resonances
- possible translations
- mismatches
- limits
- what not to claim
- what the comparison helps clarify

A Bridge is not a Human Register.

Key distinction:

```text
Human Registers = how the framework speaks.
Bridges = how the framework compares and translates across systems.
Expression Formats = how the framework appears, circulates, and operates.
```

---

## 8. Expression Format files

The `expression-formats/` directory describes the forms the framework can take.

Current files:

```text
expression-formats/README.md
expression-formats/github-markdown.md
```

Future files may include:

```text
expression-formats/wanda-agent.md
expression-formats/printable-pdfs.md
expression-formats/diagrams.md
expression-formats/physical-model.md
expression-formats/structured-data.md
expression-formats/future-astro-site.md
```

Expression Format files should explain how the framework is:

- stored
- displayed
- navigated
- taught
- reused
- executed
- circulated

An Expression Format is not a new layer.

It is a way the framework takes form.

---

## 9. Agent files

The `agents/` directory is reserved for future AI-agent materials.

Near-term target:

```text
agents/wanda/
  README.md
  wanda-system-prompt.md
```

Agent files should be more operational than expression-format files.

For example:

```text
expression-formats/wanda-agent.md
```

would explain Wanda as a type of expression.

But:

```text
agents/wanda/wanda-system-prompt.md
```

would contain actual working prompt material.

Agent files should preserve the core distinctions:

- Layer 0, Layer 1, Layer 2
- Human Registers vs Bridges vs Expression Formats
- The Three Forces vs The Three Pulls
- Slack, Tight, Misdirected, and Coherent Formation
- canonical structure vs register translation

---

## 10. Data files

The `data/` directory is reserved for future machine-readable canon.

Possible future files:

```text
data/layer-0-canon.json
data/layer-1-canon.json
data/layer-2-registers-index.json
data/bridges-index.json
data/diagnostic-matrix.json
```

Markdown is for explanation.

Structured data is for reuse by:

- AI agents
- websites
- search tools
- diagrams
- future applications

Data files should not contradict the Markdown canon.

If a data file and a canonical Markdown file conflict, the Markdown file should be treated as authoritative until the conflict is resolved.

---

## 11. Archive files

The `archive/` directory is for retired, superseded, or experimental material.

Use the archive when something is worth preserving but should not guide current usage.

Examples:

- old names
- deprecated diagrams
- earlier layer structures
- retired intervention grids
- exploratory notes
- abandoned terminology
- superseded register drafts

The archive protects the main repository from clutter without deleting useful history.

Archived files should be clearly marked as archived, retired, deprecated, or historical.

---

## 12. Naming conventions

Use lowercase kebab-case for file names.

Preferred:

```text
layer-0-structural-layer.md
layer-1-mechanical-layer.md
layer-2-human-registers.md
three-pulls-register.md
embodied-register.md
github-markdown.md
peirce-bridge.md
```

Avoid:

```text
Layer 0 Structural Layer.md
layer_0_structural_layer.md
Layer0.md
PeirceBridge.md
```

File names should be boring, readable, and predictable.

---

## 13. Markdown conventions

Use clear Markdown structure.

Preferred heading style:

```markdown
# Page title

## 1. Major section

### Subsection
```

Use short paragraphs.

Use tables when comparing parallel terms.

Use fenced code blocks for:

- repository trees
- prompts
- structured examples
- machine-readable summaries
- file paths

Use bold for official terms on first use.

Avoid excessive decoration.

The framework is already symbol-rich. The page design should stay calm.

---

## 14. Icon-first convention

When a term has an assigned icon and the icon is useful, put the icon first.

Use:

- **★ Quality**
- **● Contact**
- **■ Continuity**
- **⟶ The Three Forces**
- **⬡ The Three Capacities**
- **↻ The Three Operations**
- **∿ Slack**
- **≡ Tight**
- **↯ Misdirected**
- **✓ Coherent Formation**

Do not write:

- Quality ★
- Contact ●
- The Three Forces ⟶
- Slack ∿

The icon-first convention helps both human readers and AI agents recognize framework terms consistently.

However, do not overuse dense notation in human-facing files.

Plain language is preferred when clarity matters more than precision.

---

## 15. Working draft status

Most files in this repository should be treated as **Working Drafts** unless explicitly marked otherwise.

Use status labels such as:

- **Canonical working draft**
- **Working draft**
- **Experimental**
- **Stub**
- **Archived**
- **Deprecated**
- **Retired**

A working draft can be useful without being final.

The goal is disciplined iteration, not premature polish.

---

## 16. Public-facing caution

This is a public-facing repository.

Avoid including:

- private group names
- private participant names
- private conversations
- identifiable internal dynamics
- unnecessary personal disclosure

The public repository should be understandable without private context.

Use general language such as:

- collaborators
- AI agents
- development conversations
- private working group

The framework can have a private development history without exposing that history in public files.

---

## 17. Human-and-agent-readable writing

This repository is intended to be readable by both humans and AI agents.

Good human-and-agent-readable writing is:

- explicit
- consistent
- well-structured
- readable in raw Markdown
- low on unexplained inside jokes
- careful with canonical terms
- clear about status
- clear about source layer and target use

Avoid unnecessary ambiguity.

If a term is canonical, use it consistently.

If a term is experimental, mark it as experimental.

If a file is a stub, say so.

Prefer concrete headings, stable terms, and clear structure.

---

## 18. What belongs here

A file belongs in this repository if it helps define, translate, compare, express, test, or operate The Triadic Integrity Framework.

Good additions include:

- core framework definitions
- Human Register translations
- Bridge comparisons
- diagnostic matrices
- AI-agent instructions
- Expression Format documentation
- diagrams
- structured data
- public-facing explanations
- archived historical material

Weak additions include:

- unrelated essays
- private notes
- undeveloped fragments
- disconnected metaphors
- material that cannot be traced back to the framework
- material that creates new terminology without adding clarity

---

## 19. Repository growth principle

The repository should grow vertically before it grows horizontally.

This means:

- deepen one register before adding many more
- add worked examples before adding more vocabulary
- test distinctions before multiplying terms
- keep Bridge work separate from Register work
- keep Expression Formats separate from both
- prefer demonstrated usefulness over conceptual elegance

A clean repository is not just larger.

It is easier to navigate, test, revise, and use.

---

## 20. Working rule

When adding or editing Markdown in this repository, ask:

```text
What section does this belong in?
Is this canonical, working draft, experimental, stub, archived, or retired?
Does this use the current naming conventions?
Does this preserve the distinction between Framework, Human Registers, Bridges, and Expression Formats?
Can a human reader follow it?
Can an AI agent use it?
Does this help the repository become clearer rather than merely bigger?
```

The repository should grow without becoming a pile of fragments.

Markdown is the first public form of the framework.

It should stay clear enough to become other forms later.
