<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Microsoft Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Creation of a Windows 10 Virtual Machine (VM) in Microsoft Azure with 2-4 Virtual CPUs (allow Azure to create a new Virtual Network while creating VM)
- Remote Desktop application in order to access the VM
- Install / Enable IIS in the Windows 10 VM
- Download Web Platform Installer (link provided to me from Course Careers)
- Open Web Platform Installer, Add MySQL 5.5 and add all simple versions of x86 PHP up until version 7.3
- Install osticket v1.15.8
- Copy the UPLOAD folder and paste it into C - inetpub - wwwroot, then restart Internet Information Services Manager. IIS Manager can be found in the start menu.
- Go to C - inetpub - wwwroot - osTicket - include and rename ost-sampleconfig.php to ost-config.php
- Open osTicket in your web browser and begin the basic installation process
- Download and Install HeidiSQL, Create a new session, root/Password1, Connect to the session, Create a database called “osTicket”
- Finish the installation process and CONGRATS! osTicket should be installed
- Next is a bit of clean up. Delete: C:\inetpub\wwwroot\osTicket\setup, Set Permissions to “Read” only: C:\inetpub\wwwroot\osTicket\include\ost-config.php
- Login to the osTicket Admin Panel

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/RT9V45l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a resource group in Microsoft Azure Environment. 
</p>
<br />

<p>
<img src="https://i.imgur.com/w9BdW0k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/OwnmOl6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a Windows10 Virtual Machine in Microsoft Azure with 2-4 Virtual CPUs. 
</p>
<br />

<p>
<img src="https://i.imgur.com/XhCGlcn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Use the Microsoft Remote Desktop App to access the Virtual Machine. Use the VM's IP Address (created in azure environment) in order to use Remote Desktop. Enter in your username and password to access the virtual machine. 
</p>
<br />

<p>
<img src="https://i.imgur.com/s8ZER1e.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to the Start Menu, Control Panel, Programs(Unistall a Program), Turn Windows Features On or Off, look for Internet Imnformation Services and turn it on. 
</p>
<br />

<p>
<img src="https://i.imgur.com/npXUXyO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download Web Platform Installer
</p>
<br />

<p>
<img src="https://i.imgur.com/dOUWNhG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open Web Platform Installer, Add MySQL 5.5 and add all simple versions of x86 PHP up until version 7.3
</p>
<br />

<p>
<img src="https://i.imgur.com/5W0uyAV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install osticket v1.15.8
</p>
<br />

<p>
<img src="https://i.imgur.com/Apj16hR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Copy the UPLOAD folder and paste it into C - inetpub - wwwroot, then restart Internet Information Services Manager. IIS Manager can be found in the start menu.
</p>
<br />

<p>
<img src="https://i.imgur.com/OCkMydh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to C - inetpub - wwwroot - osTicket - include and rename ost-sampleconfig.php to ost-config.php
</p>
<br />

<p>
<img src="https://i.imgur.com/NXjOkjz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open osTicket in your web browser and begin the basic installation process
</p>
<br />

<p>
<img src="https://i.imgur.com/fpOivnO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and Install HeidiSQL 
Create a new session, root/Password1
Connect to the session
Create a database called “osTicket”
</p>
<br />

<p>
<img src="https://i.imgur.com/1M3rVcT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finish the installation process and CONGRATS! osTicket should be installed
</p>
<br />

<p>
<img src="https://i.imgur.com/Z4rIlOb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next is a bit of clean up. Delete: C:\inetpub\wwwroot\osTicket\setup
Set Permissions to “Read” only: C:\inetpub\wwwroot\osTicket\include\ost-config.php
</p>
<br />

<p>
<img src="https://i.imgur.com/5trEXyf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login to the osTicket Admin Panel
</p>
<br />
