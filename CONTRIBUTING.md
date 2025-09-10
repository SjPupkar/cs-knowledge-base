# Contributing

Thanks for helping improve this CS knowledge base!

## Style Guide
- Write in **Markdown** (`.md`) inside `docs/`.
- Use **H1 once** at the top (`# Title`), then `##`, `###`.
- Keep paragraphs short; use bullets and tables for clarity.
- Add **Examples**, **Templates**, or **Checklists** when possible.

## File Naming
- Kebab-case file names (e.g., `renewal-runbook.md`).
- Start each doc with **front matter** for metadata:
  ```yaml
  ---
  title: Renewal Runbook
  summary: Step-by-step playbook to drive on-time renewals and reduce churn risk.
  tags: [renewals, playbook]
  last_updated: 2025-09-09
  author: Your Name
  ---
  ```

## Structure
- `docs/articles` – Thought pieces, how-tos, frameworks.
- `docs/playbooks` – Step-by-step runbooks (QBRs, renewals, expansions).
- `docs/onboarding` – 30-60-90s, role onboarding guides, checklists.
- `docs/checklists` – Standalone checklists.

## Pull Requests
1. Create a new branch.
2. Ensure docs build locally with `mkdocs build` (optional).
3. Follow templates in `.github/`.
4. Keep PRs small & focused.

## Linting
- CI runs a Markdown linter (MD rules). Fix warnings before merging.
