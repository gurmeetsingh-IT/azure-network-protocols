# azure-network-protocols

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
- Ubuntu Server 24.04

<h2>High-Level Steps</h2>

- Create a Network Security Group (NSG)
- Associate the NSG
- Define Security Rules to Inspect Traffic
- Traffic Evaluation and Logging

<h5>Observations <h5>

<img width="1918" height="1001" alt="Screenshot 2026-06-26 163055" src="https://github.com/user-attachments/assets/7ffa4bed-7a49-470a-9062-840e330e1b36" />

</p>
<p>
Cloud Infrastructure Setup (Microsoft Azure)

- Created a cloud workspace to organize and manage project resources
- Set up a Windows 10 computer in the cloud
- Set up an Ubuntu (Linux) computer in the same cloud environment
- Created secure login credentials for both cloud computers.
- Connected both cloud computers to the same private network so they could communicate with each other.
- Gained hands-on experience with cloud computing, virtual machines, networking, and resource management using Microsoft Azure.
</p>
<br />

<p>
  <img width="1913" height="1067" alt="Screenshot 2026-06-26 165216" src="https://github.com/user-attachments/assets/a4eec315-3cbb-4ebe-a7e3-1d13218c68b9" />
</p>
<p>
Remote Access & Wireshark Setup

- Installed Microsoft Remote Desktop on Windows 11 to enable secure remote access to a Windows 10 virtual machine
- Accessed and used a Windows computer remotely to complete tasks and practice
- Installed Wireshark to capture and analyze network traffic
- Observed how computers send and receive information to better understand how devices communicate.
</p>
<br />

<p>
<img width="1918" height="1152" alt="image" src="https://github.com/user-attachments/assets/679d8a36-b51b-4a93-b616-98827f6d8d40" />
<img width="1920" height="1143" alt="image" src="https://github.com/user-attachments/assets/87386044-fa3d-461f-a04e-274e6da0ebe7" />

</p>
<p>
Network Traffic Analysis (ICMP Testing)

- Monitored network activity while computers communicated with each other.
- Located the network address of another computer to test the connection.
- Tested communication between two virtual computers to confirm they could connect successfully.
- Reviewed the results to verify the connection was working and identify any issues.
</p>
<br />

</p>
<img width="1912" height="1092" alt="image" src="https://github.com/user-attachments/assets/a7a7e6f7-ad18-45c0-b961-abe9dc58de58" />
</p>
<p>
<p>
<img width="1920" height="1152" alt="image" src="https://github.com/user-attachments/assets/ef2fe992-d973-4824-a367-90160de634d6" />
</p>
<p>
<p>
<img width="1917" height="1152" alt="image" src="https://github.com/user-attachments/assets/a3d7a3f2-893d-4a8b-8886-b220b1cefa2f" />
</p>
<p>
Network Security Group (NSG) Testing & Traffic Conrol

- Tested the connection between two virtual computers to make sure they could communicate
- Changed security settings to temporarily block communication between the computers (As you can see from the second picture it timed out)
- Observed how the blocked connection affected communication
- Restored the security settings to allow the computers to ommunicate again
- Confirmed the connection was working properly after the changes
- Gained hands-on experience with computer security settings and troubleshooting network connections


