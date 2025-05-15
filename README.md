# Patching and Securing Windows Server Lab

## 🎯 Objective
This project simulates a real-world red team vs. blue team cybersecurity engagement. You begin by exploiting a vulnerable Windows Server using Metasploit on Kali Linux (red team), then pivot to the defensive side by hardening and patching the system (blue team). This demonstrates both offensive and defensive technical skills used in SOC and cybersecurity analyst roles.

---

## 🧪 Lab Breakdown

### 1. Red Team (Offensive)
- Used Metasploit to exploit an SMB vulnerability on a Windows Server.
- Gained a Meterpreter shell access.
- Uploaded malware to simulate a real-world compromise.

### 2. Blue Team (Defensive)
- Closed vulnerable services (e.g., Telnet, FTP).
- Installed and configured Windows Updates to patch the SMB vulnerability.
- Configured firewall rules to restrict unnecessary traffic.
- Scanned and removed malware using Microsoft Security Essentials.

---

## 🛠️ Tools Used
- Kali Linux (Metasploit)
- Nmap & Zenmap
- Windows Server
- Microsoft Security Essentials
- Windows Firewall

---

## 📂 Folder Structure

- `/1_Exploitation_Red_Team` – Red team actions using Metasploit.
- `/2_Hardening_Blue_Team` – Defensive remediation and hardening steps.
- `/3_Firewall_Configuration` – Configuring host firewall rules.
- `/4_Antivirus_Malware_Removal` – Detecting and removing malware.
- `/5_Topology_and_Diagrams` – Visual diagrams for the lab setup and concepts.

---

## 📸 Screenshots
Each folder contains step-by-step screenshots documenting key actions and their outcomes.

---

## 🧠 Key Takeaways
- Unpatched systems are vulnerable to known exploits (like EternalBlue).
- Defense-in-depth is not a theory — it's a practical, layered approach.
- Blue teamers must think like attackers to defend effectively.
