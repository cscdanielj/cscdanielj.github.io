---
layout: default
title: SOC Lab Documentation
---

<section class="section">
  <div class="container">
    <h2>Home SOC Lab Documentation</h2>
    <p>This guide walks through the process of setting up and configuring my SOC labs, including environment setup, installation, and initial detection testing.</p>

    <!-- Introduction -->
    <h3>1. Lab Overview</h3>
    <p>I built a Security Operations Center (SOC) home lab to practice detection and response. The lab consists of:</p>
    <ul>
      <li>Ubuntu 20.04.6 server running SOC tools</li>
      <li>Windows 10 virtual machine acting as an endpoint</li>
      <li>Host-only and NAT networking for isolation and internet access</li>
    </ul>

    <img src="/assets/img/soc-diagram.png" alt="SOC Lab Diagram" style="max-width: 600px; display: block; margin: 20px auto;">

    <!-- Setup Steps -->
    <h3>2. Environment Setup</h3>
    <p>Steps I followed to prepare the environment:</p>
    <ol>
      <li>Installed VirtualBox / VMware on my host machine.</li>
      <li>Created a new Ubuntu 20.04.6 VM (2 vCPU, 4GB RAM, 40GB disk).</li>
      <li>Created a new Windows 10 VM (2 vCPU, 4GB RAM, 60GB disk).</li>
      <li>Configured networking: one NAT adapter (internet) and one Host-only adapter (lab traffic).</li>
    </ol>

    <img src="/assets/img/vbox-network.png" alt="VirtualBox Network Setup" style="max-width: 600px; display: block; margin: 20px auto;">

    <!-- Ubuntu Configuration -->
    <h3>3. Ubuntu SOC Configuration</h3>
    <p>On the Ubuntu VM, I performed the following:</p>
    <ol>
      <li>Updated packages (<code>sudo apt update && sudo apt upgrade -y</code>)</li>
      <li>Configured static IP address on the host-only adapter</li>
      <li>Prepared system for SOC tools (to be documented as I expand)</li>
    </ol>

    <!-- Windows Configuration -->
    <h3>4. Windows Endpoint Configuration</h3>
    <p>On the Windows 10 VM, I configured:</p>
    <ol>
      <li>Enabled Windows Event Logging.</li>
      <li>Installed updates and hardened system (basic security configs).</li>
      <li>Prepared system for log forwarding and testing alerts.</li>
    </ol>

    <img src="/assets/img/win10-setup.png" alt="Windows 10 Setup" style="max-width: 600px; display: block; margin: 20px auto;">

    <!-- Initial Tests -->
    <h3>5. First Tests</h3>
    <p>After setup, I ran initial checks to ensure traffic flowed between VMs and that logs were being collected:</p>
    <ul>
      <li>Pinged Ubuntu server from Windows endpoint.</li>
      <li>Verified connectivity to the internet and lab subnet.</li>
      <li>Confirmed system logs were being written locally.</li>
    </ul>

    <img src="/assets/img/ping-test.png" alt="Ping Test" style="max-width: 600px; display: block; margin: 20px auto;">

    <!-- Future Work -->
    <h3>6. Next Steps</h3>
    <p>Planned expansions for this lab include:</p>
    <ul>
      <li>Configuring centralized log collection</li>
      <li>Testing alert rules</li>
      <li>Documenting detections with screenshots and case studies</li>
    </ul>
  </div>
</section>
