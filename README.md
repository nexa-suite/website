<div align="center">

<br />

<img src="./assets/img/nexa.svg" alt="Nexa" width="240" />

# Nexa Website

**Public product experience and entry point for Nexa.**

![HTML5](https://img.shields.io/badge/HTML5-semantic-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-responsive-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Static](https://img.shields.io/badge/site-static-2563EB?style=flat-square) ![Release](https://img.shields.io/github/v/release/nexa-suite/website?display_name=tag&sort=semver&style=flat-square&label=release)

[Changelog](./CHANGELOG.md) · [Release notes](./docs/releases/) · [Contributing](./.github/CONTRIBUTING.md) · [Security](./.github/SECURITY.md)

</div>

---

## Overview

Static public site for product discovery, cold-chain positioning, product context, contact and demo entry points. Contact form delegates persistence, validation and abuse controls to Nexa API.

Website does not implement backend, database, tenant authorization, mobile, AI, IoT or cloud services. Marketing copy can describe future capabilities only when clearly marked as future.

## Related repositories

The organization profile owns the full public ecosystem map. This repository links to adjacent Nexa surfaces without copying their release state.

- [Nexa API](https://github.com/nexa-suite/api) — business and integration backbone.
- [Nexa Platform](https://github.com/nexa-suite/platform) — internal operational workspace.
- [Nexa Buyer Portal](https://github.com/nexa-suite/portal) — buyer-facing experience.
- [Nexa Mobile](https://github.com/nexa-suite/mobile) — documentation and native runway.

## Public Experience

- Product overview and calls to action.
- Platform, Buyer Portal and solution pages.
- ES/EN content and responsive layouts.
- Contact and demo intake through API contract.
- Legal, privacy, cookies and FAQ pages.

## Technology Stack

| Concern | Technology |
| --- | --- |
| Markup | HTML5 |
| Styling | CSS3 with tokens and responsive layout |
| Interactivity | Vanilla JavaScript |
| Internationalization | Custom ES/EN dictionaries |
| Local hosting | Python static server, Docker/nginx or declared static host |

## Getting Started

    python3 -m http.server 8000

Open http://localhost:8000. Local contact intake targets http://localhost:8080/api/v1 by default.

## Validation

    node --check assets/js/i18n.js
    node --check assets/js/interactions.js
    node --check assets/js/animations.js
    node --check assets/js/pricing.js

## Repository Structure

    assets/css/       Design tokens and page styles
    assets/img/       Logos, illustrations and product imagery
    assets/js/        Internationalization and interactions
    pages/            Product, solution and legal pages
    docs/             Releases and documentation

## Documentation

- [Release notes](./docs/releases/)
- [Changelog](./CHANGELOG.md)
- [Release policy](./.github/RELEASE_POLICY.md)


## Historical provenance

Earlier UPC repositories remain evidence only. They do not define current Nexa identity, implementation authority or TARGET architecture.

- [nexa-platform](https://github.com/upc-pre-202610-1asi0730-12242-king/nexa-platform) — predecessor backend and REST API layer.
- [nexa-webapp](https://github.com/upc-pre-202610-1asi0730-12242-king/nexa-webapp) — historical unified Vue application.
- [nexa-website](https://github.com/upc-pre-202610-1asi0730-12242-king/nexa-website) — previous public Website lineage.
- [nexa-ecosystem-report](https://github.com/upc-pre-202610-1asi0730-12242-king/nexa-ecosystem-report) — historical requirements and architecture evidence.


## Security

Do not report vulnerabilities through public issues. Follow the repository [Security Policy](./.github/SECURITY.md).

## Legal

Copyright © 2026 Nexa. All rights reserved. No open-source license is selected by this README.

<div align="center"><br />Nexa · Current product, explicit evidence boundaries</div>
