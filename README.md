# secure_home_network_lab

## Overview

This project documents the setup and configuration of my home network lab focused on networking, DNS filtering, virtualization, and overall infrastructure management. The goal of this lab is to gain hands-on experience with real-world networking and cybersecurity concepts while building a reliable and scalable home network environment.

This lab also serves as a foundation for future projects involving virtualization, monitoring, network security, and self-hosted services.

---

# Goals

- Learn practical networking concepts
- Configure and manage a home network
- Implement custom DNS filtering
- Improve network reliability and performance
- Gain hands-on troubleshooting experience
- Document infrastructure and configurations
- Prepare for future cybersecurity and homelab projects

---

# Hardware Used

## Router
- TP-Link BE500 Wi-Fi 7 Router

## Systems & Devices
- Desktop PC
- MacBook
- iPhone
- Apple TV
- Proxmox Server

---

# Technologies & Concepts

- Router Administration
- DNS Filtering
- DHCP
- NAT
- IP Addressing
- Ethernet Networking
- Wi-Fi Networking
- Linux Administration
- SSH
- Proxmox Virtualization
- Network Troubleshooting

---

# DNS Configuration

The network uses custom DNS filtering to improve security, privacy, and overall control over network traffic.

Features include:

- Malware blocking
- Ad and tracker blocking
- Device-level filtering
- Safer web browsing
- Productivity-focused filtering

---

# Current Network Topology

```text
Internet
   │
ISP Modem
   │
Main Router
   ├── Wi-Fi Devices
   │   ├── Phones
   │   ├── Laptops
   │   └── Smart Home Devices
   │
   ├── Desktop PC        [Ethernet]
   ├── Proxmox Server    [Ethernet]
   └── Apple TV          [Ethernet - Planned]
```

The current setup uses the main router for wireless devices while important systems such as the desktop PC and Proxmox server are connected through Ethernet for improved reliability and performance.

Future plans include expanding Ethernet connectivity to additional devices such as the Apple TV and MacBook through a Thunderbolt Ethernet adapter.

---

# Project Documentation

## Documentation
- `docs/router-setup.md`
- `docs/dns-setup.md`
- `docs/network-notes.md`

## Screenshots
Router settings, DNS dashboards, and future configuration screenshots are stored in the `screenshots/` directory.

## Diagrams
Network topology diagrams and infrastructure drawings are stored in the `diagrams/` directory.

---

# Skills Demonstrated

- Network configuration
- Router administration
- DNS management
- Infrastructure documentation
- Linux networking
- Virtualization fundamentals
- Troubleshooting
- Ethernet deployment
- Home network optimization

---

# Future Improvements

- Add Ethernet connection for Apple TV
- Add Ethernet adapter for MacBook
- Expand Proxmox virtualization environment
- Implement network monitoring tools
- Configure firewall and advanced security rules
- Self-host additional services
- Explore VLAN segmentation
- Deploy centralized logging and monitoring

---

# Why I Built This

I built this lab to gain practical hands-on experience with networking, infrastructure, and cybersecurity concepts outside of a classroom environment. This project allows me to continuously improve my technical skills while documenting real-world troubleshooting and system administration experience.

```
