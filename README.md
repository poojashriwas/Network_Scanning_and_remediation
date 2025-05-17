#  Network_Scanning_and_remediation

# 🔍 Network Vulnerability Assessment & Exploitation with Kali Linux

## 🚀 Overview
This project presents a real-world simulation of *network penetration testing* using Kali Linux and Metasploitable 2. It includes *network scanning, **service enumeration, **exploitation, **password cracking, and **security remediation* — all within a safe, virtual lab environment.

## 🎯 Objectives
- Discover devices and open ports on the network
- Identify vulnerable services and operating systems
- Exploit known vulnerabilities (FTP, Telnet, HTTP)
- Crack weak passwords using John the Ripper
- Suggest and apply real-world remediation techniques

## 🧰 Requirements
- VirtualBox or VMware
- Kali Linux ISO / VM
- Metasploitable 2 VM
- Basic Linux & Networking knowledge

## 🛠 Tools Used
- Kali Linux (Attacker)
- Metasploitable 2 (Target)
- nmap – Port and service scanner
- john – Password cracker
- Metasploit Framework – Exploitation
  
## 🖥 Lab Setup
- *Environment*: VirtualBox or VMware
- *Kali Linux*: Used for scanning and exploitation
- *Metasploitable 2*: Vulnerable target machine
- *Network Mode*: Host-only Adapter for isolated lab

## 🧪 Tasks & Outcomes

### ✅ Task 1: Basic Network Scan

Result: Identified all active devices and open ports

🔐 Task 2: Hidden Port Scan

Result: Revealed hidden or uncommon open ports

🧾 Task 3: Service Version Detection

Result: Detected services like vsFTPd 2.3.4 and Apache 2.2.8


🧠 Task 4: Operating System Detection

Result: OS detected as Linux 2.6.x (Metasploitable 2)

⚔ Task 5: Service Exploitation

FTP: Backdoor exploit via Metasploit
Telnet: Weak login access
HTTP: Apache vulnerability scan via Nikto


🔓 Task 6: Password Cracking

Result: Cracked weak passwords

🛡 Remediation (Real-World Fixes)

| 🔧 Service | ⚠ Current Version | ✅ Recommended | 💡 Fix |
|-----------|------------------|----------------|--------|
| vsFTPd    | 2.3.4            | 3.0.5+         | Update FTP, disable anonymous login |
| Apache    | 2.2.8            | 2.4.59+        | Upgrade, apply security headers |
| Telnet    | Enabled          | Disabled       | Replace with SSH |
| MySQL     | 5.0.51a          | 8.3.0+         | Upgrade and use strong credentials |


🧠 Key Learnings

Learned the full cycle of ethical hacking: Reconnaissance → Exploitation → Remediation

Understood risks of outdated services

Developed skills in vulnerability analysis and system hardening

Practiced responsible and legal ethical hacking techniques


⚠ Disclaimer

This project is for educational and research purposes only. Do NOT use these tools on unauthorized systems.
