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
To begin, please initiate the download of VirtualBox from Oracle by visiting the provided web address:
<br />
https://www.virtualbox.org/
<br />
<img src="https://i.imgur.com/Z2hBLdQ.png" height="80%" width="80%" alt="Virtual Box download."/>
<br />
<br />
Locate your download and run Virtualbox-x.x.x-Win.exe:
<br/>
<img src="https://i.imgur.com/kWP8CEp.png" height="80%" width="80%" alt="Run exe."/>
<br />
<br />
Follow the download Wizard:
<br/>
<img src="https://i.imgur.com/ducFh8a.png" height="80%" width="80%" alt="Wizard steps"/>
<br />
<img src="https://i.imgur.com/nMuuu4u.png" height="80%" width="80%" alt="Wizard Steps"/>
<br />
<img src="https://i.imgur.com/odaN9K6.png" height="80%" width="80%" alt="Wizard Steps"/>
<br />
<img src="https://i.imgur.com/SmOEHzp.png" height="80%" width="80%" alt="Wizard Steps"/> 
<br />
<img src="https://i.imgur.com/lTYravc.png" height="80%" width="80%" alt="Wizard Steps"/>
<br />
<img src="https://i.imgur.com/vy0KcMZ.png" height="80%" width="80%" alt="Wizard Steps"/> 
<br />
<img src="https://i.imgur.com/iviTC2c.png" height="80%" width="80%" alt="Wizard Steps"/> 
<br />
<br />
Once you have completed the setup wizard and checked the "Start Oracle VM VirtualBox 7.0.10 after installation" option, Oracle will open:  
<br/>
<img src="https://i.imgur.com/eXeozQZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now we need to download Kali Linux, first go to: https://www.kali.org/ click "Installer Images"
<br/>
<img src="https://i.imgur.com/3ws41co.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
For our installation, we will opt for the 64-bit version:
<br/>
<img src="https://i.imgur.com/Lqblxc9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
We can now make a Virtual machine: 
In Oracle, we need create a new Virtual machine by selecting "New".
<br/>
<img src="https://i.imgur.com/J1G7FtK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Name your VM: 
<br/>
<img src="https://i.imgur.com/938kYaK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Pick your ISO: <br/>
<img src="https://i.imgur.com/llHpeTH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After those 2 fields are filled out click "Next":  
<br/>
<img src="https://i.imgur.com/6YtmGAK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, we must configure the hardware settings, ensuring that we do not allocate all available resources from your machine. We will allocate 2 cores and 4GB of RAM. When specifying RAM, multiply the desired amount by 1024. For example, 4GB of RAM translates to 4 x 1024 = 4096. Once you've entered these values, click on the "Next" button:
<br/>
<img src="https://i.imgur.com/qmKllkT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now, we'll proceed with the creation of the hard drive. Since we're utilizing SIEM tools, it's advisable to allocate ample storage for logs. In this instance, we'll allocate 25GB of storage. Once you've determined the storage amount, click the "Next" button: 
<br/>
<img src="https://i.imgur.com/aNlC7Lf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Review your selections and hit "Finish": 
<br/>
<img src="https://i.imgur.com/0FzMng8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br />
Find your machine and double-click on it to access it:
<br />
<img src="https://i.imgur.com/UuNa9wN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Kali Linux will take you through the installation Wizard:
<br/>
<img src="https://i.imgur.com/rWoaT2i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
For this installation we're going to select "Graphical install":
<br/>
<img src="https://i.imgur.com/zT9TDmd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select your language and click "Continue".
<br />
<img src="https://i.imgur.com/DMiILbw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select your location and click "Continue".
<br />
<img src="https://i.imgur.com/DH4sdko.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select your Keyboard preference, then click "Continue": 
<br/>
<img src="https://i.imgur.com/MdpbdcR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Name your machine, we're going with Kali5. Then select "Continue":
<br/>
<img src="https://i.imgur.com/Q3OLbxz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
If you have a domain, put that information in. If you don't just click "Continue":
<br/>
<img src="https://i.imgur.com/7XrKP7n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Give your user a name, we went with Kali5. Then click "Continue":
<br/>
<img src="https://i.imgur.com/LEjSNmQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add your password for the Root user. Click "Continue":
<br/>
<img src="https://i.imgur.com/TzZt9sQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Choose your time zone and click "Continue":
<br/>
<img src="https://i.imgur.com/K2WHIdd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
If you don't need to partition your hard drive choose "Guided -use entire disk":
<br/>
<img src="https://i.imgur.com/TlgeHmj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Choose the hard drive we created earlier, the select "Continue":
<br/>
<img src="https://i.imgur.com/vWgdgEn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
We're going to choose "All files in one partition (recommended for new users)", then click "Continue":
<br/>
<img src="https://i.imgur.com/DzVy7g4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify the hard drive is correct, make sure "Finish partitioning and write changes to disk". Click "Continue":
<br/>
<img src="https://i.imgur.com/1gTaPDj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify your hard drive has been partition correctly and select "Yes". Then we click "Continue":
<br/>
<img src="https://i.imgur.com/LJFCfhA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
We've opted for the default selections, but you have the option to choose Gnome if you prefer. It will become available later in the installation process. Once you have made all your selections, click on "Continue.":
<br/>
<img src="https://i.imgur.com/IngqoCf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
We've created a new hard drive at the beginning, select "Yes", and click "Continue":
<br/>
<img src="https://i.imgur.com/t7XEYbG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select our hard drive and click "Continue":
<br/>
<img src="https://i.imgur.com/mooN8bG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
When the installation is complete, you'll be prompted to reboot the VM. Click "Continue":
<br/>
<img src="https://i.imgur.com/qlyTzPB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Please be patient for a few moments, and you will be prompted to enter the username and password that we previously set up. After entering this information, click on "Log in.":
<br/>
<img src="https://i.imgur.com/12RIqhy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once you've successfully logged in, you've completed the installation of Kali Linux. Make sure to perform any necessary updates for Kali and enjoy your newly installed operating system!:
<br/>
<img src="https://i.imgur.com/2yTxXVp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

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
