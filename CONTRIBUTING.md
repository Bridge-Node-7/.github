# Contributing

Thanks for your interest in Bridge Node 7 public repositories.

## Before you start

- Read the repository README for scope, non-goals, and license posture.
- Do not open issues or pull requests that include personal data (personal emails, phone numbers, home addresses, private names beyond a public GitHub handle, or secrets).
- Prefer GitHub noreply commit emails.

## Commit messages

Use [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` user-visible capability
- `fix:` bug fix
- `docs:` documentation only
- `ci:` workflows / automation
- `chore:` maintenance
- `security:` security or privacy hardening
- `perf:` performance
- `refactor:` non-behavioral restructure
- `test:` tests only

Examples:

- `fix: reject null criticality at graph intake`
- `docs: clarify public README scope`
- `chore(deps): bump github-actions group`

Breaking changes: add `!` after the type (for example `feat!: ...`) or a `BREAKING CHANGE:` footer.

## Pull requests

1. Keep changes focused and reversible.
2. Do not bump version numbers by hand when release-please is enabled — merge release PRs instead.
3. Ensure CI is green.
4. Avoid committing local virtualenvs, `__pycache__`, or IDE files.

## Security

Do not file public issues for vulnerabilities. Follow `SECURITY.md`.

## License

Contributions are accepted under the license stated in each repository's `LICENSE` file. Some Bridge Node 7 repositories are All Rights Reserved / evaluation-only — check before contributing substantial work.
