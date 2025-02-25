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

- (Observe ICMP Traffic)
- (Configuring a Firewall [Network Security Group])
- (Observe SSH Traffic)

<h2>Actions and Observations</h2>

![image](https://github.com/user-attachments/assets/a21716a8-5011-4721-9599-ef20a9494ed4)

If using Mac, install Microsoft Remote Desktop
Use Remote Desktop to connect to your Windows 10 Virtual Machine

![image](https://github.com/user-attachments/assets/b4657354-0c26-42f0-b460-7304cdf3c50f)

Within your Windows 10 Virtual Machine, Install Wireshark
Open Wireshark and start packet capture

![image](https://github.com/user-attachments/assets/9c7831af-a135-4cea-90da-7f29604e9b47)


(Configuring a Firewall [Network Security Group])
Initiate a perpetual/non-stop ping from your Windows 10 VM to your Ubuntu VM

![image](https://github.com/user-attachments/assets/9130503a-c295-4c68-b984-a885c422f03d)


(Observe SSH Traffic)
Log back into the windows-vm
Back in Wireshark, start a packet capture up
Filter for SSH traffic only
