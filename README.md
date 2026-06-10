# WHAT.md
The WHAT-WHY-HOW-WHO specification standard to sync contexts between humans and AI agents.

# Standard Rule Set

> **"Define intention, align agent. A minimalist intent specification standard for Human-AI collaboration."**

`WHAT.md` is a high-abstraction human scratchpad designed to synchronize core project contexts between human developers and AI agents in under 3 seconds of scanning. It eliminates verbose prompts and keeps the foundational "intent" clear and immutable.

---

## 📜 Core Rule Set

### 1. Human-Only Write (Human Scratchpad)
This document is a sacred canvas exclusive to human developers. AI agents are strictly forbidden from modifying, updating, or deleting this file. Agents must treat this as a **Read-Only** foundation of truth.

### 2. Core 4-Axis Fixed Architecture
The document must strictly consist of exactly four top-level headers (`# WHAT`, `# WHY`, `# HOW`, `# WHO`). Adding arbitrary subheaders or extra sections is prohibited to prevent cognitive clutter.

### 3. Under 10 Lines Constraint
Each section (W) must contain **10 lines or fewer** of content, including blank lines and links. If a section exceeds 10 lines, it violates the core philosophy of immediate readability.

### 4. TMI Outsourcing (Detail Offloading)
Do not write low-level implementation details here. Any extensive technical details, specific architecture diagrams, protocols, or code snippets must be offloaded to separate files using markdown links (e.g., `[Details](docs/architecture.md)`).

### 5. Scratchpad Formatting (No Prose)
Formal, long-form prose is strictly banned. Content should feel like a raw sketch on a whiteboard—using keywords, concise bullet points, abbreviations, and arrows (`->`) to maximize scannability.

### 6. High-Abstraction Only
Only the highest-level concept, direction, and "pure intent" belong in this file. Low-abstraction components like library versions, configuration variables, or file structures must live elsewhere.

### 7. Agent Context Lock (Boundary Enforcer)
AI agents must prioritize reading this file before initiating any execution or generation task. Agents must strictly operate within the boundaries defined here and are prohibited from arbitrarily implementing or suggesting features out of this scope.

### 8. Single Source of Intent (SSOI)
When a project's macro direction changes, the human developer must update `WHAT.md` first before refactoring any code. This file must always reflect the absolute freshest, single source of truth regarding the project's existential purpose.

---

## 📝 Quick Template Example

```markdown
# WHAT
[High-level summary of what you are building in <10 lines]

# WHY
[The core problem and why existing solutions fail in <10 lines]

# HOW
[The high-level technical paradigm and interfaces in <10 lines]

# WHO
[The target audience from novice to experts in <10 lines]
