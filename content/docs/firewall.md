---
title: Firewall Configuration
weight: 4
---

This guide covers the Firewall Configuration for the ProxHome homelab, utilizing pfSense as the primary firewall and router. The firewall sits at the core of the ProxHome network topology and manages traffic between WAN, LAN, and DMZ subnets, as well as access control for services and remote VPN connections via Tailscale.

### Firewall Overview

ProxHome uses **pfSense**, a robust open-source firewall/router software, deployed as a virtual machine inside the Proxmox environment. pfSense handles:

- **Inter-VLAN Routing**
- **NAT and Port Forwarding**
- **Traffic Filtering (Inbound & Outbound)**
- **VPN Gateway via Tailscale**
- **Access Control between LAN, DMZ, and WAN**

### Interface Mapping

| Interface | pfSense Name | Bridge | Subnet | Purpose |
|----------|---------------|--------|--------|---------|
| net0     | WAN           | vmbr0  | 192.168.1.1/24 | External / Internet access |
| net1     | LAN           | vmbr1  | 10.10.1.1/24 | Internal trusted network |
| net2     | DMZ           | vmbr2  | 10.10.200.1/24 | Exposed services network |
