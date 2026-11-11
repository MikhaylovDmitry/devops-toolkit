# Contributing to DevOps Toolkit

This repository is a shared collection of DevOps tools, scripts, queries, CLI commands, and troubleshooting solutions.

All team members are encouraged to contribute useful tools and share solutions that can benefit others.

## Repository Structure

Place contributions in the appropriate directory:

| Directory | Contents |
|---|---|
| `scripts/` | Automation scripts (Bash, Python). |
| `queries/` | SQL, monitoring, logging, and infrastructure queries. |
| `cli/` | Useful CLI commands and examples (AWS, kubectl, Docker, Linux). |
| `troubleshooting/` | Diagnostic commands and troubleshooting solutions. |

## Contribution Requirements

Every tool or solution must include documentation explaining its purpose and usage.

Documentation must be provided as a separate Markdown (`.md`) file alongside the corresponding tool.

For troubleshooting guides and CLI references, the Markdown file itself can contain the complete solution.

### Documentation Content

Each documentation file should include the following sections where applicable:

| Section | Description |
|---|---|
| Purpose | What the tool does and what problem it solves. |
| Prerequisites | Required tools, versions, permissions, and dependencies. |
| Usage | How to use the tool, including parameters and options. |
| Examples | Practical examples and expected output. |
| Notes | Important considerations, limitations, or potential risks. |

## Naming Convention

- Use lowercase filenames.
- Use hyphens (`-`) to separate words.
- Use descriptive names reflecting the tool's purpose.
- Use appropriate file extensions (`.sh`, `.py`, `.sql`, `.md`, etc.).
- Keep tool and documentation filenames consistent.

Examples:

    scripts/
    ├── cleanup-logs.sh
    └── cleanup-logs.md

    queries/
    ├── find-slow-queries.sql
    └── find-slow-queries.md

    troubleshooting/
    └── kubernetes-pod-crash-loop.md

## General Guidelines

- Prefer reusable and generic solutions over environment-specific implementations.
- Do not commit passwords, API keys, tokens, credentials, or sensitive production data.
- Clearly document commands that may modify or delete data or affect production systems.
- Check existing contributions before adding duplicates.
- Test scripts and queries before sharing them.
- Keep documentation accurate and up to date.

## Pull Request and Review Process (Draft)

All contributions should be submitted through Pull Requests and reviewed before merging into the main branch.

This process is a proposed starting point and may be adjusted as the team establishes repository conventions and policies.

### Contributor Responsibilities

Before submitting a Pull Request, the contributor should:

- Ensure the tool and its documentation are included.
- Test the solution where applicable.
- Check that no credentials, secrets, tokens, or sensitive data are included.
- Ensure the solution does not violate known company security requirements or access restrictions.
- Describe the purpose and intended use of the contribution.

### Reviewer Responsibilities

The reviewer should check:

| Area | Review Criteria |
|---|---|
| Security | No hardcoded credentials, secrets, tokens, or sensitive information. |
| Permissions | The tool follows company access policies and does not require unauthorized privileges. |
| Compliance | The solution does not violate known company security policies or operational requirements. |
| Safety | Potentially destructive or disruptive operations are clearly documented and appropriately safeguarded. |
| Functionality | The script, query, or command is understandable and behaves as intended. |
| Documentation | Usage instructions, prerequisites, and limitations are sufficiently explained. |

### Approval

- A contribution should only be merged after the reviewer has completed the checks and approved the Pull Request.
- If issues are identified, the contributor should address them before merging.
- Company security and approval requirements take precedence over this repository's review process.

## Maintenance

The repository is maintained collaboratively by the DevOps team.

Contributors are encouraged to improve existing content, correct outdated information, and share useful solutions.

---

**Note:** This document describes an initial proposed workflow. Contribution conventions, review requirements, and approval responsibilities are subject to further agreement within the DevOps team.
