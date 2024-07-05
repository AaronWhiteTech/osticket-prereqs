# osticket-prereqs
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

- IIS
- PHP manager
- Microsoft VC
- SQL/HelfiSQL
- 

<h2>Installation Steps</h2>

![Screenshot 2024-06-25 230156](https://github.com/AaronWhiteTech/osticket-prereqs/assets/155200818/2be50ceb-21b5-4f71-a3be-6bbf1dbc6c9a)

- (Step 1)  go to settings programs and features-turn features on and off, select IIS-IIS Management Console, World Wide Web Services -Application Development Features -CGI -Common HTTP Features




![Screenshot 2024-06-26 203449](https://github.com/AaronWhiteTech/osticket-prereqs/assets/155200818/9887f5e4-74f6-4c17-9f86-ad8e0959629b)



(Step 2)Create the directory C:\PHP, Download and Install PHP Manager into PHP folder



![Screenshot 2024-06-26 224240](https://github.com/AaronWhiteTech/osticket-prereqs/assets/155200818/4b190683-abde-4907-9bf9-2865b7d3fb44)

(Step 3) Download and install Microsoft cisual C++


![Screenshot 2024-06-26 202949](https://github.com/AaronWhiteTech/osticket-prereqs/assets/155200818/4649fb56-d1ad-44ae-aa26-f47408290278)



(Step 4)Download and install MYSQL, click Typical Setup, Launch Configuration Wizard (post install), click Standard Configuration, type Password1, keep root username



![Screenshot 2024-06-26 204154](https://github.com/AaronWhiteTech/osticket-prereqs/assets/155200818/e8c68aba-cd94-4f7b-9d84-f2d890a451dc)



(Step 5) Open IIS as an Admin, Register PHP from within IIS, download osticket, Extract and copy “upload” folder to c:\inetpub\wwwroot
Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”







![Screenshot 2024-06-27 005218](https://github.com/AaronWhiteTech/osticket-prereqs/assets/155200818/205c49c5-b18d-46bf-a638-39bf478cc68a)

Go to sites -Default  -osTicket, On the right, click “Browse *:80” observe the osticket install screen


![Screenshot 2024-06-26 224020](https://github.com/AaronWhiteTech/osticket-prereqs/assets/155200818/dd0c770c-abe0-4bac-aa03-8aee307e035e)

Go back to IIS, sites - Default - osTicket
Double-click PHP Manager, Click “Enable or disable an extension” Enable the following php_imap.dll, php_intl.dll and  php_opcache.dll
Refresh the osTicket site in your browser

