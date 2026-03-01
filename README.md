# Active-Directory-Attack-Defense-Lab
Active Directory Attack &amp; Defense Simulation Lab using Windows Server 2019, Kali Linux, and windows 10
Project Overview

Built a fully functional Active Directory lab to simulate enterprise attack scenarios and defensive monitoring techniques.

🏗 Lab Architecture

Windows Server 2019 (Domain Controller)

Windows 10 Client

Kali Linux Attacker Machine

VMware Workstation

Domain: logesh.local

SIEM: Splunk (Log Monitoring)

🎯 Attack Simulation Performed

✔ Domain enumeration using CrackMapExec
✔ SMB share enumeration
✔ Password spraying simulation
✔ Privileged group enumeration
✔ Domain Admin membership analysis
✔ Authentication log monitoring (Event IDs 4624, 4625, 4769)
✔ BloodHound data collection for attack path mapping

🛠 Tools Used

CrackMapExec

SMBClient

Nmap

BloodHound (Data Collector)

Windows Event Viewer

Splunk SIEM

🔎 Key Findings

Identified Domain Admin accounts

Observed authentication failure patterns

Detected password spray attempts in Event Logs

Mapped user-to-group privilege relationships

🛡 Defensive Analysis

Enabled Advanced Audit Policies

Monitored Event IDs 4624 & 4625

Created detection logic for suspicious authentication attempts

Recommended strong password policy & account lockout policy

📚 Learning Outcome

This project enhanced practical understanding of:

Active Directory internals

Red Team enumeration techniques

Authentication-based attack detection

SIEM log correlation
