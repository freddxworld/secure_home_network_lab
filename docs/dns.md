# DNS Setup

## Overview

Configured custom DNS filtering on the home network by replacing the default ISP DNS servers with NextDNS. The DNS configuration was implemented through the router’s DHCP settings so all connected devices on the network would automatically use the custom DNS service.

The goal of this setup was to improve security, privacy, content filtering, and overall control over network traffic while gaining hands-on experience with DNS administration.

---

# DNS Provider

DNS Service:
- NextDNS

NextDNS was selected because it provides:
- DNS-based filtering
- Malware protection
- Ad and tracker blocking
- Custom filtering rules
- Device-level policies
- Usage analytics and logging

Future plans may include experimenting with more advanced DNS and self-hosted solutions.

---

# Router Configuration

The DNS servers were manually configured through the router DHCP settings to override the default ISP-provided DNS servers.

This allows devices connected to the network to automatically use the custom DNS configuration without requiring manual setup on every device.

---

# Security & Filtering Features

Configured features include:

- Malware blocking
- Ad blocking
- Tracker blocking
- Safer browsing protections
- Content filtering
- Custom scheduled blocking rules

---

# Social Media Scheduling

Certain social media platforms are blocked during specific times of the day using DNS filtering rules.

Example:
- Instagram access restricted during scheduled hours

This was implemented to:
- Reduce distractions
- Improve productivity
- Learn practical DNS policy management

---

# Permanent Content Filtering

Inappropriate or unsafe websites are blocked 24/7 through DNS filtering policies in addition to the default security protections provided by NextDNS.

This setup helps reduce exposure to:
- Malicious domains
- Unsafe content
- Suspicious websites
- Tracking services

---

# Notes

Some devices may temporarily continue showing ISP DNS servers due to:
- Cached DNS entries
- Device-specific DNS behavior
- IPv6 DNS settings
- Browser secure DNS configurations

Troubleshooting steps included:
- Flushing DNS cache
- Restarting devices
- Rebooting the router
- Verifying DHCP-assigned DNS settings

---

# Goals

- Learn practical DNS administration
- Improve network security
- Gain experience with content filtering
- Understand DHCP and DNS interactions
- Improve privacy and network control
- Build foundational cybersecurity skills
