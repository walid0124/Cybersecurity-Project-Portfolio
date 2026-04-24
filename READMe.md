# Walid Ali | Cybersecurity Portfolio
**BAS Cybersecurity Candidate @ George Mason University (Dec 2026)**  
*Secret Clearance-Eligible | Focus: Vulnerability Management & GRC*

# Enterprise Vulnerability Scanning & Host Enumeration
**Tools Used:** Kali Linux, Nmap, Searchsploit, Exploit-DB  
**Target Environment:** Ubuntu Linux (192.168.0.2)

---

## 🎯 Project Objective
The goal of this lab was to conduct comprehensive host enumeration and vulnerability scanning on a simulated target environment. I focused on identifying system configurations, open ports, and exploitable vulnerabilities to support forensic investigations and simulate adversarial reconnaissance.

## 🛠️ Methodology & Execution
- **Network Mapping:** Identified the target system IP and MAC address to establish a baseline.
- **Port Discovery:** Executed TCP SYN (`-sS`) and TCP Connect (`-sT`) scans to identify open ports (22, 139, 445, 5901, 6001).
- **Service Fingerprinting:** Utilized aggressive scanning (`-A`) to identify OpenSSH 6.0p1, Samba 3.6.6, and VNC protocol 3.8.
- **Vulnerability Identification:** Deployed the Nmap Scripting Engine (`--script=vuln`) to detect an **SMB-related Denial of Service vulnerability**.
- **Exploit Research:** Used `searchsploit` to cross-reference discovered services with known CVEs in the Exploit Database.

---

## 📸 Lab Evidence

### Service Version Fingerprinting
![Nmap Scan Result](./nmap-scan.png)
*Figure 1: Identifying vulnerable versions of OpenSSH and Samba.*

### Automated Vulnerability Detection
![NSE Vulnerability Result](./nse-vuln.png)
*Figure 2: Using Nmap Scripting Engine to detect an active SMB DoS vulnerability.*

---

## 🔑 Key Findings & Outcomes
- **Actionable Intelligence:** Successfully linked raw network scan data to known CVE databases.
- **Risk Assessment:** Mapped the target's service footprint without credentials, highlighting the danger of misconfigured SMB and VNC services.
- **Forensic Readiness:** Demonstrated proficiency in active reconnaissance techniques required for incident response.

---

## 🛠️ Technical Skill Stack
- **Security Tools:** Nessus, Splunk (SIEM), Wireshark, Nmap, Metasploit.
- **Compliance & Frameworks:** NIST 800-53, DISA STIGs, RMF, MITRE ATT&CK.
- **Systems & Networking:** Windows Active Directory, Linux (Kali/Ubuntu), TCP/IP.

---

## 🚀 Featured Cybersecurity Projects

### [Vulnerability Management & System Hardening Lab](./Vulnerability-Lab/)
*Performed automated scans and manual hardening on a virtualized enterprise network.*
- **The Challenge:** Identify and remediate "Critical" and "High" CVEs in a Windows 10 environment.
- **The Solution:** Used **Nessus** for discovery and **DISA STIG** checklists for manual remediation.
- **Result:** Successfully reduced the attack surface by 85% and achieved a "Pass" on the STIG compliance report.

### [Network Traffic Analysis & Incident Response](./Network-Defense-Lab/)
*Analyzed malicious traffic patterns and configured SIEM alerts.*
- **The Challenge:** Detect a simulated brute-force attack and data exfiltration attempt.
- **The Solution:** Monitored traffic via **Wireshark** and ingested logs into **Splunk**.
- **Result:** Created custom dashboard alerts that reduced "Time to Detect" (TTD) for unauthorized login attempts.

---

## 📜 Certifications
- **Google Cybersecurity Professional Certificate**
- **CompTIA Security+** *(In Progress - Expected 2026)*

---

## 📫 Connect with me
- **LinkedIn:** https://www.linkedin.com/in/walidalitheadeptus/
- **Email:** walidbd26@gmail.com
