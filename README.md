# Kioptrix Level 1.2 (#3) Penetration Testing

## Project Description
This project demonstrates a comprehensive penetration testing process on the Kioptrix Level 1.2 (#3) virtual machine, designed for penetration testing practice. The primary objective was to exploit vulnerabilities, gain root access, and provide actionable recommendations to enhance system security.

The methodology includes reconnaissance, vulnerability assessment, exploitation, privilege escalation, and post-exploitation activities. Tools like Nmap, Nikto, SQLMap, and Burp Suite were utilized to identify and exploit weaknesses such as SQL injection, remote command execution, and improper privilege management.

---

## Features
- **Reconnaissance**: Network and service scanning using Nmap.
- **Vulnerability Assessment**: Discovery of potential weaknesses with tools like Nikto and Dirb.
- **Exploitation**: Execution of SQL injection and remote command execution via LotusCMS vulnerabilities.
- **Privilege Escalation**: Exploiting misconfigurations to gain root access.
- **Post-Exploitation**: Adding a backdoor user and clearing tracks to maintain access.
- **Recommendations**: Detailed steps to mitigate identified vulnerabilities.

---

## Tools Used
- **Nmap**: Network scanning and vulnerability discovery.
- **Nikto**: Web server vulnerability analysis.
- **SQLMap**: Automated SQL injection exploitation.
- **Burp Suite**: Manual web traffic manipulation.
- **Dirb**: Directory and file discovery.
- **Crackstation**: Password cracking.

---

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/kioptrix-level1.2-penetration-testing.git
   Install the required tools:
   sudo apt install nmap nikto sqlmap dirb

   Follow the methodology outlined in the documentation/ folder to reproduce the results Documentation

## Documentation 
- **Methodology**: A detailed breakdown of the penetration testing process.
- **Findings**: Threats, vulnerabilities, and impact assessments.
- **Recommendations**: Steps to secure similar systems against such attacks.



