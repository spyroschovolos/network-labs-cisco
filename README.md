# Cisco Networking Labs & Topology Simulations

This repository contains advanced network simulations and diagnostic reports developed during the Computer Communications course at the University of the Aegean (ICSD). It demonstrates practical knowledge of L2/L3 networking, switching protocols, and system-level troubleshooting.


## 🛠️Key Technical Areas

• Spanning Tree Protocol (STP): Implementation and analysis of loop prevention in redundant switch topologies. Root Bridge election process and port state identification (Root, Designated, Alternate).

• Routing & Switching: Inter-VLAN routing, static routing configuration, and analysis of IPv4 routing tables.

• Network Diagnostics: Hands-on experience with ARP, ICMP (Ping/Traceroute), and DHCP protocols to identify and resolve connectivity issues.

• Hardware Interface Management: Identifying MAC addresses, vendor specifications, and managing network interface drivers.


## Repository Structure

• /PKT_FIles (.pkt): Original Cisco Packet Tracer files for various network topologies (Star, Mesh, Redundant).

• /PDF_Reports (.pdf): Detailed technical documentation explaining the logic, screenshots of CLI commands (show ip route, show spanning-tree), and diagnostic results.


## Skills Demonstrated

• Network Design: Building scalable topologies in Cisco Packet Tracer.

• CLI Proficiency: Configuring Cisco IOS devices via command line.

• Troubleshooting: Analyzing ARP tables and DNS resolution errors to fix LAN/WAN issues.


## Sample Topology Logic
In the STP lab, I successfully configured a redundant network where Switch 3 was elected as the Root Bridge, and specific ports were automatically blocked (Alternate state) to prevent broadcast storms, ensuring 100% network stability.

![Network Topology](topology_screenshot.png)
