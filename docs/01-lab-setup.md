# Lab Setup Guide

## 1. Network Topology
- All VMs are running on VMware Workstation using a NAT network (`192.168.129.0/24`).

## 2. Wazuh SIEM Installation
- Imported the official Wazuh OVA into VMware.
- Reduced RAM to 4GB for performance optimization.
- Accessed the Wazuh Dashboard at `https://192.168.129.138` (default credentials: admin/admin).

## 3. Windows 11 Endpoint Configuration
- Installed **Sysmon** using the SwiftOnSecurity configuration file to capture detailed system activity.
- Installed the **Wazuh Agent** and configured `ossec.conf` to forward Sysmon logs to the Wazuh Manager.

## 4. Attacker Setup (Kali Linux)
- Installed Kali Linux and downloaded the `10k-most-common.txt` wordlist for brute-forcing.
- Confirmed network connectivity to the Windows victim via Nmap.
