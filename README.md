# Enterprise Network Design, Security & Incident Response Lab

## Project Overview

This project simulates the design, configuration, security and troubleshooting of a small enterprise network using Cisco Packet Tracer.

The objective is to develop practical networking and cybersecurity skills through realistic infrastructure deployment and incident investigation scenarios.

## Lab 01: Basic LAN Connectivity

**Objective:** Build and verify communication between two computers connected through a Cisco 2960 switch.

### Network Configuration

| Device | IP Address | Subnet Mask | Switch Port |
|---|---|---|---|
| PC-Finance | 192.168.10.10 | 255.255.255.0 | Fa0/1 |
| PC-HR | 192.168.10.20 | 255.255.255.0 | Fa0/2 |

### Activities Completed

- Connected two PCs to a Cisco 2960 switch using copper straight-through cables.
- Configured static IPv4 addresses.
- Verified connectivity using ICMP ping.
- Investigated ARP resolution and IP-to-MAC address mappings.
- Examined the switch's dynamic MAC address table.
- Investigated an initially empty MAC address table and verified MAC learning after generating fresh network traffic.

### Results

Both computers successfully communicated within the same subnet. The switch learned two dynamic MAC addresses associated with the connected interfaces.

### Key Learning Outcomes

Developed practical understanding of OSI Layers 1–3, IPv4 addressing, ARP, ICMP, Ethernet switching, MAC address learning and basic network troubleshooting.

## Tools

- Cisco Packet Tracer
- Wireshark (planned for later exercises)
- Visual Studio Code (planned for later exercises)

## Next Lab

Lab 02: VLAN Configuration and Network Segmentation.
