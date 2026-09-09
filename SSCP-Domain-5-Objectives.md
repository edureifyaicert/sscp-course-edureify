# [Domain-5](#domain-5-cryptography) **Cryptography**

> 🤖 [AI Tutor](https://edureify.com/certification/exam/sscp) · 🎓 [Training](https://edureify.com/certification/cybersecurity/sscp/training) · 📝 [Practice Test](https://edureify.com/certification/cybersecurity/sscp/practice-test) · 🎯 [Mock Exam](https://edureify.com/certification/cybersecurity/sscp/mock-exam) · 📊 [Readiness Test](https://edureify.com/certification/cybersecurity/sscp/readiness-test) · 📄 [Cheat Sheet](https://edureify.com/certification/cybersecurity/sscp/cheat-sheet) · 📖 [Study Guide](https://edureify.com/certification/cybersecurity/sscp/study-guide)

- **13% weighting.** Substantial overlap with CISSP Domain 3.6/3.7, at an implementer's rather than architect's depth

## 5.1 Understand reasons and requirements for cryptography

- Core drivers: **confidentiality**, **integrity and authenticity**, and protecting sensitive data categories specifically — PII, intellectual property, and PHI (Protected Health Information)
- **Regulatory and industry drivers**: PCI-DSS and ISO standards frequently mandate specific cryptographic protections
- **Cryptographic entropy**: an explicit nod to quantum cryptography and quantum key distribution as an emerging requirement driver (see CISSP Domain 3.6 for fuller post-quantum context)

## 5.2 Apply cryptography concepts

- **Hashing and salting**: integrity verification and defeating precomputed-hash (rainbow table) attacks on stored passwords
- **Symmetric/asymmetric encryption and ECC (Elliptic Curve Cryptography)**: the standard algorithm categories and their trade-offs (speed vs. key-distribution convenience)
- **Non-repudiation**: digital signatures/certificates, HMAC (Hash-based Message Authentication Code), and audit trails
- **Strength of encryption algorithms and keys**: knowing current-strength standards (e.g., AES, RSA at appropriate key lengths) versus deprecated/weak choices
- **Cryptographic attacks and cryptanalysis**: recognizing common attack categories (see CISSP Domain 3.7 for detail)

## 5.3 Understand and implement secure protocols

- **Services and protocols mapped to use cases**: credit card processing, file transfer, web client connections, VPNs, and PII transmission each have an appropriate secure protocol choice
- **Limitations and vulnerabilities**: every protocol has known weaknesses or deprecated predecessor versions (e.g., SSL vs. TLS) — an SSCP should know which are currently acceptable versus which to actively phase out

## 5.4 Understand Public Key Infrastructure (PKI)

- **Key management fundamentals**: storage, rotation, composition, generation, destruction, exchange, revocation, and escrow — the full operational lifecycle of a cryptographic key, not just its initial creation
- **Web of Trust (WoT)**: a decentralized trust model (e.g., PGP/GPG) contrasted with PKI's centralized certificate-authority model; blockchain is referenced as a modern extension of decentralized trust concepts

## AI integration in this domain (2025–26 outline update)

- Cryptography's role expands to protecting **data used to train and run AI models** — securing "data in use" during training and inference specifically, not just data at rest or in transit
- The outline also flags applying **cryptographic signatures to AI model outputs**, so the provenance and integrity of an automated decision can be verified — extending non-repudiation concepts to AI-generated results
