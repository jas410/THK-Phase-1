# Week 9 — Web Application Vulnerabilities, API Security & Chained Exploitation

## Objective
Perform a full‑stack security assessment across modern web applications by identifying OWASP Top 10 vulnerabilities, exploiting chained attack paths, and documenting secure coding remediations.

## What I Worked On
- Tested authentication workflows for SQL Injection using tautology‑based payloads and UNION‑based data extraction  
- Enumerated database schemas and exfiltrated sensitive records through crafted SQLi queries  
- Executed both Stored and Reflected XSS to demonstrate DOM manipulation, session hijacking, and persistent payload injection  
- Built CSRF attacks using hidden‑image triggers to force unauthorized financial actions  
- Intercepted and modified API traffic in Burp Suite to exploit Broken Object Level Authorization (BOLA)  
- Performed business‑logic brute‑forcing to uncover hidden discount codes and authorization flaws  
- Combined multiple vulnerabilities into a chained exploitation workflow targeting a legacy corporate portal  

## Artifacts
- 🗂️ **sqli_report.txt** — Database schema mapping and UNION‑based data exfiltration  
- 🧪 **xss_payloads.txt** — Stored/Reflected XSS payloads and weaponized CSRF attack samples  
- 📡 **api_audit.log** — BOLA exploitation logs and Burp Intruder brute‑force results  
- 📝 **OmniPortal_Assessment.md** — Full chained exploitation report with remediation guidance  

## Skills Demonstrated
- Identification and exploitation of SQL Injection flaws  
- Execution of Stored and Reflected XSS for session compromise  
- Use of Burp Suite to intercept, analyze, and manipulate API traffic  
- Detection of BOLA vulnerabilities and business‑logic weaknesses  
- Ability to chain multiple vulnerabilities into a high‑impact attack path  
- Delivery of secure coding recommendations including parameterized queries, output encoding, and server‑side authorization checks  

## Outcome
Completed a multi‑layer assessment across several web environments, demonstrating practical exploitation of SQLi, XSS, CSRF, and API authorization flaws. Successfully chained vulnerabilities to compromise a legacy portal and produced professional‑grade remediation guidance to harden the application against modern web threats.
