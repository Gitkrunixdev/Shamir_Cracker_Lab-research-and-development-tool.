## 🤝 Contribution Guidelines

Thank you for your interest in contributing to **Gitkrunixdev**.

This repository provides **cryptographic command‑line tooling** intended for expert‑level usage in research, development, and audit‑oriented environments. Contributions are welcome, but must adhere to strict standards of correctness, transparency, and security discipline.

---

## 1. Scope of Acceptable Contributions

Contributions are accepted if they:

- Improve correctness, reliability, or performance
- Extend CLI tooling in a deterministic and auditable manner
- Improve documentation, reproducibility, or compliance clarity
- Fix verified bugs with clear reproduction steps
- Enhance testability or auditability

Contributions are **not accepted** if they:

- Introduce network communication or telemetry
- Obscure cryptographic behavior through abstraction
- Add custodial, managed, or service‑like functionality
- Include marketing, promotional, or non‑technical content
- Weaken security assumptions or trust boundaries

---

## 2. Coding Standards

All contributions must:

- Be deterministic and reproducible
- Avoid hidden state or implicit configuration
- Use explicit error handling
- Preserve offline‑first execution
- Avoid dynamic code execution
- Avoid unnecessary dependencies

Cryptographic logic must be:
- Transparent
- Inspectable
- Clearly documented

---

## 3. Security Expectations

Contributors must:

- Avoid introducing new attack surfaces
- Respect existing security boundaries
- Document any security‑relevant changes
- Follow the disclosure process defined in `SECURITY.md`

Security vulnerabilities **must not** be submitted via public issues or pull requests.

---

## 4. Documentation Requirements

Any non‑trivial contribution must include:

- Updated documentation
- Clear explanation of intent
- Notes on security implications (if applicable)

Documentation should prioritize **clarity, precision, and auditability**.

---

## 5. Review Process

All contributions are subject to review for:

- Technical correctness
- Security impact
- Architectural consistency
- Documentation quality

Maintainers reserve the right to:

- Request changes
- Reject contributions without detailed explanation
- Close inactive or low‑quality submissions

Large or architectural changes should be discussed prior to submission.

---

## 6. Branch Policy

- Contributions must target the `main` branch
- Experimental work should be proposed before submission
- Forks are encouraged for experimentation

Security responsibility for forks lies with their maintainers.

---

## 7. Licensing

By contributing, you agree that:

- Your contribution is licensed under **GPL‑3.0**
- You have the legal right to submit the contribution
- You do not introduce incompatible licenses

All contributions become part of the GPL‑3.0 licensed codebase.

---

## 8. Attribution and Continuity

Original project author and cryptographic research continuity:
- **@shamircrackerlab**
- https://x.com/shamircrackerlab

Gitkrunixdev operates as a **development and experimentation layer**.

---

## 9. Final Note

This project prioritizes:

- Correctness over convenience
- Transparency over abstraction
- Responsibility over velocity

If you are unsure whether a contribution fits the scope, initiate a discussion **before** submitting code.

