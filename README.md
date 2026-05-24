# Deploying-Wazuh-SIEM-for-Cross-Platform-Threat-Detection-
Deployed and configured Wazuh SIEM on Ubuntu Linux to monitor Linux and Windows systems, simulate cyber attacks, and analyse real-time security alerts using threat hunting and log analysis techniques.
# Deploying Wazuh SIEM to Detect Event Log Clearing Audits across Cross-Platform Environments

## 📌 Overview
This project demonstrates the deployment and configuration of the Wazuh SIEM platform for monitoring and detecting suspicious activities across Linux and Windows environments. The lab focuses on real-time log analysis, threat hunting, alert generation, and security event monitoring using practical attack simulations.

The objective of this project was to gain hands-on experience with SIEM technologies, telemetry monitoring, and SOC analyst workflows by generating and analyzing real-world security alerts.

---

# 🛠️ Technologies Used

- Wazuh SIEM
- Ubuntu Linux
- Windows 11
- Oracle VirtualBox
- PowerShell
- SSH
- Threat Hunting & Log Analysis

---

# 🖥️ Environment Setup

## Linux Environment
- Ubuntu Linux Virtual Machine configured as the Wazuh Server
- SSH authentication monitoring enabled
- Threat Hunting dashboard configured for event analysis

## Windows Environment
- Windows system integrated with Wazuh using the Wazuh Agent
- Agent Name: `Naina`
- Windows telemetry and security event monitoring enabled

---

# 🚨 Attack Simulations Performed

## 1️⃣ Linux SSH & Sudo Failed Login Detection

Multiple failed authentication attempts were intentionally generated on the Ubuntu Linux system to simulate suspicious login activity.

### Detection Results
- **Rule ID:** `5404`
- **Severity Level:** `10`
- **Alert Description:** `Three failed attempts to run sudo`

### Skills Demonstrated
- Linux log analysis
- SSH monitoring
- Authentication event investigation
- Threat hunting

---

## 2️⃣ Windows Event Log Clearing Detection

A Windows defense evasion simulation was performed using PowerShell to clear Windows Security Event Logs.
 
Command Used
```powershell
Clear-EventLog -LogName Security

#Detection Results
Rule ID: 63103
Severity Level: 12+
Alert Description: Audit log was cleared
🎯 Project Outcome

Successfully deployed a functional Wazuh SIEM environment capable of:

Monitoring Linux and Windows systems
Detecting suspicious login attempts
Detecting audit log clearing activities
Performing real-time security event analysis
Investigating alerts using threat hunting techniques
📌 Author

Nagatejaswini Saparay

Aspiring Cybersecurity & SOC Analyst focused on SIEM, Threat Detection, Telemetry Engineering, and Blue Team Operations.
