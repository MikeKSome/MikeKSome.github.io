---
title: "Wazuh SIEM Setup & Testing"
permalink: /wazuh/
layout: single
classes: wide
---

# 🛡️ Wazuh SIEM Setup & Testing

This personal project involved deploying a full-featured **Security Information and Event Management (SIEM)** system using **Wazuh**. The goal was to gain practical experience with log collection, analysis, and threat detection across multiple systems.

---

## 🎯 Objective

To implement and evaluate a functioning SIEM using open-source tools, and document the process as a personal cybersecurity learning project.

---

## 🛠️ Tools Used

- **VMware Workstation Pro**
- **Ubuntu Server 22.04**
- **Wazuh SIEM** (Manager + Dashboard)
- **Windows 11 Agent**
- **Kali Linux Agent**

---

## 🔧 Project Tasks

- ✅ Installed Ubuntu Server and Wazuh manager
- ✅ Connected Windows and Kali Linux agents
- ✅ Set up File Integrity Monitoring (FIM)
- ✅ Integrated VirusTotal for hash lookup
- ✅ Simulated file changes and service disruptions
- ✅ Investigated security event alerts on the dashboard

---

## 📄 Documentation

- 📘 [Setup Guide PDF](../../docs/wazuh-setup.pdf)
- 📘 [Testing & Evaluation PDF](../../docs/wazuh-testing.pdf)

---

## 📊 Key Outcomes

- Monitored real-time logs from Windows and Kali agents
- Detected file additions, deletions, and service stops
- Visualized alerts and rule triggers in the Wazuh dashboard
- Understood how SIEM systems can aid in security monitoring and incident response

---

## 📸 Screenshots

> *(Add screenshots if available using `![desc](path)`)*  
> You can store them in `/assets/images/` or `/assets/projects/wazuh/`

---

## 🧠 What I Learned

- How to deploy and manage a SIEM using Wazuh
- Practical use of File Integrity Monitoring
- Understanding of agent-manager communication
- How threat intelligence (e.g., VirusTotal) integrates into SIEM workflows

---

---

## 🚀 Potential Future Projects with Wazuh

Here are some ideas for expanding this project further:

- 🛡️ **CIS Benchmark Hardening**
  - Use Wazuh’s CIS module to audit system security settings and raise the compliance score.
  
- 🔍 **Advanced Log Correlation**
  - Define custom rules to detect suspicious behavior patterns (e.g., failed logins followed by privilege escalation).

- 🌐 **Network Traffic Monitoring**
  - Integrate Wazuh with Suricata or Zeek for real-time network intrusion detection.

- 🗃️ **Centralized Logging for Multiple Devices**
  - Deploy Wazuh agents across multiple VMs or devices to simulate an enterprise setup.

- 🧑‍💼 **Host-Based Intrusion Detection**
  - Focus on host-based rules and responses for detecting malware, ransomware activity, and rootkits.

- 📊 **Automated Reporting**
  - Set up scheduled report generation (e.g., daily security summaries or weekly audit reports).

- 🔄 **SIEM + SOAR Integration**
  - Explore linking Wazuh to automation tools like TheHive, Cortex, or custom scripts for response automation.

- ☁️ **Cloud Monitoring**
  - Try monitoring cloud environments (e.g., AWS or Azure) by forwarding logs into Wazuh.

- ⚠️ **Attack Simulation Lab**
  - Simulate brute force, privilege escalation, or data exfiltration attacks and observe Wazuh's detection and alerts.



## 🔗 Related Projects

- [Projects Index](/projects/)
- [Wazuh Documentation Page](/documentation/)
