<h1>SOHO Project</h1>


<h2>Overview</h2>
The SOHO Project I created explores the Cisco Packet Tracer program. Here is the breakdown of this project.<br/><br/>

Gleton Enterprises is a fast-growing company in Detroit, Michigan with more than 2 million customers globally. The company deals with manufacturing and selling of auto parts, which are operated from the headquarters. The company intends to open a branch in Pontiac, Michigan. Thus, the company requires young IT graduates to design the network for the branch. The network is intended to operate separately from the HQ network. Being a small network, the company has the following requirements during implementation:<br/><br/>

• One router and one switch are to be used (all CISCO products).<br/>
• A 3 departments (Admin/IT, Finance/HR, and Customer Service/Reception).<br/>
• Each department is required to be in different VLANS.<br/>
• Each department is required to have a wireless network for the users.<br/>
• Host devices in the network are required to obtain IPv4 addresses automatically.<br/>
• Devices in all the departments are required to communicate with each other.<br/><br/>

Assume the ISP gave out a base network of 192.168.1.0, as the young network engineer who has been hired, designed, and implement a network considering the above requirements. <br/><br/>


<h2>Technologies Implemented:</h2>

- <b>Creating a Simple Network using a Router and Access Layer Switch.</b> 
- <b>Connecting Networking devices with Correct cabling.</b> 
- <b>Creating VLANs and assigning ports VLAN numbers.</b> 
- <b>Subnetting and IP Addressing.</b> 
- <b>Configuring Inter-VLAN Routing (Router on a stick).</b> 
- <b>Configuring DHCP Server (Router as the DHCP Server).</b> 
- <b>Configuring WLAN or wireless network (Cisco Access Point).</b> 
- <b>Host Device Configurations.</b> 
- <b>Test and Verifying Network Communication.</b> 

<br />
<h2>Program walk-through:</h2>
<!--
<p align="center">
 --!>
 
<br />

• I selected my devices and connected all the devices into different departments. <br/><br/>
<img src="https://i.imgur.com/6Qx42BV.png" height="80%" width="80%" alt=""/>
<img src="https://i.imgur.com/fMMjJ3p.png" height="80%" width="80%" alt=""/>
<br />
<br />

• Subnetting the network to each department. <br/><br/>
<img src="https://i.imgur.com/S2UB7BC.png" height="80%" width="80%" alt=""/>
<img src="https://i.imgur.com/KJcUgki.png" height="80%" width="80%" alt=""/>
<img src="https://i.imgur.com/1H5hIRJ.png" height="80%" width="80%" alt=""/>
<br />
<br />

<br/>
• Creating the VLANS. <br/><br/>
<img src="https://i.imgur.com/M5TIOou.png" height="80%" width="80%" alt=""/>
<br />
<br />

•  Setting up WIFI for each department. <br/><br/>
<img src="https://i.imgur.com/CoJeMS2.png" height="80%" width="80%" alt=""/> 
<img src="https://i.imgur.com/icfcEUq.png" height="80%" width="80%" alt=""/>
<img src="https://i.imgur.com/7xnJs4s.png" height="80%" width="80%" alt=""/> 
<br />
<br />

• Switch config. <br/><br/>
<img src="" height="80%" width="80%" alt=""/>
<br />
<br />

• Router config. <br/><br/>
<img src="" height="50%" width="50%" alt=""/>
<br />
<br />

• VLAN config. <br/><br/>
<img src="" height="80%" width="80%" alt=""/>
<img src="" height="80%" width="80%" alt=""/>
<br />
<br />

• Setting up DHCP. <br/><br/>
<img src="" height="6%" width="60%" alt=""/>
<br />
<br />



 <!--
<br />
<br />
Users Name List to input in PowerShell: <br/>
<img src="https://i.imgur.com/C79ylHN.png" height="80%" width="80%" alt=""/>
<br />
<br />
Inputing user list into PowerShell script:  <br/>
<img src="https://i.imgur.com/1nXLyo7.png" height="80%" width="80%" alt=""/>
<br />
<br />
Can now find users after running script:  <br/>
<img src="https://i.imgur.com/7NjkmL7.png" height="80%" width="80%" alt=""/>
<br />
<br />
 --!>

 
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
