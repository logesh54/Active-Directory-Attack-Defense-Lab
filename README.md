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


# Screenshots 

1.<img width="1900" height="1016" alt="1" src="https://github.com/user-attachments/assets/610d1fee-2449-4b08-95dd-ad1df4d0ce68" />

2.<img width="1912" height="783" alt="2" src="https://github.com/user-attachments/assets/207db0c5-8abd-4efc-9aee-88528173c6cf" />

3.<img width="1915" height="801" alt="3" src="https://github.com/user-attachments/assets/66afc75c-9b57-4e0e-ade5-43bd6c1fe6cf" />

4.<img width="1913" height="704" alt="4" src="https://github.com/user-attachments/assets/64749a42-eda1-4b01-b4f9-92448a73b24d" />

5.<img width="1901" height="777" alt="5" src="https://github.com/user-attachments/assets/162b99a8-2ac4-4549-bb5b-82b647af767f" />

6.<img width="1919" height="745" alt="6" src="https://github.com/user-attachments/assets/56ba0603-c86f-4edd-b947-08c5ec5f709d" />


7.<img width="1408" height="868" alt="7" src="https://github.com/user-attachments/assets/329488f4-5164-4eea-8fda-3edf3c9d156e" />

8.<img width="1031" height="753" alt="8" src="https://github.com/user-attachments/assets/6d724282-403f-445f-a52d-fed2578c7c62" />

9.<img width="1263" height="862" alt="9" src="https://github.com/user-attachments/assets/d82698d6-94f3-49da-b3b4-8fdf4d35b6b8" />


10.<img width="1917" height="872" alt="10" src="https://github.com/user-attachments/assets/7a41bf85-15cf-4786-a7b4-05740cf91c5d" />

11.<img width="1910" height="535" alt="11" src="https://github.com/user-attachments/assets/926edf49-9832-46ba-a050-08a5bbfbd47b" />

12.<img width="1907" height="725" alt="12" src="https://github.com/user-attachments/assets/cf3b09c8-6876-441f-bde5-35595c63c3c2" />
13.<img width="1918" height="645" alt="13" src="https://github.com/user-attachments/assets/42a68c95-eeaf-4015-945e-2f8a4bc2af6a" />

14.![Uploading 14.png…]()

15.<img width="1910" height="874" alt="15" src="https://github.com/user-attachments/assets/a44757ea-6a46-426d-bd75-f570c7332617" />

16.<img width="1909" height="698" alt="16" src="https://github.com/user-attachments/assets/cbd49da3-d0a4-4b22-aa4c-bd8548b56706" />

17.<img width="1915" height="785" alt="17" src="https://github.com/user-attachments/assets/f4f6145c-46c7-42c8-8cf0-d67d746ba7aa" />

       
