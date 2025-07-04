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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/44szsnj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First we start by creating the virtual machine
</p>
<br />

<p>
<img src="https://i.imgur.com/WDoSMsu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After we create the virtual machine, we will put it's public IP address into the remote desktop to connect.
</p>
<br />

<p>
<img src="https://i.imgur.com/V9F0gIG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once we are in the Remote Desktop we then go to files,then downloads and find the osTicket installation file
</p>
<br />

<p>
<img src="https://i.imgur.com/HSo8piS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We then Extract the files
</p>
<br />

<p>
<img src="https://i.imgur.com/AioLKCb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we go to control Panel and click uninstall a program under programs
</p>
<br />

<p>
<img src="https://i.imgur.com/2GN1kO3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It will show this screen. we will turn on NET Framework4.8 Advanced Services by selecting the check box
</p>
<br />

<p>
<img src="https://i.imgur.com/ee4m9ZQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We next click on PHP ManagerForllS_V1.5.0
</p>
<br />

<p>
<img src="https://i.imgur.com/CYRVMNe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Complete the Installation.
</p>
<br />

<p>
<img src="https://i.imgur.com/VkKen9i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we Install IIS URL Rewrite Module 2 Setup
</p>
<br />

<p>
<img src="https://i.imgur.com/ZvT1k5Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After that we are going to create a new folder for PHP
</p>
<br />

<p>
<img src="https://i.imgur.com/TkmLznj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
create the folder.(Make sure they are in Uppercase Lettering).
</p>
<br />

<p>
<img src="https://i.imgur.com/oO237Vo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we will go to the PHP zipped file
</p>
<br />

<p>
<img src="https://i.imgur.com/NoCh51s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Extract the Folder.
</p>
<br />

<p>
<img src="https://i.imgur.com/kg2xyXD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We then make sure everything has been Extracted.
</p>
<br />

<p>
<img src="https://i.imgur.com/e4b28Fp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we Install VC_redist.x86
</p>
<br />

<p>
<img src="https://i.imgur.com/zBQYkTo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It will take us here. We are going to Install
</p>
<br />

<p>
<img src="https://i.imgur.com/hKiY5Gd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we will install mysql-5.5.62-win32
</p>
<br />



<p>
<img src="https://i.imgur.com/ItGjuby.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We will press next
</p>
<br />

<p>
<img src="https://i.imgur.com/B8UARpM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set the configuration to standard then press next
</p>
<br />

<p>
<img src="https://i.imgur.com/mndZ6T4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
(This is very important) we will set the password as "root", make sure the retype is EXACTLY the same as the new password. then click next
</p>
<br />

<p>
<img src="https://i.imgur.com/sPt06Jk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
we then make sure everything is checkmarked then click finish
</p>
<br />

<p>
<img src="https://i.imgur.com/JTBTlN5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It will then bring us here. we will click on PHP manager
</p>
<br />

<p>
<img src="https://i.imgur.com/PofXrSk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
click on Register new PHP version
</p>
<br />

<p>
<img src="https://i.imgur.com/8DD5COC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then click on the php-cgi folder
</p>
<br />

<p>
<img src="https://i.imgur.com/aqLZwFi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
once it shows this press OK
</p>
<br />

<p>
<img src="https://i.imgur.com/NyqIerE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we will stop the server then start the sever after a few seconds
</p>
<br />

<p>
<img src="https://i.imgur.com/vJjwnvT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we will go back to files then extract the osTicket-v1.15.8 folder
</p>
<br />

<p>
<img src="https://i.imgur.com/rNIFL7G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Extract It
</p>
<br />

<p>
<img src="https://i.imgur.com/buZRrgj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next click on the Inetpub folder
</p>
<br />

<p>
<img src="https://i.imgur.com/7GkVoPL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then click on wwwroot
</p>
<br />

<p>
<img src="https://i.imgur.com/mxMbDLE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We are then going to move the upload folder from the osTicket-v1.15.8 to wwwroot
</p>
<br />

<p>
<img src="https://i.imgur.com/amhKrWD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we rename the folder to osTicket
</p>
<br />

<p>
<img src="https://i.imgur.com/uxsgJLD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After that we go back to IIS Manager and select the osTicket folder. after that we click browse under Browse Folder
</p>
<br />

<p>
<img src="https://i.imgur.com/r1mJf48.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It will then take us to this screen. as we can see there are a few things not checkmarked so we are going to fix that.
</p>
<br />

<p>
<img src="https://i.imgur.com/Ia4M8Rm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We go back to IIS manager and select PHP Manager
</p>
<br />

<p>
<img src="https://i.imgur.com/Kz4XgEt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We then select Enable or disable extensions
</p>
<br />
<p>
<img src="https://i.imgur.com/t1MKFhS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Make sure these exact extensions are Enabled
</p>
<br />

<p>
<img src="https://i.imgur.com/Oj5eWQR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now it should show the majority checkmarked except for the bottom two.
</p>
<br />




<p>
<img src="https://i.imgur.com/j27Qjuw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/KqHEjlC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZD9mfYr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/oAdqQaz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/uYliVzj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/RewzOez.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/Vz2Efhz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/hxVtHX8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/BJDkasz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/90bXdMQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/bPMtqKS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/B74xV06.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />




