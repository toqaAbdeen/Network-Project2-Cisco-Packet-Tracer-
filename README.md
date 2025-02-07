# ENCS3320 - Computer Networks Project #2

This repository contains the implementation and documentation for **Project #2** of the **ENCS3320 - Computer Networks** course at Birzeit University. The project focuses on designing and simulating a network topology using **Cisco Packet Tracer**, incorporating various networking concepts such as subnetting, routing, wireless security, and essential network services like DNS, DHCP, Web, and Email servers.

---

## Project Overview

The project involves designing a network of networks consisting of three Autonomous Systems (AS):
1. **Google Network (AS-300)**
2. **Faculty of Engineering and Technology Network (AS-100)**
3. **Home-ISP Network (AS-200)**

The network is designed to demonstrate the following:
- **Subnetting** and IP address allocation.
- Configuration of **DNS**, **DHCP**, **Web**, and **Email** servers.
- Implementation of **OSPF** for intra-AS routing and **BGP** for inter-AS routing.
- Wireless network setup with **WPA2** security.
- **NAT** and **PAT** configuration for Internet connectivity.
- Testing and verification of network functionality using **ping**, **email**, and **web access**.

---

## Repository Structure

The repository is organized as follows:
- **`Project2_TeamName.pkt`**: The Cisco Packet Tracer file containing the network topology.
- **`report.pdf`**: The project report documenting the design, implementation, and testing of the network.

---

## Key Features

### 1. **Google Network (AS-300)**
- **DNS Server**: Configured with resource records (RRs) for domain name resolution.
- **Email Server**: Set up with SMTP and POP3 protocols, including user accounts.
- **Routing**: OSPF and BGP configured for intra-AS and inter-AS routing.

### 2. **Faculty of Engineering and Technology Network (AS-100)**
- **Subnetting**: Efficient IP address allocation for servers, ECE, CS, and backbone subnets.
- **Web Server**: Customized index page with HTML/CSS for the faculty website.
- **Email Server**: Configured with SMTP and POP3, including user accounts.
- **DHCP Server**: Pools configured for ECE and CS subnets with IP helper commands.
- **Routing**: OSPF with multiple areas and BGP for inter-AS routing.

### 3. **Home-ISP Network (AS-200)**
- **Wireless Network**: Configured with WPA2 security for wireless devices.
- **DHCP Server**: Set up for dynamic IP allocation in the home subnet.
- **NAT with PAT**: Configured for Internet access using a single public IP.
- **Routing**: OSPF and BGP configured for inter-AS communication.

---

## Tools and Technologies

- **Cisco Packet Tracer**: Used for designing and simulating the network topology.

---

## Important Note: Project Limitations

**This project is not fully functional.** Some components, such as email communication between networks and packet transmission between certain devices, did not work as expected. For a detailed explanation of the issues encountered and the steps taken to troubleshoot them, please refer to the **Alternative Solutions, Issues, and Limitations** section in the [project report](report.pdf).

---

## How to Use

1. **Download Cisco Packet Tracer**: Ensure you have the latest version of Cisco Packet Tracer installed from [NetAcad](https://www.netacad.com/cisco-packet-tracer).
2. **Open the `.pkt` File**: Load the `Project2_TeamName.pkt` file in Cisco Packet Tracer to view the network topology.
3. **Review the Report**: Refer to the `report.pdf` for detailed explanations of the network design, configurations, and testing results.

---


**Good luck with your network simulations!**
