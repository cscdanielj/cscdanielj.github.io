---
layout: default
title: Windows 10 VM Lab
---

<section class="section">
  <div class="container">
    <h2>Windows 10 VM Lab</h2>
    <p>Step-by-step guide for configuring my Windows 10 endpoint lab.</p>

    <div class="grid">
      <article class="card">
        <div class="body">
          <h3>1 — Create the VM</h3>
          <p>Configured a new Windows 10 Pro VM in VirtualBox:</p>
          <ul>
            <li>2 vCPU, 4GB RAM, 60GB disk</li>
            <li>Networking: NAT + Host-only adapter</li>
          </ul>
          <img src="/assets/img/win10-vm-settings.png" alt="Windows VM Settings" style="max-width:100%; border-radius:8px; margin-top:10px;">
        </div>
      </article>

      <article class="card">
        <div class="body">
          <h3>2 — System Prep</h3>
          <p>After install, updated Windows and enabled Event Viewer logs.</p>
          <img src="/assets/img/win10-eventviewer.png" alt="Windows Event Viewer" style="max-width:100%; border-radius:8px; margin-top:10px;">
        </div>
      </article>

      <article class="card">
        <div class="body">
          <h3>3 — Networking Test</h3>
          <p>Verified network connection to Ubuntu VM (ping test).</p>
          <img src="/assets/img/ping-win10.png" alt="Ping Test Windows" style="max-width:100%; border-radius:8px; margin-top:10px;">
        </div>
      </article>
    </div>
  </div>
</section>
