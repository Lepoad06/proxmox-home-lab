# Proxmox Home Lab

This repository documents my journey building a full virtualized IT home lab using Proxmox VE on a dedicated Lenovo ThinkPad.  
The goal of this project is to create a realistic environment for learning IT support, Windows Server administration, Linux fundamentals, networking, and troubleshooting — the same skills used in real helpdesk and junior IT roles.

I’m using this lab to practise:
- Active Directory (users, groups, GPOs)
- Windows client troubleshooting
- Linux server administration
- Docker and web services
- Ticketing systems (GLPI)
- Monitoring and dashboards
- Break/fix scenarios
- Documentation and version control

Everything in this repo is written as if I were handing it to another technician.  
Clear steps, screenshots, issues encountered, and what I learned.

---

## 🖥️ Hardware Used
- Lenovo ThinkPad (Ryzen Pro 3700U)
- 16GB RAM
- 500GB SSD
- Wired Ethernet connection
- Proxmox VE 8.x (latest stable release)

This machine acts as my hypervisor and runs all virtual machines for the lab.

---

## 📦 What’s Inside This Repo

### **1. Proxmox Installation**
Step‑by‑step documentation of installing Proxmox VE on the ThinkPad, including:
- BIOS configuration  
- Bootable USB creation  
- Network setup  
- First login  
- Screenshots of the full process  

📄 **Docs:** `docs/proxmox-install.md`  
🖼️ **Images:** `images/`

---

### **2. Virtual Machines**
Each VM has its own documentation folder with:
- Specs  
- Installation steps  
- Configuration  
- Issues encountered  
- What I learned  

Planned VMs include:
- Windows Server 2022 (Domain Controller)
- Windows 10/11 clients
- Ubuntu Server
- Debian Server (Docker)
- GLPI ticketing system
- Monitoring stack (Grafana/Prometheus)

---

## 🎯 Goals of This Lab
- Build real, hands‑on experience for IT Support roles  
- Practise troubleshooting in a safe environment  
- Learn Windows + Linux administration  
- Document everything for my portfolio  
- Prepare for CompTIA A+ and future certifications  

This lab is my “experience” — the same kind of work I’d be doing in a junior IT job.

---

## 📚 Documentation Style
Every project includes:
- Objective  
- Environment  
- Steps taken  
- Screenshots  
- Problems I ran into  
- How I fixed them  
- Final result  
- What I learned  

I’m treating this like real internal IT documentation.

---

## 🚀 What’s Next
- Build Active Directory domain  
- Join Windows clients  
- Create GPOs  
- Deploy Docker services  
- Set up GLPI  
- Add monitoring  
- Create break/fix scenarios  
- Expand the portfolio  

I’ll keep updating this repo as the lab grows.

---

## 🤝 Why I Built This
I’m working toward my first IT Support role, and this home lab is how I’m building the practical skills employers look for.  
If you’re following along or building your own lab, feel free to use this structure as inspiration.
