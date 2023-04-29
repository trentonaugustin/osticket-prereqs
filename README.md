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

- https://drive.google.com/drive/u/1/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6
- Control Panel
- ISS as Admin
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src=https://i.imgur.com/mYoYQXB.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The first thing you have to do is open up your control panel, turn on Internet Information Services, and click the plus beside ISS, world wide web Services, and application developer features so you can turn on CGI. The next thing you need to do is download the PhP manager, Rewrite module, and PHP 7.3.8 after you those are done create a folder called C:\PHP so you can extract the PHP 7.3.8 and put in the folder now we download VC redist.x86.axe and MY.SQL.5.5.62b when you get ready to install the MY.SQL.5.5.62b its going to ask you to choose a setup make sure you pick typical and then it gonna ask to pick a configuration you gotta click standard and when get to the password you can make yourown and then finsh installing the SQL.
</p>
<br />

<p>
<img src=https://i.imgur.com/jZmpcR6.png height="80%" width="80%" alt="Disk Sanitization Steps"/>cow
</p>
<p>
  Next step is to open Internet Information Services as a admin. Once that's done click on PHP Manager and then register new PHP version it will ask to choose a file you're gonna select on the php folder and then the php-cgi files after you do that press the restart button in ISS. Now your gonna download the osticket file once that done open two to tabs of the file explorer on the first tab go to download and then click on the file osticket file and you see a folder named upload rename it as osTicket now you move to your second tab and move to the this pc tab and select on the window c drive and then inetpub and drag the osticket folder inside the wwwroot so it can extract. If you come back to the Iss tab hit the restart button next step is to go to sites then default and osticket now if you look to the right of your screen you should see browse *80, click on that and it should bring you to a website for the osticket installer.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Now you return back to ISS and click PHP manager and then on enable or disable an extension so we can allow osticket to access to these following php_imap.dll, php_intl.dll, and php_opcache.dll after you enable all three your gonna to the osticket installer and refresh it then head to file explorer and go to the folder called osticket the click on include find ost-sampleconfig.php and rename it ost-config.php after you do that right click on and go to properties and security then click on disable inheritance after that theres gonna be an option that say remove all inherited permission from this object click on that then on add after this your gonna select a principle and when that is there should be a box you should be able to write in type everyone them you're gonna click check names and ok. Now you should be able to mark one of the basic permission your gonna turn on full control then ok and apply next open the back up the osticket installer press continue and fill out the information when you get to the database setting your're gonna need to download Heidi SQL. After it's done open up Heidi SQL once it's open your gonna type in your password that you created for MySQL and click on open then you will right click on unnamed to create a database which your're gonna name it osTicket this is what your also need put for the MySQL database on the osticket installer then you should be able to fill in the rest so you can click install on the osticket installer now your gonna need to do two more things then your done the first one is to open up your file exploer and click on the osticket folder and then delele the upload files and the last thing you need to do is find the ost-config.php file and change the basic permission from full control to only read and read & execute.
</p>
<br />
