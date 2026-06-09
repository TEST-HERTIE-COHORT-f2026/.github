# GitHub Actions Configuration

This org allows public actions necessary for course management:

## Allowed actions (automatically available)

- `actions/checkout` — clone repositories
- `actions/setup-python` — Python environments
- `actions/setup-node` — Node.js environments
- `actions/upload-artifact` — store build outputs
- `actions/download-artifact` — fetch build outputs
- `actions/create-release` — publish releases
- `github/super-linter` — code quality checks
- `softprops/action-gh-release` — release automation
- All other GitHub-owned actions (github/*)
- All Hertie DSL actions (hertie-data-science-lab/*)

## Disabled

- Third-party actions (unless explicitly approved)
- Actions from untrusted sources
- Any action with credential write access

## Adding new actions

Contact the DSL team before enabling new actions.
