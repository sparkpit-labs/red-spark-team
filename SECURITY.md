# Security Policy

> 🔒 **Responsible disclosure protects users. Always follow this process.**

---

## 🐕‍🦺 Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| main    | ✅ Actively maintained |

All security work and standards in this repository apply to the current `main` branch.

---

## 🚨 Reporting a Vulnerability

### In a Sparkpit Labs Project (any repo)

**If you find a security vulnerability in any sparkpit-labs repository:**

1. **Do NOT open a public GitHub issue** — public disclosure risks exploitation of users before a fix is ready
2. **Contact the maintainers directly** — via GitHub Security Advisories (preferred) or org-level contact
3. **Include the following in your report:**
   - Project/repo name
   - Description of the vulnerability
   - Affected versions (if known)
   - Steps to reproduce
   - Potential impact assessment
   - (Optional) Suggested fix or mitigation

### GitHub Security Advisories (Recommended)

Use GitHub's private vulnerability reporting:

1. Go to the affected repository
2. Click **Security** tab
3. Click **Advisories** → **Report a vulnerability**
4. Complete the form with as much detail as possible

### Expected Response Timeline

| Severity | First Response | Target Resolution |
|----------|---------------|-------------------|
| Critical (RCE, data breach) | 24 hours | TBD per case |
| High | 48 hours | TBD per case |
| Medium | 1 week | TBD per case |
| Low / Informational | 2 weeks | TBD per case |

---

## 📖 Scope of This Repo

`red-spark-team` is a **security standards and coordination repo**. This policy applies to:

- Security findings documented here
- Tools and automation in this repo
- Standards and checklists published here

For vulnerabilities in **specific product repos**, report directly in those repos via GitHub Security Advisories.

---

## 🔐 Security Standards We Maintain

- All audit findings are reviewed before being marked public
- Proof-of-concept exploit code is kept private and excluded from committed files
-敏感 findings (RCE, auth bypass, data exposure) follow a private-first disclosure process
- Remediation PRs are coordinated with maintainers before merge

---

## ✅ Acknowledgements

We maintain a public SECURITY acknowledgements page. Contributors who report responsibly disclosed vulnerabilities will be credited (unless anonymity is requested).

---

*Last updated: 2026-04-24*
