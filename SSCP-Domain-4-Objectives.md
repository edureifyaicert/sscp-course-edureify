# [Domain-4](#domain-4-incident-response-and-recovery) **Incident Response and Recovery**

> 🤖 [AI Tutor](https://edureify.com/certification/exam/sscp) · 🎓 [Training](https://edureify.com/certification/cybersecurity/sscp/training) · 📝 [Practice Test](https://edureify.com/certification/cybersecurity/sscp/practice-test) · 🎯 [Mock Exam](https://edureify.com/certification/cybersecurity/sscp/mock-exam) · 📊 [Readiness Test](https://edureify.com/certification/cybersecurity/sscp/readiness-test) · 📄 [Cheat Sheet](https://edureify.com/certification/cybersecurity/sscp/cheat-sheet) · 📖 [Study Guide](https://edureify.com/certification/cybersecurity/sscp/study-guide)

- **14% weighting**, combining incident handling, forensics, and business continuity/disaster recovery into one domain — CISM candidates will recognize most of this content already

## 4.1 Understand and support incident response lifecycle

- Lifecycle stages referencing both **NIST** and **ISO** models: **Preparation** (defining roles, training programs) → **Detection, analysis, and escalation** (including incident communication and public relations considerations) → **Containment** → **Eradication** → **Recovery** (with incident documentation) → **Post-incident activities** (lessons learned, new countermeasures, continuous improvement)
- Directly mirrors the incident lifecycle covered in CISM Domain 4.B and CISSP Domain 7.6, at an SSCP's hands-on execution level

## 4.2 Understand and support forensic investigations

- **Legal and ethical principles**: civil, criminal, and administrative investigation types each carry different evidentiary standards (see CISSP Domain 1.5)
- **Evidence handling**: first-responder actions, triage, chain of custody, and preservation of the scene — mishandling any of these can render otherwise-solid evidence unusable
- **Reporting of analysis and organizational security policy compliance**: forensic findings must be documented in a way that supports both any legal process and internal policy requirements

## 4.3 Understand and support Business Continuity Plan (BCP) and Disaster Recovery Plan (DRP)

- **Emergency response plans and procedures**: information system contingency planning, pandemic response, natural disaster response, and crisis management
- **Interim or alternate processing strategies**: keeping critical functions running during a disruption
- **Restoration planning**: RTO (Restore Time Objective), RPO (Restore Point Objective), and MTD (Maximum Tolerable Downtime) — the same core continuity metrics used across CISM Domain 4.A and CISSP Domain 1.7
- **Backup and redundancy implementation**: the technical execution layer supporting the restoration targets above
- **Testing and drills**: playbooks, tabletops, and disaster recovery exercises, scheduled and executed regularly rather than left untested

## AI integration in this domain (2025–26 outline update)

- Incident response now explicitly includes **AI-assisted triage and automated playbooks** to speed initial response, plus forensic investigations where an AI system itself was either the target or the vector of an incident — including chain-of-custody discipline extended to model logs and AI-related evidence
- Recovery planning must account for **restoring ML models and their training data**, not just traditional systems and databases, when a disruption affects AI-driven infrastructure
