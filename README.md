<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>List of Prerequisites</h2>

- Azure Virtual Machine
- Internet Information Services (IIS)
- PHP Manager
- Rewrite Module
- VC Redist
- MySQL
- Heidi SQL
- osTicket v1.15.8
- Link to downloads: https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6


<h2>Installation Steps</h2>


1.) Before setting up the ticketing system, you will create a virtual machine by going to https://portal.azure.com/. Select Windows 10 Pro, version 22H2 as the image. Also, make sure that the virtual machine contains at least 2 vCPUs and 16 GB of memory.

2.) Once you have setup your virtual machine, you will connect to it by using the public IP address the vm is setup with. Open the Remote Desktop app and enter the public IP address from VM and username that you created and click Connect. 
</p>
<br />

<p>
<img src="https://imgur.com/MAhXK2e.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://imgur.com/Zf2jw07.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
3.) Once you have connected to your virtual machine, the first step is enabling IIS with CGI. In your VM, open Control Panel and click on "Programs and Features" under Programs. Next, click on "Turn Windows features on or off". 

<p>
<img src="https://imgur.com/fGXMpx4.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/a/fqJy8h8" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
