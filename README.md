# Aeronautical-Telecommunication-Network(Cisco Packet Tracer)
**Configuration of Major Components Used**

The ATC Router (ISR4331) is responsible for managing communication between the internal network and external network.
•	Configured GigabitEthernet interface: 

o	G0/0/0 → IP Address: 10.0.0.2/24 (Connected to ASA Firewall) 
•	Enabled the interface using: 
o	no shutdown 
The router forwards data between networks and ensures proper communication in the system.

4.2 ASA Firewall Configuration
The ASA 5505 firewall provides security by controlling and filtering traffic between internal and external networks.
•	Configured VLAN interfaces: 
o	VLAN 1 (Inside) → 192.168.1.1/24 
o	VLAN 2 (Outside) → 10.0.0.1/24 
•	Assigned ports: 
o	Ethernet0/0 → Outside 
o	Ethernet0/1 → Inside 
•	Set security levels: 
o	Inside → 100 
o	Outside → 0 
•	Configured default routing: 
o	Route to external network via 10.0.0.2

4.3 Wireless Router Configuration
The wireless router (WRT300N) enables wireless communication for aircraft systems.
•	Router IP Address: 192.168.1.5 
•	Subnet Mask: 255.255.255.0 
•	Default Gateway: 192.168.1.1 
•	DHCP: Disabled 
•	Connected laptops (aircraft devices) wirelessly 
•	Ensured all devices are in the same subnet (192.168.1.0/24)

4.4 PC Configuration (Ground Systems)
Ground PCs represent ATC operators and airport systems.
•	Assigned IP addresses: 
o	PC0 → 192.168.1.2 
o	PC1 → 192.168.1.3 
o	PC2 → 192.168.1.4 
•	Subnet Mask: 255.255.255.0 
•	Default Gateway: 192.168.1.1
4.5 Server Configuration
The server provides services such as flight data storage and communication.
•	IP Address: 192.168.1.10 
•	Subnet Mask: 255.255.255.0 
•	Default Gateway: 192.168.1.1
4.6 Printer Configuration
The printer is used for printing reports and communication logs.
•	IP Address: 192.168.1.20 
•	Subnet Mask: 255.255.255.0 
•	Default Gateway: 192.168.1.1

4.7 Laptop Configuration (Aircraft Systems)
Laptops simulate aircraft communication systems.
•	Assigned IP addresses: 
o	Laptop0 → 192.168.1.6 
o	Laptop1 → 192.168.1.7 
•	Subnet Mask: 255.255.255.0 
•	Default Gateway: 192.168.1.1 
•	Connected wirelessly via wireless router




