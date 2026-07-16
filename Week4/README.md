# Week 4 — Containerization & Secure Deployment

## Objective
Learn how to design, deploy, and secure containerized environments using Docker, network segmentation, and automated provisioning techniques.

## What I Worked On
- Built an isolated malware‑analysis sandbox using a host‑only network to ensure complete separation from external systems  
- Deployed a disposable web server using Docker to practice rapid provisioning and safe teardown workflows  
- Created a multi‑container architecture with Docker Compose to simulate real‑world application and database separation  
- Implemented frontend/backend segmentation to restrict sensitive services from internet exposure  
- Validated isolation controls by testing outbound connectivity and confirming restricted communication paths  
- Automated container deployment and cleanup using Bash scripting  

## Artifacts
- 🛠️ **deploy_web.sh** — Automated Docker deployment and teardown script  
- 🐳 **docker-compose.yml** — Multi‑container architecture with segmented services  
- 📊 **hyperstack_audit.json** — Security audit of the container environment  
- 🧪 **sandbox_report.txt** — Validation report for the air‑gapped malware sandbox  

## Skills Demonstrated
- Containerization using Docker and Docker Compose  
- Network segmentation and secure service isolation  
- Multi‑tier architecture design and deployment  
- Automation of infrastructure workflows using Bash  
- Practical validation of containment and communication boundaries  

## Outcome
Successfully deployed a segmented, containerized application environment with enforced isolation controls, reduced attack surface, and validated secure communication paths across all components.

