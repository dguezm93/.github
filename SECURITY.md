# Security policy

## Reporting a vulnerability

Please use **Security → Report a vulnerability** in the affected repository to submit a private report.

Include the affected version or commit, reproduction steps, likely impact, and a minimal proof of concept. Remove tokens, personal data, and unrelated confidential material.

Do not publish an exploit or sensitive details in a public issue. If the private reporting button is unavailable, open an issue that only asks the maintainer to enable private reporting; omit vulnerability details.

## Supported versions

Unless a project states otherwise, security fixes target its default branch. No support period or response-time guarantee is implied.

## Handling secrets

Revoke or rotate an exposed credential immediately. Deleting a file or commit does not invalidate a credential. Use repository / environment secrets or a dedicated secret manager and grant only the permissions needed.
