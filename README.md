# Zero-Trust-Architecture-for-Ransomware-Defence-in-Virtualised-Environment
Implementation and evaluation of a Zero Trust Architecture for ransomware defence in a virtualised environment using open-source tools (Wazuh, auditd, UFW).
This repository contains the implementation, configuration, and report files for the project by **Atharva Dhumal** at the **National College of Ireland**, supervised by **Dr. Mosab Hamdan**.

## 🎯 Objective
To design, implement, and evaluate a Zero Trust Architecture (ZTA) framework for detecting and containing ransomware within a virtualised environment.  
The project uses **open-source security tools** to demonstrate real-time monitoring, least privilege enforcement, and micro-segmentation.

## 🧩 Tools and Technologies
- **Wazuh** – SIEM and rule-based detection  
- **auditd** – Linux kernel auditing and file activity logging  
- **UFW (Uncomplicated Firewall)** – Network micro-segmentation  
- **VirtualBox** – Virtualised lab environment  
- **Python** – Ransomware simulation script  

## 🧪 System Architecture
Two VirtualBox VMs:
1. **Ubuntu 22.04 (Victim Node)** – runs Wazuh, auditd, and UFW  
2. **Kali Linux (Attacker Node)** – executes simulated ransomware attack  

Network: Internal host-only adapter (“ZTA-Net”) for isolation and segmentation.
