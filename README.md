# Cybersecurity Research Notes

A focused repository for cybersecurity research notes, threat breakdowns, vulnerability reviews, incident response thinking, and detection ideas.

The purpose of this repo is to document security research in a practical analyst format: what happened, why it matters, what evidence to look for, how detection can be improved, and what response actions reduce risk.

## Current Research Notes

| Date | Topic | Focus |
| --- | --- | --- |
| 2026-07-07 | [CVE-2026-48282: Adobe ColdFusion Path Traversal](research-notes/2026/2026-07-07-cve-2026-48282-adobe-coldfusion-path-traversal.md) | Internet-facing application risk, traversal detection, web log review, response steps |
| 2026-07-01 | [CVE-2026-45659: Microsoft SharePoint Server Deserialization](research-notes/2026/2026-07-01-cve-2026-45659-microsoft-sharepoint-deserialization.md) | Authenticated code execution risk, SharePoint/IIS/Windows evidence, response notes |
| 2026-06-29 | [CVE-2026-48558: SimpleHelp OIDC Authentication Bypass](research-notes/2026/2026-06-29-cve-2026-48558-simplehelp-oidc-authentication-bypass.md) | Identity validation risk, remote support monitoring, IdP correlation, MFA review |

## Past Year KEV Review

Monthly reviews based on CISA's Known Exploited Vulnerabilities catalog. Each note highlights representative exploited vulnerabilities from that month and turns them into analyst-focused review points.

| Month | Review |
| --- | --- |
| 2026-06 | [June 2026 KEV Review](research-notes/past-year/2026-06-kev-review.md) |
| 2026-05 | [May 2026 KEV Review](research-notes/past-year/2026-05-kev-review.md) |
| 2026-04 | [April 2026 KEV Review](research-notes/past-year/2026-04-kev-review.md) |
| 2026-03 | [March 2026 KEV Review](research-notes/past-year/2026-03-kev-review.md) |
| 2026-02 | [February 2026 KEV Review](research-notes/past-year/2026-02-kev-review.md) |
| 2026-01 | [January 2026 KEV Review](research-notes/past-year/2026-01-kev-review.md) |
| 2025-12 | [December 2025 KEV Review](research-notes/past-year/2025-12-kev-review.md) |
| 2025-11 | [November 2025 KEV Review](research-notes/past-year/2025-11-kev-review.md) |
| 2025-10 | [October 2025 KEV Review](research-notes/past-year/2025-10-kev-review.md) |
| 2025-09 | [September 2025 KEV Review](research-notes/past-year/2025-09-kev-review.md) |
| 2025-08 | [August 2025 KEV Review](research-notes/past-year/2025-08-kev-review.md) |
| 2025-07 | [July 2025 KEV Review](research-notes/past-year/2025-07-kev-review.md) |

## Templates and Methodology

| Area | Notes |
| --- | --- |
| Threat Intelligence | [Threat Research Template](templates/threat-research-template.md) |
| Vulnerability Review | [Vulnerability Research Template](templates/vulnerability-research-template.md) |
| Detection Ideas | [Detection Notes Template](templates/detection-notes-template.md) |
| Methodology | [Research Methodology](docs/research-methodology.md) |

## Focus Areas

- Threat intelligence and incident breakdowns
- CVE and vulnerability impact review
- SOC alert triage and investigation thinking
- SIEM detection logic ideas
- Windows Event Log analysis
- Identity and access-related attacks
- Phishing, credential abuse, malware, ransomware, and cloud security incidents
- MITRE ATT&CK mapping and response lessons

## Research Note Format

Each research note should answer:

1. What happened?
2. What systems, users, or data may be affected?
3. What evidence should be reviewed?
4. What detection logic or SIEM search ideas apply?
5. What response or remediation steps reduce risk?
6. What lesson can be reused in future investigations?

## Repository Goals

- Keep research notes concise and evidence-based.
- Connect current threats with practical SOC thinking.
- Build reusable templates for investigations and writeups.
- Improve detection, response, and risk communication skills.

## Disclaimer

These are personal research and study notes. They are not official advisories. Always verify active threats, vulnerabilities, and mitigations with official vendor advisories, CISA, NIST NVD, and trusted security sources.