---
layout: default
title: Ubuntu VM Lab
permalink: /projects/ubuntu-lab.html
---
<section class="section">
  <div class="container">
    <div class="grid">


# 🐧 Ubuntu VM Lab

This guide walks through setting up an **Ubuntu 20.04.6 virtual machine** in Oracle VirtualBox to be used as part of a home SOC lab.  
Each step includes notes and placeholders for screenshots you will upload later.

---

## Step 1: Download Ubuntu ISO
Download the official Ubuntu 20.04.6 ISO from the Ubuntu website.  
[Ubuntu ISO Download](https://www.releases.ubuntu.com/focal/ubuntu-20.04.6-desktop-amd64.iso)

---

## Step 2: Create New VM
Launch Oracle VirtualBox Manager and click **New** to create a virtual machine.

Follow along with the images to complete the setup.  
 
  <img src="screenshots/ubuntu/settings1.png" alt="VM Setup Step 1" width="60%">
 
  <img src="screenshots/ubuntu/settings2.png" alt="VM Setup Step 2" width="60%">
  
  <img src="screenshots/ubuntu/settings3.png" alt="VM Setup Step 3" width="60%">

- After setup is complete, click "Finish"

---

## Step 3: Network Settings
Select the Ubuntu VM’s **Settings → Network**.  

  <img src="screenshots/ubuntu/settings4.png" alt="Network Settings" width="60%">
Configure the following network settings.
    <img src="screenshots/ubuntu/settings5.png" alt="Network Settings" width="60%">

---

## Step 4: Installing Ubuntu on VM
1. Launch the Ubuntu VM.  
2. Follow through the Ubuntu installation process.  
3. Use the following 9 screenshots as a guide for each step.  

  <img src="screenshots/ubuntu/setup1.png" alt="Ubuntu Install Step 1" width="60%"> 
  <img src="screenshots/ubuntu/setup2.png" alt="Ubuntu Install Step 2" width="60%">
  <img src="screenshots/ubuntu/setup3.png" alt="Ubuntu Install Step 3" width="60%">
  <img src="screenshots/ubuntu/setup4.png" alt="Ubuntu Install Step 4" width="60%">
  <img src="screenshots/ubuntu/setup5.png" alt="Ubuntu Install Step 5" width="60%">
  <img src="screenshots/ubuntu/setup6.png" alt="Ubuntu Install Step 6" width="60%">
  <img src="screenshots/ubuntu/setup7.png" alt="Ubuntu Install Step 7" width="60%">
  <img src="screenshots/ubuntu/setup8.png" alt="Ubuntu Install Step 8" width="60%">
  <img src="screenshots/ubuntu/setup9.png" alt="Ubuntu Install Step 9" width="60%">

✅ Once completed, Ubuntu is now fully installed on the VM.

---

## Step 5: Update and Prepare Your VM
After installation, open the terminal in Ubuntu and run the following commands to update, upgrade, and install essential tools:

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install curl git ufw -y
