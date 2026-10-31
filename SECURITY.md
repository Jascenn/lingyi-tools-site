# Security Policy

## Supported Versions

Security fixes apply to the latest commit on `main`. Forks and older static
deployments are not maintained by this repository.

## Reporting a Vulnerability

Do not open a public issue for a security vulnerability. Use GitHub Security
Advisories:

https://github.com/Jascenn/lingyi-tools-site/security/advisories/new

Include the affected commit, reproduction steps, expected impact, and any
suggested mitigation. Do not include cookies, access tokens, or private user
data.

## Static Site Boundary

This repository contains the public product page only. It does not provide
accounts, forms, payments, or local monitoring data.

The page currently loads:

- a self-hosted Minilytics script
- a font stylesheet from jsDelivr
- links to GitHub releases, source code, and Lingyi properties

Changes that add scripts, embeds, forms, redirects, or external requests must be
reviewed in the pull request and documented in `PRIVACY.md`.
