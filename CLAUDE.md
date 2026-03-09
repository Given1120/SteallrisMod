# CLAUDE.md — AI Assistant Guide for SteallrisMod

## Project Overview

**SteallrisMod** is a game mod project. This repository is in early setup — source files will be added as the project develops. This document will be updated as conventions and structure are established.

---

## Repository Structure

```
SteallrisMod/
├── CLAUDE.md        # This file — AI assistant guide
└── README.md        # Project README
```

As mod files are added, this structure will expand. Update this section accordingly.

---

## Git Workflow

### Branches
- `master` — stable/main branch
- `claude/...` — branches used by AI assistants for automated tasks

### Commit Conventions
- Write clear, descriptive commit messages in imperative mood (e.g., "Add player speed modifier")
- Keep commits focused on a single change

### Pushing Changes
Always push to the correct branch:
```bash
git push -u origin <branch-name>
```

---

## Development Notes

- This is a **game mod** project. When mod files (scripts, config files, assets, etc.) are added, document their purpose and game system here.
- Update this CLAUDE.md whenever new conventions, tools, or workflows are established.
- If a build system, mod loader, or game engine SDK is introduced, document setup steps here.

---

## For AI Assistants

- **Do not delete or overwrite mod files** without explicit user confirmation.
- **Preserve mod-specific syntax** — game mod files often use custom scripting languages or DSLs that differ from standard code conventions.
- **Ask before refactoring** — mod file structure is often dictated by the game engine, not best practices.
- When in doubt about a file's purpose, ask the user rather than assuming.
- This file should be updated as the project grows to reflect the actual codebase.
