<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This project demonstrates setting up the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

-  Step 1:Create Virtual Machine using Azure
-  Step 2: Within Virtual Machine download OS Ticket Zip File
- Step 3 Install/Enable IIS in Windows with CGI
- Step 4: Install PHP manager for IIS
- Step 5: Install rewrite module
- Step 6: Create the directory C:\PHP
- Step 7: Install VC_redist.x86.exe
- Step 8: Install My SQL 5.5.62
- Step 9: Register PHP from within IIS
- Step 10: Install osTicket v 1.15.8
- Step 11: Enable Extensions 
- Step 12: Assign Permissions: ost-config.php
- Step 13: Install HeidiSQL
- Step 14: Finalize osTicket set up in web browser 

<h2>Installation Steps</h2>
<img width="1440" alt="Creating VM Step 1" src="https://github.com/user-attachments/assets/bf81cb51-556b-43f5-be86-88822652699d" />
<p>
/>
</p>
<p>The first step of the installation process for this project is to create a virtual machine using Azure cloud services. Using a virtual machine creates a safe environment to practice the installation of the osTicket system with out causing any damage to the host operating system. 
<br />
<img width="1440" alt="osticket zipfile installation" src="https://github.com/user-attachments/assets/e81ffe5e-d91b-454f-a180-e7c68ead0ddc" />
  Step 2: Within the virtual Machine download the OS Ticket Zip file. This gives you access to all the files neccesary for installing the OS Ticket software.
<p><img width="1440" alt="Enable IIS with CGI" src="https://github.com/user-attachments/assets/7caaf05e-f28c-49f3-9d55-e5d1f4204b99" />
</p>
<p>
Step 3: Installing and Enabling IIS in Windows using CGI is an important step in the porcess of setting up the osTicket program. IIS  is the web server for Windows. osTicket is a web-based PHP application, so you need a web server to run it. IIS serves multiple purposes in relation to osTicket including, serving web pages to users accesing osTicket via a web browser and acts as the HTTP server that responds to client requests and delivers osTicket's user interface.</p>
<br />
<img width="1440" alt="Php Manager Installation" src="https://github.com/user-attachments/assets/2c6ecbd2-2414-4df8-afeb-d393a9190ccc" />
Step 4: Install PHP manager for IIS: PHP is a graphical administrative tool used within IIS. Installing this file makes it easier to configure and manage PHP settings within the IIS web server .
<img width="1440" alt="Rewrite Module Installation" src="https://github.com/user-attachments/assets/d391b4bd-494d-4cb9-9e82-8c5785e2d09b" />
Step 5: Install rewrite module: The URL rewrite module is an extension for IIS. It allows the web server to rewrite url's based upon defined rules, convert long or complex url's into clean, readable links and performing routing and redirecting processes behind the scenes. 
<img width="1440" alt="Create Directory" src="https://github.com/user-attachments/assets/599df6d5-88d5-4d03-9a7b-c58c117223b7" />
Step 6:  Create the directory C:\PHP : Creating this directory makes it easier to configure PHP with IIS. This directory creates a designated environment for all of the core PHP manager files. 
<img width="1440" alt="VC Redistributal Install" src="https://github.com/user-attachments/assets/db5c5b9c-49f7-4e6e-8d24-cf4a585cd005" />
Step 7: Install VC_redist.x86.exe: Installing this file ensures that PHP and its extensions can function properly within the Windows/IIS system.
<<img width="1440" alt="MySQL Installation" src="https://github.com/user-attachments/assets/76a638d2-6dfc-429a-b722-833a9a80acc6" />
<p>
Step 8: Install MySQL: Installing MySQL during the setup of osTicket is essential because MySQL is the database system that stores all of osTicket's data. osTicket is a web-based ticketing system that needs to store, retrieve, and manage data such as tickets and support requests, user accounts and department SLA plans.
  <img width="1440" alt="Register PHP within IIS" src="https://github.com/user-attachments/assets/52db298c-3fd6-476c-9442-7a648d90e527" />
  Step 9: Register PHP within IIS: This allows IIS to properly recognize and and process PHP files. 
  <img width="1440" alt="OsTicket File Installation" src="https://github.com/user-attachments/assets/bad377fb-df7e-4f62-b422-07a8f7413dc5" />
<img width="1440" alt="OsTicket File Installatin p2" src="https://github.com/user-attachments/assets/f9349dc8-0c57-4bbf-bd71-b865784d1030" />
Step 10: Once you have completed some of the prerequiste steps such as Enabling IIS you are able to complete the installation of the osTicket files onto your device. 
  <img width="1440" alt="OsTicket File Installatin p2" src="https://github.com/user-attachments/assets/efa77413-5980-4feb-85a3-9c401c0484c1" />
  Step 11: Enable Extensions: These extensions need to be enabled in order for the OsTicket system to function properly. 
<img width="1440" alt="Assign ost-config Permissions" src="https://github.com/user-attachments/assets/4f79d8b4-c3ae-42d9-8d9d-430491dc0ce9" />
Step 12: In order for the osTicket program to function properly you have to assign the proper permissions to the ost-config.php file folder. This file contains sensitive information such as data base hostname, database username and password, and encryption settings. 
  <img width="1440" alt="HeidiSQL Installation" src="https://github.com/user-attachments/assets/502b60d6-1fae-4e66-80ab-7964974447aa" />
  <img width="1440" alt="HeidiSQL Installation p2" src="https://github.com/user-attachments/assets/93b452f9-c112-4990-82f8-a0e692af16c9" />
  Step 13: Install Heidi SQL: Heidi SQL is a database management tool that allows you to connect to and manage MySQL databases, run custom SQL queries and fix any date base issues/errors. 
<img width="1440" alt="Os Ticket help desk set Up" src="https://github.com/user-attachments/assets/00a2b8fb-d85f-4ad4-aaa2-c0fcfdee888f" />
<img width="1440" alt="Osticket Installation Complete" src="https://github.com/user-attachments/assets/06f7874f-129d-4b2e-92a7-92dec37ef829" />
 Step 14: The osTicket installation process is complete once you have set up your own help desk configuration and completing the installation procecess via web browser. 
