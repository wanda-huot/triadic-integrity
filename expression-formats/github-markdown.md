# GitHub Markdown Repository

**Status:** Active  
**Expression Format:** GitHub Markdown Repository  
**Framework:** The Triadic Integrity Framework  
**Also known as:** Tri Everything  
**Author:** Gwendolyn Huot with ChatGPT

---

## 1. Purpose

The GitHub Markdown repository is the first active **Expression Format** of the Triadic Integrity Framework.

Its purpose is to make the framework:

- public
- navigable
- versionable
- readable by humans
- ingestible by AI systems
- easy to revise
- easy to extend

This repository is not only a storage place.

It is a working expression of the framework.

---

## 2. Why Markdown?

Markdown is useful because it can hold both prose and structure.

It works well for:

- conceptual definitions
- tables
- maps
- prompts
- register files
- quick references
- documentation
- AI-ingestible source material

Markdown is plain enough to stay portable, but structured enough to support future formats such as:

- websites
- PDFs
- agent prompts
- structured data
- diagrams
- teaching materials

---

## 3. Repository role

This repository currently serves as:

```text
canonical working reference + public draft + AI-ingestible source
```

It is not final.

It is not just private notes.

It is a minimum viable public structure for developing the framework in a disciplined way.

---

## 4. Main sections

The repository is organized around these major sections:

```text
framework/            = the framework itself
registers/            = Human Registers
expression-formats/   = ways the framework appears and operates
agents/               = working AI-agent materials
data/                 = future machine-readable canon
archive/              = old, retired, or experimental material
```

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

They should avoid becoming examples, applications, journal entries, or register-specific essays.

---

## 6. Register files

The `registers/` directory contains Layer 2 Human Registers.

Current MVP register files:

```text
registers/three-pulls-register.md
registers/kid-register.md
registers/working-register.md
registers/embodied-register.md
registers/proposed-registers.md
```

Each register file should translate the framework into a specific kind of human language.

A register file should not become a separate framework.

It should remain traceable back to:

- **Layer 0: The Structural Layer**
- **Layer 1: The Mechanical Layer**
- **Layer 2: The Human Registers Layer**

---

## 7. Expression Format files

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

These files should explain how the framework is stored, displayed, navigated, taught, reused, or executed.

---

## 8. AI-agent files

The `agents/` directory is for working AI-agent packages.

Near-term target:

```text
agents/wanda/
  README.md
  wanda-system-prompt.md
```

The agent files should be more operational than the expression-format files.

For example:

```text
expression-formats/wanda-agent.md
```

explains Wanda as a type of expression.

But:

```text
agents/wanda/wanda-system-prompt.md
```

contains actual working prompt material.

---

## 9. Data files

The `data/` directory is reserved for future machine-readable canon.

Possible files:

```text
data/layer-0-canon.json
data/layer-1-canon.json
data/layer-2-registers-index.json
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

---

## 10. Archive files

The `archive/` directory is for retired, superseded, or experimental material.

Use the archive when something is worth preserving but should not guide current usage.

Examples:

- old names
- deprecated diagrams
- earlier layer structures
- retired intervention grids
- exploratory notes
- abandoned terminology

The archive protects the main repository from clutter without deleting useful history.

---

## 11. Naming conventions

Use lowercase kebab-case for file names.

Preferred:

```text
layer-0-structural-layer.md
layer-1-mechanical-layer.md
layer-2-human-registers.md
three-pulls-register.md
embodied-register.md
github-markdown.md
```

Avoid:

```text
Layer 0 Structural Layer.md
layer_0_structural_layer.md
Layer0.md
```

File names should be boring, readable, and predictable.

---

## 12. Markdown conventions

Use clear Markdown structure.

Preferred heading style:

```markdown
# Page title

## 1. Major section

### Subsection
```

Use tables when comparing parallel terms.

Use fenced code blocks for:

- repository trees
- prompts
- structured examples
- machine-readable summaries
- file paths

Use bold for official terms on first use.

Avoid excessive decoration.

The framework is already symbol-rich; the page design should stay calm.

---

## 13. Icon-first convention

When a term has an assigned icon, put the icon first.

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

The icon-first convention helps both human readers and AI systems recognize framework terms consistently.

---

## 14. Working Draft status

Most files in this repository should be treated as **Working Drafts** unless explicitly marked otherwise.

Use status labels such as:

- **Canonical**
- **Working Draft**
- **Experimental**
- **Archived**
- **Retired**

A working draft can be useful without being final.

The goal is disciplined iteration, not premature polish.

---

## 15. Public-facing caution

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

---

## 16. AI-ingestible writing

Because this repository is AI-native, files should be written so that AI systems can parse them reliably.

Good AI-ingestible writing is:

- explicit
- consistent
- well-structured
- low on unexplained inside jokes
- careful with canonical terms
- clear about status
- clear about source layer and target use

Avoid unnecessary ambiguity.

If a term is canonical, use it consistently.

If a term is experimental, mark it as experimental.

---

## 17. What belongs here

A file belongs in this repository if it helps define, translate, express, test, or operate the Triadic Integrity Framework.

Good additions include:

- core framework definitions
- register translations
- diagnostic matrices
- AI-agent instructions
- expression-format documentation
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

---

## 18. Working rule

When adding or editing Markdown in this repository, ask:

```text
What section does this belong in?
Is this canonical, working draft, experimental, archived, or retired?
Does this use the current naming conventions?
Does this preserve the distinction between layers, registers, and expression formats?
Can a human reader follow it?
Can an AI system ingest it?
```

The repository should grow without becoming a pile of fragments.

Markdown is the first public form of the framework.

It should stay clear enough to become other forms later.
