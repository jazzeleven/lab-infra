# Homelab Infrastructure — Technical Documentation 

This repository documents a multi-environment virtualised lab for learning systems administration, networking, and security operations. 

--- 
## Environments 

### Proxmox VE Host (Dedicated Server) 
- **Hardware:** Sony workstation, AMD E-450 APU, 8 GB RAM, 596 GB HDD SATA 
- **Hypervisor:** Proxmox VE 9.0.11
- **Purpose:** Production-like virtualisation with VLAN segmentation 
- **Current VMs:** 2

### VirtualBox Laboratory 
- **Hardware:** Desktop PC, AMD Ryzen 7, 32 GB RAM, 512 GB SSD NVMe
- **Hypervisor:** Oracle VirtualBox 7.x 
- **Purpose:** Isolated sandbox for Active Directory and security testing 
- **VMs:** Windows Server 2025 DC & Client workstations, OSINT investigation VM, forensic analysis VM 

### Raspberry Pi (Home Automation) 
- **Model:** Raspberry Pi 4 Model B, 4 GB RAM, 32 GB microSD 
- **Runtime:** Docker Engine, Docker Compose 
- **Services:** Pi-hole, Home Assistant, n8n

- --- 
## Network Topology

...

---

*Last updated: October 2026*