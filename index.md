---
layout: default
title: Home
---

<section class="hero">
  <div class="container hero-grid">
    <div>
      <div class="kicker">CYBER DEFENSE PORTFOLIO</div>
      <h1>Jason Daniel</h1>
      <h3>Aspiring Cybersecurity Defense Professional</h3>
      <p>I build compact, realistic SOC labs and document detections and investigations so others can repeat them.</p>
      <div class="cta-group">
        <a class="btn btn-primary" href="#projects">View Projects</a>
        <a class="btn btn-outline" href="/resume/Jason-Daniel-Resume.pdf">Download Resume</a>
      </div>
    </div>
  
   <div class="panel" style="text-align:center;">
  <img src="/assets/img/img-defense.png" 
       alt="Jason Daniel Cyber Portfolio" 
       style="max-width: 260px; border-radius: 12px; box-shadow: 0 0 18px rgba(0,229,255,.4);">
</div>

  </div>
</section>

<section id="projects" class="section">
  <div class="container">
    <h2>Projects</h2>
    <div class="grid">

      <!-- Finished Project -->
      <article class="card">
        <div class="thumb">
          <!-- Replace with /assets/img/soc-thumb.png if you add one -->
          SOC · WAZUH · SURICATA
        </div>
        <div class="body">
          <h3>Project 1 — Home SOC Lab (Finished)</h3>
          <p>Wazuh SIEM + Suricata IDS on Ubuntu 20.04.6. Host-only network, log collection, alerts, and a short incident walkthrough.</p>
          <div class="tags">
            <span class="tag">SIEM</span><span class="tag">IDS</span><span class="tag">Docker</span>
          </div>
          <div class="actions">
            <a class="btn btn-primary" href="https://github.com/cscdanielj/homelab-ubuntu-soc">Open Repo</a>
          </div>
        </div>
      </article>

      <!-- Future Projects Section (WIP cards) -->
      <article class="card">
        <div class="thumb">WINDOWS · SYSMON</div>
        <div class="body">
          <h3>Windows 10 Endpoint Lab (Work in Progress)</h3>
          <p>Planned: Sysmon + Winlogbeat forwarding to the SOC. Goal: endpoint visibility, log shipping, benign alert validation.</p>
          <div class="tags">
            <span class="tag">Sysmon</span><span class="tag">Winlogbeat</span><span class="tag">Detection</span>
          </div>
        </div>
      </article>

      <article class="card">
        <div class="thumb">NMAP · DISCOVERY</div>
        <div class="body">
          <h3>Network Scanning with Nmap (Planned)</h3>
          <p>Port/service discovery and baseline mapping for the home lab network.</p>
          <div class="tags"><span class="tag">Nmap</span><span class="tag">Networking</span></div>
        </div>
      </article>

      <article class="card">
        <div class="thumb">BURP · WEB SEC</div>
        <div class="body">
          <h3>Web Vulnerability Testing with Burp Suite (Planned)</h3>
          <p>Interception proxy, spidering, and reporting for common web flaws.</p>
          <div class="tags"><span class="tag">Burp Suite</span><span class="tag">AppSec</span></div>
        </div>
      </article>

      <article class="card">
        <div class="thumb">WIRESHARK · PCAP</div>
        <div class="body">
          <h3>Packet Analysis with Wireshark (Planned)</h3>
          <p>Traffic capture and analysis for anomaly detection and troubleshooting.</p>
          <div class="tags"><span class="tag">Wireshark</span><span class="tag">PCAP</span></div>
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
    <p><a class="btn btn-outline" href="/resume/Jason-Daniel-Resume.pdf">Download PDF</a></p>
  </div>
</section>
