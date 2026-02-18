# CLAUDE.md

## Repository Overview

This is a **GitHub profile repository** (`lbblaise/lbblaise`). GitHub treats a repository whose name matches its owner's username as special: the `README.md` at the root is automatically rendered on the owner's public GitHub profile page at `https://github.com/lbblaise`.

There is no application code, build system, package manager, or test suite. The entire content of this repository is a single Markdown file.

---

## Repository Structure

```
lbblaise/          (root)
├── README.md      # GitHub profile page content (rendered publicly)
└── CLAUDE.md      # This file — guidance for AI assistants
```

---

## Purpose and Content

`README.md` is a personal profile page. Its current content:

- Interests: security, software development, ethical hacking
- Currently learning: programming and CompTIA Security+
- Open to collaboration on learning-focused projects

---

## Development Workflow

Because this repository has no code, the workflow is simple:

1. **Edit `README.md`** — all profile changes go here.
2. **Commit** with a clear message describing what was updated (e.g., `Update profile: add new skills`).
3. **Push to `master`** — changes are immediately live on the GitHub profile.

There is no CI/CD pipeline, no linting, and no build step.

---

## Conventions

### Markdown style
- Use standard GitHub Flavored Markdown (GFM).
- Emoji are acceptable and commonly used in profile READMEs.
- Keep sections short and scannable; this is a public-facing profile, not documentation.
- Avoid including any personal contact information, credentials, or sensitive data.

### Commit messages
- Use present tense, imperative mood: `Add`, `Update`, `Remove`, not `Added` or `Updates`.
- Keep the subject line under 72 characters.
- Example: `Update README: add CompTIA Security+ progress`

### Branch hygiene
- `master` is the default branch and the source of truth for the profile.
- Feature branches (e.g., `claude/...`) are used for AI-assisted changes and should be merged or deleted after review.

---

## Notes for AI Assistants

- **Only `README.md` matters** for the profile. Any other files are invisible to GitHub profile rendering.
- Do not add build tooling, package managers, or configuration files unless explicitly requested; they serve no purpose here.
- Do not invent or suggest technologies/skills not mentioned by the owner — the profile should be accurate.
- Keep changes minimal and focused. This is a personal profile, not a project codebase.
- When editing `README.md`, preserve the owner's voice and tone.
