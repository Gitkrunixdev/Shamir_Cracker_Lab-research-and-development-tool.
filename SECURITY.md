# 🔐 Security Policy

## Scope

This repository provides **cryptographic CLI tooling** for research, development, and audit-oriented workflows involving Shamir-based secret recovery and analysis.

The project **does not provide custodial services**, hosted infrastructure, or managed recovery operations.

---

## Supported Versions

This repository is under active development.

| Version / Branch | Security Support |
|------------------|------------------|
| `main`           | ✅ Supported |
| Development forks | ⚠️ Best-effort |
| Experimental modules | ❌ Not supported |

Only the `main` branch is considered for coordinated security disclosures.

---

## Security Model

- All tools operate **locally** and **offline by design**
- No secrets, keys, or credentials are transmitted externally
- No telemetry, analytics, or remote logging is implemented
- Users are responsible for validating outputs independently

This project assumes **expert-level usage** and does not attempt to abstract cryptographic risk.

---

## Reporting a Vulnerability

If you discover a security vulnerability, please report it **privately**.

### Preferred Contact
- **X (Twitter):** https://x.com/shamircrackerlab

Please include:
- A clear description of the issue
- Reproduction steps (if applicable)
- Affected modules or CLI agents
- Potential impact assessment

Do **not** open public GitHub issues for security vulnerabilities.

---

## Disclosure Policy

- Valid reports will be acknowledged within a reasonable timeframe
- Fixes will be coordinated before public disclosure
- Credit will be given to reporters unless anonymity is requested

There is **no bug bounty program** associated with this repository.

---

## Limitations & Responsibility

This software is provided **“as is”**, without warranty of any kind.

- No guarantee of successful recovery
- No liability for data loss or misuse
- No legal or compliance assurances

Users are responsible for ensuring lawful and ethical use.

---

## Forks & Derivatives

Security responsibility for forks and derivative works lies with their respective maintainers.

Only disclosures affecting the original architecture or shared codebase will be considered.

---

## Cryptographic Disclaimer

This project implements cryptographic concepts for **analysis and recovery tooling**.

It does **not** replace:
- Professional key management systems
- Hardware security modules (HSMs)
- Custodial or enterprise-grade recovery services

---

## Contact Continuity

Original project author and cryptographic research continuity:
- https://x.com/shamircrackerlab

Gitkrunixdev operates as a **development and experimentation layer**.

