# CLAUDE.md

This file provides guidance for AI assistants (e.g., Claude Code) working in this repository.

## Repository Overview

This is a personal resume repository owned by Eric Watkins ([@ericdub](https://github.com/ericdub)). The sole content file is `resume.md`, a Markdown-formatted curriculum vitae.

**Repository:** `ericdub/Resume`
**Primary file:** `resume.md`

## Repository Structure

```
Resume/
└── resume.md   # The resume / CV content (Markdown)
```

There are no build tools, dependencies, package managers, test suites, or CI pipelines in this repository.

## Development Workflow

### Branching

- `master` is the main branch.
- Feature/update branches follow the pattern `claude/<description>` (e.g., `claude/add-claude-documentation-Ogb2a`).
- Always develop on a named branch and push before opening a PR; never push directly to `master` unless the user explicitly instructs it.

### Making Changes

Because this is a pure-Markdown repository:

1. Edit `resume.md` directly — no build step is required.
2. Verify Markdown renders correctly (preview with any Markdown viewer; GitHub renders it natively).
3. Commit with a clear, concise message describing what changed (e.g., `Add senior engineer experience at Acme Corp`).
4. Push to the feature branch: `git push -u origin <branch-name>`.

### Commit Style

- Use the imperative mood: `Add`, `Update`, `Remove`, `Fix`.
- Keep the subject line under 72 characters.
- No body is needed for simple content edits; add one only when the reason for the change is non-obvious.

## resume.md Conventions

- Use standard Markdown headings (`#`, `##`, `###`) to organise sections.
- Common top-level sections: Contact, Summary/Objective, Experience, Education, Skills, Projects.
- Keep entries in reverse-chronological order within each section.
- Bullet points (`-`) for responsibilities/achievements under each role.
- Avoid raw HTML unless strictly necessary for formatting.
- Dates should be consistent: `Month YYYY – Month YYYY` or `Month YYYY – Present`.

## Key Constraints for AI Assistants

- **Do not add content you cannot verify.** Only add or edit resume content when the user provides explicit details (dates, titles, descriptions).
- **Do not push to `master` without explicit user approval.**
- **Do not create a pull request** unless the user explicitly asks for one.
- There are no tests, linters, or build commands to run — skip any steps that reference them.
- The repository is restricted to `ericdub/Resume`; do not interact with other repositories.
