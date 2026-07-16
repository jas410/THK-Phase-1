# Week 7 — Perimeter Scanning, Web Service Auditing & Risk Triage

## Objective
Assess perimeter hosts by performing network discovery, targeted service enumeration, vulnerability auditing, and structured risk triage across a simulated subnet.

## What I Worked On
- Conducted a full subnet sweep to identify live hosts and exposed perimeter services  
- Performed targeted port scans to isolate web‑accessible systems for deeper analysis  
- Used Nikto to audit each web server for misconfigurations and missing security headers  
- Evaluated findings based on impact, exploitability, and relevance to perimeter hardening  
- Produced a structured risk triage outlining severity levels and recommended remediation steps  

## Artifacts
- 🗂️ **Perimeter_Assessment.md** — Full perimeter scan, vulnerability audit, and risk summary  

## Key Findings
- **Host 172.88.0.28 — Apache/2.4.66**  
  - Inode leakage via ETag headers  
  - *Risk:* Medium — supports resource fingerprinting and cache manipulation  
  - *Fix:* Restrict or disable ETag generation  

- **Host 172.88.0.44 — BusyBox httpd 1.13**  
  - Missing X‑Frame‑Options header  
  - *Risk:* Medium — enables clickjacking attacks  
  - *Fix:* Add X‑Frame‑Options or CSP frame‑ancestors  

## Outcome
Completed a full perimeter assessment identifying medium‑severity misconfigurations across two web‑exposed hosts. Findings indicate hardening gaps rather than critical vulnerabilities, and all recommended fixes can be applied through configuration updates without downtime.
