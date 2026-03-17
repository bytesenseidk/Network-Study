# From Packets to Persistence — A Practical Cybersecurity Knowledge Base

This repository is not just a collection of notes — it is a structured journey through how modern systems work, how they are attacked, and how they are defended.

It began with a simple goal:  
to deeply understand networking at the packet level.

But as that understanding grew, so did the realization:

> To truly understand systems, you must understand how they break.

This project evolved into a comprehensive knowledge base that bridges:

- Networking fundamentals  
- Offensive security (Red Team)  
- Detection engineering (Blue Team)  

---

# 🎯 What Makes This Repository Different

Most resources focus on isolated topics:

- networking **or** security  
- theory **or** tools  
- red team **or** blue team  

This repository connects them.

Every concept is tied to:

- how it works  
- how it is abused  
- how it is detected  

---

# 🔴 Real Red Team Engagement Thinking

At the core of this project is a structured **Red Team Engagement framework**.

Instead of random attack notes, this repository models:

- real attacker workflows  
- multi-stage attack chains  
- practical exploitation paths  

Each attack is documented as a **repeatable playbook**, including:

- objectives  
- step-by-step execution  
- tools and commands  
- expected results  
- defensive considerations  

---

# 🔵 Detection Engineering Built In

This is not just an attacker’s perspective.

Every major technique is paired with:

- log sources  
- detection strategies  
- SIEM queries (Splunk, KQL)  
- investigation workflows  

This allows you to understand:

> not just how attacks happen — but how they are caught.

---

# ⚔️ Red vs Blue Labs

The repository includes practical **Red vs Blue labs** that simulate real-world scenarios:

- Password spraying → detection via authentication logs  
- Kerberoasting → detection via Kerberos activity  
- Phishing → detection via user behavior and sign-in anomalies  
- DCSync → detection via directory replication events  

And full attack chains:

- Initial access → credential abuse → domain compromise  

These labs reinforce a critical concept:

> attacks are not isolated — they are chained.

---

# Project Goals

This project aims to:

- Build a **strong foundation in networking**
- Understand **how attacks work across different surfaces**
- Learn **real-world offensive techniques**
- Develop **detection and defense strategies**
- Connect **theory → attacks → detection**

---

# Core Areas Covered

## Networking Fundamentals

- OSI / TCP-IP models
- Routing and packet delivery
- Protocol behavior
- Packet analysis (Wireshark)
- Network troubleshooting

---

## Red Team (Offensive Security)

Organized by attack surface:

- Web attacks (XSS, SQLi, SSRF, IDOR)
- Credential attacks (spraying, token abuse)
- Network attacks (NTLM relay, Kerberos abuse)
- Wireless attacks (Evil Twin, WPA cracking)
- Cloud attacks (AWS, Azure)
- Social engineering (phishing, pretexting)

Also includes:

- Post-exploitation
- Persistence techniques
- Command and control
- Evasion techniques

---

## Blue Team (Detection Engineering)

- Sigma rules
- Splunk detection strategies
- KQL (Microsoft Sentinel)
- Detection tuning
- Threat hunting playbooks
- Alert triage workflows

---

## Red vs Blue Labs

Practical scenarios combining:

- Attack execution
- Detection logic
- Investigation workflows

Examples:

- Password spraying detection
- Kerberoasting detection
- Phishing detection
- DCSync detection

---

# Learning Approach

Each topic includes:

- clear explanations  
- real-world context  
- step-by-step workflows  
- commands and tools  
- defensive insights  
- Q&A sections  

This reinforces:

- understanding  
- retention  
- practical application  

---

# Repository Structure
Engagements/
├── 00_Engagement_Methodology.txt
├── 00_Practice_Labs
├── 01_Reconnaissance
├── 02_Web_Attacks
├── 03_Credential_Attacks
├── 04_Network_Attacks
├── 05_Wireless_Attacks
├── 06_Cloud_Attacks
├── 07_Social_Engineering_Attacks
├── 08_Post_Exploitation
├── 09_Defensive_Evasion
├── 10_Detection_Engineering
└── 11_Red_vs_Blue_Labs

The structure follows a **real attacker lifecycle**.

---

# Tools Referenced

- Nmap  
- Gobuster  
- Hashcat  
- Responder  
- Impacket  
- Metasploit  
- Aircrack-ng  
- Wireshark  
- AWS CLI / Azure CLI  

---

# Who This Is For

- Cybersecurity students  
- Self-taught learners  
- Penetration testers  
- Security analysts  
- Blue team engineers  
- Anyone wanting to understand **how attacks actually work**  

---

# How to Use This Repository

Recommended approach:

1. Start with networking fundamentals  
2. Move into attack categories  
3. Study attack workflows  
4. Learn detection alongside attacks  
5. Practice using Red vs Blue labs  

---

# Key Philosophy

This project focuses on:
Concept → Protocol → Attack → Detection

Understanding systems deeply → simulating real attacks → building strong detection.

---

# Future Improvements

- Lab environment setup guides  
- Full attack chain simulations  
- Detection rule libraries (Sigma / SIEM)  
- Incident response scenarios  
- Visual diagrams and attack maps  

---

# License

For educational purposes.

---

# Author

[**Byte Sensei**](https://github.com/bytesenseidk)
