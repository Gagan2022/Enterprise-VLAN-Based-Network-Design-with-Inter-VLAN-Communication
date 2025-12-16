# Small Office Network Design – VLAN & Inter-VLAN Routing

## 📌 Project Overview

This project demonstrates the design and validation of a **VLAN-based small office enterprise network**. The network is logically segmented at **Layer 2 using VLANs** and enabled for **controlled inter-VLAN communication at Layer 3** using a router.

The project was completed as **hands-on practice after CCNA M1 & M2**, focusing on realistic enterprise LAN design concepts using **Cisco Packet Tracer**.

---

## 🎯 Project Objectives

- Design an enterprise-style LAN with multiple departments
- Implement **logical isolation at Layer 2** using VLANs
- Create an **IPv4 subnetting plan** for each VLAN
- Enable **inter-VLAN routing** for controlled communication
- Validate end-to-end connectivity across VLANs

---

## 🏢 Network Scenario

A small organization has the following departments:

- **HR**
- **IT**
- **Sales**

Each department requires:

- A dedicated network segment for security and traffic control
- The ability to communicate with other departments when required

---

## 🧩 Network Components Used

- **1 Router** – provides inter-VLAN routing and default gateways
- **3 Layer 2 Switches** – connect end devices and enforce VLAN separation
- **Multiple PCs** – assigned to different departments
- **Ethernet connections** for device connectivity

---

## 🌐 Network Design Summary

- Departments are separated using **VLANs**, ensuring Layer 2 logical isolation
- Each VLAN is assigned a **unique IPv4 subnet**
- The router acts as the **centralized routing point** for all VLANs
- Inter-VLAN communication occurs only through Layer 3 routing

---

## 🧮 VLAN & IP Addressing Plan

The network includes:

- A VLAN-to-department mapping
- A dedicated IPv4 subnet for each VLAN
- A default gateway assigned per VLAN

Detailed VLAN assignment tables and subnetting tables are included as part of the project documentation.

---

## 🔁 Inter-VLAN Communication

- Devices within the same VLAN can communicate directly
- Devices in different VLANs require routing through the router
- Layer 2 isolation is maintained while allowing Layer 3 connectivity

---

## 🔍 Validation & Testing

The network was validated by:

- Verifying correct VLAN membership for all devices
- Testing intra-VLAN communication
- Testing inter-VLAN communication using ping
- Confirming successful routing between all VLANs

---

## 🧠 Concepts Demonstrated

- VLAN-based network segmentation
- Layer 2 isolation vs Layer 3 communication
- IPv4 subnetting and address planning
- Inter-VLAN routing concepts
- Enterprise LAN design fundamentals

---

## 🛠 Tools Used

- Cisco Packet Tracer
- Cisco IOS (basic routing and switching concepts)

---

## 📂 Project Artifacts

- Network topology diagram
- VLAN assignment tables
- Subnetting / IP addressing tables
- Inter-VLAN connectivity test screenshots



---

## 🚀 Learning Outcome

This project strengthened my understanding of enterprise LAN design by combining VLAN segmentation, subnetting, and routing into a single scalable and structured network solution.

