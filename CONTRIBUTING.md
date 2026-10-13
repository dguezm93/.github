# Contributing

Small, well-explained improvements are welcome. English and Spanish are welcome.

## Before coding

- Read the project's README and security policy.
- Search existing issues and pull requests.
- For a substantial change, open an issue describing the problem, constraints, and acceptance criteria.
- Never publish credentials, private customer data, or confidential logs.

## Development

1. Fork or clone the repository and create a focused branch.
2. Follow the README's setup instructions.
3. Add tests when behavior changes. Cover errors and edge cases, not only the happy path.
4. Run formatting, static checks, and tests.
5. Update documentation and examples when behavior changes.

## Pull requests

Explain what changed and why, how it was verified, and any compatibility or security impact. Include screenshots for user-interface changes when useful. Keep unrelated refactoring separate.

Use clear commit messages, for example `fix: handle empty input` or `docs: clarify setup`.

## Review and releases

Checks must pass before merging. Review dependency updates before accepting them. A green CI run is one part of review, not proof that a change is safe to deploy.

For deployments, identify configuration, migration steps, monitoring, and a rollback procedure. Never add production credentials to repository files.
