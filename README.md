# PROJECT 05 – Enterprise Campus Network Design & Configuration

**Cisco Packet Tracer | Cisco IOS | VLAN | Inter-VLAN Routing | RIPv2 | DHCP | Static Routing**

## 📌 Project Overview
<img width="2580" height="1529" alt="campus project" src="https://github.com/user-attachments/assets/1b30a977-997c-4227-b3a7-ea0dd7b2645f" />


This project focuses on designing and configuring a multi-campus enterprise network infrastructure for a fictional university, Albion University.

The university operates two campuses located approximately 20 miles apart. The network is designed to provide secure, reliable, and efficient communication between departments, faculties, administrative offices, student laboratories, internal servers, and external cloud-based services.

The topology uses a hierarchical network design with routers, multilayer switches, access switches, VLAN segmentation, and WAN connectivity.

## 🎯 Project Objectives

- Design a multi-campus enterprise network topology.
- Establish communication between the main campus and branch campus.
- Separate departments and faculties using VLANs.
- Implement inter-VLAN communication.
- Configure routing between internal network segments.
- Provide dynamic IP addressing for Building A using DHCP.
- Enable access to internal servers and external cloud services.
- Apply appropriate switch security configurations.

## 🏢 Network Architecture

The network consists of two campuses and an external cloud network.

### 1. Main Campus

The main campus is divided into three buildings.

**Building A – Administration & Business**
- Administration / Management
- Human Resources (HR)
- Finance
- Business Faculty

**Building B – Engineering & Computing**
- Engineering & Computing (E&C)
- Art & Design (A&D)

**Building C – Students & IT Department**
- Student Laboratory
- IT Department
- Internal University Web Server
- Additional Internal Servers

### 2. Branch Campus – Albion Branch

The smaller campus accommodates the Faculty of Health & Sciences.

- Staff Network
- Student Laboratory Network

Separate VLANs are used to isolate staff and student network traffic.

### 3. External Cloud Network

An external cloud network hosts the university's email server, allowing the internal university network to access external services.

## 🌐 VLAN and IP Addressing Plan

Each department or faculty is assigned a separate IP network.

| VLAN ID | Department / Network | Network Address |
|---|---|---|
| 10 | Administration | 192.168.1.0/24 |
| 20 | Human Resources | 192.168.2.0/24 |
| 30 | Finance | 192.168.3.0/24 |
| 40 | Business Faculty | 192.168.4.0/24 |
| 50 | Engineering & Computing | 192.168.5.0/24 |
| 60 | Art & Design | 192.168.6.0/24 |
| 70 | Student Laboratory | 192.168.7.0/24 |
| 80 | IT Department | 192.168.8.0/24 |
| 90 | Branch Campus Staff | 192.168.9.0/24 |
| 100 | Branch Campus Student Lab | 192.168.10.0/24 |

## ⚙️ Technologies & Protocols

- **Cisco Packet Tracer** – Network topology design and simulation.
- **Cisco IOS** – Router and switch configuration.
- **VLAN** – Logical network segmentation.
- **Trunking** – Carrying multiple VLANs between switches and network devices.
- **Inter-VLAN Routing** – Communication between different VLANs.
- **RIPv2** – Dynamic routing within the internal network.
- **Static Routing** – Connectivity towards the external cloud network.
- **DHCP** – Automatic IP address allocation for Building A devices.
- **WAN Connectivity** – Communication between the main and branch campuses.

## 🔧 Key Network Components

- Cisco routers for campus and WAN connectivity.
- Multilayer switches for Layer 3 switching and inter-VLAN routing.
- Access switches for departmental connectivity.
- End devices including PCs, printers, and servers.
- Cloud network representing external email services.

## 🧪 Implementation & Testing

The project involves configuring the core network devices and selected end devices to establish end-to-end connectivity.

Key verification activities include:

- Verify VLAN creation and assignment.
- Verify trunk link configurations.
- Verify inter-VLAN communication.
- Verify routing table entries.
- Test connectivity between main and branch campuses.
- Verify DHCP address allocation in Building A.
- Test access to internal servers.
- Verify connectivity to the external cloud server.

## 📷 Network Topology

The following diagram represents the designed Albion University multi-campus enterprise network.

![Albion University Enterprise Campus Network Topology](DONE.png)

## 📚 Learning Outcomes

Through this project, I developed practical knowledge and experience in:

- Enterprise network architecture and hierarchical network design.
- VLAN planning and network segmentation.
- Cisco router and multilayer switch configuration.
- Inter-VLAN routing and WAN connectivity.
- Dynamic and static routing concepts.
- IP addressing and subnetting.
- DHCP configuration and network troubleshooting.
- Designing networks for multi-campus environments.

## 🛠️ Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI

## 👨‍💻 Project Information

**Project:** PROJECT 05 – Enterprise Campus Network Design & Configuration

**Platform:** Cisco Packet Tracer

**Category:** Enterprise Networking

**Status:** Academic Coursework Project
