# 🛡️ Open-Source SOC Monitoring Environment 

This repository presents the project I completed during my cybersecurity internship at Attijari Bank, where I deployed a host-based and network-based intrusion detection environment using open-source tools.  
The objective was to strengthen my defensive security skills and implement a functional monitoring pipeline capable of detecting common attack techniques.

## 🚀 Project Scope

### ✔️ Completed Work

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

### 🧪 Testing & Validation

Several controlled attack scenarios were launched from a Kali Linux VM to evaluate detection accuracy, including:
- Network scans (Nmap)
- Suspicious traffic injections
- Host-level event triggering (authentication failures, file modifications)

**Results:** Wazuh + Suricata provided clear, actionable alerts, demonstrating strong detection capabilities in a lab environment.

### 🔮 Future Enhancements (Planned)

Although not implemented in this internship due to scope and time constraints, this project lays the foundation for a full-featured SOC. Future improvements may include:
- **TheHive — Incident Response Platform**: Centralized case management and structured investigation workflows.
- **Cortex — Automated Analysis**: Execution of analyzers and responders to automate repetitive tasks.
- **MISP — Threat Intelligence**: Enrichment of alerts using community and organizational threat intelligence feeds.
- **SOAR automation**: Integration of playbooks for automated response actions.

These enhancements would transform the monitoring environment into a complete SOC ecosystem.

## 🎯 Skills Gained
- Defensive monitoring & intrusion detection
- SIEM configuration (Wazuh)
- NIDS rule development (Suricata)
- Linux system administration
- Virtualized SOC lab design
- Attack simulation & detection validation
- Cybersecurity documentation
