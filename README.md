# Detection Engineering Lab

<p align="center">

![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-blue?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Detection%20Engineering-orange?style=for-the-badge)
![MITRE](https://img.shields.io/badge/MITRE-ATT%26CK-red?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)

</p>

---

## Overview

Detection Engineering Lab is a continuously evolving cybersecurity portfolio focused on building, validating, and improving security detections using realistic attack simulations, enterprise security tools, and structured investigation workflows.

The objective of this repository is to document the complete detection lifecycle—from infrastructure deployment and telemetry collection to detection development, alert investigation, threat hunting, and detection improvement.

Rather than focusing on a single SIEM platform, this project emphasizes practical detection engineering concepts that can be applied across different security technologies.

---

# Objectives

- Build a realistic enterprise security laboratory
- Simulate real-world attack techniques
- Generate and analyze endpoint telemetry
- Develop and validate security detections
- Investigate security alerts
- Perform threat hunting
- Map detections to the MITRE ATT&CK Framework
- Document findings and lessons learned
- Build reusable detection content

---

# Lab Environment

## Infrastructure

- VMware Workstation
- Windows Server 2022
- Windows 10
- Ubuntu Server
- Kali Linux

## Enterprise Services

- Active Directory
- DNS
- Windows Domain Environment

## Security Platforms

- Wazuh SIEM
- Splunk Enterprise
- Microsoft Sentinel *(Planned)*

## Endpoint Monitoring

- Sysmon
- Windows Event Logs
- Windows Defender

---

# Technology Stack

| Category | Technologies |
|----------|--------------|
| SIEM | Wazuh, Splunk, Microsoft Sentinel |
| Operating Systems | Windows Server, Windows 10, Ubuntu, Kali Linux |
| Endpoint Monitoring | Sysmon, Windows Event Logs |
| Identity | Active Directory |
| Networking | TCP/IP, DNS |
| Scripting | PowerShell, Python, Bash |
| Detection Standards | MITRE ATT&CK, Sigma |

---

# Detection Lifecycle

Every attack scenario in this repository follows a structured workflow.

```text
Attack Simulation
        │
        ▼
Telemetry Generation
        │
        ▼
Log Collection
        │
        ▼
Detection Logic
        │
        ▼
Alert Generation
        │
        ▼
Investigation
        │
        ▼
MITRE ATT&CK Mapping
        │
        ▼
Detection Improvement
```

---

# Attack Scenarios

| MITRE ID | Technique | Status |
|-----------|-----------|--------|
| T1110 | Brute Force | ✅ Completed |
| T1059 | PowerShell | 🚧 In Progress |
| T1046 | Network Service Discovery | ⏳ Planned |
| T1087 | Account Discovery | ⏳ Planned |
| T1021 | Remote Services | ⏳ Planned |
| T1078 | Valid Accounts | ⏳ Planned |
| T1053 | Scheduled Tasks | ⏳ Planned |
| T1547 | Boot or Logon Autostart Execution | ⏳ Planned |
| T1486 | Data Encrypted for Impact | ⏳ Planned |

---

# Detection Engineering

The repository includes detection development and validation for:

- Windows Authentication Monitoring
- Active Directory Monitoring
- PowerShell Detection
- Sysmon Process Monitoring
- Brute Force Detection
- Network Reconnaissance Detection
- Persistence Detection
- Privilege Escalation Detection
- Credential Access Detection
- Lateral Movement Detection
- Custom Wazuh Rules
- Sigma Rules

---

# Threat Hunting

Practical threat hunting exercises include:

- Authentication Analysis
- PowerShell Activity
- Process Creation
- Network Connections
- Endpoint Investigation
- IOC Analysis
- Windows Event Correlation
- Sysmon Analysis

---

# Repository Structure

```
detection-engineering-lab
│
├── docs/
│
├── infrastructure/
│
├── attack-scenarios/
│
├── detections/
│
├── threat-hunting/
│
├── scripts/
│
├── screenshots/
│
├── assets/
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# Skills Demonstrated

- Detection Engineering
- Security Monitoring
- SIEM Administration
- Threat Hunting
- Incident Investigation
- Active Directory Security
- Windows Security
- Endpoint Monitoring
- Log Analysis
- MITRE ATT&CK Mapping
- Detection Rule Development
- Security Automation

---

# Roadmap

### Infrastructure

- [x] Windows Domain Environment
- [x] Active Directory
- [x] Wazuh SIEM
- [x] Windows Endpoint
- [x] Sysmon
- [ ] Microsoft Sentinel
- [ ] Splunk Enterprise

### Detection Scenarios

- [x] Brute Force Detection
- [ ] PowerShell Detection
- [ ] Active Directory Enumeration
- [ ] Network Discovery
- [ ] Privilege Escalation
- [ ] Lateral Movement
- [ ] Persistence
- [ ] Ransomware Simulation

### Detection Content

- [ ] Custom Wazuh Rules
- [ ] Sigma Rules
- [ ] Detection Testing
- [ ] Threat Hunting Playbooks
- [ ] Investigation Reports

---

# Documentation

Each attack scenario includes:

- Objective
- Lab Configuration
- Attack Execution
- Generated Telemetry
- Detection Logic
- Alert Analysis
- MITRE ATT&CK Mapping
- Investigation Workflow
- Lessons Learned

---

# Disclaimer

This repository is intended solely for educational and defensive cybersecurity purposes.

All attack simulations are performed within isolated virtual laboratory environments owned and controlled by the repository author.

---

# Author

**Raj Kiran**

Cybersecurity Graduate | SOC Analyst | Detection Engineering

**GitHub**

https://github.com/rkc0809

**LinkedIn**

https://linkedin.com/in/raj-kiran9

---

⭐ If you find this repository useful, consider giving it a star.
