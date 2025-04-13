# 🏡 My Homelab Network Setup (2025)

Welcome to a breakdown of my first homelab project! This repo documents the process I went through to revive a used Netgear M4100-26G managed switch, fix network segmentation issues, and lay the foundation for future home server projects like Plex.

---

## 🔧 Project Summary

I started with a second-hand Netgear managed switch that wasn't showing up on my network. After some troubleshooting, here's what I did:

- Discovered the switch's static IP using **Advanced IP Scanner**
- Realized my router was on a different subnet (`10.0.0.1`) while the switch was on (`192.168.0.2`)
- Reconfigured my home router to be on the `192.168.0.x` subnet to match the switch
- Successfully accessed the switch's GUI and began configuring VLANs and ports

---

## 🛠️ Hardware Used

- Netgear Managed Switch (used)
- Basic home router (now on `192.168.0.1`)
- Custom-built Windows PC
- Ethernet cables (hand-crimped myself!)
- Patch panel for better cable management

---

## 🧰 Skills Learned

- Network troubleshooting and IP discovery  
- Subnet logic and device isolation issues  
- Static IP configuration on both routers and switches  
- Using tools like **Advanced IP Scanner**  
- Crimping Ethernet cables and setting up a patch panel  
- Planning for future integrations (Plex server, homelab services)

---

## 📺 What's Next

I'm planning to:

- Build a Plex server and integrate it with this new network
- Add a storage server and possibly run Docker or Proxmox
- Try setting up VLANs to segment media, IoT, and admin traffic
- Expand monitoring and automation tools (maybe with Grafana or Pi-hole)

---

## 💬 Why I’m Sharing This

I’m documenting my homelab journey to:

- Help others getting started with used hardware
- Track my own progress and learning

---
