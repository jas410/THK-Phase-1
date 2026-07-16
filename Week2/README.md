# Week 2 — Network Recovery, Protocol Analysis & Subnet Engineering

## Objective
Strengthen core networking skills by diagnosing connectivity failures, repairing protocol issues, and analyzing subnet boundaries on a headless Linux system.

## What I Worked On
- Restored network connectivity by activating interfaces, assigning IP details, and rebuilding the default gateway  
- Identified and corrected DNS poisoning by auditing `/etc/hosts` and validating proper name resolution  
- Discovered hidden services using tools such as `ss -tuln`, `curl -I`, and header inspection  
- Analyzed a misconfigured `/26` subnet using binary breakdowns and `ipcalc` to determine correct network boundaries  
- Repaired multi‑layer network failures by fixing subnet masks, removing malicious DNS overrides, and validating packet flow with `tcpdump`  

## Artifacts
- 🛰️ **network_audit.txt** — Network interface recovery, routing fixes, and gateway restoration  
- 🔐 **protocol_audit.txt** — DNS repair, service discovery, and protocol behavior analysis  
- 🧮 **subnet_blueprint.txt** — Subnet boundary inspection and corrected addressing plan  
- ⚡ **tlab_report.txt** — Full remediation summary with packet‑level verification  

## Skills Demonstrated
- Ability to diagnose and repair broken network interfaces  
- Understanding of DNS behavior, poisoning indicators, and name‑resolution troubleshooting  
- Experience analyzing ports, services, and HTTP headers for hidden or misconfigured components  
- Proficiency in subnet math, CIDR boundaries, and address planning  
- Hands‑on packet capture and verification using `tcpdump`  

## Outcome
Successfully restored full network functionality by correcting addressing errors, repairing DNS integrity, rebuilding routing paths, and validating connectivity through packet‑level analysis.
