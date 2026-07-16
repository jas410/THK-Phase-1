# 🗂️ **Week 3 – Python Automation, Log Forensics & System Auditing**

This week focused on building automated security tools using Python to replace manual investigation. In these assignments, I developed scripts that parse logs, detect threats, audit systems, and generate structured security reports—core skills used in SOC, DFIR, and security automation roles.

---

## 🧪 **port_check.py — Automated Port Scanner & Access Validation**
I wrote a Python script that checks whether Port 22 is open across multiple IPs. I used lists, loops, and socket connections to test each host and report if the port was open or closed.

---

## 🔍 **brute_detector.py — Log Forensics & Brute‑Force Attack Detection**
II built a script that scans authentication logs for brute‑force attempts. I filtered for “Failed password” events, counted occurrences, and exported a clean report using safe file handling and defensive programming.

---

## 🛡️ **system_auditor.py — Automated Process Monitoring & JSON Alerting**
I created a system auditor that detects unauthorized processes on a Linux server. I used subprocess to run system commands, parsed the output, and generated a JSON alert when suspicious activity appeared.
