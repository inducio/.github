# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is the `inducio/.github` repository — a special GitHub organization repository that provides default community health files and shared workflows for all repositories in the `inducio` organization.

Files placed here act as defaults for any `inducio` repo that doesn't have its own version of these files.

## Typical Contents

- `profile/README.md` — Organization profile page shown on the `inducio` GitHub org page
- `ISSUE_TEMPLATE/` — Default issue templates (bug reports, feature requests)
- `PULL_REQUEST_TEMPLATE.md` — Default PR description template
- `CONTRIBUTING.md` — Contribution guidelines applied org-wide
- `CODE_OF_CONDUCT.md` — Code of conduct applied org-wide
- `FUNDING.yml` — Funding/sponsorship configuration
- `workflows/` — Reusable GitHub Actions workflows (called via `uses: inducio/.github/.github/workflows/...`)

## GitHub Actions Workflows

Reusable workflows live at `.github/workflows/` and are referenced from other repos as:
```yaml
uses: inducio/.github/.github/workflows/<workflow-file>.yml@main
```
