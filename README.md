# kirby-great-essay

*This skill is part of the [Kirby Skills Collection](https://github.com/markkirby125/kirby-skills-collection).*

An AI agent skill that establishes the editorial framework for producing authoritative, high-retention essays. It optimises long-form content for both human readers and AI Answer Engines (AEO/GEO).

## Key Features

- **7-Phase Editorial Architecture:** Guides agents from problem inversion to final syntax audits.
- **3-Layer RAG Chunking:** Structures text to maximise generative AI citations and vector retrieval.
- **Empirical GEO Multipliers:** Enforces hard numerical statistics, external standards, and active SVO declarative prose.
- **Anti-Slop Enforcement:** Prevents generic AI writing patterns and hollow intensifiers.

## Tech Stack

- **Format**: Markdown / YAML
- **Compatibility**: Antigravity, Claude Code, Cursor, Windsurf, Cline

## Prerequisites

- An AI coding assistant or agent runner (e.g., Antigravity, Claude Code, Cursor).
- A workspace where you want the agent to write or edit long-form essays.

## Getting Started

### 1. Installation via The Magic Prompt

Copy and paste this directly to your AI (Cursor, Windsurf, Claude Code):

```markdown
@agent Please install the kirby-great-essay skill into this workspace.
1. Read the `SKILL.md` file (and `references/` directory if applicable) from this repository: https://github.com/markkirby125/kirby-great-essay
2. Identify the correct rules system for our current environment (e.g., `.cursor/rules/` for Cursor, `.windsurfrules` for Windsurf, `.clinerules` for Cline, or `~/.agents/skills/` for Antigravity).
3. Save the contents appropriately. If our environment supports multi-file dispatcher skills, clone the directory structure exactly.
4. Confirm when the installation is complete.
```

### 2. Manual Installation

If your agent does not support web fetching, you can install the skill manually:

- **Cursor:** Copy `SKILL.md` to `.cursor/rules/kirby-great-essay.mdc`
- **Windsurf:** Append the contents of `SKILL.md` to `.windsurfrules`
- **Antigravity:** Clone this repository to `~/.agents/skills/kirby-great-essay`

## Architecture

This skill operates as a single-file Markdown document containing YAML frontmatter and the core standard operating procedure (SOP). 

### Directory Structure

```
├── SKILL.md      # The main skill definition and instructions
├── README.md     # Project documentation
└── .gitignore    # Ignored files
```

### Skill Logic Flow

1. **Phase 1: Pre-Flight Inversion:** Identifies the Status Quo belief the essay will displace and its operational cost.
2. **Phase 2: Dynamic Header Hardening:** Structures `<h2>` and `<h3>` tags as independent, entity-rich titles.
3. **Phase 3: The Introduction Engine:** Follows a strict 5-step flow (Common Ground → Concession → Pivot → Cost → Point).
4. **Phase 4: Fractal Structuring:** Ensures every section follows the 3-Layer RAG Chunking model (Atomic Answer, Empirical Proof, Edge Cases).
5. **Phase 5: Syntactic Information Flow:** Enforces SVO dependency parsing and specific paragraph patterns.
6. **Phase 6: GEO Retrieval Multipliers:** Integrates external standards, hard statistics, and structured tables.
7. **Phase 7: QA Verification Gates:** Subjects the text to The Skim Test, RAG Chunk Independence Audit, and Single Point Audit before completion.

## Usage

Once installed, the agent will automatically trigger this skill when you ask it to write or edit essays, editorial content, or thought leadership pieces.

To manually invoke the skill, instruct the agent:
> "Write an essay about [topic] using the kirby-great-essay skill."

## Troubleshooting

### Agent Ignores the Framework
**Issue:** The agent writes a standard, generic AI essay.
**Solution:** Explicitly mention the skill in your prompt. Ask the agent to output its checklist from Phase 7 (The QA Verification Gates) to force adherence.

### AI Slop Detected
**Issue:** The output contains words like "leverage," "seamless," or "testament to."
**Solution:** Combine this skill with a dedicated unslop or anti-AI writing skill. Instruct the agent to run the output through a strict filter before finalizing.

## External Resources & Authority Links
- [Google Search Central: Creating helpful, reliable, people-first content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content)
- [Nielsen Norman Group: How Users Read on the Web](https://www.nngroup.com/articles/how-users-read-on-the-web/)
- [Anthropic: Prompt Engineering Guide](https://docs.anthropic.com/claude/docs/prompt-engineering)
- [Purdue OWL: Essay Structure](https://owl.purdue.edu/owl/general_writing/academic_writing/essay_writing/index.html)
