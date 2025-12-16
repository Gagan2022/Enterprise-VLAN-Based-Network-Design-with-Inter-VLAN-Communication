# Enterprise VLAN-Based Network Design with Inter-VLAN Communication

## 📌 Project Overview

This project demonstrates the design and implementation of an **enterprise-level VLAN-based network** with **Inter-VLAN communication** using Cisco networking concepts. The objective is to segment the network into multiple VLANs for improved performance, security, and manageability, while enabling controlled communication between VLANs using a Layer 3 device.

The project closely follows **CCNA-level enterprise networking standards** and simulates a real-world organizational network.

---

## 🎯 Objectives

* Design a scalable enterprise network using VLANs
* Implement logical network segmentation
* Enable communication between VLANs (Inter-VLAN Routing)
* Apply best practices for IP addressing and subnetting
* Configure Cisco switches and routers
* Verify connectivity using testing and troubleshooting tools

---

## 🧱 Network Architecture

* **Access Layer:** VLAN-based access switches
* **Distribution Layer:** Router-on-a-Stick (ROAS) for Inter-VLAN routing
* **End Devices:** PCs representing different departments

---

## 🗂 VLAN Design

| VLAN ID | VLAN Name | Department       |
| ------: | --------- | ---------------- |
|      10 | Sales     | Sales            |
|      20 | IT        | IT Department    |
|      30 | HR        | Human Resources  |
|      40 | Native    |        --        |

---

## 🌐 IP Addressing Scheme

| VLAN | Network Address | Subnet Mask     | Default Gateway |
| ---: | --------------- | -------------   | --------------- |
|   10 | 192.168.10.0    | 255.255.255.192 | 192.168.10.1    |
|   20 | 192.168.10.64   | 255.255.255.192 | 192.168.10.65   |
|   30 | 192.168.10.128  | 255.255.255.192 | 192.168.10.129  |

---

## ⚙️ Technologies & Tools Used

* Cisco Packet Tracer
* Cisco Routers and Switches
* VLAN Configuration
* Trunking (802.1Q)
* Router-on-a-Stick (ROAS)
* Subnetting & IP Addressing
* ICMP (Ping) for testing

---

## 🔧 Key Configurations

### Switch Configuration

* VLAN creation and naming
* Access port assignment
* Trunk port configuration

### Router Configuration

* Sub-interface creation
* Encapsulation using 802.1Q
* IP address assignment for each VLAN
* Enabling Inter-VLAN routing

---

## 🧪 Verification & Testing

* Ping tests between devices in the **same VLAN**
* Ping tests between devices in **different VLANs**
* Verification of trunk links and VLAN assignments

All VLANs successfully communicate through the router, confirming correct Inter-VLAN routing.

---

## 📁 Project Files

* Network topology (.pkt file)
* VLAN & Subnetting tables (Excel/PDF)
* Configuration screenshots
* README.md (this file)

---

## 📘 Learning Outcomes

* Strong understanding of VLAN concepts
* Practical knowledge of Inter-VLAN routing
* Hands-on experience with enterprise network design
* Improved troubleshooting and verification skills

---

## 🚀 Future Enhancements

* Implement DHCP for dynamic IP allocation
* Add ACLs for traffic filtering between VLANs
* Introduce redundancy using multiple switches
* Integrate Wireless VLANs

---

## 👤 Author

**Gagan Agarwal**
Aspiring Network Engineer 

---

## 📄 License

This project is for educational and learning purposes only.
