---
layout: default
title: Ubuntu VM Lab
---

<section class="section">
  <div class="container">
    <h2>Ubuntu VM Lab</h2>
    <p>Step-by-step guide for building the Ubuntu side of my Home SOC Lab Setup.</p>

    <div class="grid">
      <article class="card">
        <div class="body">
          <h3>1 — Create the VM</h3>
          <p>Configured a new Ubuntu 20.04.6 LTS VM in VirtualBox:</p>
          <ul>
            <li>2 vCPU, 4GB RAM, 40GB disk</li>
            <li>Networking: NAT + Host-only adapter</li>
          </ul>
          <img src="/assets/img/ubuntu-vm-settings.png" alt="Ubuntu VM Settings" style="max-width:100%; border-radius:8px; margin-top:10px;">
        </div>
      </article>

      <article class="card">
        <div class="body">
          <h3>2 — Update & Prepare</h3>
          <pre><code>sudo apt update && sudo apt upgrade -y
sudo apt install curl git ufw -y
          </code></pre>
          <img src="/assets/img/ubuntu-update.png" alt="Ubuntu Update" style="max-width:100%; border-radius:8px; margin-top:10px;">
        </div>
      </article>

      <article class="card">
        <div class="body">
          <h3>3 — Networking Test</h3>
          <p>Ensured connectivity between Windows VM and Ubuntu server via <code>ping</code>.</p>
          <img src="/assets/img/ping-ubuntu.png" alt="Ping Test Ubuntu" style="max-width:100%; border-radius:8px; margin-top:10px;">
        </div>
      </article>
    </div>
  </div>
</section>
