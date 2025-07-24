---
title: RCE3 Knowledge Base
aliases:
  - Home
description: Welcome to the RCE3 Knowledge Base, the community repository of RCE3-related knowledge and research.
---

Welcome to the RCE3 Knowledge Base! This is a community-driven repository of knowledge and research related to RCE3. It is is designed for seasoned technical professionals. Here’s how it’s organized and how to find what you need.

## What you’ll find

- **Core domains & subdomains**, each with its own folder and note structure;
- **Research notes**, **projects**, and **references** at the root for cross-domain work;
- Structured templates:
  - `Concept.md` — define core ideas
  - `Project.md` — outline objectives and milestones
  - `Lit.md` — archive source metadata & highlights
  - `Log.md` — track experiments, meetings, and outcomes.

## Search efficiently

> [!info]
> Quartz uses high-performance full-text indexing ([Flexsearch](https://github.com/nextapps-de/flexsearch)), this allows you to quickly find notes by title, content, tags, and paths.

Here’s how to make the most of it:

1. **Keyboard quick-access**
   - `Ctrl/Cmd + K` → Search all content
   - `Ctrl/Cmd + Shift + K` → Filter by tags (e.g. typing `#crypto`)

2. **Leverage tags and consistent filenames**:
   - Tags are kebab-case and domain-specific: `#concept`, `#project`, `#literature`, `#log`, plus domain tags like `#crypto`, `#fuzzing`, etc.
   - Files use clear prefixes: `Concept–Symmetric_Encryption.md`, `Lit–AES_Paper_2025.md`, etc.

## Vault structure & linking

The vault relies on structured templates to maintain consistency. Each note includes frontmatter fields—title, aliases, tags, created/date, and status—along with empty placeholder sections. This ensures every file follows a predictable format, which is crucial for scalability and maintainability across domains.

Internal connections are achieved through Wikilinks, which seamlessly integrate notes into a cohesive knowledge web. Quartz’s Graph View then visualizes these connections, turning a complex vault into a navigable map of interrelated concepts.

Aliases play an important role in reducing redundancy and enhancing discoverability. For instance, a concept might be titled “Symmetric Encryption” but include an alias like “SymEnc” to account for common shorthand.

## Quick Reference

This vault supports powerful features for efficient navigation and organization. Instant full‑text search—built on Flexsearch—delivers results in under 10 ms, even in large vaults. You can also filter via tags or folder paths. Automatic backlinks and Graph View further enrich the navigational experience.

Filename conventions are clearly defined: all notes follow one of four prefixes `Concept-...`, `Project-...`, `Lit-...`, or `Log-...`. Tagging conventions combine the note type and domain; e.g., `#concept`, `#project`, `#crypto`, `#fuzzing`, etc. Templates for each note type reside in their corresponding domain folder, ensuring uniformity across the vault.

## License

All folders except `content` are licensed under the [MIT License](https://opensource.org/licenses/MIT).

The `content` folder is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).
