# Agent Instructions

This repository holds OHTF's organisation-wide GitHub files: the org profile README and default community health files. It holds no code. Read [README.md](README.md) first.

## Core Invariants

- The website ([`ohtf/openhealthtechnology.org-website`](https://github.com/ohtf/openhealthtechnology.org-website)) is the source of truth for OHTF's policies and wording. Follow its `agent-instructions.md`, especially the voice rules, the business-as-usual rule and the legal-name rule. Change the website first, then bring these files in line.
- The Foundation Projects table in `profile/README.md` lists only repositories that have moved to github.com/ohtf and that the maintainer has confirmed as Foundation Projects. Keep it in step with the website's projects page.
- These files must stay short and link to the website for detail.
- British English, no em dashes, no hard-wrapped Markdown.

## Git Workflow

- Commit each coherent change with a conventional commit message, signed off (`git commit -s`).
- Do not push unless the user asks. Pushing to `main` changes the public org profile immediately.
