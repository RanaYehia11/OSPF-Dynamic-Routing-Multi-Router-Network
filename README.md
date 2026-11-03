# OSPF Dynamic Routing – Multi-Router Network

## 📌 Project Overview

This project demonstrates the configuration and implementation of **OSPF (Open Shortest Path First)** as a dynamic routing protocol using Cisco Packet Tracer.

The network consists of three routers connecting two separate LANs through multiple network segments. OSPF is configured to enable dynamic route exchange between routers and provide end-to-end communication across the network.

## 🖥️ Network Topology

![OSPF Network Topology](topology.png)

## 🛠️ Technologies & Concepts

- Cisco Packet Tracer
- OSPF Dynamic Routing Protocol
- IPv4 Addressing
- LAN Configuration
- Router-to-Router Connectivity
- Static vs. Dynamic Routing Concepts
- ICMP (Ping) Connectivity Testing
- Network Troubleshooting

## 🌐 Network Design

The topology includes:

- **3 Routers:** Router0, STP, and Router1.
- **2 Switches:** Connecting end devices within each LAN.
- **4 PCs:** Two PCs on each LAN.
- **Multiple Network Segments:** Connecting the routers together.

### IP Addressing

| Network Segment | Network Address |
|---|---|
| Left LAN | 192.168.1.0 |
| Router0 – STP Link | 2.2.2.0 |
| STP – Router1 Link | 3.3.3.0 |
| Right LAN | 192.168.2.0 |

*Note: Refer to the Packet Tracer configuration for the complete IP addressing and subnet masks.*

##  Implementation Steps

1. Designed the network topology in Cisco Packet Tracer.
2. Configured IP addresses on router interfaces.
3. Configured IP addressing and default gateways on all PCs.
4. Established connectivity between routers.
5. Enabled OSPF on all three routers.
6. Advertised the connected networks through OSPF.
7. Verified OSPF neighbor relationships and routing table entries.
8. Performed end-to-end connectivity tests using ICMP ping.

##  Verification & Testing

The network was tested to ensure successful communication between devices on different LANs.

**Connectivity Tests:**

- PC2 → PC3 (Same LAN)
- PC4 → PC5 (Same LAN)
- PC2 → PC4 (Different LANs)
- PC2 → PC5 (Different LANs)
- PC3 → PC4 (Different LANs)
- PC3 → PC5 (Different LANs)

**Expected Result:** All PCs can successfully communicate with each other through the OSPF-enabled network.

