# Contributing

Thanks for improving this project.

## Workflow

1. Create a short-lived branch from the default branch.
2. Use a descriptive branch name such as `feat/topic`, `fix/topic`, or `chore/topic`.
3. Keep each pull request focused on one change.
4. Use a Conventional Commit style pull request title, for example `feat(auth): add passkey login`.
5. Update tests and documentation when behavior changes.

## Before opening a pull request

- Run the repository's documented lint, type-check, test, and build commands.
- Remove secrets, credentials, generated artifacts, and unrelated changes.
- Explain the motivation, verification performed, risks, and rollback plan.
- Link the issue or requirement the change addresses.

## Review and merge

All required checks must pass. Resolve review conversations before merge. Prefer squash merge unless the repository documents a different release workflow.