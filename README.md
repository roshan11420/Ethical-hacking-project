🔐 Ethical Hacking Project
🔍 Scanning and Enumerating a Local Network with Nmap
📘 Introduction
This project simulates a real-world penetration testing lifecycle using virtual machines. It is designed for educational purposes and aims to help learners understand both offensive and defensive cybersecurity operations. By exploring how vulnerabilities are identified, exploited, and mitigated, participants develop critical skills for ethical hacking and cybersecurity roles.

🖥️ Virtual Machines Used
Kali Linux – Attacking machine with pre-installed security tools.

Metasploitable2 – Intentionally vulnerable target system for testing and training.

🛠 Tools Used
Nmap – Network scanner for host discovery and service enumeration.

Metasploit Framework – Exploitation toolkit.

John the Ripper – Password cracking tool.

Metasploitable2 VM – Vulnerable environment for safe exploitation.

📌 Project Tasks & Methodology
1. Network Scanning
Performed basic and full-range scans using Nmap.

Example command: nmap -v -p- 192.168.78.44

2. Reconnaissance
Detected hidden ports and services.

Identified OS and service versions using -sV and -O flags.

3. Enumeration
Collected detailed system and service information.

Example Output: Open Port 1716/tcp, Service xmsg

4. Exploitation
Targeted known vulnerabilities:

vsftpd 2.3.4 - CVE-2011-2523

distccd - CVE-2004-2687

Samba smbd - CVE-2003-0201

5. Privilege Escalation
Created new user with root permissions.

Extracted and analyzed password hashes.

6. Password Cracking
Cracked user passwords using John the Ripper and default wordlists.

7. Remediation & Recommendations
Suggested upgrades for outdated services (e.g., vsftpd, OpenSSH).

Advised firewall rules for insecure services like Java RMI.

🎓 Learning Outcomes
Mastery of the penetration testing lifecycle.

Hands-on experience with Kali Linux, Metasploit, and John the Ripper.

Awareness of common vulnerabilities and how to exploit/remediate them.

Understanding of ethical and legal hacking practices.

Practical skills in password cracking and user privilege escalation.

⚠️ Disclaimer
This project is for educational purposes only. All testing was performed in a controlled lab environment. Do not attempt these techniques on live systems without proper authorization.

📂 Requirements
VirtualBox or VMware

Kali Linux ISO

Metasploitable2 VM image

📧 Author
Roshan Sahu
Student, Ethical Hacking Enthusiast

