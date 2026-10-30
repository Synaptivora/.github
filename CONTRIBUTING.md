# Contributing

Thanks for your interest in Synaptivora. This document applies to every repository in the organization unless a repository provides its own `CONTRIBUTING.md`.

## Before you start

- **Open an issue first** for anything larger than a typo or a one-line fix. It avoids duplicated work and lets maintainers flag design conflicts early.
- For upstream projects, prefer contributing to the original repository rather than to a fork.

## Pull requests

1. Branch from the default branch and keep the branch focused on one change.
2. Write a description that states **what changed**, **why**, and **how it was verified**.
3. Include a reproduction or a test for bug fixes.
4. Keep the diff reviewable. Unrelated formatting churn is discouraged.
5. Make sure CI passes before requesting review.

## Commit messages

Follow Conventional Commits where practical:

```
feat(scope): add adaptive enrichment mirror comparison
fix(scope): guard against empty rank vector
docs: clarify installation steps
```

## Review

- Reviewers aim to respond within three working days.
- A pull request requires at least one approving review before merge.
- Maintainers may ask for changes; unresolved conversations block merge.

## Reporting security issues

Do not open a public issue. See [SECURITY.md](SECURITY.md).
