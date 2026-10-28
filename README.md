
# Home SOC Lab: Threat Detection & Incident Response
A personal SOC lab simulating attacks and detections using Wazuh SIEM, Sysmon, and Kali Linux.

## 📌 Project Overview
This project is a personal Home SOC (Security Operations Center) Lab designed to simulate real-world cyber attacks, detect them using a centralized SIEM, and practice incident response and log analysis.

## 🏗️ Lab Architecture
- **SIEM / Manager:** Wazuh (OVA) - IP: `192.168.129.138`
- **Endpoint / Victim:** Windows 11 (Running Sysmon & Wazuh Agent) - IP: `192.168.129.133`
- **Attacker:** Kali Linux (Hydra, Nmap)

## 🛠️ Tools & Technologies Used
- **SIEM/EDR:** Wazuh 4.14.9, Sysmon
- **Attacking Tools:** Kali Linux, Hydra, Nmap
- **Frameworks:** MITRE ATT&CK

## 🎯 Skills Demonstrated
- **Log Analysis:** Analyzing Windows Event IDs (4625) and Sysmon logs.
- **Detection Engineering:** Tuning Wazuh rules and mapping alerts to MITRE ATT&CK.
- **Incident Response:** Documenting evidence, severity assessment, and proposing remediation steps.
- **Network Security:** Configuring virtual networks, RDP, and SSH.

## 📂 Project Structure
- `[docs/](link-to-your-docs)` - Step-by-step guide on how I built and configured the lab.
- `[evidence/](link-to-your-evidence)` - Screenshots of Wazuh alerts and dashboards.
- `[incident-reports/](link-to-your-reports)` - Detailed incident response reports for each simulated attack.

## 🚨 Case Studies (Incident Reports)
- **[INC-001: RDP Brute Force Attack](link-to-your-report)** - Simulated an RDP brute-force attack using Hydra and detected 1,000+ failed logon events (Event ID 4625) mapped to MITRE T1110.

---
*Created by [SanjVN] - Aspiring SOC Analyst*
