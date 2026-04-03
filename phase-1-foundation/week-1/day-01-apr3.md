# Day 1 - April 3, 2026

## Platform: TryHackMe + PortSwigger
## Path: Jr Penetration Tester (45%) | Web Fundamentals (95%)

### What I did
- Completed all Burp Suite labs on TryHackMe
- Studied OWASP Top 10 — all 10 vulnerabilities

### OWASP Top 10 - Quick Reference
| # | Vulnerability | One line summary |
|---|---------------|-----------------|
| 1 | Broken Access Control | Users accessing resources they shouldn't |
| 2 | Cryptographic Failures | Sensitive data exposed due to weak/missing encryption |
| 3 | Injection | Untrusted data sent to interpreter (SQLi, XSS) |
| 4 | Insecure Design | Flaws baked into architecture itself |
| 5 | Security Misconfiguration | Default creds, open cloud storage, verbose errors |
| 6 | Vulnerable Components | Using libraries/frameworks with known CVEs |
| 7 | Auth Failures | Broken login, weak passwords, session issues |
| 8 | Software Integrity Failures | Unverified updates, insecure CI/CD |
| 9 | Logging Failures | No audit trail, breaches go undetected |
| 10 | SSRF | Server tricked into making requests to internal resources |

### What I learned
- SSRF can be used to access internal cloud metadata endpoints like 169.254.169.254 — didn't know that
- Burp Repeater lets you modify and resend requests manually — more powerful than I expected
### Questions / things that confused me
- How exactly does DOM-based XSS differ from Reflected XSS in a real attack scenario?
