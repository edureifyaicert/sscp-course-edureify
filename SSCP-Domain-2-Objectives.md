# [Domain-2](#domain-2-access-controls) **Access Controls**

> 🤖 [AI Tutor](https://edureify.com/certification/exam/sscp) · 🎓 [Training](https://edureify.com/certification/cybersecurity/sscp/training) · 📝 [Practice Test](https://edureify.com/certification/cybersecurity/sscp/practice-test) · 🎯 [Mock Exam](https://edureify.com/certification/cybersecurity/sscp/mock-exam) · 📊 [Readiness Test](https://edureify.com/certification/cybersecurity/sscp/readiness-test) · 📄 [Cheat Sheet](https://edureify.com/certification/cybersecurity/sscp/cheat-sheet) · 📖 [Study Guide](https://edureify.com/certification/cybersecurity/sscp/study-guide)

- **15% weighting.** The operational, day-to-day counterpart to CISSP Domain 5 — same core IAM concepts, tested here at implementation/administration depth

## 2.1 Implement and maintain authentication methods

- **Single/Multi-factor authentication (MFA)**: combining factor categories (know/have/are) for stronger authentication
- **Single Sign-On (SSO)**: e.g., Active Directory Federation Services (ADFS), OpenID Connect — reduces credential sprawl by centralizing authentication
- **Device authentication**: certificate-based, MAC address, or Trusted Platform Module (TPM)-anchored — extending authentication beyond just human users
- **Federated access**: OAuth2 and SAML as the standard protocols enabling trust across organizational boundaries (see CISSP Domain 5.3)

## 2.2 Understand and support internetwork trust architectures

- **Trust relationships**: one-way, two-way, transitive, and zero-trust — know how trust direction and transitivity affect what access actually propagates between domains
- **Internet, intranet, extranet, and DMZ**: standard network trust zones, each with a different expected trust level and corresponding control set
- **Third-party connections**: APIs, app extensions, and middleware all extend trust boundaries outward and need the same governance as any other external connection

## 2.3 Support and/or implement the identity management lifecycle

- **Authorization, proofing, provisioning/de-provisioning**: the operational steps of establishing and later removing an identity's access
- **Monitoring, reporting, and maintenance**: keeping access current as roles change or new security standards are adopted
- **Entitlement**: inherited rights and resources an identity accumulates — a common source of privilege creep if not actively reviewed
- **IAM systems**: the platforms (on-prem or cloud) an SSCP actually configures and administers to execute the lifecycle above

## 2.4 Understand and administer access controls

- **Mandatory Access Control (MAC)**: centrally enforced, classification/clearance-based (see CISSP Domain 3.2's Bell-LaPadula/Biba models)
- **Discretionary Access Control (DAC)**: resource owner decides access
- **Role-based**: subject- or object-based, including **Privileged Access Management (PAM)** for high-risk accounts specifically
- **Rule-based**: access driven by predefined rules (e.g., firewall ACLs)
- **Attribute-based (ABAC)**: access decisions evaluate multiple attributes dynamically — the most flexible model, well suited to zero-trust environments

## AI integration in this domain (2025–26 outline update)

- Managing the identity lifecycle now explicitly extends to **non-human "intelligent" entities** — AI agents and automated service accounts — applying least privilege to prevent them from reaching data or functions outside their specific operational scope
- The outline also highlights AI's *defensive* use here: **adaptive authentication and behavioral biometrics** powered by AI can detect anomalous access patterns in real time, making access control architecture more dynamic and resilient than static, rule-only models
