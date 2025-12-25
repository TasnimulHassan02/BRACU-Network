# BRACU-Network
This project implements a network design for BRAC University (BRACU) covering six departments using Cisco Packet Tracer:
CSE, MNS, EEE, BBS, LAW, BIL. The design follows given constraints on topology, IP addressing, routing, and server configuration to ensure full connectivity and fault tolerance.

🏗️ Network Design
Each department has one router
MNS → CSE only
CSE, EEE, BBS connected via a switch
CSE, LAW, BIL directly connected.

Each department includes:


2 PCs,

1 Printer,

1 Email Server,

Web Servers:
CSE → www.cse.sds.bracu.ac.bd,
MNS → www.mns.sds.bracu.ac.bd,

Central DNS Server located in CSE.



✅ Testing

All devices can ping each other
Web, Email, DNS, and DHCP services work correctly
Failover paths verified by disabling links



📁 Deliverables

Cisco Packet Tracer file (.pkt)

Network topology diagram

VLSM tree

IP address table

Router configuration commands


🛠 Tools

Cisco Packet Tracer

RIP v2

VLSM

DNS, DHCP, Web & Email Servers
