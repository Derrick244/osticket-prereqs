<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- VMware Setup
- Operating system (OS)
- software prerequisites (Web Server and Database Server)
- Email Configuration
- Permissions & Security

<h2>Installation Steps</h2>

<p>
[<img src="(https://imgur.com/a/PsdOn4y)" height="80%" width="80%" alt="Disk Sanitization Steps"/>](https://i.imgur.com/l0I9vyX.png)
</p>
<p>
1. Set Up the Virtual Machine (VM)
Create a New VM: In VMware, start by creating a new virtual machine with sufficient resources (CPU, RAM, and storage) based on the expected load. For osTicket, the VM should ideally have at least 2GB of RAM and 10GB of disk space.
Choose the Operating System: Install a compatible Linux OS (e.g., Ubuntu, CentOS) or Windows, depending on your preference or the system requirements of osTicket.
</p>
<br />

<p>
[<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>](https://i.imgur.com/fADKxji.png)
</p>
<p>
2. Install LAMP/LEMP Stack (Linux-based) or WAMP Stack (Windows-based)
Linux (LAMP/LEMP): osTicket is typically hosted on a Linux server, and you’ll need to install a web server (Apache or Nginx), a database server (MySQL or MariaDB), and PHP along with its required extensions.
Install Apache/Nginx, MySQL/MariaDB, and PHP with necessary modules.
Ensure that all firewall rules allow traffic on ports like 80 (HTTP) and 443 (HTTPS).
Windows (WAMP): For a Windows-based VM, you can use WAMP (Windows, Apache, MySQL, PHP) to host the environment, which has similar steps in terms of setting up the web server, database, and PHP.
</p>
<br />

<p>
[<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>](https://i.imgur.com/mbUc7kq.png)
</p>
<p>
3. Install osTicket and Configure it
Download and Install osTicket: Once your server environment is set up, download the latest stable release of osTicket from the official website. You can place it in the web root directory (e.g., /var/www/html on Linux).
Set Up Database: During the osTicket installation, you'll be prompted to create a database. You’ll need to configure the MySQL/MariaDB database and provide access credentials to osTicket.
Complete the Configuration: Follow the osTicket setup wizard to configure the admin account, email settings, and ticketing options. After the installation is complete, secure your server (adjust permissions, disable the installation directory, etc.) and perform any post-installation steps for proper performance and security.
Each of these steps ensures a functional and properly configured osTicket system running on VMware.
</p>
<br />
