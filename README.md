<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
In this portfolio, I will guide you through designing, building, and optimizing an Active Directory (AD) home lab environment that closely simulates a real-world enterprise network. This hands-on project allowed me to gain invaluable experience managing user accounts, group policies, security protocols, and network configurations. The lab was set up using Oracle VirtualBox, eliminating the need for physical hardware. Here, I'll provide a step-by-step guide with explanations, scripts, and corresponding images to describe the stages in the process.
<br />

<h2>Key Achievements</h2>

- <b>Infrastructure Setup:</b> <p>I meticulously set up a virtualized environment using Oracle VirtualBox, emulating multiple servers and workstations. This allowed me to create a self-contained AD network without needing physical hardware.</p>
 

1.1. [VirtualBox Installation](https://www.virtualbox.org/) : <br/>
<img src="https://imgur.com/LuhaAnu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

1.2. [Create Virtual Machines (VMs)](https://docs.oracle.com/cd/E26217_01/E26796/html/qs-create-vm.html):
- Create VMs for Windows Server and Windows Workstations.
- Configure network settings for each VM.<br/>
<img src="https://imgur.com/27yxVNd.png" height="80%" width="80%" alt="Create Virtual Machines"/><br/>
<img src="https://imgur.com/8T8nMYo.png" height="80%" width="80%" alt="Create Virtual Machines"/><br/>

1.3 <b>Allocate Resources</b>
- Assign CPU, RAM, and storage resources to each VM.
- Ensure sufficient resources for smooth operation.
  
<img src="https://imgur.com/1k0LpKY.png" height="80%" width="80%" alt="Create Virtual Machines"/><br/>

- <b>Active Directory Deployment:</b> <p>I configured and deployed Windows Server as domain controllers, successfully establishing an Active Directory forest, domain, and organizational units (OUs).</p>
2.1 <b>[Install Windows Server](https://www.microsoft.com/en-us/software-download/windows10):</b>
<img src="https://imgur.com/wnKYInO.png" height="80%" width="80%" alt="Create Virtual Machines"/><br/>

- <b>High Availability and Redundancy:</b> <p>To showcase my knowledge of best practices, I implemented fault tolerance mechanisms, such as backup domain controllers and data replication.</p>
- <b>User Management:</b> <p>I created and managed user accounts, granting them various permissions and roles, to mimic real-world scenarios. This involved user provisioning, password policies, and group memberships.</p>
- <b>Group Policy Management:</b> <p>To demonstrate my expertise in centralized management, I implemented Group Policy Objects (GPOs) for controlling security settings, software installations, and system configurations across the network.</p>
- <b>Security and Access Controls:</b> <p>Security is a paramount concern in modern IT environments. I implemented robust security measures, including firewalls, access controls, and intrusion detection systems, to safeguard the AD environment.</p>
- <b>Integration with DNS and DHCP:</b> <p>I integrated DNS and DHCP services into the Active Directory infrastructure, ensuring seamless name resolution and IP address management.</p>
- <b>Monitoring and Troubleshooting:</b> <p>I utilized monitoring tools and troubleshooting techniques to diagnose and resolve issues within the AD environment, emphasizing proactive system maintenance.</p>

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
