# BruteForceSIm
brute force simulation and remediation
# SSH Brute Force Simulation & Defense – Ubuntu Server Lab

## 📌 Overview
This project demonstrates how to simulate, detect, and mitigate **SSH brute force attacks** against an Ubuntu Server.  
The lab environment was designed to showcase authentication vulnerabilities and defensive hardening techniques.

## 🎯 Objectives
- Simulate SSH brute force attacks to study authentication weaknesses.
- Ingest system logs into **Splunk** to analyze attack patterns.
- Deploy **Fail2ban (SSH jail)** to automatically ban attacker IPs after repeated failed login attempts.
- Harden the server by updating **UFW firewall rules**, further restricting SSH access and reducing exposure.

## 🛠️ Tools & Technologies
- **Ubuntu Server** – Target environment
- **Splunk** – Log ingestion, dashboards, and alerting
- **Fail2ban** – Intrusion prevention via SSH jail
- **UFW** – Firewall configuration
- **VirtualBox** – Lab virtualization environment

## 🔎 Attack Simulation
- Used automated SSH login attempts to simulate brute force behavior
