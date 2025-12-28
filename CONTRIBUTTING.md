# 🤝 Contributing Guidelines

Thank you for your interest in contributing to **Gitkrunixdev**.

This repository maintains **cryptographic CLI tooling** intended for expert‑level usage, audit workflows, and controlled development environments. Contributions are welcome, but **quality, clarity, and security discipline are mandatory**.

---

## Contribution Scope

We accept contributions that:

- Improve code quality, correctness, or performance
- Extend CLI tooling in a **deterministic and auditable** manner
- Improve documentation, reproducibility, or compliance clarity
- Fix verified bugs with clear reproduction steps

We do **not** accept:
- Feature requests without technical justification
- UI abstractions that obscure cryptographic behavior
- Marketing content or promotional material
- Changes that weaken security assumptions

---

## Branch Policy

- All contributions must target the `main` branch
- Experimental work should be proposed before submission
- Large changes require prior discussion

---

## Code Standards

All contributions must:

- Be deterministic and reproducible
- Avoid hidden state, telemetry, or external dependencies
- Use explicit error handling
- Preserve offline‑first operation
- Avoid introducing network calls unless explicitly justified

Cryptographic logic must be:
- Transparent
- Inspectable
- Documented

---

## Documentation Requirements

Any non‑trivial change must include:
- Updated documentation
- Clear explanation of intent
- Notes on security implications (if applicable)

Documentation should favor **clarity over verbosity**.

---

## Security Considerations

- Do **not** submit security vulnerabilities via public issues
- Follow the disclosure process defined in `SECURITY.md`
- Contributions introducing cryptographic changes must include rationale

---

## Licensing

By contributing, you agree that:
- Your contribution is licensed under **GPL‑3.0**
- You have the right to submit the code
- You do not introduce incompatible licenses

---

## Review Process

All contributions are reviewed for:
- Technical correctness
- Security impact
- Architectural consistency
- Documentation quality

Maintainers reserve the right to:
- Request changes
- Reject contributions without detailed explanation
- Close inactive or low‑quality submissions

---

## Forks & Derivatives

Forks are encouraged for experimentation.

Security responsibility for forks lies with their maintainers.

---

## Contact & Continuity

Original project author and cryptographic research continuity:
- https://x.com/shamircrackerlab

Gitkrunixdev operates as a **development and experimentation layer**.

---

## Final Note

This project prioritizes **correctness, transparency, and responsibility** over velocity.

If you are unsure whether a contribution fits the scope, open a discussion **before** submitting code.

