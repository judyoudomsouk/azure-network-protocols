<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />

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

- Create our Resources
- Create Windows 10 Virtual Machine
- Create linux (Ubuntu) Virtual Machine
- Observe ICMP, SSH, DHCP, DNS, and RDP traffic

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/VdGOHwL.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download wireshark on Remote Desktop Connection.
</p>
<br />

<p>
<img src="https://i.imgur.com/xUT4YYf.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Stop ICMP traffic by denying inbound traffic from VM2.
</p>
<br />

<p>
<img src="https://i.imgur.com/fegbSAP.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Restarted ICMP traffic by allowing inbound traffic from VM2.
</p>
<br />
