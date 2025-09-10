# CS Knowledge Base (Articles, Playbooks & Onboarding)

A public, open-source library of Customer Success (CS) articles, playbooks, templates, and onboarding plans.

## Quick Start
1. **Read the structure** below and add content in `docs/` (Markdown).
2. To publish as a website, enable **GitHub Pages** and use the included MkDocs workflow.
3. Follow **CONTRIBUTING.md** for style, naming, and structure.

## Repository Structure
```
docs/
  index.md
  articles/
    sample-article.md
    templates/
      article-template.md
  playbooks/
    QBR-playbook.md
    Renewal-runbook.md
  onboarding/
    30-60-90-template.md
    csm-onboarding-checklist.md
  checklists/
    qbr-checklist.md
    renewal-checklist.md
.github/
  workflows/
    deploy-mkdocs.yml
    lint-markdown.yml
  ISSUE_TEMPLATE/
    bug_report.md
    feature_request.md
  pull_request_template.md
.gitignore
LICENSE
NOTICE
CONTRIBUTING.md
CODE_OF_CONDUCT.md
mkdocs.yml
```

## Content License
- **Content** (Markdown in `docs/`): CC BY 4.0 (see `NOTICE`).
- **Code/config** (workflows, mkdocs.yml): MIT (see `LICENSE`).

## How to Publish as a Site (MkDocs + Material)
1. Push this repo to GitHub.
2. In **Settings → Pages**, set **Source: GitHub Actions**.
3. The `Deploy MkDocs` workflow will build and publish to **https://<your-username>.github.io/<repo-name>/** after each push to `main`.

## Contributing Principles
- Outcome-first; practical, copy-pasteable snippets.
- Use clear headings, short paragraphs, bullets, and examples.
- Prefer **templates** and **checklists** for repeatable tasks.
- Keep files small and focused; link related docs.

## Maintainers
- List maintainers & responsibilities here.
