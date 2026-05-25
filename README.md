# Multi-Site-Enterprise-Network-Project
This project is a practical CCNA-level multi-site enterprise network simulation designed and implemented using Cisco Packet Tracer. It represents a fictional company with a London Head Office, Norwich Branch Office, and Remote Office, connected through a routed WAN infrastructure.  

The project demonstrates key networking concepts including VLAN segmentation, trunking, inter-VLAN routing, OSPF dynamic routing, DHCP, DHCP relay, DNS simulation, NAT/PAT, ACL-based access control, STP, EtherChannel, wireless networking, and structured troubleshooting.  
  
The aim of the project is to build a realistic enterprise network environment, document the design and implementation phase by phase, and publish the topology, configurations, testing evidence, and troubleshooting scenarios on GitHub as part of a professional Network Engineering portfolio.  

## Business Scenario

Faux Tech Ltd requires a scalable and segmented enterprise network across multiple sites. The design must support internal users, servers, guest access, wireless connectivity, inter-site communication, internet access, and basic security controls.

## Network Topology

![Logical Network Topology](diagrams/logical-topology.png)

## Key Technologies Used

- VLANs and trunking
- Inter-VLAN routing
- OSPF dynamic routing
- DHCP and DHCP relay
- DNS simulation
- NAT/PAT for internet access
- ACL-based traffic filtering
- STP and EtherChannel
- Wireless and guest network segmentation
- Basic device hardening
- Network troubleshooting and validation

## Sites Included

| Site | Address Range | Purpose |
|---|---|---|
| London Head Office | `10.10.0.0/16` | Main site, servers, internet breakout |
| Norwich Branch | `10.20.0.0/16` | Branch office network |
| Remote Office | `10.30.0.0/16` | Small remote site |
| WAN Links | `172.16.0.0/30` ranges | Point-to-point site links |

## VLAN Summary

| VLAN | Name | Purpose |
|---:|---|---|
| 10 | IT | IT users and administration |
| 20 | HR | HR department users |
| 30 | Finance | Finance department users |
| 40 | Operations | Operations users |
| 50 | Servers | Internal network services |
| 60 | Guest | Guest internet-only access |
| 99 | Management | Network device management |

## Project Phases

1. Project scope and requirements
2. Topology, IP addressing, and VLAN design
3. Switching, VLANs, trunking, and inter-VLAN routing
4. Multi-site routing with OSPF
5. DHCP, DNS, NAT, and internet access
6. Security, redundancy, and wireless integration
7. Troubleshooting scenarios and final documentation

## Repository Structure

```text
docs/             Project documentation
diagrams/         Network topology diagrams
packet-tracer/    Packet Tracer project files
configs/          Router and switch configurations
screenshots/      Testing and verification evidence
troubleshooting/  Fault scenarios and resolutions
```

## Skills Demonstrated

This project demonstrates practical understanding of enterprise network design, routing, switching, segmentation, access control, network services, redundancy, and troubleshooting.

## Final Outcome

The final deliverable will include a complete Packet Tracer network, topology diagrams, IP addressing plan, VLAN design, device configurations, testing evidence, and documented troubleshooting scenarios.

## Author

Prasad Kadam  
Github: @prasaddkadam  
LinkedIn: @prasaddkadam  
Website: www.prasadkadam.com
