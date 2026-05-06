# Cisco Packet Tracer Networking Labs

This repository contains a collection of completed Cisco Packet Tracer labs used for hands-on networking practice. The labs cover topics from basic device configuration and IP addressing to switching, routing, network services, security, IPv6, wireless networking, and enterprise infrastructure.

Each `.pkt` file represents a completed Packet Tracer activity focused on a specific networking topic. The enterprise infrastructure lab combines multiple technologies into a larger, more realistic network scenario.

## Purpose

The purpose of this repository is to document practical experience with Cisco networking technologies. These completed labs demonstrate configuration, verification, and troubleshooting work across a range of networking topics.

## Topics Covered

- Packet Tracer basics
- OSI model
- IPv4 addressing and VLSM
- Interface configuration
- VLANs and trunking
- DTP and VTP
- Ethernet LAN switching
- Spanning Tree Protocol
- HSRP
- Static routing
- Floating static routes
- EIGRP
- OSPF
- IPv6 configuration and IPv6 static routes
- GRE tunnels
- DHCP
- DNS
- NTP
- FTP and TFTP
- SSH
- NAT and PAT
- Extended ACLs
- Basic device security
- DHCP Snooping
- Dynamic ARP Inspection
- Wireless LANs
- Multilayer switching

## Enterprise Infrastructure Lab

The `Enterprise__Infrastructure.pkt` file is the main capstone-style lab in this repository. It simulates a small enterprise network and includes many technologies used together in one topology.

This lab includes work with:

- Initial router and switch setup
- Secure local authentication
- VLAN creation and trunk configuration
- Layer 2 and Layer 3 EtherChannel
- VTP configuration
- HSRP gateway redundancy
- Rapid PVST+
- OSPF routing
- Static and floating default routes
- DHCP, DNS, NTP, Syslog, SNMP, FTP, and SSH
- Static NAT and dynamic PAT
- ACL-based traffic filtering
- Port Security
- DHCP Snooping
- Dynamic ARP Inspection
- IPv6 migration basics
- Wireless LAN configuration using a WLC

The file `Enterprise_Instructions.txt` contains the original task list used for the enterprise lab.

## Repository Structure

Most files in this repository are Cisco Packet Tracer `.pkt` files. Each file is named after the topic it demonstrates, for example:

- `VLANs (Part 1).pkt`
- `OSPF (Part 3).pkt`
- `DHCP Snooping.pkt`
- `Dynamic ARP Inspection.pkt`
- `Enterprise__Infrastructure.pkt`

## Reviewing the Labs

To review the completed labs:

1. Download or clone this repository.
2. Open a selected `.pkt` file using Cisco Packet Tracer.
3. Inspect the topology, addressing, and device configurations.
4. Use verification commands to review the configuration, such as:

show ip interface brief
show running-config
show vlan brief
show interfaces trunk
show spanning-tree
show ip route
show ip ospf neighbor
ping
traceroute
