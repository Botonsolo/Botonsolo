# Hi, I'm Jorge Cortés 👋

**Cybersecurity Technician · Blue Team & SOC**

I detect, contain, and respond to real-world security incidents — not just in labs, but in production infrastructure. Currently building my career around threat detection, incident response, and defensive security engineering.

📍 Valencia, Spain &nbsp;|&nbsp; 🎓 ASIR + Cybersecurity Specialization (CIPFP Cheste) &nbsp;|&nbsp; 🛡️ Blue Team focused

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jorgecorteshernandez)

---

## 🧭 About Me

I'm a cybersecurity technician with hands-on, production-environment experience detecting and neutralizing active threats — not just certifications and CTF flags (though I have plenty of those too). During my time at the **Ayuntamiento de Buñol**, I identified and contained **3 active security incidents** (SEO poisoning, malware) across a live multi-server environment, and built the organization's first layer of detection and response from the ground up: SIEM, IDS/IPS, network segmentation, and systematic hardening.

I approach security through structured frameworks — **MITRE ATT&CK**, the **Cyber Kill Chain**, **OWASP** — because ad-hoc incident response doesn't scale, and documentation matters as much as detection. I reinforce this daily through offensive-side practice on CTF platforms, because understanding attacker methodology is what makes defensive work effective.

I'm looking to bring this into a **SOC / Blue Team** role where I can contribute from day one.

---

## 🛠️ Technical Skills

**SIEM & Detection**
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat&logo=splunk&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-2E4053?style=flat)
![Snort](https://img.shields.io/badge/Snort_IDS%2FIPS-FF6600?style=flat)
![Suricata](https://img.shields.io/badge/Suricata-EF3B24?style=flat)
![Sysmon](https://img.shields.io/badge/Sysmon-0078D4?style=flat)

**Frameworks & Methodology**
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-D63333?style=flat)
![OWASP](https://img.shields.io/badge/OWASP-000000?style=flat&logo=owasp&logoColor=white)
Cyber Kill Chain · MITRE ATLAS · RFC 3227 · ISO 27037/27042

**Traffic & Forensic Analysis**
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white)
tcpdump · Autopsy · FTK Imager · Volatility

**Operating Systems**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white)
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=flat&logo=kalilinux&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat&logo=windows&logoColor=white)

**Networking**
TCP/IP · DNS · DHCP · VLANs · Firewalls · VPNs · Active Directory / LDAP

**Monitoring**
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)

**Scripting & Automation**
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)

**Virtualization**
![VMware](https://img.shields.io/badge/VMware-607078?style=flat&logo=vmware&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=flat&logo=virtualbox&logoColor=white)

---

## 💼 Experience Highlights

**Technician (ASIR) — Ayuntamiento de Buñol** &nbsp;·&nbsp; *2025 (4 months)*

- Detected and contained **3 active security incidents** (SEO poisoning, malware) through continuous network monitoring — from initial alert to full resolution with zero service impact.
- Deployed **SIEM, IDS/IPS, and antivirus** across the organization's entire server infrastructure, establishing its first detection and response capability.
- Audited and hardened up to **4 servers** through periodic vulnerability analysis, reducing exposed attack surface.
- Administered a mixed **Linux/Windows Server environment of up to 10 servers**, ensuring continuous availability for ~50 users.
- Segmented and protected the corporate network via **VLANs, firewalls, and VPNs**, minimizing lateral movement risk in the event of compromise.
- Managed access control for ~27 users via **Active Directory / LDAP**, applying least-privilege principles.
- Designed and implemented the organization's **backup and disaster recovery plan**.
- Automated recurring administrative tasks with **Bash, Python, and PHP** scripts, freeing up team time for higher-value work.

---

## 🚨 SOC Alerts

Sanitized alerts and triage notes from my detection work. All personal data, hostnames, IPs and internal domains are removed or replaced.

| Date | Alert | Source | Verdict | Write-up |
|---|---|---|---|---|


📂 Raw alert samples and rule tuning notes are in [`soc-alerts`](https://github.com/Botonsolo/soc-alerts) *(add link when published)*.

> **Sanitization rule:** remove IPs, usernames, hostnames, domains and any data that belongs to a real organization before publishing.

---

## 📚 Forensic Playbooks & Tips

Reusable procedures and notes from my investigations.

| Type | Document | Description |
|---|---|---|
| Playbook | *Phishing triage* | Steps from alert to header analysis, IOC extraction and containment |
| Tips | *Windows registry files* | Guide for Registry files in Windows  |
| Forensics | *Chain of custody and evidence handling* | RFC 3227 and ISO 27037 applied to lab work |

📄 Full documents are in [`security-writeups`](https://github.com/Botonsolo/security-writeups) under `/playbooks` and `/tips`.

---

## 🚩 CTF Practice

Hands-on offensive practice to sharpen the defensive mindset — full end-to-end compromise and analysis: enumeration, exploitation, privilege escalation, and forensic log review to reconstruct the attack vector.

| Platform | Machines |
|---|---|
| **HackMyVM** | Soc1, gift, Hunter |
| **VulnHub** | LazySysAdmin, Thales |

---

## 🕵️‍♂️ Sherlocks (HTB)

DFIR-focused challenges: log analysis, incident triage, and threat hunting.

| Category | Sherlock | Difficulty |
|---|---|---|
| DFIR | WhaleSecret | — |
| DFIR | Kraken (Mid Diff) | Medium |
| DFIR | Registry Hive (Mid Diff) | Medium |

📄 Write-ups for CTFs, Sherlocks, and Forensic Analysis reports available in [`security-writeups`](https://github.com/Botonsolo/security-writeups)

---

## 🔐 Featured Projects

### [SecPass](https://github.com/Botonsolo/secPass) — Password Manager

A security-first password manager built to address a real problem: password disorder, credential reuse, and predictable/personally-guessable passwords. Designed with a documented threat model, defense-in-depth principles, and a roadmap toward a hardened client-server architecture.

### [BlueWatch](https://github.com/Botonsolo/BlueWatch) — Phishing Detection Suite

BlueWatch is a personal SOC lab that lets me practise the full workflow of a SOC analyst in an environment I control. Wazuh collects and centralises security events, Sysmon on a Windows endpoint provides detailed process, network and file telemetry, and Suricata detects suspicious network traffic and forwards its alerts to Wazuh. This setup makes it possible to build custom detection rules, test them with controlled scenarios, and then investigate the resulting alerts, deciding whether each one is a true or false positive and documenting the reasoning.

The next stages focus on turning raw alerts into evidence-based findings. That means extracting indicators of compromise, mapping observed behaviour to MITRE ATT&CK techniques, and writing up each case in a structured report. Malware analysis in an isolated sandbox and threat intelligence correlation are planned but not yet implemented, so I describe them as future work rather than current capability.
### 🏛️ [MuniSec](https://github.com/joliher/munisec) — Secure Municipal Infrastructure

A full-scope cybersecurity project simulating the complete IT infrastructure of a municipal government (Ayuntamiento de Guarromán), built with a team of 8 security specialists over two months. The lab deployed two VPN-connected sites (main office + secondary building) with segmented VLANs, Active Directory, a DMZ, and a working SOC — then subjected the environment to real penetration testing (both internal and from a rival red team) and an actual disaster-recovery scenario after an electrical storm took down the primary VPN infrastructure.

Scope covered: network architecture & VLAN segmentation · SOC/SIEM (Wazuh, Suricata) · deep hardening (2FA, iptables) · incident response & disaster recovery · digital forensics (memory analysis, automation scripts) · OSINT reconnaissance methodology · full red team engagement (initial access → root) · ENS/RGPD regulatory compliance mapping.

*Team project hosted in a teammate's repository as the central hub.*

---

## 📜 Certifications & Training

- **Security Analyst Level 1 (SAL1)** — TryHackMe
- **Certified Computer Forensic Analyst (CCFA)** — eSecurity Institute
- **CCNA: Introduction to Networks** — Cisco Networking Academy
- **CCNA: Switching, Routing and Wireless Essentials** — Cisco Networking Academy
- **Introduction to Cybersecurity** — Cisco Networking Academy
- **Network Technician Career Path** — Cisco Networking Academy
- **Esquema Nacional de Seguridad (RD 311/2022)** — 4 courses, 115h
- **Metodología de adecuación al μCeENS** — 75h
- **Forti NSE1** — FortiCloud

---

## 🎓 Education

- **Specialization Course in Cybersecurity** — CIPFP Cheste *(2025–2026)*
  Offensive and defensive security, digital forensics, network/system hardening, ethical hacking.
- **Higher Technician Degree in Network Systems Administration (ASIR)** — CIPFP Cheste *(2023–2025)*

---

## 🌐 Languages

Spanish (Native) · Valencian (C1) · English (B2)

---

## 📫 Let's Connect

I'm actively looking for opportunities in SOC / Blue Team roles. Feel free to reach out:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jorgecorteshernandez)
