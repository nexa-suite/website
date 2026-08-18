# Nexa Website Security Policy

## Supported version

| Repository | Current release | Support scope |
|---|---:|---|
| `nexa-suite/website` | `v1.1.x` | Static HTML, CSS, JavaScript and documentation |

No deployed service is asserted by this repository.

## Scope

Security review covers static pages, client-side scripts, local browser state, public links, legal pages, repository configuration and community documentation.

## Reporting a vulnerability

Do not open a public issue for vulnerabilities. Email `nexa.business.contact@gmail.com` with subject `[SECURITY][website] concise vulnerability title`.

Include the affected file or page, reproduction steps, expected and actual behavior, browser/environment details, risk and suggested mitigation when known. Do not send tokens, passwords, personal data or destructive exploit instructions.

## Security requirements

- Keep secrets and private deployment values out of the repository.
- Keep public links HTTPS-based and claim-accurate.
- Review third-party scripts before adding them.
- Keep privacy and cookie language aligned with the current static-site behavior.
- Run the documented JavaScript syntax checks before a release.
