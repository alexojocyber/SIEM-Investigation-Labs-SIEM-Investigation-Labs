#  SIEM Investigation Labs – Final Project Summary  
*Author:* Alex Ojo  
*Date:* December 2025  
*Platform:* Kali Linux (VirtualBox)  
*Skills Demonstrated:* SOC Analysis • Log Forensics • Bash Automation • Attack Simulation • Incident Reporting • Linux Security  

---

##  Project Overview  
This repository contains *three structured SOC-style cybersecurity investigations*, each designed to simulate real-world blue-team scenarios.  
The investigations showcase your ability to:

- Analyze system logs  
- Detect brute-force attacks  
- Build automation scripts  
- Investigate suspicious shell behavior  
- Provide complete SOC analysis and reporting  
- Document evidence professionally  

Each investigation includes:

✔ Screenshots  
✔ Forensic findings  
✔ Indicators of Compromise (IoCs)  
✔ Security recommendations  
✔ Explanation of attack behavior  

---

#  Breakdown of Investigations

---

##  *Investigation 1 — Failed Login Analyzer Script*  
A custom Bash script was built to scan:

- failed system logins  
- usernames targeted  
- attacker IPs attempting access  
- top 5 most frequent malicious IPs  

The script shows your ability to:

- create security automation tools  
- parse authentication logs  
- extract meaningful security signals  
- understand how log files work on systemd-based Linux  

This reflects Tier 1 SOC tasks such as alert triage and log extraction.

---

##  *Investigation 2 — SSH Brute-Force Attack Detection*  
A real brute-force attack was simulated using *Hydra* against the Linux SSH service.

*Evidence collected included:*

- thousands of failed SSH attempts  
- rotating attacker ports (Hydra's multi-threading)  
- targeted username: root  
- attacker IP: 10.0.2.15  
- timestamps showing burst activity  
- complete journalctl logs with “Failed password” entries  

This investigation demonstrates:

- hands-on SIEM-level log analysis  
- detection of brute-force patterns  
- MITRE ATT&CK mapping  
- identification of IoCs  
- SSH hardening techniques (Fail2Ban, disabling root login, key-based auth)  

This is the most valuable piece of your portfolio for SOC/Blue Team roles.

---

##  *Investigation 3 — File Manipulation & Script Behavior Analysis*  
This investigation analyzes:

- unauthorized file creation  
- file deletion and recreation  
- text manipulation  
- execution of a suspicious script using conditional logic  
- analysis of ${1,,} lowercase-check behavior  
- how attackers hide logic in shell scripts  

This mirrors real-world Linux forensic investigation where analysts check for:

- rogue user scripts  
- file tampering  
- malicious automation  
- hidden privilege escalation logic  

---

#  Skills Demonstrated Across All Investigations

###  *Linux Forensics*
- journalctl analysis  
- SSH authentication investigation  
- file operations and permission review  
- process and service inspection  

###  *Security Automation (Bash)*
- log analyzer creation  
- text parsing using grep, awk, sort, wc  
- automation logic for failed-login detection  

###  *Offensive Security Awareness*
- brute-force methodology  
- Hydra password attack execution  
- observing attacker behavior in logs  

###  *Defensive Security Techniques*
- SSH hardening  
- Fail2Ban deployment  
- disabling root login  
- auditing unauthorized file activity  

###  *Incident Reporting*
- full SOC-style DRR (detection, response, recommendation)  
- timeline creation  
- IoC extraction  
- analyst-driven conclusions  

---

#  Final Assessment  
This project demonstrates complete readiness for roles such as:

- *SOC Analyst (Tier 1)*  
- *Cybersecurity Analyst*  
- *Incident Response Intern*  
- *Blue Team Apprentice*  

It shows:

✔ Hands-on attack simulation  
✔ Accurate investigation skills  
✔ Real log analysis  
✔ Ability to write professional reports  
✔ Understanding of attacker behavior  
✔ Capability to automate detection tasks  
✔ Practical security-hardening knowledge  

This is exactly the type of practical, real work hiring managers want to see in an entry-level cybersecurity or SOC portfolio.

---

*End of Summary*
