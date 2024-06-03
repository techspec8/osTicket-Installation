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

- Install / Enable IIS in Windows with CGI
- Install MySQL / Setup Username and Password
- Register PHP from within IIS / Enable Extensions
- Install HeidiSQL Extension
- Configure Permissions / Install osTicket


<h2>Installation Steps</h2>

<p>
Install and Enable IIS with CGI and Common HTTP Features
</p>
<p>
<img src= https://i.imgur.com/6el85cH.png</p> <img src= https://i.imgur.com/FLESqr3.png</p>
<br />

<p> Download PHP and the Rewrite Module for IIS, and create a folder to unzip PHP files into
</p>
<img src= https://i.imgur.com/eFR13SD.png
</p>
<br />

<p> Install MySQL Server Database
</p>
<img src= https://i.imgur.com/bxhBVtg.png
</p>
<br />

<p> Open IIS as Admin from the start menu and register PHP from within IIS then, restart the server
</p>
<img src= https://i.imgur.com/wXSwTHv.png
</p>
</p>
<img src= https://i.imgur.com/WUDIofp.png
</p>
<br />

<p>
Access the osTicket browser to confirm installation, then from osTicket enable PHP extensions 
</p>
<p>
<img src= https://i.imgur.com/LWZflrd.png
</p>
<p>
<img src= https://i.imgur.com/E1j7g0z.png
</p>
<br />

<p>
Install HeidiSQL to connect to the SQL database, name a new connection to the SQL database, 
</p>
<p><img src= https://i.imgur.com/SGj9wCt.png</p> <img src= https://i.imgur.com/3cYkcLY.png</p>
<p>
<img src= https://i.imgur.com/FbHgF7W.png
</p>
<br />
  
<p>
Complete the osTicket installation and log in to begin creating tickets
</p>
 <p>
<img src= https://i.imgur.com/5qMppiG.png
</p>
<br />
