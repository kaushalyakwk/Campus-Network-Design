# Enterprise Campus Network Design using Cisco Packet Tracer

## Project Overview

This project demonstrates the design and implementation of a multi-campus enterprise network using Cisco Packet Tracer. The network consists of a **Main Campus** and a **Branch Campus** connected through serial WAN links. Dynamic routing is implemented using **RIPv2**, enabling communication between all VLANs across both campuses.

The project includes VLAN segmentation, Layer 3 switching, inter-VLAN routing, WAN connectivity, and successful end-to-end communication between all hosts.

## Features

- Multi-campus enterprise network
- VLAN implementation
- Inter-VLAN Routing
- Layer 3 Switching
- Dynamic Routing using RIPv2
- Serial WAN connectivity
- Department-based network segmentation
- Printer and Server connectivity
- End-to-end connectivity verification using Ping

## Network Topology

### Main Campus

| VLAN | Department | Network |
|------|------------|----------------|
| VLAN 10 | Administration | 192.168.1.0/24 |
| VLAN 20 | HR | 192.168.2.0/24 |
| VLAN 30 | Finance | 192.168.3.0/24 |
| VLAN 40 | Business | 192.168.4.0/24 |
| VLAN 50 | Engineering | 192.168.5.0/24 |
| VLAN 60 | Design | 192.168.6.0/24 |
| VLAN 70 | Laboratory | 192.168.7.0/24 |
| VLAN 80 | IT | 192.168.8.0/24 |

### Branch Campus

| VLAN | Department | Network |
|------|------------|----------------|
| VLAN 90 | Staff | 192.168.9.0/24 |
| VLAN 100 | Student Lab | 192.168.10.0/24 |

## Devices

- 3 Cisco Routers
- Layer 3 Core Switches
- Multiple Access Switches
- PCs
- Network Printers
- Email Server
- Web Server
- FTP Server

## Connectivity Test

End-to-end communication was verified successfully.

Example ping tests:

- PC0 ➜ PC3
  <img width="475" height="237" alt="Screenshot 2026-07-18 113020" src="https://github.com/user-attachments/assets/bb134267-d38c-4620-ab63-8dfa8115ad1e" />

-  Main Campus ➜ Branch Campus (PC1 ➜ PC8)
  <img width="476" height="218" alt="Screenshot 2026-07-18 113104" src="https://github.com/user-attachments/assets/dc22e045-45f9-4b60-8182-23582e54b057" />

- Access to Email Server
  <img width="478" height="348" alt="Screenshot 2026-07-18 113257" src="https://github.com/user-attachments/assets/b565b2be-a0e2-411e-b1f6-b56f7b71c412" />


### Network Topology

<img width="914" height="258" alt="Screenshot 2026-07-18 112927" src="https://github.com/user-attachments/assets/4c42869b-6bc3-4f33-9c56-427309fbf57a" />
