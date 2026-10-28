# INC-001: RDP Brute Force Attack Detected
## 1. Summary
On October 28, 2026, at approximately 14:36 UTC, the Wazuh SIEM detected a high volume of failed logon attempts against the Windows 11 endpoint (`Windows-Victim`). Over 1,000 failed authentication events were recorded within a 15-minute window, indicating an automated Brute Force attack.

## 2. Evidence
- **Victim Agent:** Windows-Victim (192.168.129.133)
- **Attacker IP:** [192.168.129.130]
- **Target Account:** `Sanj`
- **Key Logs:** 
  - Wazuh Rule 60122: *Logon Failure - Unknown user or bad password*
  - Wazuh Rule 60204: *Multiple Windows Logon Failures*
  - Windows Event ID: **4625**

## 3. MITRE ATT&CK Mapping
- **Tactic:** Credential Access
- **Technique:** **T1110 (Brute Force)**

## 4. Analysis
The attacker utilized Hydra on Kali Linux to perform an RDP brute-force attack. Although the attack tool encountered technical limitations and failed to compromise the account, the SIEM successfully correlated the individual failures into a high-severity alert (Rule Level 10). No successful logon (Event ID 4624) was observed from the attacker's IP.

## 5. Remediation & Recommendations
1. **Immediate:** Block the attacker's IP address at the network firewall.
2. **Short-term:** Implement an Account Lockout Policy (e.g., lock account after 5 failed attempts).
3. **Long-term:** Disable RDP if not strictly required, or enforce Network Level Authentication (NLA) and Multi-Factor Authentication (MFA).]
- **Target Account:** `Sanj`
- **Key Logs:** 
  - Wazuh Rule 60122: *Logon Failure - Unknown user or bad password*
  - Wazuh Rule 60204: *Multiple Windows Logon Failures*
  - Windows Event ID: **4625**

## 3. MITRE ATT&CK Mapping
- **Tactic:** Credential Access
- **Technique:** **T1110 (Brute Force)**

## 4. Analysis
The attacker utilized Hydra on Kali Linux to perform an RDP brute-force attack. Although the attack tool encountered technical limitations and failed to compromise the account, the SIEM successfully correlated the individual failures into a high-severity alert (Rule Level 10). No successful logon (Event ID 4624) was observed from the attacker's IP.

## 5. Remediation & Recommendations
1. **Immediate:** Block the attacker's IP address at the network firewall.
2. **Short-term:** Implement an Account Lockout Policy (e.g., lock account after 5 failed attempts).
3. **Long-term:** Disable RDP if not strictly required, or enforce Network Level Authentication (NLA) and Multi-Factor Authentication (MFA).]
- **Target Account:** `Sanj`
- **Key Logs:** 
  - Wazuh Rule 60122: *Logon Failure - Unknown user or bad password*
  - Wazuh Rule 60204: *Multiple Windows Logon Failures*
  - Windows Event ID: **4625**

## 3. MITRE ATT&CK Mapping
- **Tactic:** Credential Access
- **Technique:** **T1110 (Brute Force)**

## 4. Analysis
The attacker utilized Hydra on Kali Linux to perform an RDP brute-force attack. Although the attack tool encountered technical limitations and failed to compromise the account, the SIEM successfully correlated the individual failures into a high-severity alert (Rule Level 10). No successful logon (Event ID 4624) was observed from the attacker's IP.

## 5. Remediation & Recommendations
1. **Immediate:** Block the attacker's IP address at the network firewall.
2. **Short-term:** Implement an Account Lockout Policy (e.g., lock account after 5 failed attempts).
3. **Long-term:** Disable RDP if not strictly required, or enforce Network Level Authentication (NLA) and Multi-Factor Authentication (MFA).]
- **Target Account:** `Sanj`
- **Key Logs:** 
  - Wazuh Rule 60122: *Logon Failure - Unknown user or bad password*
  - Wazuh Rule 60204: *Multiple Windows Logon Failures*
  - Windows Event ID: **4625**

## 3. MITRE ATT&CK Mapping
- **Tactic:** Credential Access
- **Technique:** **T1110 (Brute Force)**

## 4. Analysis
The attacker utilized Hydra on Kali Linux to perform an RDP brute-force attack. Although the attack tool encountered technical limitations and failed to compromise the account, the SIEM successfully correlated the individual failures into a high-severity alert (Rule Level 10). No successful logon (Event ID 4624) was observed from the attacker's IP.

## 5. Remediation & Recommendations
1. **Immediate:** Block the attacker's IP address at the network firewall.
2. **Short-term:** Implement an Account Lockout Policy (e.g., lock account after 5 failed attempts).
3. **Long-term:** Disable RDP if not strictly required, or enforce Network Level Authentication (NLA) and Multi-Factor Authentication (MFA).
