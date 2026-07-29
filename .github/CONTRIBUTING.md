# Contributing to Nexa Website

## Repository context

This repository is the static public Website for Nexa Suite.

| Field | Value |
|---|---|
| Latest published product release | `v0.1.0` |
| Documentation edition | `v1.0.0` |
| Local Git state | HEAD is untagged |
| Runtime | Static HTML / CSS / JavaScript |
| Dependencies | None required for local serving |
| Deployment configuration | `render.yaml` only; deployment is not asserted here |

## Workflow

1. Create a branch from `develop`.
2. Keep changes scoped to a page, content area or documentation concern.
3. Preserve the existing static HTML/CSS/JavaScript structure.
4. Use conventional commits and do not add temporary files, screenshots, OS metadata or secrets.
5. Validate locally before opening a pull request.

## Architecture rules

- Use semantic HTML and the existing page-relative asset paths.
- Keep styles in the current CSS layers and JavaScript small and page-focused.
- Keep visible copy aligned with Nexa's B2B cold-chain domain.
- Mark future API, database, AI, IoT, mobile and hosting capabilities as roadmap unless independently evidenced.
- Do not migrate the stack or introduce dependencies as part of a content or documentation change.

## Validation checklist

```bash
python3 -m http.server 8000
node --check assets/js/i18n.js
node --check assets/js/interactions.js
node --check assets/js/animations.js
node --check assets/js/pricing.js
```

For visual changes, inspect desktop and mobile layouts in a browser. For documentation changes, check relative links and release/version claims.

## Pull request notes

Include affected files, public claim or link changes, responsive impact, validation commands and deployment notes only when deployment was actually verified.

Nexa Suite · Website · 2026
