<h1>Setting Up Home Lab - Active Directory</h1>

 ### Setting up a Home lab for Future projects ##

<h2>Description</h2>
Creating a home lab and using active directroy to implemate over 1k users. (Step by Step guide below)

<h2>Layout Example</h2>
<p align="center">
 <br/>
<img src="https://i.imgur.com/0Dv0JC4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />


<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>
- <b>VirtualBox on MAC OS</b>
- <b>https://github.com/joshmadakor1/AD_PS.git (Link to download User list or create new one)</b>


<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Windows Server 2019</b>

<h2>Walk-Through:</h2>

<p align="center">
Set up Virtual machines - Windows 10 and Windows Server 2019 <br/>
<img src="https://i.imgur.com/qmdE7iX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />


<p align="center">
Checking Internet Config <br/>
<img src="https://imgtr.ee/images/2023/05/12/lCrAr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
 

<p align="center">
Check IPv4 address for internet and internal networks <br/>
<img src="https://i.imgur.com/mPqnxsl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
 

<p align="center">
Configure Ips for Internal network  <br/>
<img src="https://imgtr.ee/images/2023/05/12/lCxLY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 


<p align="center">
Install AD/Domain Services  <br/>
<img src="https://imgtr.ee/images/2023/05/12/lCWks.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
 

<p align="center">
Promote Server to DC  <br/>
<img src="https://imgtr.ee/images/2023/05/12/lCIb1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
 
 
<p align="center">
Add new Forest (mydomain.com)  <br/>
<img src="https://imgtr.ee/images/2023/05/12/lCeAX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
 
<p align="center">
ADD FOLDER _ADMIN <br/>
<img src="https://imgtr.ee/images/2023/05/12/lCEL3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
 
<p align="center">
Add self as Admin <br/>
<img src="https://imgtr.ee/images/2023/05/12/lCcfL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
 
<p align="center">
Add User to Domain Admins <br/>
<img src="https://imgtr.ee/images/2023/05/12/lCfYF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
 

<p align="center">
Add Remote access for client access <br/>
<img src="https://imgtr.ee/images/2023/05/12/lC3RU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
 

<p align="center">
Add Routing for Roles <br/>
<img src="https://imgtr.ee/images/2023/05/12/lCPbB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
 
 
<p align="center">
Set up DC Routing and remote  (NAT) <br/>
<img src="https://imgtr.ee/images/2023/05/12/lCzhQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br /> 
  

<p align="center">
Completed RAS AND NAT setup <br/>
<img src="https://imgtr.ee/images/2023/05/12/lCglI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
 
<p align="center">
Adding DHCP server <br/>
<img src="https://imgtr.ee/images/2023/05/12/lIGi7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  
 
<p align="center">
Configure (new scope) IPv4/IPv6  <br/>
<img src="https://imgtr.ee/images/2023/05/12/lIOnA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
 
<p align="center">
Add the Ip address range for leases <br/>
<img src="https://imgtr.ee/images/2023/05/12/lIRZ2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  
 
<p align="center">
Proof for DHCP IPv4 and 6 active <br/>
<img src="https://imgtr.ee/images/2023/05/12/lIotz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  
 
<p align="center">
Powershell- adding users <br/>
<img src="https://imgtr.ee/images/2023/05/12/lI9Rx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
  
<p align="center">
cd command into master user folder to run <br/>
<img src="https://imgtr.ee/images/2023/05/12/lIUpJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
   
<p align="center">
ls command <br/>
<img src="https://imgtr.ee/images/2023/05/12/lInXr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
    
<p align="center">
Powershell (running adding users from readme.txt)<br/>
<img src="https://imgtr.ee/images/2023/05/12/lI0vn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
 
<p align="center">
Check if usersers added from powershell<br/>
<img src="https://imgtr.ee/images/2023/05/12/lI8Nc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
  
<p align="center">
On windows machine check IPconfig<br/>
<img src="https://imgtr.ee/images/2023/05/12/lIJiY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
   
<p align="center">
Adding Client1 to mydomain.com<br/>
<img src="https://imgtr.ee/images/2023/05/12/lIlyq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
    
<p align="center">
Adding Client1 to mydomain.com<br/>
<img src="https://imgtr.ee/images/2023/05/12/lIlyq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
                                      <h1> !!!!!Process complete!!!!!</h1>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
