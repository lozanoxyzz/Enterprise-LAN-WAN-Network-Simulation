# Enterprise LAN/WLAN Network Simulation

This project simulates a redundant enterprise LAN/WLAN infrastructure built in Cisco Packet Tracer.  
It demonstrates the design and configuration of VLANs, redundancy mechanisms, Layer 2 security, and wireless integration within an enterprise environment.

---

## 1. Project Overview

The network topology provides redundancy at both the switching and gateway levels.  
It includes four interconnected switches using EtherChannel and redundant routers implementing HSRP as the default gateway.  
A dedicated stub network is used for the DHCP server, and two access points provide wireless coverage in separate zones.

---

## 2. Logical Topology

The logical topology interconnects the switches and routers through redundant links to ensure high availability.  
Each VLAN is assigned to a specific subnet and configured for inter-VLAN routing through HSRP.

