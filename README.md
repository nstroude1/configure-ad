<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 Create A Resource Group
- Step 2 Create A Virtual Network
- Step 3 Create A VM to use as a Domain Controller (DC-1)
- Step 4 

<h2>Deployment and Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/2dececf0-7254-45ba-808e-e877e82cb98b)

<p>
This is a container that will hold all resources as a group in Microsoft Azure.
  1. From the Azure homepage hover over the resource group icon and select create.
  2. Name resource group, choose region and click review and create/create
</p>
<br />

![image](https://github.com/user-attachments/assets/549dcf8a-1a43-4315-8630-1e53719bb542)

<p>
The Virtual Network acts as a network in a data center in which you can isolate, scale or change the availability at the touch of a button.
  1. Again from the Azure homepage hover over the virtual network icon and select create.
  2. Choose the resource group to put the network in, name the virtual network
  3. Click review and create/create
</p>
<br />

![image](https://github.com/user-attachments/assets/5ad050a7-16c7-4c9e-a80b-2eafa15054d3)

<p>
I created a Vitual Machine which will act as a server to which I will install Azure to act as a Domain Controller.
  1. 
</p>
<br />
