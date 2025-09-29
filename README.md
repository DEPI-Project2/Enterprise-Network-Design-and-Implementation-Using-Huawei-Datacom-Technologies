Enterprise Network Design and Implementation Using Huawei Datacom Technologies

🔹 Project Overview

This project focuses on the design, simulation, and implementation of an enterprise network using Huawei Datacom technologies inside the eNSP environment. The goal is to build a realistic enterprise network that demonstrates how organizations can ensure scalability, high availability, security, and efficient data communication using Huawei routers, switches, firewalls, and wireless devices.

🔹 Objectives

Network Design – Plan a hierarchical enterprise network (Core, Distribution, Access layers).

Implementation in eNSP – Configure Huawei routers, switches, and security devices in a simulated environment.

Services Configuration – Implement key services such as VLANs, routing, DHCP, NAT, ACLs, and VPNs.

Resiliency – Enable redundancy protocols like STP, VRRP, and Link Aggregation.

Security – Apply ACLs, firewall rules, and user authentication to secure the enterprise network.

Testing & Validation – Verify connectivity, failover, and service delivery across departments.

🔹 Network Topology (in eNSP)

Your topology might include:

Core Layer: Huawei CloudEngine/Core switches + AR routers (for WAN/Internet).

Distribution Layer: Aggregation switches with redundancy (STP/VRRP).

Access Layer: Switches connecting end devices (PCs, servers, IP phones).

Security Zone: USG firewall controlling inbound/outbound traffic.

Wireless: Huawei WLAN controllers and APs for enterprise Wi-Fi.

Servers: DHCP, DNS, Web, and Mail servers to simulate enterprise services.

🔹 Key Technologies & Configurations

VLAN & Inter-VLAN Routing – Segment departments (HR, Finance, IT, Guest).

Dynamic Routing Protocols – Configure OSPF/IS-IS for internal routing; static/default route to Internet.

High Availability – Implement VRRP (gateway redundancy) and Eth-Trunk (link aggregation).

IP Services – DHCP server for dynamic IP assignment, NAT for Internet access.

Security – Configure ACLs (e.g., Finance only allowed access to database servers), enable AAA authentication.

Firewall Policies – Block unauthorized traffic, allow controlled remote access (VPN).

QoS – Prioritize VoIP and critical business applications.

🔹 Project Outcomes

By the end of the simulation in eNSP, you will demonstrate:

A fully functioning enterprise network design.

Secure connectivity between multiple departments.

High availability and redundancy (failover tested).

Controlled Internet access via NAT/firewall.

Wireless integration for mobile users.

🔹 Benefits of Using eNSP

No need for physical Huawei devices – cost-effective simulation.

Supports CLI-based configuration, close to real Huawei equipment.

Allows packet capture and troubleshooting for validation.

Provides a safe environment to test enterprise-scale designs.
