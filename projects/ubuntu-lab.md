---
layout: default
title: Ubuntu VM Lab
permalink: /projects/ubuntu-lab.html
---

# 🐧 Ubuntu VM Lab

This guide walks through setting up an **Ubuntu 20.04.6 virtual machine** in Oracle VirtualBox to be used as part of a home SOC lab.  
Each step includes notes and placeholders for screenshots you will upload later.

---

## Step 1: Download Ubuntu ISO
Download the official Ubuntu 20.04.6 ISO from the Ubuntu website.  
[Ubuntu ISO Download](https://releases.ubuntu.com/20.04/)

📸 *Screenshot Placeholder*  
<img src="../screenshots/ubuntu/step1-download.png" alt="Ubuntu ISO Download" width="70%">

---

## Step 2: Create New VM
Launch Oracle VirtualBox Manager and click **New** to create a virtual machine.

📸 *Screenshot Placeholder — Launch New VM*  
<img src="../screenshots/ubuntu/step2-new-vm.png" alt="New VM Creation" width="70%">

Follow along with the VM setup wizard (3 screenshots will be included here).  

📸 *Screenshot Placeholder — VM Setup 1*  
<img src="../screenshots/ubuntu/step2-vm-setup1.png" alt="VM Setup Step 1" width="70%">

📸 *Screenshot Placeholder — VM Setup 2*  
<img src="../screenshots/ubuntu/step2-vm-setup2.png" alt="VM Setup Step 2" width="70%">

📸 *Screenshot Placeholder — VM Setup 3*  
<img src="../screenshots/ubuntu/step2-vm-setup3.png" alt="VM Setup Step 3" width="70%">

---

## Step 3: Network Settings
Select the Ubuntu VM’s **Settings → Network**.  
Configure the following network settings (1 screenshot will be included here).

📸 *Screenshot Placeholder — Network Settings*  
<img src="../screenshots/ubuntu/step3-network.png" alt="Network Settings" width="70%">

---

## Step 4: Installing Ubuntu on VM
1. Launch the Ubuntu VM.  
2. Follow through the Ubuntu installation process.  
3. Use the following 9 screenshots as a guide for each step.  

📸 *Screenshot Placeholders — 9 installation images*  
<img src="../screenshots/ubuntu/step4-install1.png" alt="Ubuntu Install Step 1" width="70%">  
<img src="../screenshots/ubuntu/step4-install2.png" alt="Ubuntu Install Step 2" width="70%">  
<img src="../screenshots/ubuntu/step4-install3.png" alt="Ubuntu Install Step 3" width="70%">  
<img src="../screenshots/ubuntu/step4-install4.png" alt="Ubuntu Install Step 4" width="70%">  
<img src="../screenshots/ubuntu/step4-install5.png" alt="Ubuntu Install Step 5" width="70%">  
<img src="../screenshots/ubuntu/step4-install6.png" alt="Ubuntu Install Step 6" width="70%">  
<img src="../screenshots/ubuntu/step4-install7.png" alt="Ubuntu Install Step 7" width="70%">  
<img src="../screenshots/ubuntu/step4-install8.png" alt="Ubuntu Install Step 8" width="70%">  
<img src="../screenshots/ubuntu/step4-install9.png" alt="Ubuntu Install Step 9" width="70%">

✅ Once completed, Ubuntu is now fully installed on the VM.

---

## Step 5: Update and Prepare Your VM
After installation, open the terminal in Ubuntu and run the following commands to update, upgrade, and install essential tools:

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install curl git ufw -y
