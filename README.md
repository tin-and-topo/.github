# GitHub Organization Defaults

Welcome! This special repository centralizes the default community health files and templates for all repositories within the `tin-and-topo` GitHub organization.

The files here provide a consistent baseline for contributions, support, and automation. Repository-specific files will always override these defaults.

## What's Inside

| Path | Purpose |
| --- | --- |
| profile/README.md | The public-facing README for the `tin-and-topo` organization. |
| CONTRIBUTING.md | Default guide for how to contribute to our projects. |
| CODE_OF_CONDUCT.md | Sets participation expectations for a positive community. |
| SECURITY.md | Instructions for responsibly reporting security vulnerabilities. |
| SUPPORT.md | Guidance on how to get help and support. |
| GOVERNANCE.md | Outlines project stewardship and decision-making. |
| AGENTS.md | Instructions for AI coding assistants interacting with our repos. |
| .github/ISSUE_TEMPLATE | Default forms for creating new issues (bugs, features). |
| .github/PULL_REQUEST_TEMPLATE.md | The default template for pull request descriptions. |
| workflow-templates | Reusable GitHub Actions workflow templates for CI/CD. |

## How Defaults Work

GitHub automatically uses these files for any repository in the organization that does not have its own version of that file.

If a project needs specific instructions (e.g., different contribution steps or a unique issue template), simply add the corresponding file to that project's own `.github` folder. The project-specific file will always take precedence.

## Improving These Defaults

Since these files affect all repositories, changes should be broadly applicable. If you have a suggestion to improve a default template or policy, please open an issue or pull request in this repository.