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

-  Create Virtual Machine using Azure 
- Install/Enable IIS in Windows with CGI
- Install My SQL 5.5.62
- Install osTicket v 1.15.8
- Assign Permissions: ost-config.php
- Finalize osTicket set up in web browser 

<h2>Installation Steps</h2>
<img width="1440" alt="Creating VM Step 1" src="https://github.com/user-attachments/assets/bf81cb51-556b-43f5-be86-88822652699d" />
<p>
/>
</p>
<p>The first step of the installation process for this project is to create a virtual machine using Azure cloud services.
<br />

<p><img width="1440" alt="Enable IIS with CGI" src="https://github.com/user-attachments/assets/7caaf05e-f28c-49f3-9d55-e5d1f4204b99" />
</p>
<p>
Installing and Enabling IIS in Windows using CGI is an important step in the porcess of setting up the osTicket program. IIS  is the web server for Windows. osTicket is a web-based PHP application, so you need a web server to run it. IIS serves multiple purposes in relation to osTicket including, serving web pages to users accesing osTicket via a web browser and acts as the HTTP server that responds to client requests and delivers osTicket's user interface.</p>
<br />

<p>
<<img width="1440" alt="MySQL Installation" src="https://github.com/user-attachments/assets/76a638d2-6dfc-429a-b722-833a9a80acc6" />
<p>
Installing MySQL during the setup of osTicket is essential because MySQL is the database system that stores all of osTicket's data. osTicket is a web-based ticketing system that needs to store, retrieve, and manage data such as tickets and support requests, user accounts and department SLA plans 
<img width="1440" alt="OsTicket File Installatin p2" src="https://github.com/user-attachments/assets/f9349dc8-0c57-4bbf-bd71-b865784d1030" />
Once you have completed some of the prerequiste steps such as Enabling IIS you are able to complete the installation of the osTicket files onto your device. 
<img width="1440" alt="Assign ost-config Permissions" src="https://github.com/user-attachments/assets/4f79d8b4-c3ae-42d9-8d9d-430491dc0ce9" />
In order for the osTicket program to function properly you have to assign the proper permissions to the ost-config.php file folder. This file contains sensitive information such as data base hostname, database username and password, and encryption settings. 
<img width="1440" alt="Os Ticket help desk set Up" src="https://github.com/user-attachments/assets/00a2b8fb-d85f-4ad4-aaa2-c0fcfdee888f" />
<img width="1440" alt="Osticket Installation Complete" src="https://github.com/user-attachments/assets/06f7874f-129d-4b2e-92a7-92dec37ef829" />
The osTicket installation process is complete once you have set up your own help desk configuration and completing the installation procecess via web browser. 
