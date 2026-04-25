# Incident Response Portfolio

A collection of hands-on incident response labs documenting real attack simulations, SIEM detections, and analysis writeups built in a home lab environment.

---

## About

I'm a cybersecurity student graduating July 2026, pursuing a career in incident response. This portfolio demonstrates practical blue team skills through simulated attacks and documented detection workflows using industry-standard tools.

**Certifications:** CompTIA A+, Network+, Security+, Pentest+, Cloud Essentials, ITF+ | ISC2 CC  
**In Progress:** PJPT | OSCP  
**Target Role:** Incident Response Analyst

---

## Lab Environment

| Component | Details |
|-----------|---------|
| SIEM | Splunk Enterprise 10.2.2 (macOS M4) |
| Victim Machine | Ubuntu 24.04 ARM64 |
| Attacker Machine | Kali Linux |
| Log Forwarding | rsyslog → UDP 514 → Splunk |
| Virtualization | Parallels Desktop (Apple Silicon) |

---

## Writeups

| # | Title | Attack Type | Tools Used |
|---|-------|-------------|------------|
| 01 | [SSH Brute Force Detection](./01-ssh-bruteforce-detection/ssh-bruteforce-detection.md) | Credential Attack | Hydra, Splunk, rsyslog |

*More writeups in progress...*

---

## Skills Demonstrated

- SIEM deployment and configuration
- Real-time log ingestion and analysis
- Attack simulation and detection
- SPL (Splunk Search Processing Language)
- Incident documentation and response procedures
- Linux system administration

---

## Connect

- GitHub: [offensivesecguru](https://github.com/offensivesecguru)
- TryHackMe | HackTheBox: offensivesecguru
