## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch


# Objective
To configure and test basic LAN connectivity between two PCs using a switch.
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram


<img width="1600" height="847" alt="98449c48-857e-4fb0-a126-cc4a9b80c42a" src="https://github.com/user-attachments/assets/ce033a03-f767-4470-a0c4-001770c98540" />

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
<img width="860" height="542" alt="98d95447-016f-4710-9d27-13f5a3d5a504" src="https://github.com/user-attachments/assets/8e1c33b2-6eaf-44aa-80aa-86c8d732b99d" />
<img width="933" height="637" alt="2ee1ecda-e8a5-4a72-8393-5d31550d26b4" src="https://github.com/user-attachments/assets/9a0abb5c-1e2a-4cb4-95d7-bc086e12afcd" />


Insert screenshots showing ping success, configuration, or simulation results.
________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
