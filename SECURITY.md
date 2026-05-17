# Security Policy

## Supported Versions

This project follows a rolling support model on the `main` branch.

- `main`: Supported
- Release tags/older commits: Best effort only

## Reporting a Vulnerability

Please do **not** open public GitHub issues for suspected vulnerabilities.

Report security issues privately via:
- GitHub Security Advisories (preferred): use the repository's **Report a vulnerability** flow.
- Or email the maintainer: **tanphuc16797@gmail.com**

Include as much detail as possible:
- A clear description of the issue
- Reproduction steps or proof of concept
- Impact assessment
- Suggested mitigation (if known)

## Response Expectations

Security reports are handled on a **best-effort** basis.

- No guaranteed response or remediation SLA
- Prioritization depends on severity, reproducibility, and maintainer availability
- Some reports may be deferred if maintainers are inactive

We will coordinate disclosure and credit reporters when appropriate.

## Scope Notes

This repository is a wiki/template and automation toolkit. Reports are in scope when they can impact:
- Integrity of generated artifacts or workflows
- Confidentiality of local/project data handled by scripts/commands
- Unsafe defaults that may cause security regressions in downstream usage
