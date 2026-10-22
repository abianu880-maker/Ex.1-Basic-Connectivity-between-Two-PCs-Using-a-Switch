## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 	22.10.2026	

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

Insert the network topology from Packet Tracer (Screenshot or drawing)

________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)
<img width="1920" height="1080" alt="Screenshot (590)" src="https://github.com/user-attachments/assets/9c280a7f-31d4-4954-804b-6dc76c41a044" />

<img width="1920" height="1080" alt="Screenshot (586)" src="https://github.com/user-attachments/assets/ee2aa9cf-b971-448d-a7dc-2ca048a142cb" />
<img width="1920" height="1080" alt="Screenshot (585)" src="https://github.com/user-attachments/assets/06789fce-871d-4256-ab1f-cabda306b4e3" />
<img width="1920" height="1080" alt="Screenshot (584)" src="https://github.com/user-attachments/assets/d97e87fb-9e28-4c30-a055-6d4d2e4738ae" />
<img width="1920" height="1080" alt="Screenshot (587)" src="https://github.com/user-attachments/assets/05e5c52c-83f7-4788-9c09-f30177adaaaa" />
<img width="1920" height="1080" alt="Screenshot (587)" src="https://github.com/user-attachments/assets/f32e6128-be35-423b-92be-acd9b8f1a530" />
<img width="1920" height="1080" alt="Screenshot (589)" src="https://github.com/user-attachments/assets/22b85972-94c8-4b37-8a3b-61ae002cfc20" />

Insert screenshots showing ping success, configuration, or simulation results.
________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
