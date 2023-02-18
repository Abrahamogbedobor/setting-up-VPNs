<p align="center">
<img src="https://i.imgur.com/gnC9oL4.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Virtual Private Networks(VPN) Setup and Usage in Azure</h1>
This tutorial outlines setup and usage of VPN (Proton) within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Set-up and use VPNs within Azure Computer](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Proton VPN Server
- PowerShell

<h2>Operating Systems Used</h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>VPN Usage and Configuration Steps</h2>

- Documenting IP Address of Home Computer Using open source website (whatismyipddress.com) 
- Connecting Home Computer with Microsoft Azure VMs Using RDC (Then re-browse into whatismyipaddress.com)
- Signing up and Download of Proton VPN Client on Microsoft Azure
- Using Proton VPN Server in Azure to browse into (whatismyipaddress.com)
- 

<h2>Setup and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/bGVSNxB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/dtYNXAM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the above figure, home PC was first used to browse into an open source website (whatismyipaddress) with the aim of documenting its IP-address. Again, 
</p>
<br />

<p>
<img src="https://i.imgur.com/rFx9wGt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/gjsmhvE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The above figure shows a resource groups been created in Azure with the aim of setting up a virtual machine that was then connected with home PC using RDC(Remote Desktop Connection). In creating the resource group, an option of choosing a subscription was given as shown above (Azure for student) and the resource group was named RG-Lab-1 and London as its region depending where the organisation data centre was based. Notably, some countries have some strict rules that prevent organisation from shifting any of its resources outside its region.
</p>
<br />

<p>
<img src="https://i.imgur.com/QbIzjDX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/EJw69EA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The above figure is a resource created inside the resource group container (RG-Lab-1). This resource is referred to as storage account that is used for storing fils with wide range of functionality. Notably, resources in azure could be related to a google drive with more capability. In this lab, the resource named abrahamlab is been used as a folder where a bunch of files are stored.
</p>
<br />

<p>
<img src="https://i.imgur.com/3nWuAVG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As shown above the text file named vpn-lab1.txt was stored inside a resource container vpn. Notably, the file is been opened and could be edited, downloaded and share within and outside the organisation as well as many more functionalities.
</p>
<br />

<p>
<img src="https://i.imgur.com/bhqwJB7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/PrTg2Ho.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In other not to incurred too much cost and overused the available credit as this lab was done under free subscription, the baove figure shows how resource grouop was deleted after each successful lab has been done. Also, figure2 above shows cost analysis that enables organiosation to know what resources is costing them more and hiow to reduce it.
</p>
<br />

<p>
<img src="https://i.imgur.com/bhqwJB7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Haven't succesfully connected to azure, the above figure shows the steps used in creating virtual machine in azure then using RDP to connect home PC with the VMs that was created. Thereafter, the IP address of the VM after RDP connection was then be documented on a textfile as shown above.
</p>
<br />


<p>
<img src="https://i.imgur.com/bhqwJB7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The above step involves connecting azure virtual machine to home pc using RDP (Remote Desktop Protocol). After the above connection, the open source website WHATISMYIPADDRESS.COM was then browse to document the VMs IP address as shown above.
</p>
<br />
