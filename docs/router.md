# Router Setup

## Router Information

Router:
- TP-Link BE500 Wi-Fi 7 Router

---

# Basic Configuration

Configured:

- Wi-Fi network setup
- WPA2/WPA3 wireless security
- Ethernet device connections
- DHCP enabled
- Router admin password changed
- Automatic scheduled router reboot enabled

The router was configured with separate wireless networks to simulate basic network segmentation between trusted devices, IoT devices, and guest devices.

---

# Wireless Networks

## Personal Network
Used for trusted personal devices such as:
- Phones
- Laptops
- Desktop systems

## IoT Network
Used for smart home and IoT devices such as:
- Smart TVs
- Streaming devices
- Smart home equipment

## Guest Network
Used for temporary or guest devices to help isolate external users from the main network.

---

# Ethernet Connected Devices

Current wired devices:

- Desktop PC
- Proxmox Server

Planned future wired devices:

- Apple TV
- MacBook using a Thunderbolt Ethernet adapter

Ethernet was used for important systems to improve:
- Reliability
- Stability
- Network performance
- Lower latency

---

# Security Hardening

Basic router hardening steps included:

- Changing the default admin password
- Configuring WPA2/WPA3 security
- Separating devices into different wireless networks
- Enabling custom DNS filtering
- Disabling unnecessary default settings where applicable

---

# Scheduled Maintenance

Configured the router to automatically reboot on a schedule during late-night hours when devices are inactive.

Purpose:
- Clear temporary memory/cache
- Maintain router stability
- Improve long-term uptime and responsiveness

---

# Goals

- Improve network reliability
- Reduce latency on important devices
- Learn practical network administration
- Gain hands-on troubleshooting experience
- Simulate basic network segmentation concepts
- Build a scalable homelab environment
