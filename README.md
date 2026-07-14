# Smart Campus Network Simulation using Cisco Packet Tracer

## Overview

The project models the networking infrastructure of a modern smart university campus by integrating traditional networking concepts with IoT-enabled automation systems.

The campus is divided into multiple departments, each operating within its own subnet while maintaining secure communication through a hierarchical routing architecture. In addition to standard networking devices, the project demonstrates the use of IoT devices for smart infrastructure management such as automated lighting, environmental monitoring, RFID access control, and surveillance.

---

## Network Architecture

The topology follows a **hierarchical campus network design** consisting of:

- Core Router
- Distribution Routers
- Department Routers
- Access Layer Switches
- Server Farm
- Department LANs
- Wireless Networks
- IoT Devices

Each department is assigned an independent subnet while maintaining communication through the core routing infrastructure.

---

## Campus Departments

The simulated campus consists of the following departments and facilities:

- Administration
- Library
- Computer Science & Engineering (CSE)
- Electronics & Communication Engineering (ECE)
- Bachelor's of Business Analytics (BBA)
- Bachelor's of Commerce (B.COM)
- Canteen
- Parking Area
- Central Server Room

Each department includes its own networking devices and end-user systems.

---

## Features

### Enterprise Network

- Multi-router campus backbone
- Department-wise LAN segmentation
- Hierarchical topology
- Scalable architecture
- Centralized server network

### End Devices

- Desktop PCs
- Laptops
- Smartphones
- Network Printers

### Wireless Infrastructure

- Wireless Access Points
- Wireless Clients
- Mobile Devices

### Smart Campus IoT

The project integrates various IoT devices including:

- Smart LED Lights
- Smart Fans
- Smart Air Conditioners
- Webcams
- Fire Monitoring Sensors
- Smoke Detectors
- Water Drain Sensors
- RFID Readers
- RFID Access Cards

---

## Network Components

| Device | Purpose |
|---------|----------|
| Routers | Inter-department routing |
| Switches | Local network connectivity |
| Servers | Centralized campus services |
| PCs & Laptops | End-user devices |
| Wireless Access Points | Wireless connectivity |
| Cloud Devices | Internet/Cloud simulation |
| IoT Devices | Smart campus automation |
| RFID Readers | Access control |

---

## Addressing Scheme

The campus uses separate IP subnets for different departments to ensure proper traffic segregation and efficient routing.

Example subnet allocation:

| Department | Network |
|------------|----------|
| Administration | 10.0.0.0/24 |
| Library | 20.0.0.0/24 |
| CSE | 30.0.0.0/24 |
| BBA | 40.0.0.0/24 |
| ECE | 50.0.0.0/24 |
| B.COM | 60.0.0.0/24 |
| Canteen | 70.0.0.0/24 |
| Parking | 80.0.0.0/24 |
| Server Farm | 90.0.0.0/24 |

*(Based on the topology.)*

---

## Technologies Used

- Cisco Packet Tracer
- IPv4 Addressing
- Routing
- Switching
- Wireless Networking
- IoT Device Simulation
- Enterprise Network Design

---

## Topology Highlights

- 50+ network nodes
- Multiple interconnected routers
- Dedicated departmental LANs
- Centralized server room
- IoT-enabled smart campus
- Wireless communication
- RFID-based access simulation
- Smart monitoring infrastructure

---

## Simulation

The project supports simulation mode in Cisco Packet Tracer for observing packet traversal between departments.

Connectivity can be verified using:

- Ping
- Simulation Mode
- Packet Tracer Event List
- IoT device interaction

---

## Project Structure

```
Smart-Campus-Network/
│
├── Smart_Campus_Network.pkt
├── README.md
└── images/
    └── topology.png
```

---

## How to Run

1. Install Cisco Packet Tracer (version 8.x or above recommended).
2. Open the `.pkt` file.
3. Switch to **Logical Workspace**.
4. Explore individual departments.
5. Use **Realtime** mode for normal operation.
6. Use **Simulation** mode to visualize packet flow.
7. Verify connectivity using `ping` between devices across departments.

---

---

## License

This project was developed for educational purposes as part of the **Computer Networks** course.
