---
title: ProxLink
layout: hextra-home
---

{{< hextra/hero-badge >}}
  <div class="hx-w-2 hx-h-2 hx-rounded-full hx-bg-primary-400"></div>
  <span>Version: 0.7.0</span>
  {{< icon name="arrow-circle-right" attributes="height=14" >}}
{{< /hextra/hero-badge >}}

<div class="hx-mt-6 hx-mb-6">
{{< hextra/hero-headline >}}
  Welcome to ProxHome!
{{< /hextra/hero-headline >}}
</div>

<div class="hx-mb-12">
{{< hextra/hero-subtitle >}}
  Creating HomeLab using Proxmox Hypervisor
{{< /hextra/hero-subtitle >}}
</div>


<div class="hx-mb-6">
{{< hextra/hero-button text="Documentation" link="/docs/introduction/" >}}
</div>

<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6"></div>

{{< hextra/feature-grid >}}
  {{< hextra/feature-card
    title="Proxmox"
    icon="server"
    subtitle="Experience simplified deployment, management, and orchestration of virtual machines using Proxmox. It offers a powerful web-based interface and full support for containers and virtual machines. Maintain flexibility and performance without adding complexity to your infrastructure."
  >}}
  {{< hextra/feature-card
    title="PfSense"
    icon="shield-check"
    subtitle="Securely manage your homelab network with PfSense, a powerful open-source firewall and routing platform. It features advanced firewall rules, traffic shaping, and intrusion detection. Seamlessly integrate VPNs and multi-WAN setups for enhanced control and reliability."
  >}}
  {{< hextra/feature-card
    title="TailScale"
    icon="globe-alt"
    subtitle="Access your homelab from anywhere using Tailscale’s secure mesh VPN built on WireGuard. It enables full-tunnel connections without exposing your services to the public internet. Setup is fast, requires no port forwarding, and scales effortlessly across devices."
  >}}
  {{< hextra/feature-card
    title="ELK Stack (In-progress)"
    icon="binoculars"
    subtitle="Centralize log and metric collection with the ELK Stack — Elasticsearch, Logstash, and Kibana. Gain observability across services using dashboards, filters, and alerts. Extend visibility using Beats, APM agents, and custom pipeline integrations."
  >}}
  {{< hextra/feature-card
    title="TrueNAS (In-progress)"
    icon="database"
    subtitle="Expand your homelab’s storage capacity with TrueNAS, a powerful network-attached storage (NAS) solution. It provides data redundancy, ZFS snapshots, and advanced sharing protocols like SMB and NFS. Scale storage reliably while maintaining performance and data integrity."
  >}}
  {{< hextra/feature-card
    title="And Much More..."
    icon="sparkles"
    subtitle="Unlock even greater potential in your homelab with automation scripts, powerful monitoring tools, and advanced integrations. Customize every component to suit your exact needs. Backed by detailed documentation and a modular setup, your environment evolves as you do."
  >}}
{{< /hextra/feature-grid >}}