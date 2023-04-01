<h1>Active Directory Project</h1>

<h2>Description</h2>
An Active Directory project involves ensuring that critical network services such as DNS, DHCP, and Group Policy are properly configured, enabling reliable and secure access to network resources. Additionally, administrators may implement redundancy and disaster recovery measures to minimize the risk of downtime and ensure that network resources remain available, even in the event of a system failure or disaster. These measures are crucial for maintaining business continuity, reducing the impact of unexpected events on the organization's network infrastructure, and ensuring that employees can work productively without interruption.
<br />


<h2>Languages and Tools</h2>

- <b>Active Directory</b> 
- <b>Powershell</b>
- <b>Windows Server</b> 
- <b>Virtualization (Oracle VirtualBox)</b> 

<h2>Operation System </h2>

- <b>Windows 10</b> (21H2)

<h2>Project walk-through:</h2>

<p align="center">
Launch the Oracle VM VirtualBox <br/>
<img src="https://imgur.com/glOQWx6.gif" height="80%" width="80%"/>
<br />

<br />
Create Virtual 2 Virtual Machines for Domain Controller and Client Computer <br/>
<img src="https://imgur.com/MId0UJV.gif" height="80%" width="80%"/>
<br />

<br />
Launch the VM using Windows Server 19 ISO <br/>
<img src="https://imgur.com/mGUiJhn.gif" height="80%" width="80%"/>
<br />


<br />
Check to see which one is your main internet and rename it (easier to locate)  <br/>
<img src="https://imgur.com/4Nqkmsv.gif" height="80%" width="80%"/>
<br />

<br />
Change the IP Address for the Internal Internet  <br/>
<img src="https://imgur.com/CXYOp91.gif" height="80%" width="80%"/>
<br />

<br />
Install Active Directory and set up your new domain  <br/>
<img src="https://imgur.com/HuXIl2X.gif" height="80%" width="80%"/>
<img src="https://imgur.com/BjsG4Pg.gif" height="80%" width="80%"/>
<br />

<br />
Install NAT for Client Computer to connect through Domain  <br/>
<img src="https://imgur.com/QvsMpLd.gif" height="80%" width="80%"/>
<img src="https://imgur.com/Q181W7R.gif" height="80%" width="80%"/>
<img src="https://imgur.com/nrnuoGH.gif" height="80%" width="80%"/>
<br />

<br />
Install DHCP and set up  <br/>
<img src="https://imgur.com/pnCb482.gif" height="80%" width="80%"/>
<img src="https://imgur.com/3UBAUsk.gif" height="80%" width="80%"/>
<br />

<br />
Run Powershell scipt to create users (Lab Experience)  <br/>
<img src="https://imgur.com/P88YJVm.gif" height="80%" width="80%"/>
<img src="https://imgur.com/y20narI.gif" height="80%" width="80%"/>
<br />

<br />
Create a Client Virtual Machine for testing  <br/>
<img src="https://imgur.com/C9y2A2Z.gif" height="80%" width="80%"/>
<br />

<br />
Check if the machine has connected to the domain internet  <br/>
<img src="https://imgur.com/jJFH9Wf.gif" height="80%" width="80%"/>

</p>
