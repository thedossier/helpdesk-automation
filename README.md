# 🧩 Helpdesk Automation

A collection of PowerShell and Python scripts designed to streamline common IT support workflows.  
This project simulates real-world Help Desk scenarios such as service restarts, system diagnostics, and user ticket tracking.

---

### 🧰 Features
- Automated collection of system and network information  
- Service restart scripts (e.g., Print Spooler recovery)  
- Ticket logging and resolution tracking  
- Example troubleshooting documentation with screenshots

---

### 💡 Skills Demonstrated
- Windows administration and troubleshooting  
- PowerShell scripting for repetitive Help Desk tasks  
- Problem documentation and escalation workflows  
- Git version control for script management

---

### 📂 Example Files
- `restart-spooler.ps1` – Restart and log Windows Print Spooler service  
- `collect-system-info.ps1` – Gather key system information for triage  
- `ticket_log.csv` – Sample Help Desk ticket queue  
- `helpdesk-readme.md` – Detailed runbook and instructions

---

### 🧾 Project Summary
This lab will mirror a real Help Desk workflow: from identifying user issues, documenting tickets, and resolving system problems through automation scripts.  
It will demonstrate practical troubleshooting and communication skills valuable in entry-level IT support roles.

---

## 🧱 Virtualization Environment

This lab is fully virtualized to simulate a real-world IT environment.

**Platform:** VirtualBox (or VMware Workstation / Hyper-V)  
**Topology:**
- 🖥️ Windows Server (Domain Controller / File Server)
- 💻 Windows 10 Client(s)
- 🧰 Security Tools VM (Kali Linux, Wazuh, Security Onion, etc.)
- 🌐 pfSense (firewall + router)

**Networking:**  
- Internal NAT network for internet access  
- Host-only network for isolated lab traffic  
- Static IP addressing for critical systems  

This setup demonstrates understanding of:
- Virtual networking & isolation
- Resource allocation (CPU, memory, storage)
- Snapshot management
- System provisioning and configuration in a virtual environment

---
