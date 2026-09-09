# [Domain-6](#domain-6-network-and-communications-security) **Network and Communications Security**

> 🤖 [AI Tutor](https://edureify.com/certification/exam/sscp) · 🎓 [Training](https://edureify.com/certification/cybersecurity/sscp/training) · 📝 [Practice Test](https://edureify.com/certification/cybersecurity/sscp/practice-test) · 🎯 [Mock Exam](https://edureify.com/certification/cybersecurity/sscp/mock-exam) · 📊 [Readiness Test](https://edureify.com/certification/cybersecurity/sscp/readiness-test) · 📄 [Cheat Sheet](https://edureify.com/certification/cybersecurity/sscp/cheat-sheet) · 📖 [Study Guide](https://edureify.com/certification/cybersecurity/sscp/study-guide)

- **16% weighting**, tied for the heaviest domain — the most hands-on, device-configuration-heavy domain on the exam

## 6.1 Understand and apply fundamental concepts of networking

- **OSI and TCP/IP models**, network topologies, and network relationships (peer-to-peer vs. client-server)
- **Transmission media types**: wired vs. wireless
- **Software-Defined Networking (SDN)**: including SD-WAN, network virtualization, and automation (see CISSP Domain 4.2)
- **Commonly used ports and protocols**: foundational recall knowledge that underpins nearly every other topic in this domain

## 6.2 Understand network attacks

- **Attack types**: DDoS, man-in-the-middle (MITM), and DNS cache poisoning as named examples
- **Countermeasures**: CDNs (absorbing/distributing volumetric attack traffic), firewalls, network access controls, and IDPS — matching countermeasure to attack type is the core testable skill here

## 6.3 Manage network access controls

- **Standards and protocols**: IEEE 802.1X (port-based network access control), RADIUS, and TACACS+ for centralized authentication of network access
- **Remote access**: thin client, VPN, and virtual desktop infrastructure (VDI) configuration and operation

## 6.4 Manage network security

- **Logical and physical device placement**: inline, passive, or virtual — determines whether a device can actively block traffic or only observe it
- **Segmentation**: physical/logical separation, data/control plane separation, VLANs, ACLs, firewall zones, and micro-segmentation — a full spectrum from coarse to very fine-grained isolation
- **Secure device management**: hardening and controlling access to the network devices themselves, since a compromised management plane undermines every control built on top of it

## 6.5 Operate and configure network-based security appliances and services

- **Firewalls and proxies**: filtering methods, WAF (Web Application Firewall), and CASB (Cloud Access Security Broker)
- **Network IDS/IPS, routers, and switches**: core traffic inspection and forwarding infrastructure
- **Traffic-shaping devices**: WAN optimization and load balancing
- **NAC, DLP, and UTM (Unified Threat Management)**: access enforcement, data-loss prevention, and consolidated multi-function security appliances respectively

## 6.6 Secure wireless communications

- **Technologies**: cellular, Wi-Fi, Bluetooth, and NFC (Near-Field Communication) each carry distinct range and security considerations
- **Authentication/encryption protocols**: WPA, WPA2, WPA3, and EAP — know the strength progression and current recommended standard (WPA3)

## 6.7 Secure and monitor Internet of Things (IoT)

- Configuration hardening, network isolation (segmenting IoT devices away from critical infrastructure), firmware update management, and End of Life (EOL) planning for devices that stop receiving security updates

## AI integration in this domain (2025–26 outline update)

- Network architecture must now account for **AI workload-specific demands** — including micro-segmentation to isolate AI training clusters, preventing a compromised AI interface from being used as a lateral-movement foothold into the broader network
- **AI-powered firewalls and IPS** are increasingly used to detect sophisticated "low and slow" attacks that evade traditional signature-based detection, extending the network defense toolkit described in 6.5
