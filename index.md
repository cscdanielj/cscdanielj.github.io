---
layout: default
---

<div align="center">

# Jason Daniel  
**SOC / Blue Team Portfolio**

I build small, realistic home labs and document what I learn so others can repeat it.

[Portfolio Repo](https://github.com/cscdanielj) · [LinkedIn](https://www.linkedin.com/in/jason-daniel-067236346/) · [Email](mailto:your.email@example.com)

</div>

---

## Quick links
- 🧰 **Ubuntu SOC Lab** → <https://github.com/cscdanielj/homelab-ubuntu-soc>
- 🖥️ **Windows 10 Endpoint Lab** → <https://github.com/cscdanielj/homelab-windows10-vm>
- 🧪 **Detection Notes** → <https://github.com/cscdanielj/detection-notes>

---

## Skills snapshot
**Platforms:** Ubuntu Server, Windows 10  
**SOC stack:** Wazuh, Suricata, Elastic/Beats  
**Endpoint:** Sysmon, Winlogbeat  
**Networking:** NAT / Host-only lab networks, packet capture, log shipping  
**Scripting:** Bash, PowerShell (task focused)

<p>
  <img alt="Ubuntu" src="https://img.shields.io/badge/Ubuntu-20.04.6-orange" />
  <img alt="Wazuh" src="https://img.shields.io/badge/Wazuh-SIEM-blue" />
  <img alt="Suricata" src="https://img.shields.io/badge/Suricata-IDS-red" />
  <img alt="Sysmon" src="https://img.shields.io/badge/Sysmon-Endpoint-purple" />
  <img alt="Winlogbeat" src="https://img.shields.io/badge/Beats-Winlogbeat-lightgrey" />
</p>

---

## Projects {#projects}

### Ubuntu SOC Lab — *Wazuh + Suricata*
Deploy **Wazuh all-in-one** on Ubuntu 20.04.6 LTS. Optional **Suricata IDS** monitors a host-only network. Includes screenshots, configs, and a short incident walkthrough.

- **Repo:** <https://github.com/cscdanielj/homelab-ubuntu-soc>
- **Highlights:** SIEM deployment, IDS tuning, Docker, network segmentation
- **Proof:** Wazuh alert screenshots, Suricata events, detection writeup

---

### Windows 10 Endpoint Lab — *Sysmon + Winlogbeat*
Harden a Windows 10 VM, install **Sysmon** with a curated config, and ship logs via **Winlogbeat** to the SOC. Validate with benign test artifacts (EICAR, LOLBAS examples).

- **Repo:** <https://github.com/cscdanielj/homelab-windows10-vm>
- **Highlights:** Sysmon mapping, log shipping, KQL/ELS queries, alerting
- **Proof:** Query snippets + alert screenshots

---

### Detection Notes (optional but recommended)
Lightweight repo where I keep search queries, rule ideas, tuning notes, and links to related screenshots/JSON.

- **Repo:** <https://github.com/cscdanielj/detection-notes>
- **Highlights:** Iterative learning, false-positive tuning, rule hygiene

---

## Writeups {#writeups}
Short blog-style notes you can read in 3–5 minutes.

- **Tuning Suricata HOME_NET** — reducing noise while keeping coverage
- **Suspicious PowerShell** — command-line patterns to watch
- **Sysmon 101** — events I actually use for triage

---

## Resume {#resume}
- **PDF:** [Download](./resume/Jason-Daniel-Resume.pdf)  
- Keep a plaintext copy in the repo too: `resume/README.md`

---

## Contact
- **LinkedIn:** <https://www.linkedin.com/in/jason-daniel-067236346/>
- **Email:** your.email@example.com
- **Location:** Ocean Springs, MS

<br/>

<div align="center">
  <sub>© {{ site.author }} · Built with GitHub Pages</sub>
</div>
