---
title: Introduction
weight: 1
next: /docs/installation
prev: /docs
---

Welcome to my ProxHome HomeLab Documentation!

## What is ProxHome?

ProxHome is my approach to tinker with technology and building a versatile home lab using open-source technologies like Proxmox, pfSense, Tailscale, ELK stack and TrueNAS. It enables me to test my knowledge and hone it in a controlled and secure environment keeping my coureswork and imporant data isolated from the stuff I am working on, enabling me to experiment with virtualized environments, networking strategies, and software integrations securely and conveniently at home.


## Network Topology
![Network](/images/ProxHome.png)

## Configuration
{{< cards >}}
  {{< card link="/docs/hardware/" title="Hardware Configuration" icon="chip" subtitle="Overview of the hardware powering the ProxHome." >}}
  {{< card link="/docs/network/" title="Network Configuration" icon="globe-alt" subtitle="Managing virtual networks within Proxmox." >}}
  {{< card link="/docs/firewall/" title="Firewall Configuration" icon="shield-check" subtitle="Securing the network using pfSense firewall rules." >}}
  {{< card link="/docs/vpn/" title="VPN Configuration" icon="lock-closed" subtitle="Enabling remote access through Tailscale VPN." >}}
{{< /cards >}}

## Features

- **Powerful Virtualization** – ProxHome leverages Proxmox VE's a purpose built hypervisor with an intuitive web interface to efficiently manage virtual machines and containers, ensuring flexibility and scalability.

- **Robust Network Security** – The lab integrates pfSense firewall/router capabilities, delivering advanced security features, VPN connectivity, and comprehensive network monitoring.

- **Seamless Remote Access** – TailScale provides secure, reliable remote connectivity within the lab environment, with minimal setup and low-maintenance operation.

- **Observability** - ELK stack works as a centralized monitoring system which collect logs, and metrics from machines in DMZ, and LAN. This helps monitor and manage resources in a efficient way (In-progress)

- **Reliable Storage Management** – TrueNAS is used for data organization, advanced snapshotting, redundancy, and secure file-sharing, enhancing overall data resilience. (In-Progress)

- **Extensible and Customizable** – ProxHome offers extensibility through scripting, automation, thorough documentation, Configuration as a Code and powerful integrations, allowing flexible customization.

- **Optimized for Learning and Growth** – The project is structured to provide a practical, accessible learning environment suitable for all skill levels, from beginners to experienced IT professionals.

## Questions or Feedback?

{{< callout type="warning" >}}
  ProxHome is still in **active** development. Questions/Suggestions: [open an issue](https://github.com/arbaaz29/ProxHome)
{{< /callout >}}