
# 🧪 Wazuh SIEM Home Lab - Rick & Morty Edition

> *"Sometimes science is more art than science, Morty."* – Rick Sanchez

## 👨‍💻 Overview

This project is a home-based **SIEM lab** using **Wazuh**, designed to simulate real-world attacks and improve detection skills for SOC and blue team operations.

Systems Monitored:
- 🖥️ Windows 10
- 💻 Kali Linux
- 🍎 macOS
- 🏢 Active Directory (Domain Controller)

## 🔍 Simulated Attack Scenarios

| Technique           | Description                                |
|---------------------|--------------------------------------------|
| Port Scanning       | Detected using Nmap from Kali to Win10     |
| Brute Force         | SSH login attempts logged and alerted      |
| Privilege Escalation| Windows event ID-based rule triggers       |
| Web Exploitation    | LFI/XSS attempts on Apache server          |

## 🧠 What I Learned

- Creating and tuning custom Wazuh rules
- Investigating logs across diverse OSes
- Using Wazuh dashboards to trace real threats
- How attackers think... and how defenders catch them

## 🖼️ Screenshots

Check out the `/screenshots` folder for dashboard visuals and alert examples.

## 🛠️ Tools Used

- Wazuh Manager + Agent
- Filebeat + Elasticsearch
- VirtualBox / VMware
- Nmap, Hydra, Burp Suite

## 🎯 Goal

Strengthen hands-on skills in:
- Threat Detection
- Incident Response
- Log Analysis
- Realistic Blue Team Operations

---

*Built with sweat, caffeine, and questionable sci-fi inspiration.*
