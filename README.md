<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create azure tenant(organization)
- Create a resource group
- Create a virtual machine
- Install osTicket on vm

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/suvOPLH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created a Resource Group(RG-osTicket), as well as a Windows 10 VM with 4 virtual CPUs. I then located VM-1's public IP address, where I copied it and opened the Remote Desktop application to login to vm.
</p>
<br />

<p>
<img src="https://i.imgur.com/tx4iH5a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Pre-installation, I enabled IIS in Windows with CGI and common HTTP features. Then I installed PHP Manager for IIS and Rewrite Module. I created the directory C:\PHP, as well as MySql. Finished with Install of osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/OqwqUF8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Loaded osTicket and verified a successful login.
</p>
<br />
