# ✈️ Aeronautical Telecommunication Network (ATN) using Cisco Packet Tracer

## 📌 Project Overview

This project simulates an **Aeronautical Telecommunication Network (ATN)** using Cisco Packet Tracer.
It demonstrates communication between aircraft systems and ground control through a secure and structured network.

The network integrates routing, switching, firewall security, and wireless communication to represent real-world aviation communication systems.

---

## 🎯 Objectives

* To understand ATN communication between aircraft and ground systems
* To design a network topology using Cisco Packet Tracer
* To implement IP addressing and routing
* To configure ASA Firewall for network security
* To demonstrate wireless communication using WiFi
* To test connectivity using ping and simulation mode

---

## 🏗️ Network Architecture

The network consists of the following components:

* **ISR4331 Router** → Handles routing between networks
* **ASA 5505 Firewall** → Provides security and traffic filtering
* **3560 Multilayer Switch** → Connects all LAN devices
* **Wireless Router (WRT300N)** → Provides wireless connectivity
* **PCs (ATC Systems)** → Represent ground control systems
* **Server** → Stores and provides data services
* **Printer** → Outputs reports
* **Laptops (Aircraft Systems)** → Simulate aircraft communication

---

## 🔁 Data Flow

```
Aircraft (Laptop) → Wireless Router → Switch → Firewall → Router → Server/PC
```

The response follows the reverse path ensuring successful communication.

---

## ⚙️ Configuration Summary

### Router Configuration

* Interface: GigabitEthernet0/0/0
* IP Address: 10.0.0.2/24

### ASA Firewall Configuration

* Inside Network: 192.168.1.0/24
* Outside Network: 10.0.0.0/24
* Security Levels: Inside (100), Outside (0)
* Default Route: 10.0.0.2

### Wireless Router

* IP: 192.168.1.5
* DHCP: Disabled

### End Devices

* PCs: 192.168.1.2 – 192.168.1.4
* Server: 192.168.1.10
* Printer: 192.168.1.20
* Laptops: 192.168.1.6 – 192.168.1.7

---

## 🧪 Results

* Successful communication between all devices
* 0% packet loss observed using ping
* Stable and secure network operation
* Proper routing and firewall filtering achieved

---

## 🔐 Key Features

* Secure communication using ASA Firewall
* Wireless connectivity for aircraft simulation
* Static IP addressing
* Real-time packet flow analysis using simulation mode

---

## 🛠️ Tools Used

* Cisco Packet Tracer
* Networking Concepts (Routing, Switching, Firewall)

