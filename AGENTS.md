# PlayPen — Agent Guide

**Repo:** `github.com/soapgu/PlayPen` (personal technical blog)

## What this is

- Knowledge base organized as **GitHub Issues** (not code).
- `README.md` is the index/catalog — links to issues grouped by topic.
- Only two on-disk files matter: `README.md` and images under `images/`.

## Adding content

1. Create a GitHub issue with the technical content.
2. Optionally place supporting images in `images/` and reference them via `![](/images/...)`.
3. Add a new bullet link in `README.md` under the appropriate section heading.

## Conventions

- **Commit messages:** follow Conventional Commits with emoji (e.g. `feat: 🎸 update to #275`, `docs: ✏️ update to #232`).
- **Branching:** single `main` branch. No feature branches.
- **Images:** committed to `images/` directory before referencing in README or issues.
- **.gitignore:** only `.DS_Store` is ignored.

## What NOT to do

- Do not add source code, build config, or package manifests — this is not a code project.
- Do not create new files or directories outside `images/` without a clear reason.
