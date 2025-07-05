Campus_Network_Design_Project

📡 Overview

A redundant campus network design built in Cisco Packet Tracer for structured lab training and scalable real-world campus environments.

This project includes:

4 Routers (Primary + Backup structure)

2 Multi-Layer Switches with Inter-VLAN Routing

VLAN segmentation for organized device groups

OSPF dynamic routing between routers and MLS

NAT configuration for internet access

Redundancy for high availability



---

🖥️ Topology

The design uses:

Router0 and Router1: Main and backup with OSPF and NAT

Router2 and Router3: Second pair with redundancy

MLS0 and MLS1: Multi-Layer Switches acting as gateways with VLAN segmentation

End devices (PCs, printers, tablets) grouped under VLANs with structured IP plans

All devices use MLS as their default gateway.


Routers handle internet NAT while MLS devices handle VLAN and inter-VLAN routing.


---

🌐 Technologies Used

Cisco Packet Tracer for simulation

OSPF for dynamic routing

NAT for internet access

VLANs for network segmentation

HSRP (optional future extension) for gateway redundancy



---

⚙️ How to Open

1. Download project-1.1.pkt.


2. Open using Cisco Packet Tracer.


3. Review device configurations (Routers and MLS) using CLI inside PT.


4. Test connectivity using ping between VLANs and out to the simulated internet.




---

🛠️ Future Improvements

Implement HSRP on MLS and routers for full failover.

Add DHCP services for automatic IP management.

Add monitoring using SNMP or Syslog for lab practice.



---
