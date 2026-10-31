# Contributing

This repository contains a static product site. It must remain independent
from the local monitoring application in
`Jascenn/local-software-update-monitor`.

## Local Preview

```bash
python3 -m http.server 8000
```

Open `http://127.0.0.1:8000/`.

## Before Opening a Pull Request

- open the page locally and verify desktop and mobile layouts
- check all links and the `404.html` fallback
- keep `_headers` in place
- document any analytics, embedded content, or new external request
- do not add real account data, tokens, or private screenshots
- run `git diff --check`

## Pull Request Guidelines

- keep each pull request focused
- include before/after screenshots for visual changes
- use English Conventional Commits, such as `fix: clarify release link`
- complete the repository pull request template
- report security issues privately as described in `SECURITY.md`
