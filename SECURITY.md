# 🔐 Security Policy

## 1. Scope

This security policy applies to the **Gitkrunixdev** repository and the cryptographic CLI tooling contained within it.

The project provides tools intended for:
- cryptographic analysis,
- Shamir‑based secret reconstruction,
- research, testing, and audit‑oriented workflows.

This policy **does not apply** to:
- forks or derivative repositories,
- third‑party integrations,
- user deployment environments,
- production systems operated by external parties.

---

## 2. Supported Branches

| Branch | Security Support |
|------|------------------|
| `main` | ✅ Supported |
| Development branches | ⚠️ Best‑effort |
| Experimental modules | ❌ Not supported |

Only the `main` branch is covered by coordinated security disclosure and remediation.

---

## 3. Security Model

Gitkrunixdev is designed around the following security assumptions:

- **Offline‑first execution**
- **No network communication**
- **No telemetry or analytics**
- **No persistent secret storage**
- **Deterministic execution**
- **Explicit trust boundaries**
- **No background services or daemons**

The repository provides **tools, not services**.  
Operational security remains the responsibility of the user.

---

## 4. Reporting Security Vulnerabilities

Security vulnerabilities must be reported **privately**.

### Preferred Contact
- **X (Twitter):** https://x.com/shamircrackerlab

Reports should include:
- a clear description of the vulnerability,
- reproduction steps (if applicable),
- affected modules or CLI agents,
- an assessment of potential impact.

❗ **Do not report vulnerabilities via public GitHub Issues or Pull Requests.**

---

## 5. Disclosure Policy

- Valid reports will be reviewed within a reasonable timeframe
- Fixes will be coordinated prior to public disclosure
- Reporters may be credited unless anonymity is requested
- No bug bounty program is offered

Uncoordinated public disclosure may result in the report being rejected.

---

## 6. Limitations of Responsibility

This project:
- does not guarantee successful recovery outcomes,
- does not provide regulatory or compliance assurances,
- does not assume liability for data loss, asset loss, or misuse,
- does not replace HSMs, KMSs, or enterprise custody solutions.

The software is provided **“as is”**, without warranty.

---

## 7. User Responsibilities

Users are solely responsible for:
- lawful and ethical use of the tooling,
- authorization to perform recovery operations,
- independent verification of outputs,
- securing their execution environment.

---

## 8. Forks and Derivative Works

Security responsibility for forks and derivative works lies entirely with their maintainers.

Gitkrunixdev assumes no responsibility for:
- modified codebases,
- downstream distributions,
- third‑party integrations.

---

## 9. Attribution and Continuity

Original cryptographic architecture and research:
- **@shamircrackerlab**
- https://x.com/shamircrackerlab

Gitkrunixdev operates as a **development and experimentation layer**.

---

## 10. Acceptance

By using, copying, or modifying this software, you acknowledge that you have read, understood, and accepted this security policy.

