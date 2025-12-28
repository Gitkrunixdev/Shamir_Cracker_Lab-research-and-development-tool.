# 📜 Changelog

All notable changes to this project are documented in this file.

This changelog follows principles inspired by
[Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and adopts **Semantic Versioning (SemVer)** where applicable.

---

## [Unreleased]

### Planned
- Further hardening of CLI agents
- Additional audit‑oriented documentation
- Expanded test coverage for deterministic execution
- Optional visualization and reporting enhancements

---

## [0.2.0] — Gitkrunixdev Fork Initialization

### Added
- Initialization of the **Gitkrunixdev** fork
- Institutional‑grade documentation set:
  - `README.md`
  - `SECURITY.md`
  - `ARCHITECTURE.md`
  - `CONTRIBUTING.md`
  - `DISCLAIMER.md`
- Explicit security posture and non‑custodial disclaimers
- Audit‑oriented architectural overview

### Changed
- Repositioned repository as a **development and experimentation layer**
- Clarified scope: tooling only, no services or guarantees
- Standardized documentation language for compliance and audits

### Notes
- This release establishes Gitkrunixdev as a **controlled fork**
- No cryptographic logic was modified at this stage
- Functional behavior remains aligned with upstream

---

## [0.1.0] — Upstream Baseline

### Added
- Initial Shamir‑based CLI architecture
- Core agents:
  - `decode-monometric`
  - `threshold-analyze`
  - `seed-reconstruct`
  - `recover-password`
  - `wallet-unlock`
- Modular export formats (JSON, SVG, PDF)

### Notes
- Original implementation authored by **@shamircrackerlab**
- Served as the foundational cryptographic toolkit

---

## Versioning Policy

This project follows **Semantic Versioning**:

- **MAJOR** version increments indicate breaking changes
- **MINOR** version increments indicate backward‑compatible feature additions
- **PATCH** version increments indicate backward‑compatible bug fixes

Pre‑1.0 versions (`0.x.y`) indicate active development and experimentation.
Breaking changes may occur without backward compatibility guarantees.

---

## Change Categories

Future entries will use the following categories where applicable:

- **Added** — new features or modules
- **Changed** — modifications to existing behavior
- **Deprecated** — features scheduled for removal
- **Removed** — removed features or modules
- **Fixed** — bug fixes
- **Security** — security‑relevant changes

---

## Attribution

Original project:
- **krunixbase**
- Author: **@shamircrackerlab**
- https://github.com/krunixbase/krunixbase

Gitkrunixdev maintains full attribution and GPL‑3.0 compliance.

---

## Disclaimer

This changelog documents **code and documentation changes only**.
It does not imply guarantees of stability, security, or recovery success.

