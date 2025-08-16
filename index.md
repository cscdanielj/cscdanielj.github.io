---
layout: default
title: Home
---

# Jason Daniel
**SOC / Blue Team Portfolio**

I build small, realistic home labs and document what I learn so others can repeat it.

[GitHub](https://github.com/cscdanielj) · [LinkedIn](https://www.linkedin.com/in/jason-daniel-067236346/) · [Email](mailto:your.email@example.com)

---

## Skills
**Platforms:** Ubuntu Server, Windows 10  
**SOC stack:** Wazuh, Suricata, Elastic/Beats  
**Endpoint:** Sysmon, Winlogbeat  
**Networking:** NAT/Host-only, packet capture, log shipping  
**Scripting:** Bash, PowerShell

<p class="badges">
  <img alt="Ubuntu" src="https://img.shields.io/badge/Ubuntu-20.04.6-orange" />
  <img alt="Wazuh" src="https://img.shields.io/badge/Wazuh-SIEM-blue" />
  <img alt="Suricata" src="https://img.shields.io/badge/Suricata-IDS-red" />
  <img alt="Sysmon" src="https://img.shields.io/badge/Sysmon-Endpoint-purple" />
  <img alt="Winlogbeat" src="https://img.shields.io/badge/Beats-Winlogbeat-lightgrey" />
</p>

---

## Labs {#labs}

<div class="card">
<h3>Ubuntu SOC Lab — Wazuh + Suricata</h3>
Deploy Wazuh all-in-one on Ubuntu 20.04.6 with optional Suricata monitoring a host-only network.
<br><br>
<strong>Repo:</strong> <a href="https://github.com/cscdanielj/homelab-ubuntu-soc">homelab-ubuntu-soc</a><br>
<strong>Highlights:</strong> SIEM deployment, IDS tuning, Docker, network segmentation<br>
<strong>Proof:</strong> Wazuh alert screenshots, Suricata events, detection writeup
</div>

<div class="card">
<h3>Windows 10 Endpoint Lab — Sysmon + Winlogbeat</h3>
Harden a Windows 10 VM, install Sysmon with a curated config, ship logs via Winlogbeat.
<br><br>
<strong>Repo:</strong> <a href="https://github.com/cscdanielj/homelab-windows10-vm">homelab-windows10-vm</a><br>
<strong>Highlights:</strong> Sysmon mapping, log shipping, query logic, alerting<br>
<strong>Proof:</strong> Query snippets + alert screenshots
</div>

---

## Writeups {#writeups}
- Tuning Suricata HOME_NET — reducing noise while keeping coverage  
- Suspicious PowerShell — command-line patterns to watch  
- Sysmon 101 — events I actually use for triage

*(Add these as Markdown files later in `/writeups` or in lab repos and link them here.)*

---

## Resume {#resume}
- **PDF:** [Download](./resume/Jason-Daniel-Resume.pdf)

---

## Certifications
See the dedicated page: [Certifications](/certifications/)
