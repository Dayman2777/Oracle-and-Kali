# Oracle-and-Kali
Installing Oracle and then installing Kali Linux
<h1>Installing Oracle and then installing Kali Linux</h1>


<h2>Description</h2>
The objective of this guide is to illustrate the step-by-step procedure for setting up a virtual machine using Oracle. To accomplish this, we will utilize a Windows 10 machine equipped with a quad-core processor and 16GB of RAM. Subsequently, we will guide you through the process of obtaining Kali Linux and conducting the operating system installation within the virtual machine.

<br />


<h2>Languages and Utilities Used</h2>

- <b>Oracle Virtual box</b> 
- <b>Kali Linux</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> Oracle VM Virtualbox

<h2>Program walk-through:</h2>

<p align="center">
Launch the shell and type- sudo apt update: <br/>
<img src="https://i.imgur.com/8n7r4Mu.png" height="80%" width="80%" alt="Open you shell and type- sudo apt update."/>
<br />
<br />
Type password:  <br/>
<img src="https://i.imgur.com/uVZ3j97.png" height="80%" width="80%" alt="Type in your Root password."/>
<br />
<br />
Wait for update to complete: <br/>
<img src="https://i.imgur.com/i3C45yA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Launch your web browser; in this tutorial, we've utilized Firefox. Begin by searching for "Nessus Essentials download" or use the following link:
https://www.tenable.com/downloads/nessus?loginAttempted=true: <br />
<img src="https://i.imgur.com/KJdXxpk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After reaching the download site, ensure that you have selected the latest version by clicking the drop-down menu for "Version." Next, navigate to the "Platform" section and choose the Nessus version compatible with Debian that matches your Kali Linux version. For this tutorial, we're utilizing the "Linux-Debian-amd64" option. Once you've made your selection, click on the "Download" button and agree to the terms and conditions:  <br/>
<img src="https://i.imgur.com/Ca5DXkq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once the download is finished, clear your terminal and navigate to the "Downloads" directory by using the "cd" command:  <br/>
<img src="https://i.imgur.com/ZptPlYh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Employ the "ls" command to inspect the Nessus download in your directory:  <br/>
<img src="https://i.imgur.com/CmwwwGe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now we're going to run- sudo dpkg -i Nessus-10.6.1-debian_amd64.deb. Type password if needed: <br/>
<img src="https://i.imgur.com/Y6xfP4I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once the download has finished, you will receive the login information for accessing Nessus.Select the disk:  <br/>
<img src="https://i.imgur.com/g3yJbS4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
First step is to run command- /bin/systemctl start nessusd.service: <br/>
<img src="https://i.imgur.com/EaGMuD7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
You'll be asked for your password:  <br/>
<img src="https://i.imgur.com/jSNw5iV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now, open your web browser and enter the address provided in the second step. In this case, it was:
 https://kali5:8834: <br/>
<img src="https://i.imgur.com/J2Zzq29.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Accept the risk by clicking "Advanced" and "Accept the Risk and Continue":  <br/>
<img src="https://i.imgur.com/mzoE025.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
At this point, you should be on the Welcome screen. Click the "Continue" button:  <br/>
<img src="https://i.imgur.com/H7ynGzk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br />
 We're going to select "Register for Nessus Essentials", click "Continue": <br />
<img src="https://i.imgur.com/u7GHW7I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter your information for the service:  <br/>
<img src="https://i.imgur.com/d2ENEk8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once you've completed the information, you'll be provided with activation code: <br/>
<img src="https://i.imgur.com/orSFmVV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generate a username and password of your choice, then click the "Submit" button:  <br/>
<img src="https://i.imgur.com/CwfudPh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After completing your username and password you'll go through a Initializing screen:  <br/>
<img src="https://i.imgur.com/BEEkyXb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Following the Initializing screen, you will be directed to the Nessus Home page. Please be patient as everything updates and completes the installation. You will notice a loading icon at the top right corner, and when it disappears, you can initiate a Nessus scan:  <br/>
<img src="https://i.imgur.com/EdJHusD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Nessus will inform you when this process is finished and prompt you to initiate your scan. In this tutorial, please click on the "Close" option:  <br/>
<img src="https://i.imgur.com/rk2Axf2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
 <br />
 On the top right side you'll see "New Scan": <br/>
<img src="https://i.imgur.com/tV0BYQY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click "Advance Scan":  <br/>
<img src="https://i.imgur.com/MV4XNak.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
You can now perform a more comprehensive scan. In this tutorial, we'll name the initial scan "Scan1" and configure it with the specific IP addresses to be scanned. Once you've filled in all the necessary fields and saved the settings, you'll be returned to the home screen: <br/>
<img src="https://i.imgur.com/3dKtOwg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, you'll find your scan listed, and on the right-hand side, click the play button to initiate it:  <br/>
<img src="https://i.imgur.com/5WGLiNU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once the scan has finished, you can access the scan results to identify vulnerabilities within your network. The Essentials package grants you the ability to scan up to 16 IP addresses for free. Always remember that conducting scans on networks without proper authorization is illegal:  <br/>

</p>

</p>


</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
