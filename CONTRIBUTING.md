# Contributing to red-spark-team

Thank you for your interest in contributing to the red-spark-team security initiative! This document outlines how to contribute safely, clearly, and effectively.

---

## 🚨 Security-First Guidelines

### Before You Start

- **No live vulnerabilities in issues.** If your finding is a real, exploitable vulnerability in a sparkpit-labs project, follow the [SECURITY.md](./SECURITY.md) disclosure process — do NOT open a public issue or PR.
- **Scope awareness.** Contributions to this repo are documentation, tooling, and standards. Audit findings for specific projects may belong in those projects' repos.
- **Sign your work.** All commits must be signed (`git commit -S`) where possible. By submitting a PR, you agree to the [DCO](#dco-developer-certificate-of-origin).

---

## 💡 Contribution Types

### 🐛 Bug Reports / Findings
- Use GitHub Issues (for non-sensitive findings only)
- Include: affected component, description, reproduction steps, severity estimate
- Do NOT include live exploit code or sensitive attack paths in public issues

### 📝 Documentation Improvements
- Fixes, clarifications, and expansions are always welcome
- Keep language professional and factual
- Reference existing standards (OWASP, NIST, etc.) where appropriate

### 🔧 Tooling & Automation
- Security scanners, linters, and CI/CD security checks
- Must not introduce new dependencies without approval
- Include usage docs and limitations in the PR description

### ✅ Code Review Contributions
- Follow the review checklist in any associated PR
- Be constructive and specific
- Distinguish between blocking issues and suggestions

---

## 🔄 Pull Request Process

### 1. Fork & Branch

```bash
# Create a feature branch from main
git checkout -bfeat/description
# or
git checkout -bdocs/description
# or
git checkout -btool/description
```

Branch naming: `feat/`, `docs/`, `tool/`, `fix/`, `audit/` + short description

### 2. Make Your Changes

- Keep changes **focused and minimal** — one logical change per PR
- Do not bundle unrelated improvements
- Update relevant docs alongside code/tool changes
- For audit reports: use a standardized format (see active issues for examples)

### 3. Commit

```bash
git commit -S -m "type: brief description

- detail 1
- detail 2
Ref: #issue-number (if applicable)"
```

**Commit types:** `feat`, `docs`, `tool`, `fix`, `audit`, `chore`, `refactor`

### 4. Push & Open PR

```bash
git push origin your-branch-name
```

Open a Pull Request against `main`. Fill out the PR template if one exists.

### 5. Review & Merge

- At least one maintainer review is required
- Address review feedback promptly or flag if you need clarification
- Maintainers will merge once all checks pass and the PR is approved

---

## 📋 PR Checklist (Contributor)

Before submitting, confirm:

- [ ] My change is scoped and focused (no bundled refactors)
- [ ] No live vulnerabilities are exposed in this PR
- [ ] Documentation is updated if behavior changes
- [ ] New tooling includes usage instructions
- [ ] Commits are signed and follow the format above
- [ ] No new dependencies added without discussion

---

## ❓ Questions?

Open a Discussion or reach out through the sparkpit-labs org. For sensitive security matters, see [SECURITY.md](./SECURITY.md).

---

## DCO: Developer Certificate of Origin

By contributing to red-spark-team, you certify that your contribution was created in whole or in part by you and you have the right to submit it under the license provided.

---

*Last updated: 2026-04-24*
