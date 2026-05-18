# Cybersecurity Vulnerability Assessment & Penetration Testing Project

## Project Title

Cybersecurity Practical Assessment using Kali Linux, Nessus Essentials, and
Metasploitable 2

---

## Student Information

- **Name:** Mahfuz
- **Student ID:** 2023200000270
- **Batch:** 14
- **Instructor:** Rashadul Islam

---

## Project Overview

This project demonstrates hands-on skills in Vulnerability Assessment (VA) and
Penetration Testing (PT) using Kali Linux and Metasploitable 2 in a virtual lab
environment.

The primary goal was to identify security weaknesses in the target system using
Nessus Essentials and then exploit selected vulnerabilities using the Metasploit
Framework.

---

## Lab Environment

### Attacker Machine

- Kali Linux (Latest Version)

### Target Machine

- Metasploitable 2

### Network Configuration

- NAT Network

### Tools Used

- Nessus Essentials
- Metasploit Framework (msfconsole)
- Nmap
- Hydra
- Linux Terminal Commands

---

## Target Information

- **Target IP:** 192.168.60.130
- **Kali Linux IP:** 192.168.60.128

---

## Tasks Completed

### Section A — Vulnerability Assessment

- Configured and ran a full Nessus vulnerability scan
- Analyzed Critical, High, and Medium vulnerabilities
- Identified open ports and running services
- Documented detailed findings

### Section B — Penetration Testing

- Successfully exploited the vsftpd 2.3.4 backdoor vulnerability
- Gained remote shell access using Metasploit
- Performed post-exploitation activities
- Prepared a complete penetration testing report

---

## Important Vulnerabilities Identified

### Critical Vulnerability

- vsftpd 2.3.4 Backdoor
- CVSS Score: 9.8
- Port: 21/tcp (FTP)

### Medium Vulnerability

- Unencrypted Telnet Service
- CVSS Score: 6.5
- Port: 23/tcp

---

## Exploitation Summary

The well-known **vsftpd 2.3.4** backdoor vulnerability was successfully
exploited using Metasploit.

A remote shell was obtained with root privileges on the target system.
Post-exploitation commands executed include:

- `whoami`
- `uname -a`
- `id`

---

## Screenshots Included

- va1_scan_config.png
- va1_scan_summary.png
- va2_critical_finding.png
- va2_medium_finding.png
- pt1_exploit_result.png
- pt1_post_commands.png

---

## Learning Outcomes

This project provided practical experience in:

- Vulnerability scanning with Nessus
- Risk assessment and prioritization
- Exploitation techniques using Metasploit
- Post-exploitation and privilege escalation
- Professional security reporting

---

## Conclusion

This project successfully demonstrated the complete process of identifying and
exploiting vulnerabilities in a controlled lab environment. It highlights the
importance of regular patching, proper service configuration, and strong
security practices to protect systems from real-world attacks.

---

**CyberSec_VA_PT_Assessment_Final.docx**
