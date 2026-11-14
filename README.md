# AviorLab · Development defaults

Small, reusable templates for clear tasks and reviewable changes.

| File | Purpose |
| --- | --- |
| `.github/ISSUE_TEMPLATE/bug.yml` | Capture the expected result, actual result and reproduction steps. |
| `.github/ISSUE_TEMPLATE/feature.yml` | Define the user problem, desired outcome and acceptance criteria. |
| `PULL_REQUEST_TEMPLATE.md` | Explain the change, validation and remaining limitations. |

GitHub uses these defaults in repositories owned by AviorLab that do not define their own corresponding templates. Repository-specific templates take precedence. These defaults do not copy files into other repositories.

## AI coding agents

Agent instructions belong in each project's `AGENTS.md`, alongside that project's sources of truth and validation commands. This repository does not make `AGENTS.md` inherit across unrelated repositories.

Keep one authoritative set of project instructions. Follow the project's existing instructions before making changes; do not replace them with generic templates. An instruction file does not activate a hosted coding agent or grant it access.

[GitHub documentation: default community files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
