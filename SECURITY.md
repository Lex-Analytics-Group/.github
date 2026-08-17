# Security Policy

Lex Analytics Group takes the security of our software and our users' data seriously.
This policy applies to every repository owned by the
[@Lex-Analytics-Group](https://github.com/Lex-Analytics-Group) organization.

## Reporting a vulnerability

**Please do not report security vulnerabilities through public GitHub issues, discussions,
or pull requests.**

Report privately using either channel:

1. **GitHub private vulnerability reporting** — preferred. On the affected repository, open the
   **Security** tab and choose **Report a vulnerability**.
2. **Email** — [lexanalyticsgroup@gmail.com](mailto:lexanalyticsgroup@gmail.com) with the subject
   line `SECURITY: <short description>`.

To help us triage quickly, please include:

- The type of issue (e.g. SQL injection, broken access control, exposed credential, XSS)
- The affected product, repository, URL or endpoint
- Step-by-step instructions to reproduce it
- Proof-of-concept code or screenshots, if you have them
- Your assessment of the impact and how an attacker might exploit it

## What to expect

| Stage | Target |
| --- | --- |
| Acknowledgement of your report | Within **3 business days** |
| Initial assessment and severity rating | Within **10 business days** |
| Fix or documented mitigation for critical issues | Within **30 days** of confirmation |
| Status updates while work is ongoing | At least every **14 days** |

We will let you know when the issue is resolved, and — with your permission — credit you in the
release notes. We do not currently operate a paid bug bounty programme.

## Scope

**In scope:** source code in repositories under this organization, and the production services
at `caseai.uz`, `malakasertifikati.uz`, `bankrotlik.uz` and `bankyuristi.uz`.

**Out of scope:**

- Denial-of-service, volumetric or brute-force testing against production systems
- Social engineering, phishing, or physical attacks against our staff or offices
- Reports generated solely by automated scanners with no demonstrated impact
- Missing security headers or weak TLS configuration without a working exploit
- Vulnerabilities in third-party services we do not control

## Safe harbour

If you make a good-faith effort to comply with this policy during your research, we will treat
your work as authorised, will not pursue legal action against you, and will work with you to
understand and resolve the issue quickly. Please act in good faith: do not access, modify or
destroy data belonging to other users, do not degrade our services, and give us reasonable time
to fix an issue before disclosing it publicly.

## Supported versions

We support the current production release of each product. Fixes are applied to the latest
version; we do not backport to older releases.
