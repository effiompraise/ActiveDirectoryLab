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


2.2 <p><b>VM running for DC</b></p><img src="https://imgur.com/tsLansY.png" height="80%" width="80%" alt="VM running for DC"/><br/>
2.3<P><b>Domain Controller</b></P><img src="https://imgur.com/cNfG5OF.png" height="80%" width="80%" alt="Domain Controller"/><br/>
2.4<p><b>Domain Installation</b></p><img src="https://imgur.com/9nlZl7w.png" height="80%" width="80%" alt="Domain Controller Installation"/><br/>

- <b>High Availability and Redundancy:</b> <p>To showcase my knowledge of best practices, I implemented fault tolerance mechanisms, such as backup domain controllers and data replication.</p>

- <b>User Management:</b> <p>I created and managed user accounts, granting them various permissions and roles, to mimic real-world scenarios. This involved user provisioning, password policies, and group memberships.</p>
4.1 <p><b>Creating an (OU)</b></p><img src="https://imgur.com/4pKhO2t.png" height="80%" width="80%" alt="Organizational Unit"/><br/>
4.2 <p><b>Creating a new user as Domain Admin</b></p><img src="https://imgur.com/PTtGdV0.png" height="80%" width="80%" alt="Creating a new user"/><br/>

- <b>Routing and Remote Access:</b> <p>Routing and Remote Access (RRAS) is a critical component in our Active Directory (AD) project that plays a pivotal role in managing network connectivity and access within our simulated enterprise environment.</p>
5.1 <p><b>RAS Installation</b></p><img src="https://imgur.com/gA4eNhq.png" height="80%" width="80%" alt="RAS installation"/><br/>
5.2 <p><b>RAS and NAT configuration</b></p><img src="https://imgur.com/nXN7eYU.png" height="80%" width="80%" alt="RAS and NAT configuration"/><br/>

- <b>Set Up DHCP Server on our domain</b> <p>To demonstrate how Windows 10 clients get an IP address to be able to browse the internet.</p>
- <b>Security and Access Controls:</b> <p>Security is a paramount concern in modern IT environments. I implemented robust security measures, including firewalls, access controls, and intrusion detection systems, to safeguard the AD environment.</p>
- <b>Integration with DNS and DHCP:</b> <p>I integrated DNS and DHCP services into the Active Directory infrastructure, ensuring seamless name resolution and IP address management.</p>
- <b>Monitoring and Troubleshooting:</b> <p>I utilized monitoring tools and troubleshooting techniques to diagnose and resolve issues within the AD environment, emphasizing proactive system maintenance.</p>

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>
- <b>Command Prompt</b>


<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

