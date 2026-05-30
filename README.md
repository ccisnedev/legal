# CCISNE Legal

Public legal site for CCISNE applications and projects.

## Why this repo exists

This repository centralizes public legal documents that need stable URLs across
multiple apps, stores, and release channels.

The repository name is `legal` instead of `policy` because the scope is broader
than privacy alone. It is intended to host privacy policies, terms, notices,
and other public legal pages under one durable site.

Recommended public domain: `legal.ccisne.dev`

## URL structure

Use app-specific paths instead of one generic policy page for everything.

- `/calculatrix/privacy/`
- `/calculatrix/terms/`
- `/another-app/privacy/`

This keeps store links specific to each product while still sharing one site
and one publication workflow.

## Publishing

The repository is configured for GitHub Pages through GitHub Actions.
The site artifact is published from the `site/` directory.

## Current apps

- Calculatrix
