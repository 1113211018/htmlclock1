# Copilot Instructions for htmlclock1

This repository is currently minimal.  At the time of writing it only contains:

- `.gitattributes`
- a `.git` directory

There is no application code, no build scripts, and no tests.  The project name suggests it may be intended to host a simple HTML clock, but nothing in the repository enforces or implements that.

## Big-picture context

- **Type**: apparently a lightweight static webpage project.  The workspace has *no* JavaScript, HTML, CSS or other source files yet.
- **Architecture**: none yet.  If code is added, it will likely live at the repository root; no subfolders currently exist.
- **External dependencies**: none.

Because there is no existing codebase, AI agents should not make assumptions about frameworks or build tools.  Whenever a task requires understanding of the application, ask the user for more details or sample files.

## Developer workflows

All operations currently are simple git actions.  There are no build, test or run commands defined.  Before implementing new code, confirm with the user what tooling (npm, Python, etc.) they intend to use.

## Conventions and patterns

- There are no project-specific conventions to follow yet.  If files are later added, follow the standard patterns the user creates and mimic their naming and folder structure.
- Use Windows-style paths (`\` or forward slash as appropriate) when working locally.

## Interaction guidance for AI coding agents

1. **Clarify**: when asked to add features, first check whether any source files exist.  If none, query the user for the desired language/framework and overall goal (e.g. "create a static HTML clock page").
2. **Minimal code**: start with the smallest possible implementation that satisfies the request, and add documentation to explain assumptions.
3. **Ask before writing**: refrain from inventing large scaffolding unless the user explicitly asks for a new project setup.
4. **Document new structures**: when new directories or files are introduced, update this instruction file with a brief description so future agents understand the emerging architecture.

## When updating this file

- Keep content concise (20–50 lines) and actionable.
- Merge with any previous instructions if they exist; retain useful historical notes.
- Use examples pulled from the repository as it evolves.

> **Note:** currently there is nothing to build or run.  This message should be revisited once the user adds actual code.

---

Please let me know if there are any specific workflows, file patterns, or questions you’d like the instructions to address.