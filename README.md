# configure-ad
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create the Domain controller and create the a client virtual machine 
- Install Active Directory 
- Create an Admin and Normal user account 
- Setup remote desktop for non-admin users on client virtual machine
- Create additional users on powershell 

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/R8VJcmh.png">
</p>
<p>
Verified connnectivity between the client and domain controller by enabling ICMPv4 protocols on domain controller's Firewall 
</p>
<br />

<p>
<img src="https://i.imgur.com/GOKgt0s.png"<
</p>
<p>
Successfully installed Active Directory domain services on the domain controller 
</p>
<br />

<p>
<img src="https://i.imgur.com/RS4LjlN.png"<
  /p>
<p>
Additonal users are being ![image](https://github.com/Baljeet209/configure-ad/assets/163678715/11a34389-1ab0-487e-a91f-ccc128312cef)
created in Powershell ISE using a script 
</p>
<br />
