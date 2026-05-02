# Enterprise and Smart Home Network Simulation

A Cisco Packet Tracer based networking project demonstrating the implementation of an Enterprise Network and a Smart Home IoT ecosystem.

---

## 📌 Project Overview

This project was developed using Cisco Packet Tracer to simulate real-world networking concepts including:

* VLAN segmentation
* Inter-VLAN routing
* DHCP configuration
* Enterprise network architecture
* Smart Home IoT integration
* Wireless and wired communication

The project contains two major network environments:

1. Enterprise Network
2. Smart Home Network

---

# 🏢 Enterprise Network Architecture

## Topology Design

The Enterprise Network follows a Collapsed Core Architecture where:

* An Edge Router connects to a central Gateway Switch
* The Gateway Switch acts as the distribution layer
* Multiple access switches connect end-user devices

### Key Features

* Router-on-a-Stick configuration for Inter-VLAN Routing
* Cascaded switches for higher port density
* Centralized network management
* Department-based traffic segmentation

---

## 🌐 VLAN Segmentation

| VLAN ID | Department | Subnet        | Gateway    |
| ------- | ---------- | ------------- | ---------- |
| 2       | Admin      | 172.23.0.0/24 | 172.23.0.1 |
| 3       | HR         | 172.23.1.0/24 | 172.23.1.1 |
| 4       | Dev        | 172.23.2.0/23 | 172.23.2.1 |

---

## ⚙️ Network Services

### DHCP Configuration

* Centralized DHCP services
* Automatic IP assignment for all departments

### Addressing Strategy

* Development department uses a /23 subnet
* Provides additional address space for scalability

---

# 🏠 Smart Home Network

## Residential Network Layout

The Smart Home environment uses a wireless-enabled Home Router operating on:

```text id="a1b2c3"
192.168.100.0/24
```

The network supports:

* Wired devices
* Wireless devices
* IoT automation systems

---

## 📍 Network Zones

### 1. Office Zone

Includes:

* Workstations
* Printer
* IoT Registration Server

### 2. Living Zone

Includes:

* Smart TV
* Smartphones
* Tablets
* Smart Home devices

---

## 🤖 IoT Integration

### Smart Devices

* Smart Air Conditioning Units
* Smart Door System
* Mobile device control

### Features

* Device registration through IoT Server
* Remote monitoring
* Smart automation management

---

# 🛠️ Technologies Used

* Cisco Packet Tracer
* VLANs
* DHCP
* Router-on-a-Stick
* Switching
* IoT Devices
* Wireless Networking

---

# 📁 Project Files

* Cisco Packet Tracer `.pkt` file
* Project documentation/report
* Network topology

---

# 🎯 Learning Outcomes

Through this project, we learned:

* VLAN implementation
* Inter-VLAN communication
* DHCP deployment
* Enterprise network design
* Smart Home IoT integration
* Network scalability concepts

---

# 👨‍💻 Authors

### Safiullah Sanai

CMS ID: 023-24-0148

### Abdul Manan Bohio

CMS ID: 023-24-0149

BSCS-III Section E

---

# 📌 Conclusion

This project successfully demonstrates both enterprise-level networking and modern smart home automation within a single Cisco Packet Tracer simulation. The network achieves scalability, efficient communication, traffic isolation, and IoT-based automation with verified connectivity.
