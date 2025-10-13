# Amon Hogue

Network Engineer focused on **automation-first operations** across Cisco and Ubiquiti environments. I turn **intent** (data) into safe, tested configs; detect **drift**; and make changes predictable.

- **Now:** CCNP refresh (ENCOR + ENAUTO); daily Python/Ansible/Nornir
- **Focus:** Catalyst Center & Meraki APIs, **Ubiquiti (UniFi & UISP) automation**, Webex integrations, config parsing/normalization, drift detection, safe change

## What I build
- **Inventory / Source of Truth** — Catalyst Center, Meraki, **UISP/UniFi** → normalized CSV/SQLite
- **Config Parsing & Drift** — running → structured JSON → diff vs goldens → PR/ticket
- **Change Safety Rails** — dry-run diffs, idempotent playbooks, pre/post checks, back-outs
- **QoS triage** — pcap-first (Wireshark) to confirm DSCP/class behavior, then targeted config fixes
- **Webex bots** — approvals, change-window notifications, post-change summaries

## Intent-Based Config Automation (policy-as-data)
- **Base builds**, **IPsec/VPN**, **QoS templates**, **Hardening (routers/switches)**, **Compliance drift**
- Data-driven inputs → Jinja renders → guarded apply via Catalyst Center/SSH

## Ubiquiti automation (UniFi & UISP)
- **UniFi**: site templates (SSIDs, VLANs, switch/AP profiles), zero-touch device adoption, WLAN policy baselines, scheduled backups
- **UISP**: device inventory & status sync, config/firmware baseline checks, alert routing to chat, change logs for field devices
- **Cross-vendor**: normalize UniFi/UISP + Cisco inventories into one SoT for reports and playbooks

## Tooling
Python · Ansible · Nornir · Netmiko/NAPALM · Jinja2 · Pandas  
Cisco **Catalyst Center** & **Meraki** APIs · **Ubiquiti UniFi/UISP** APIs · **Webex** REST/Webhooks  
GitHub Actions · pytest · pre-commit · Wireshark

📁 **Portfolio:** https://github.com/amonhogue/portfolio
