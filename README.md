# 🚀 Create a Windows Virtual Machine using Azure Sandbox (Microsoft Learn)

This guide walks you through the process of creating a Windows virtual machine in Microsoft Azure and connecting to it via Remote Desktop Protocol (RDP). Perfect for beginners looking to gain hands-on experience with Azure cloud services!

## 📚 Project Overview

In this project, I followed the **Microsoft Learn** self-paced lab to:

- Sign in and activate the Azure sandbox
- Create a Windows Server Virtual Machine
- Connect to the VM using Remote Desktop Protocol (RDP)
- Learn the basics of cloud infrastructure and Azure Portal

This repository includes screenshots and documentation of each step I completed.

---

## 🛠️ Steps I Followed

### ✅ Step 1: Sign into Microsoft Learn

- Go to: [https://learn.microsoft.com](https://learn.microsoft.com)
- Click **"Sign in"**
- If you don’t have an account, click **"Create now!"** to register

---

### ✅ Step 2: Activate the Azure Sandbox

- Click on **Documentation** > **Azure**
- Under Azure, go to **Virtual Machines**
- Choose the module: **Create a Windows Virtual Machine in Azure**
- Scroll to **Unit 3** and click **"Activate Sandbox"**
- Click **Review Permissions** and accept
- Launch the **Azure Portal**

---

### ✅ Step 3: Create the Virtual Machine

- In Azure Portal, click **Create a resource**
- Search and select **Windows Server**
- Under Plan, select: `[smalldisk] Windows Server 2019 Datacenter`
- Fill in the **Basics**, **Disk**, and **Networking** settings
- For networking: Create a new virtual network

---

### ✅ Step 4: Connect to the Virtual Machine (RDP)

- Click **Review + Create**, then **Create**
- Wait for deployment to complete
- Go to your VM resource
- Click **Connect** > **Download RDP File**
- Open the RDP file and log in using the credentials you created

---

## 🖼️ Screenshots

All screenshots of the project steps are available in the `/screenshots` folder.

---

## 🔐 Notes

This project was completed using the **Microsoft Learn Sandbox** environment, which provides temporary Azure resources for learning.

To recreate this project in your own Azure environment, simply follow the steps above. Remember that outside the Microsoft Learn sandbox, you'll need an active Azure subscription.

---

##  Conclusion

Congratulations! You've successfully:

-  Created a Windows Server 2019 virtual machine in Azure

-  Configured networking and storage

-  Connected to your VM using Remote Desktop Protocol

This hands-on experience provides valuable skills in cloud computing and Azure administration. For those looking to continue learning, consider exploring:

-  Azure Virtual Machine scaling
-  Network security groups
-  Azure Monitor for performance tracking

---


