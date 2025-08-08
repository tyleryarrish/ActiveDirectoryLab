<h1>Active Directory Home Lab</h1>
<h2>Description</h2>
Built a home lab to simulate an enterprise Active Directory environment using virtual machines. Deployed a Windows Server VM as a Domain Controller, installed and configured Active Directory Domain Services (AD DS), and used PowerShell to automate user account creation and management. This project strengthened my skills in identity and access management, automation, and Windows Server administration.

<h2>Tools Used</h2>

✅ Oracle VirtualBox ✅ PowerShell ✅ VMware ✅ Windows Server & Windows 10

<h2>Takeaways</h2>
This project gave me practical, hands-on experience with deploying and managing an Active Directory environment. I strengthened my skills in Windows Server setup, domain configuration, and scripting with PowerShell—foundational knowledge for enterprise IT administration and cybersecurity roles.

<h2>Project walk-through:</h2>

<p align="center">
Step 1 - Download and Install Oracle VirtualBox: I started by downloading and installing Oracle VirtualBox on my computer from the official website. Once installed, created a VM then chose "Windows Server" as the operating system and allocated appropriate resources (CPU, RAM, and disk space) for the server.  <br/>
<img src="https://i.imgur.com/UwtCbvn.png" height="80%" width="80%" alt="AD Steps"/>
<br />
<br />
Step 2 - Install Windows Server on the VM: Downloaded  the Windows Server ISO file from the official Microsoft webesite. Next, started the VM and mounted the Windows Server ISO file. After installation, I configured the server settings which included setting a strong password for the admin account and adjusted network settings. I also added in guest additions.  <br/>
<img src="https://i.imgur.com/Sda56o2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 3 - Install and Configure Active Directory Domain Services (AD DS): On the VM, opened the Server Manager and added the Active Directory Domain Services role. Then, using the AD DS Configuration Wizard, promoted the server to domain controller. I specified a domain name and followed the prompts to complete the configuration. After the server rebooted, I verified that the domain controller was functioning correctly by checking the server roles. <br/>
<img src="https://i.imgur.com/FKAxpQu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/YL48gMC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Last Step: - Add Users to Active Directory with Powershell: Opened Powershell as an administrator on the domain controller. Then, created user accounts by executing Powershell scripts in Active Directory. The scripts included commands to define user properties. <br/>
<img src="https://i.imgur.com/LnvDMsw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h2>Results:</h2>
Successfully built a home lab running Active Directory on a Windows Server VM using Oracle VirtualBox. I installed and configured AD DS, promoted the server to a domain controller, and used PowerShell to automate user account creation and management.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
