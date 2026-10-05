<div align="center">

<br />

<img src="./docs/assets/nexa.svg" alt="Nexa" width="240" />

# Nexa Website

**Public product experience and acquisition entry point for Nexa Suite.**

![HTML5](https://img.shields.io/badge/HTML5-static-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-responsive-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Latest Git tag](https://img.shields.io/github/v/tag/nexa-suite/website?sort=semver&style=flat-square&label=latest%20Git%20tag)

[Live site](https://nexa-suite.github.io/website/) · [Pages](#public-pages) · [Run locally](#run-locally) · [Releases](./docs/releases/) · [Security](#security)

</div>

---

## Overview

Nexa Website is the static bilingual public web surface for communicating Nexa’s
accepted B2B product scope, solutions, company background and public status. The
inherited visual design is retained. Product descriptions are informational and
strictly distinguish target scope from verified implementation.

Academic context: `1ACC0238 Aplicaciones para Dispositivos Móviles`, NRC `4949`,
period `202620`. Course and team data are sourced from current project materials.

The [v1.0.0 release boundary](./docs/releases/v1.0.0.md) establishes the current
public site baseline. The versioned release notes define this static-site boundary. Published tags and
GitHub Releases remain available in the repository release register.

## Nexa Product Ecosystem

<table>
<tr>
<td width="50%" valign="top">

### [Nexa Mobile Report](https://github.com/nexa-suite/mobile-report)

Academic report and delivery evidence for Nexa Mobile.

![Markdown](https://img.shields.io/badge/Markdown-academic%20evidence-000000?style=flat-square&logo=markdown&logoColor=white)

</td>
<td width="50%" valign="top">

### [Nexa Mobile](https://github.com/nexa-suite/mobile)

Mobile client repository: Operations Android client and mobile runway.

![Operations Android](https://img.shields.io/badge/Operations%20Mobile-native%20client-3DDC84?style=flat-square&logo=android&logoColor=white) ![Buyer target](https://img.shields.io/badge/Buyer%20Mobile-TARGET%20Flutter%2FDart-64748B?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Nexa API](https://github.com/nexa-suite/api)

Authoritative business and integration backbone for Nexa Suite.

![Java](https://img.shields.io/badge/Java-25-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-4.1-6DB33F?style=flat-square&logo=springboot&logoColor=white)

</td>
<td width="50%" valign="top">

### [Nexa Website](https://github.com/nexa-suite/website)

This repository: public product experience and acquisition entry point.

![HTML5](https://img.shields.io/badge/HTML5-static-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-responsive-1572B6?style=flat-square&logo=css3&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Nexa Buyer Portal](https://github.com/nexa-suite/portal)

Buyer-facing Web experience for B2B purchasing and delivery visibility.

![Angular](https://img.shields.io/badge/Angular-22-DD0031?style=flat-square&logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?style=flat-square&logo=typescript&logoColor=white)

</td>
<td width="50%" valign="top">

### [Nexa Platform](https://github.com/nexa-suite/platform)

Internal operational Web workspace for tenant teams.

![Angular](https://img.shields.io/badge/Angular-22-DD0031?style=flat-square&logo=angular&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?style=flat-square&logo=typescript&logoColor=white)

</td>
</tr>
</table>

## Public Pages

- `index.html` — Nexa product scope and value proposition overview.
- `pages/platform.html` — Product operational domains and Platform boundaries.
- `pages/buyer-portal.html` — Buyer Portal presentation and self-service purchasing scope.
- `pages/company.html` — Company background and organization information.
- `pages/about-the-team.html` — Verified project team profiles.
- `pages/about-the-product.html` — Product architecture and operational scope description.
- `pages/pricing.html` — Commercial plans, pricing tiers, and enterprise inquiry entry point.
- `pages/faq.html` — Product scope and frequently asked questions.
- `pages/solutions/` — Industry target segment solutions (importers, distributors, cold storage).
- `pages/legal/` — Legal terms, privacy policy, and cookie disclosure.
- `pages/login.html` — Enterprise multi-tenant access portal and mobile terminal guidance.

## Technology Stack

| Concern | Implementation |
| --- | --- |
| Markup | HTML5 semantic elements |
| Styling | CSS3 responsive layouts |
| Logic | Vanilla JavaScript (no framework or heavy bundle) |
| Hosting | GitHub Pages / Render static web service |
| Configuration | `render.yaml` infrastructure-as-code specification |

## Run Locally

The site uses static HTML, CSS, and JavaScript; no package installation or build step is required:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000` in any modern web browser.

## Repository Structure

```text
index.html                  Landing page entry point
pages/                      Public sub-pages (platform, buyer-portal, company, pricing, FAQ)
pages/solutions/            Industry target segment solution descriptions
pages/legal/                Terms of service, privacy, and cookies disclosures
assets/                     Static stylesheets, images, scripts and icons
docs/                       Content provenance, releases and brand assets
render.yaml                 Render deployment configuration
```

## Ownership & Boundaries

- Website owns public marketing presentation, informational content, and contact/demo intake entry points.
- Nexa API remains the server authority for authentication, tenant scope, and business operations.
- This repository does not claim product acceptance, system acceptance, production readiness, a public service SLA, pricing commitments, or customer support guarantees.

## Documentation

- [Content provenance](./docs/content-provenance.md)
- [Release notes](./docs/releases/)
- [Changelog](./CHANGELOG.md)

## Nexa Engineering & Documentation

<table>
<tr>
<td width="50%" valign="top">

### [Nexa Blueprint](https://github.com/nexa-suite/blueprint)

Canonical Product, Domain, Architecture, data, security and accepted
engineering decision source.

![Markdown](https://img.shields.io/badge/Markdown-canonical%20documentation-000000?style=flat-square&logo=markdown&logoColor=white)

</td>
<td width="50%" valign="top">

### [Nexa Web Report](https://github.com/nexa-suite/web-report)

Academic report and evidence repository for the Nexa Web course.

![Docs as Code](https://img.shields.io/badge/Docs%20as%20Code-academic%20evidence-64748B?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Nexa Complementary](https://github.com/nexa-suite/complementary)

Supporting references, reproducible engineering resources and shared tooling.

![Support tooling](https://img.shields.io/badge/Support%20tooling-reference-64748B?style=flat-square)

</td>
<td width="50%" valign="top">

### [Nexa Design Lab](https://github.com/nexa-suite/design-lab)

UX/UI, interaction, design-system, prototype and current design-evidence
workspace.

![Angular](https://img.shields.io/badge/Angular-22-DD0031?style=flat-square&logo=angular&logoColor=white)

</td>
</tr>
</table>

## Security

Follow the organization security policy for reporting vulnerabilities. Do not
submit sensitive business inquiries or security reports through public repository
issues.

## Legal

Copyright © 2026 Nexa. All rights reserved. No open-source license is claimed
by this README.

<div align="center"><br />Nexa · Public product experience, explicit evidence boundaries</div>
