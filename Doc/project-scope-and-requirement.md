# Phase 1: Project Scope and Requirements

## Project Title

**Multi-Site Enterprise Network Design and Implementation**

## Project Overview

This project is a CCNA-level network engineering portfolio project built using Cisco Packet Tracer. It simulates the design and implementation of a multi-site enterprise network for a fictional organisation with a head office, branch office, and remote office.

The project will demonstrate practical networking skills including VLAN segmentation, inter-VLAN routing, OSPF, DHCP, NAT/PAT, ACLs, STP, EtherChannel, wireless networking, and structured troubleshooting.

The final outcome will be a fully documented network design with topology diagrams, configuration files, Packet Tracer files, testing evidence, and troubleshooting scenarios.

## Business Scenario

Faux Technologies Ltd is a growing organisation with three UK-based locations:

- London Head Office
- Norwich Branch Office
- Remote Office

The company requires a scalable and secure network that allows users across all sites to communicate, access shared services, connect to the internet, and remain separated by department for security and management purposes.

The London Head Office will act as the main site, hosting central network services such as DHCP, DNS simulation, server resources, network management, and internet breakout.

## Project Purpose

The purpose of this project is to build a realistic enterprise-style network that demonstrates hands-on networking knowledge rather than only theoretical understanding.

This project is designed to showcase practical experience with routing, switching, segmentation, security controls, network services, and troubleshooting.

## Project Objectives

The main objectives of this project are to:

- Design a multi-site enterprise network topology.
- Segment users and services using VLANs.
- Implement inter-VLAN routing.
- Connect multiple sites using OSPF dynamic routing.
- Provide DHCP services to users across different VLANs and sites.
- Configure NAT/PAT for simulated internet access.
- Apply ACLs to control traffic between departments.
- Add basic redundancy using STP and EtherChannel.
- Include corporate and guest wireless network access.
- Document testing, validation, and troubleshooting scenarios.

## Sites Included

| Site | Purpose |
|---|---|
| London Head Office | Main site hosting core switching, servers, DHCP/DNS, management, and internet breakout |
| Norwich Branch Office | Branch network connected to the head office over WAN |
| Remote Office | Smaller remote site with basic user connectivity |
| ISP / Internet | Simulated external network for internet access testing |

## Departments and Network Segments

The network will be segmented into the following logical areas:

| VLAN | Name | Purpose |
|---:|---|---|
| 10 | IT | IT users and administrative access |
| 20 | HR | HR department users |
| 30 | Finance | Finance department users |
| 40 | Operations | Operations department users |
| 50 | Servers | Internal services such as DHCP, DNS, and web simulation |
| 60 | Guest | Guest internet-only access |
| 99 | Management | Management access for routers and switches |

## High-Level Requirements

The network must support:

- Separate VLANs for different departments.
- Routing between approved internal networks.
- Dynamic routing between sites using OSPF.
- Central or relay-based DHCP services.
- Simulated internet access using NAT/PAT.
- Guest access restricted from internal company networks.
- IT access to management and infrastructure devices.
- Basic switch redundancy and loop prevention.
- Wireless access for corporate and guest users.
- Clear documentation and testing evidence.

## Security Requirements

The network should enforce basic access control rules:

- Guest users must only access the internet.
- Guest users must not access internal VLANs.
- Non-IT users must not access the Management VLAN.
- HR and Finance traffic should be restricted from each other where appropriate.
- IT users should be allowed administrative access to infrastructure devices.
- Unused switch ports should be disabled.
- SSH should be used for device management where supported.

## In Scope

This project includes:

- Logical network design
- IP addressing and VLAN planning
- Cisco Packet Tracer implementation
- Switching and trunking
- Inter-VLAN routing
- OSPF routing
- DHCP and DHCP relay
- NAT/PAT
- ACL security rules
- STP and EtherChannel
- Basic wireless integration
- Testing and troubleshooting documentation

## Out of Scope

The following items are not included in the initial project scope:

- Real physical Cisco hardware
- Production firewall appliances
- BGP, MPLS, or SD-WAN
- Site-to-site VPN
- Cisco ISE or 802.1X
- Advanced wireless controller deployment
- Cloud integration
- Network automation using Python or Ansible

These may be considered as future project enhancements.

## Assumptions

This project assumes:

- Cisco Packet Tracer will be used as the simulation platform.
- The network is designed for learning and portfolio demonstration.
- The London Head Office will host central services.
- All sites require internal connectivity.
- Internet access will be simulated.
- Packet Tracer limitations may require simplified versions of some enterprise features.

## Success Criteria

Phase 1 will be considered complete when:

- The project purpose is clearly defined.
- The business scenario is documented.
- The sites and departments are identified.
- The high-level technical requirements are listed.
- The initial scope and exclusions are clear.
- The project is ready to move into topology and IP addressing design.

The overall project will be considered successful when the final network is built, tested, and documented.

## Phase 1 Deliverable

The deliverable for this phase is this scope and requirements document.

This document establishes the foundation for the project and will be used as the reference point for later phases, including topology design, IP addressing, VLAN design, routing, security, testing, and troubleshooting.

## Next Phase

**Phase 2: Topology, IP Addressing, and VLAN Design**

The next phase will define the logical network topology, site addressing structure, VLAN subnets, WAN links, and device naming convention.
