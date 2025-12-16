# VLAN-Based Departmental Network Design

## Overview
This project demonstrates the implementation of Virtual LANs (VLANs) to segment a network by department, following real-world enterprise networking practices. The design improves security, reduces broadcast traffic, and enables better network management.

## Network Design
| Department | VLAN ID | IP Address Range |
|-----------|--------|------------------|
| HR        | VLAN 10 | 192.168.10.0/24  |
| Sales     | VLAN 20 | 192.168.20.0/24  |
| IT        | VLAN 30 | 192.168.30.0/24  |

## Implementation Details
- VLANs were created and assigned to switch access ports
- Devices within the same department communicate within their VLAN
- Broadcast traffic is isolated per VLAN
- Inter-VLAN communication is restricted and requires Layer 3 routing

## Tools Used
- Cisco Packet Tracer
- Cisco IOS CLI

## Skills Demonstrated
- VLAN configuration
- IP addressing and subnetting
- Switch port configuration
- Network segmentation
- Basic enterprise network design

## How to Use
1. Open the `.pkt` file using Cisco Packet Tracer
2. Review VLAN configurations on the switch
3. Test connectivity within and across VLANs

## Author
Ogunleye David  
Aspiring Network Engineer
