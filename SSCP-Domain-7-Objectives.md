# [Domain-7](#domain-7-systems-and-application-security) **Systems and Application Security**

> 🤖 [AI Tutor](https://edureify.com/certification/exam/sscp) · 🎓 [Training](https://edureify.com/certification/cybersecurity/sscp/training) · 📝 [Practice Test](https://edureify.com/certification/cybersecurity/sscp/practice-test) · 🎯 [Mock Exam](https://edureify.com/certification/cybersecurity/sscp/mock-exam) · 📊 [Readiness Test](https://edureify.com/certification/cybersecurity/sscp/readiness-test) · 📄 [Cheat Sheet](https://edureify.com/certification/cybersecurity/sscp/cheat-sheet) · 📖 [Study Guide](https://edureify.com/certification/cybersecurity/sscp/study-guide)

- **11% weighting** — the smallest domain, covering malware/threat recognition, endpoint, mobile, and cloud/virtualization security

## 7.1 Identify and analyze malicious code and activity

- **Malware categories**: rootkits, spyware, scareware, ransomware, trojans, viruses, worms, trapdoors/backdoors, fileless malware, and app/code/OS/mobile-specific vulnerabilities
- **Malware countermeasures**: scanners, anti-malware, containment/remediation processes, and software security practices generally
- **Malicious activity types**: insider threat, data theft, DDoS, botnets, zero-day exploits, web-based attacks, and Advanced Persistent Threats (APTs)
- **Countermeasures for malicious activity**: user awareness/training, system hardening, patching, isolation, and DLP
- **Social engineering methods**: spam email, phishing/smishing/vishing, impersonation, scarcity tactics, and whaling (executive-targeted phishing)
- **Behavior analytics**: machine learning, AI, and data analytics increasingly used to detect anomalous activity that signature-based tools miss

## 7.2 Implement and operate endpoint device security

- **HIPS/HIDS**: host-based intrusion prevention/detection
- **Host-based firewalls and application allowlisting**: restricting what can run or communicate on an individual endpoint
- **Endpoint encryption**: full-disk encryption as the baseline protection for data at rest on a device
- **TPM (Trusted Platform Module)**: hardware security module management underpinning secure boot and key protection
- **Secure browsing**: digital certificate validation as a core user-facing trust mechanism
- **EDR (Endpoint Detection and Response)**: the modern, behavior-aware evolution beyond traditional signature-based endpoint tools

## 7.3 Administer and manage mobile devices

- **Provisioning models**: COPE (Corporate-Owned, Personally Enabled), BYOD (Bring Your Own Device), managed via MDM (Mobile Device Management)
- **Containerization**: separating corporate and personal data/apps on the same device
- **Encryption and mobile application management**: device-level and app-level controls working together

## 7.4 Understand and configure cloud security

- **Deployment models**: public, private, hybrid, community
- **Service models**: IaaS, PaaS, SaaS
- **Virtualization**: hypervisors and Virtual Private Clouds (VPCs)
- **Legal and regulatory concerns**: privacy, surveillance, data ownership, jurisdiction, eDiscovery, and shadow IT — cloud adoption raises all of these in ways traditional on-prem environments often don't
- **Data storage, processing, and transmission**: archiving, backup, recovery, and resilience considerations specific to cloud-hosted data
- **Third-party/outsourcing requirements**: SLAs, and data portability/privacy/destruction/auditing terms
- **Shared responsibility model**: the same foundational concept covered in depth across CCSP's domains, tested here at an administrator's working-knowledge level

## 7.5 Operate and maintain secure virtual environments

- **Hypervisor types**: Type 1 (bare-metal, running directly on hardware) vs. Type 2 (software, running atop a host OS) — Type 1 is generally considered more secure/performant for production environments
- **Virtual appliances and containers**: pre-packaged virtual systems and lightweight, kernel-sharing application isolation respectively
- **Continuity and resilience, and storage management**: applying the same availability principles from Domain 4.3 specifically to virtualized infrastructure
- **Threats, attacks, and countermeasures**: brute-force attacks, VM escape (a guest VM breaking isolation to affect the host or other VMs), and threat hunting as a proactive detection practice

## AI integration in this domain (2025–26 outline update)

- Application security now explicitly covers **managing the software supply chain for ML libraries** and testing for AI-specific logic flaws, including mitigating "model hijacking" and inference attacks at the application layer
- Mobile and cloud security responsibilities extend to **administering containerized AI environments** and securing the APIs connecting AI services to the rest of the enterprise — since a large share of AI functionality is now delivered through exactly these platforms
