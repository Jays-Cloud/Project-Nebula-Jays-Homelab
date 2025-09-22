# 🏠 Jays-Homelab  

## 📖 Overview  
This repository is a central hub for my **home enterprise lab projects**.  
The goal of this homelab is to simulate **enterprise-grade infrastructure** in a home environment while sharpening my skills in **cloud, security, networking, and DevOps**.  

Each major project has its own dedicated folder with detailed documentation, configurations, and lessons learned.  
This README serves as a **high-level overview** of what I’ve completed and what I plan to do next.  

---

## 🛠️ Current Architecture  
- **Hardware:**  
  - Dell Micro Desktop  
  - 2× GMKTec Mini PCs  
  - UniFi UCG-Ultra Gateway  
  - UniFi USW Lite 8 POE Switch  
  - UniFi U6+ AP WiFi 6 POE  
  - Synology DiskStation DS223j  
  - 2TB NAS HDD  

- **Networking:** VLAN segmentation, UniFi switch + firewall rules, WireGuard VPN, Cloudflare Tunnel for secure external access  
- **Virtualization:** Proxmox VE (VMs + containers)  
- **Services/VMs:**  
  - Active Directory Domain Controller  
  - Intune device management  
  - Kali Linux (offensive security testing & pentesting tools)  
  - NAS file services  
  - Veeam Backup & Replication (backup management for infrastructure + data)  
  - Cloudflare Access (SSO-protected external access to NAS + lab services)
  - - Azure Tenant (cloud identity, policy, and security baseline configuration)  
- **Monitoring (Planned):** Security Onion, SIEM (Splunk/Sentinel)  

---

## ✅ Completed Projects  
- **WireGuard VPN** → Remote access VPN via UniFi firewall with secure client configs.  
- **Active Directory Domain Services** → Domain controller, DNS configuration.  
- **NAS Integration** → Centralized storage across VLANs using Synology DiskStation.  
- **VLAN Segmentation** → Isolated IoT, Servers, Management, and VPN networks with firewall rules.  
- **Rack Assembly** → Designed and assembled a mini-rack, neatly wiring and powering lab gear for efficient organization and accessibility.  
- **Intune Device Management** → Enrolled and secured endpoints with Microsoft Intune for centralized compliance and policy enforcement.  
- **Kali Linux VM** → Deployed a Kali Linux VM in on my main PC via Oracle Virtual Box for penetration testing, vulnerability scanning, and red-team style security exercises.  
- **Cloudflare Tunnel + SSO** → Implemented Cloudflare Tunnel to securely expose internal services (e.g., NAS, Proxmox UI). Configured Cloudflare Access with Single Sign-On (SSO), allowing secure login to the NAS outside the home network via custom DNS without exposing firewall ports.  
- **Azure Tenant Configuration** → Deployed and configured a Microsoft Azure tenant, including Entra ID setup, and preparation for hybrid identity integration with on-premises AD.

---

## 🚧 In Progress / Planned  
- **Security Onion** → Deploying IDS/IPS and log analysis for threat visibility across VLANs.
- **AD DS Configuration** → Configure Group Policy for centralized authentication and policy enforcement 
- **Proxmox Deployment** → Running Home Assistant, pfSense, containers, and ADGuard on Proxmox VE.  
- **Veeam Backups** → Expanding backup strategy to protect infrastructure and lab data using Veeam.  
- **Hybrid Identity** → Configuring Azure AD Connect for hybrid on-premises + cloud identity integration.  

--- 
