# CNRoutingAssignment

## Overview
This repository contains Cisco Packet Tracer configuration files for the Computer Networks 
Routing Assignment. The assignment covers basic router configuration, static routing, 
and dynamic routing protocols (RIP and EIGRP).

---

## Repository Structure

| File | Description |
|---|---|
| Task1_BasicConfig.pkt | Basic router configuration - hostname and console password |
| Task2_StaticRouting.pkt | Static routing configuration across three networks |
| Task3_DynamicRouting.pkt | Dynamic routing using RIP and EIGRP protocols |

---

## Task 1 — Basic Router Configuration
- Configured router hostname to KandyNSBM_StudentID
- Configured console access password (NSBM)
- Enabled console login authentication

## Task 2 — Static Routing
- Built a topology with 3 routers, 3 switches and 3 PCs
- Configured IP addressing on all router interfaces
- Networks used:
  - Network A (Computing): 192.168.1.0/24
  - Network B (Business):  192.168.2.0/24
  - Network C (Science):   192.168.3.0/24
- Configured static routes on all three routers
- Verified connectivity with ping tests between all networks

## Task 3 — Dynamic Routing

### Part A - RIP Routing
- Configured RIP Version 2 on all three routers
- Routers: KandyNSBM, ColomboNSBM, GalleNSBM
- Networks used:
  - 172.16.0.0/16
  - 173.16.0.0/16
- Verified successful communication between all networks

### Part B - EIGRP Routing
- Removed RIP configuration from all routers
- Configured EIGRP with Autonomous System number 100
- Verified successful communication between all networks

---

## Tools Used
- Cisco Packet Tracer 8.x
- Cisco 2911 Router
- Cisco 2960-24TT Switch

---
