<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Install WireShark
- Filter for ICMP traffic only
- Filter for SSH traffic only
- Filter for DCHP traffic only
- Deny traffic 

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/WdjgGJp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Installing wireshark in order to watch traffic.
</p>
<br />

<p>
<img src="https://i.imgur.com/oBm2TxG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I opened powershell then pinged my VM's private ip address. Afterwards, I used wireshark to traffic the ICMP
</p>
<br />

<p>
<img src="https://i.imgur.com/sfdDMJt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I restarted the current capture and then filtered for ssh.
</p>
<br />
