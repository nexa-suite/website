<div align="center">

<br />

<img src="./assets/img/nexa.svg" alt="Nexa" width="220" />

<br /><br />

# Nexa Website

**Public product experience and entry point for Nexa.**

[![HTML5](https://img.shields.io/badge/HTML5-semantic-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML) [![CSS3](https://img.shields.io/badge/CSS3-responsive-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS) [![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript) [![Release](https://img.shields.io/github/v/release/nexa-suite/website?style=flat-square&label=release)](https://github.com/nexa-suite/website/releases)

[Changelog](./CHANGELOG.md) · [Release notes](./docs/releases/) · [Contributing](./.github/CONTRIBUTING.md) · [Security](./.github/SECURITY.md)

</div>

---

## Overview

Static public site for product discovery, cold-chain positioning, product context, contact and demo entry points. Contact form delegates persistence, validation and abuse controls to Nexa API.

Website does not implement backend, database, tenant authorization, mobile, AI, IoT or cloud services. Marketing copy can describe future capabilities only when clearly marked as future.

## Public experience

- Product overview and calls to action.
- Platform, Buyer Portal and solution pages.
- ES/EN content and responsive layouts.
- Contact and demo intake through API contract.
- Legal, privacy, cookies and FAQ pages.

## Nexa Product Ecosystem

<table>
<tr><td><strong>Nexa Website</strong><br />This repository. Public product discovery.<br /><img src="https://img.shields.io/github/v/release/nexa-suite/website?style=flat-square&label=release" alt="Website release" /></td><td><a href="https://github.com/nexa-suite/platform"><strong>Nexa Platform</strong></a><br />Internal operational workspace.<br /><img src="https://img.shields.io/github/v/release/nexa-suite/platform?style=flat-square&label=release" alt="Platform release" /></td></tr>
<tr><td><a href="https://github.com/nexa-suite/portal"><strong>Nexa Buyer Portal</strong></a><br />Buyer-facing business experience.<br /><img src="https://img.shields.io/github/v/release/nexa-suite/portal?style=flat-square&label=release" alt="Portal release" /></td><td><a href="https://github.com/nexa-suite/api"><strong>Nexa API</strong></a><br />Business and integration authority.<br /><img src="https://img.shields.io/github/v/release/nexa-suite/api?style=flat-square&label=release" alt="API release" /></td></tr>
<tr><td colspan="2"><a href="https://github.com/nexa-suite/mobile"><strong>Nexa Mobile</strong></a><br />Architecture runway for future native clients.<br /><img src="https://img.shields.io/github/v/release/nexa-suite/mobile?style=flat-square&label=release" alt="Mobile release" /></td></tr>
</table>

## Technology

| Layer | Technology |
| --- | --- |
| Markup | HTML5 |
| Styling | CSS3 with tokens and responsive layout |
| Interactivity | Vanilla JavaScript |
| Internationalization | Custom ES/EN dictionaries |
| Local hosting | Python static server, Docker/nginx or declared static host |

## Getting started

    python3 -m http.server 8000

Open http://localhost:8000. Local contact intake targets http://localhost:8080/api/v1 by default.

## Validation

    node --check assets/js/i18n.js
    node --check assets/js/interactions.js
    node --check assets/js/animations.js
    node --check assets/js/pricing.js

## Repository structure

    assets/css/       Design tokens and page styles
    assets/img/       Logos, illustrations and product imagery
    assets/js/        Internationalization and interactions
    pages/            Product, solution and legal pages
    docs/             Releases and documentation

## Documentation

- [Release notes](./docs/releases/)
- [Changelog](./CHANGELOG.md)
- [Release policy](./.github/RELEASE_POLICY.md)

## Security

Do not report vulnerabilities through public issues. Follow the [Security Policy](./.github/SECURITY.md).

## Legal

Copyright © 2026 Nexa. All rights reserved. No open-source license is selected by this README.

<div align="center"><br />Nexa · Public entry point for the product family</div>
