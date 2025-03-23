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
- Ubuntu Server 20.04



<h2>Actions and Observations</h2>

![image](https://github.com/user-attachments/assets/5ffd7e35-db1c-4b08-a9bc-a213827ec80d)

</p>
<p>
 - Create 2 VM's
</p>
<br />

![image](https://github.com/user-attachments/assets/4ed9b6fd-09dc-492a-9036-4f51428927c2)

</p>
<p>
 - Install Wireshark on the windows VM
</p>
<br />

![image](https://github.com/user-attachments/assets/7cfc86de-4d32-42f4-9b75-240b50010bfe)

</p>
<p>
- Filter for ICMP traffic and observe the properties
</p>
<br />


<p>

  
![image](https://github.com/user-attachments/assets/86169939-3167-46f2-885a-9b1b237fab0e)

![image](https://github.com/user-attachments/assets/8f7306ea-2900-47f9-a616-91aad8f37b87)

</p>

- Configure Linux VM to block inbound ICMP requests and observe
  - Turn it back on when you're done
</p>
<br />


![image](https://github.com/user-attachments/assets/b2eb4aca-27fa-449f-93df-dca4c2b236a5)

![image](https://github.com/user-attachments/assets/1102bec9-c5bc-46ad-bb0d-a82c9b55ba8b)

![image](https://github.com/user-attachments/assets/984f99a1-b08a-488b-a5c9-cac4167cb766)

![image](https://github.com/user-attachments/assets/b1906975-c29e-4831-b5c5-a64666a980d6)

</p>
<p>
- Filter for SSH, DHCP, DNS and, RDP  and observe traffic
</p>
<br />


