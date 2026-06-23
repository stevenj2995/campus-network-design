# BINUS Campus Alam Sutera Network Design (Floor 2, 4 & 5)
 
A three-floor enterprise network design and simulation for a BINUS University campus building, built and tested in **Cisco Packet Tracer**. The project covers the full TCP/IP stack — from physical cabling and device selection up to application-layer services like DNS, SMTP, HTTP, and DHCP.
 
This was a group project for the **Computer Networks (CPEN6247)** course, Odd Semester 2024/2025.
 
## Overview
 
The goal was to design a realistic, cost-aware network for three floors of a campus building, where each floor hosts classrooms, labs, studios, and specialized rooms (Library, BINUS TV, BINUS Radio, Auditorium, IT Room, etc.). The design accounts for device placement, cabling distance, IP allocation per room, inter-floor routing, and the network services that keep everything running.
 
## What's Included
 
- **Physical layer** — Cat6a cabling plan with per-floor distance and cost estimates, plus switch and router selection (Linksys gigabit switches, TP-Link Wi-Fi 6 routers).
- **IP addressing & subnetting** — VLSM-based subnet plan allocating address space per room according to host count, documented floor by floor.
- **Routing** — inter-floor routing configured so devices on different floors can communicate, using a dedicated next-hop scheme between floor routers.
- **Application layer services**:
  - **DNS** — domain-to-IP resolution served centrally to all floors.
  - **SMTP** — mail server configured for internal email between users.
  - **HTTP / HTTPS** — web server hosting accessible pages within the network.
  - **DHCP** — automatic IP assignment for client devices.
## Files
 
| File | Description |
|------|-------------|
| `Comnet_Cisco_AOL_Group_4.pkt` | The complete Cisco Packet Tracer simulation file. |
| `report.pdf` | Full design report covering each TCP/IP layer, component choices, subnetting tables, and cost breakdown. |
 
## How to Open
 
1. Install [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer) (free with a Cisco Networking Academy account).
2. Open `Comnet_Cisco_AOL_Group_4.pkt`.
3. Switch to **Realtime** mode to test connectivity (e.g. ping between floors, open the web server from a client PC, or send an internal email).
## Tools & Concepts
 
`Cisco Packet Tracer` · `TCP/IP model` · `VLSM subnetting` · `Static routing` · `DNS` · `SMTP` · `HTTP/HTTPS` · `DHCP` · `Network topology design`
 
## Team
 
Group 4 — Class LB02:
- Benedictus Alonso Harland Sutojo
- Christopher Davin Sasrawan
- Steven Jonatan
- Wilbert
---
 




