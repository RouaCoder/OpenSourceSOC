# 🛡️ Open-Source SOC Monitoring Environment 

This repository presents the project I completed during my cybersecurity internship at Attijari Bank, where I deployed a host-based and network-based intrusion detection environment using open-source tools.  
The objective was to strengthen my defensive security skills and implement a functional monitoring pipeline capable of detecting common attack techniques.

# 🛡️ Open-Source SOC Monitoring Environment

<p align="center">

  <!-- Project Identity -->
  <img src="https://img.shields.io/badge/🛡️%20SOC%20Monitoring-Internship%20Project-8A2BE2?style=for-the-badge" alt="SOC Project">

  <!-- Virtual Machines -->
  <img src="https://img.shields.io/badge/Windows%2010-Victim%20Machine-0078D6?style=for-the-badge&logo=windows" alt="Windows 10 VM">
  <img src="https://img.shields.io/badge/Kali%20Linux-Attacker%20Machine-557C94?style=for-the-badge&logo=kalilinux" alt="Kali Linux VM">

  <!-- Tools Used -->
  <img src="https://img.shields.io/badge/Wazuh-SIEM%20HIDS-1E90FF?style=for-the-badge&logo=wazuh" alt="Wazuh">
  <img src="https://img.shields.io/badge/Suricata-NIDS-FF6600?style=for-the-badge&logo=suricata" alt="Suricata">

  <!-- Category & Status -->
  <img src="https://img.shields.io/badge/Category-Cybersecurity%20Lab-green?style=for-the-badge" alt="Category">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Status">

</p>



### 🚀 Project Scope
---

## 🏗️ Lab Setup & Architecture

- **Wazuh Manager** —> SIEM & HIDS  
- **Wazuh Agents** —> Host log collection & monitoring  
- **Suricata** —> Network IDS  
- **Kali Linux VM** —>  Attack simulation  
- **Virtualization Platform** —> VMware / VirtualBox

 ## 🗺️ SOC Lab Topology

![SOC Lab Topology](images/soc-topo.png)


## ✔️ Completed Work

This SOC foundation integrates two core components:

#### 🔸 Wazuh — SIEM / Host-Based Intrusion Detection (HIDS)
- Deployment of Wazuh Manager
- Installation and configuration of Wazuh agents
- Log collection and correlation
- Real-time alerting based on host behavior (file integrity, authentication, privilege use, etc.)

#### 🔸 Suricata — Network Intrusion Detection System (NIDS)
- Deployment and integration with the monitoring environment
- Custom rule creation (DoS detection, port scanning signatures, suspicious traffic patterns)
- Packet inspection and alert generation
- Validation using simulated attacks from Kali Linux



## 🧪 Testing & Validation

- Network scans (Nmap)
- Suspicious traffic injections
- Host-level event triggering (authentication failures, file modifications)

**Results:** Wazuh + Suricata provided clear, actionable alerts, demonstrating strong detection capabilities in a lab environment.



## 🔮 Future Enhancements (Planned)

- Foundation for a full SOC (not implemented during internship)  
- **TheHive:** Incident response and case management  
- **Cortex:** Automated analysis and task execution  
- **MISP:** Threat intelligence enrichment  
- **SOAR:** Automated response playbooks

These enhancements would transform the monitoring environment into a complete SOC ecosystem.


## 🎯 Skills Gained
- Defensive monitoring & intrusion detection
- SIEM configuration (Wazuh)
- NIDS rule development (Suricata)
- Linux system administration
- Virtualized SOC lab design
- Attack simulation & detection validation
- Cybersecurity documentation
