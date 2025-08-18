---
layout: default
title: Home
---

<section class="hero">
  <div class="container hero-grid">
    <div>
      <div class="kicker">CYBER DEFENSE PORTFOLIO</div>
      <h1>Jason Daniel — SOC / Blue Team</h1>
      <p>I build compact, realistic SOC labs and document detections and investigations so others can repeat them.</p>
      <div class="cta-group">
        <a class="btn btn-primary" href="#projects">View Projects</a>
        <a class="btn btn-outline" href="./resume/Jason-Daniel-Resume.pdf">Download Resume</a>
      </div>
    </div>

    <div class="panel">
      <strong>Focus areas</strong>
      <ul>
        <li>Collect → Detect → Investigate in a home SOC</li>
        <li>Windows telemetry (Sysmon, Winlogbeat), network IDS (Suricata)</li>
        <li>Writing detections and reducing false positives</li>
      </ul>
      <strong>Stack</strong>
      <div class="tags">
        <span class="tag">Ubuntu 20.04.6</span>
        <span class="tag">Wazuh</span>
        <span class="tag">Suricata</span>
        <span class="tag">Sysmon</span>
        <span class="tag">Winlogbeat</span>
        <span class="tag">Docker</span>
      </div>
    </div>
  </div>
</section>

<section id="projects" class="section">
  <div class="container">
    <h2>Projects</h2>
    <div class="grid">

      <!-- Project 1 -->
      <article class="card">
        <div class="thumb">
          <!-- Replace with /assets/img/soc-thumb.png if you add one -->
          SOC · WAZUH · SURICATA
        </div>
        <div class="body">
          <h3>Project 1 — Ubuntu SOC Lab</h3>
          <p>Wazuh SIEM + Suricata IDS on Ubuntu 20.04.6. Host-only network, log collection, alerts, and a short incident walkthrough.</p>
          <div class="tags">
            <span class="tag">SIEM</span><span class="tag">IDS</span><span class="tag">Docker</span>
          </div>
          <div class="actions">
            <a class="btn btn-primary" href="https://github.com/cscdanielj/homelab-ubuntu-soc">Open Repo</a>
          </div>
        </div>
      </article>

      <!-- Project 2 -->
      <article class="card">
        <div class="thumb">
          <!-- Replace with /assets/img/win10-thumb.png if you add one -->
          WINDOWS · SYSMON
        </div>
        <div class="body">
          <h3>Project 2 — Windows 10 Endpoint Lab</h3>
          <p>Sysmon + Winlogbeat forwarding to the SOC. Validates detections with safe artifacts and shows query/alert screenshots.</p>
          <div class="tags">
            <span class="tag">Sysmon</span><span class="tag">Winlogbeat</span><span class="tag">Detection</span>
          </div>
          <div class="actions">
            <a class="btn btn-primary" href="https://github.com/cscdanielj/homelab-windows10-vm">Open Repo</a>
          </div>
        </div>
      </article>

      <!-- Future projects (optional, keeps the grid balanced) -->
      <article class="card">
        <div class="thumb">NMAP · DISCOVERY</div>
        <div class="body">
          <h3>Project 3 — Network Scanning (Nmap)</h3>
          <p>(Planned) Port and service discovery; baseline mapping for your lab network.</p>
          <div class="tags"><span class="tag">Nmap</span><span class="tag">Networking</span></div>
        </div>
      </article>

      <article class="card">
        <div class="thumb">BURP · WEB SEC</div>
        <div class="body">
          <h3>Project 4 — Web Vuln Scanning (Burp)</h3>
          <p>(Planned) Hands-on practice with interception, spidering, and reporting.</p>
          <div class="tags"><span class="tag">Burp Suite</span><span class="tag">AppSec</span></div>
        </div>
      </article>

    </div>
  </div>
</section>

<section id="skills" class="section">
  <div class="container split">
    <div class="box">
      <h2>Skills</h2>
      <p><strong>Platforms:</strong> Ubuntu Server, Windows 10<br>
      <strong>SOC stack:</strong> Wazuh, Suricata, Elastic/Beats<br>
      <strong>Endpoint:</strong> Sysmon, Winlogbeat<br>
      <strong>Networking:</strong> NAT/Host-only, packet capture, log shipping<br>
      <strong>Scripting:</strong> Bash, PowerShell</p>
    </div>
    <div class="box" id="about">
      <h2>About Me</h2>
      <ul>
        <li>I build SOC home labs to practice log collection, detection, and incident response.</li>
        <li>Hands-on with Wazuh, Suricata, Sysmon, and Winlogbeat.</li>
        <li>Goal: start in a SOC role and grow into detection engineering/threat hunting.</li>
      </ul>
    </div>
  </div>
</section>

<section class="section">
  <div class="container">
    <h2>Resume</h2>
    <p><a class="btn btn-outline" href="./resume/Jason-Daniel-Resume.pdf">Download PDF</a></p>
  </div>
</section>
