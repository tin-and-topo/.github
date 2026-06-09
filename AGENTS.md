# AI Agent Instructions for the .github Repository

This special repository holds default community health files and templates for the entire `tin-and-topo` GitHub organization. Changes made here have a broad impact. Adhere to these guidelines strictly.

## Core Principles
1.  **Recognize the Scope:** This repository provides the default `README.md`, `CONTRIBUTING.md`, issue templates, and workflow templates for other repositories. Edits should be generic and broadly applicable.
2.  **Preserve Template Integrity:** When editing templates (e.g., `workflow-templates/*.yml`, `.github/ISSUE_TEMPLATE/*.yml`), maintain valid syntax and structure. Do not add project-specific logic.
3.  **Prioritize Clarity and Simplicity:** These files will be read by everyone. Use clear language and standard Markdown. Avoid complex or non-standard formatting.
4.  **No Application Code:** This repository contains configuration and documentation, not application code. Do not add Python scripts, notebooks, or other project-specific files unless the request is to create a new *template*.

## File-Specific Guidance
*   **`workflow-templates/*.yml`**: These are GitHub Actions templates. Ensure changes are syntactically valid YAML and use GitHub Actions expressions correctly. The goal is to create robust, reusable workflows for other projects.
*   **`.github/ISSUE_TEMPLATE/*.yml`**: These are issue forms. Preserve the YAML structure. Edits should focus on improving the clarity of labels and descriptions for bug reports and feature requests.
*   **`profile/README.md`**: This is the public-facing README for the entire organization. Changes should be professional and concise.
*   **Root Markdown Files (`CONTRIBUTING.md`, `SECURITY.md`, etc.)**: These are default policies. Ensure they remain general enough to apply to any repository in the organization.
