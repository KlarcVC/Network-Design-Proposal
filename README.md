# Network-Design-Proposal
Enterprise Network Design &amp; Upgrade Project | Cisco Packet Tracer
🖧 Enterprise Network Design & Upgrade Project (Cisco Packet Tracer)

This project demonstrates the design and implementation of a segmented, scalable enterprise network using Cisco Packet Tracer, focusing on VLAN segmentation, inter-VLAN routing, and security-aware architecture.

📌 Project Objectives

Replace a flat network with a VLAN-based design

Enable secure inter-department communication

Introduce a server segment (DMZ-style design)

Ensure scalability and future expansion

Validate connectivity and routing functionality

🔧 Network Architecture & Features

5 VLANs, each mapped to a dedicated department and subnet:

VLAN 10 – Servers: 192.168.10.0/24

VLAN 20 – IT: 192.168.20.0/24

VLAN 30 – Engineering: 192.168.30.0/24

VLAN 40 – Marketing: 192.168.40.0/24

VLAN 50 – Human Resources: 192.168.50.0/24

Router-on-a-Stick configuration on the main router for inter-VLAN routing

802.1Q trunk links between the core switch and access switches

Dedicated server segment hosting:

File Server

Backup Server

Domain Server

Web Server

Static routing between routers for external/ISP connectivity

ICMP testing used to verify end-to-end communication across VLANs

🧠 Skills & Concepts Demonstrated

Network topology design

VLAN configuration & trunking

Inter-VLAN routing

IP addressing & subnetting

Enterprise switching (access & core layers)

Basic DMZ and segmentation concepts

Network testing & documentation

📂 Tools Used

Cisco Packet Tracer

Cisco routing & switching concepts

ICMP for validation and troubleshooting

📸 Topology Preview

(Screenshot included in repository showing the logical network design)

🚧 Future Improvements

Implement router and server redundancy

Add wireless access points (WAPs)

Introduce firewall rules and ACLs

Expand endpoint count for growth scenarios

👤 Author

Klarc Clarabal
Cybersecurity & Networking Student
