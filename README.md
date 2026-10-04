# Computer Networks

This repository contains **course materials, lecture notes, practical demonstrations, Cisco Packet Tracer labs, assignments, and supporting resources** for the **Computer Networks** course.

The repository is intended to support undergraduate students in understanding fundamental networking concepts as well as gaining hands-on experience with network configuration and troubleshooting.

---

## 📚 Course Overview

Computer Networks introduces the fundamental concepts, protocols, architectures, and technologies used to enable communication between computers and network devices.

The course combines **theoretical concepts with practical networking exercises**, with particular emphasis on configuration and troubleshooting using **Cisco Packet Tracer**.

### Key Topics

* Network Fundamentals
* OSI and TCP/IP Models
* Physical and Data Link Layer
* Ethernet and MAC Addressing
* Switching and VLANs
* Network Layer and IP Addressing
* Subnetting
* Routing
* Static and Dynamic Routing
* OSPF
* Transport Layer
* TCP and UDP
* Application Layer Protocols
* DNS, DHCP and HTTP
* Network Security Fundamentals
* Network Troubleshooting

---

## 🗂️ Repository Structure

```text
Computer-Networks-Practicals/
│
├── README.md
│
├── Notes/
│   ├── Unit-1/
│   ├── Unit-2/
│   ├── Unit-3/
│   ├── Unit-4/
│   └── Unit-5/
│
├── Practical/
│   ├── Basic-Router-Configuration/
│   ├── IP-Addressing/
│   ├── Subnetting/
│   ├── Static-Routing/
│   ├── RIP/
│   ├── OSPF/
│   ├── VLAN/
│   ├── DHCP/
│   └── DNS/
│
├── Packet-Tracer/
│   ├── *.pkt
│   └── topology-files/
│
├── Assignments/
│
└── Resources/
```

> The directory structure may evolve as additional lectures, demonstrations, and practical exercises are added.

---

## 🖥️ Practical Work

The practical component uses **Cisco Packet Tracer** to simulate real-world networking environments.

Students will work with:

* Routers
* Switches
* PCs
* Servers
* Network cables
* IP addressing
* Routing protocols
* VLANs
* Network services

### Example Practical Exercises

1. Basic Router Configuration
2. Basic Switch Configuration
3. IP Address Configuration
4. Subnetting
5. Router-to-Router Connectivity
6. Static Routing
7. RIP Configuration
8. OSPF Configuration
9. VLAN Configuration
10. Inter-VLAN Routing
11. DHCP Configuration
12. DNS Configuration
13. Network Connectivity Testing
14. Troubleshooting Network Connectivity

---

## 🔧 Cisco IOS Commands

Some commonly used commands in the practical sessions include:

```text
enable
configure terminal
hostname R1
interface gigabitEthernet 0/0
ip address 192.168.1.1 255.255.255.0
no shutdown
exit
```

### Verification Commands

```text
show ip interface brief
show running-config
show ip route
show ip protocols
show ip ospf neighbor
show ip ospf
show cdp neighbors
```

### Connectivity Testing

```text
ping 192.168.1.1
traceroute 192.168.2.1
```

---

## 🌐 OSPF Practical

OSPF (Open Shortest Path First) is one of the major dynamic routing protocols covered in the practical sessions.

A basic OSPF configuration example:

```text
Router(config)# router ospf 1
Router(config-router)# router-id 1.1.1.1
Router(config-router)# network 192.168.10.0 0.0.0.255 area 0
Router(config-router)# network 10.0.0.0 0.0.0.3 area 0
```

OSPF verification:

```text
show ip ospf neighbor
show ip ospf
show ip protocols
show ip route
```

A successful OSPF neighbor relationship should normally appear in:

```text
show ip ospf neighbor
```

with the neighbor reaching the **FULL** state.

---

## 🧪 Learning Approach

The course follows a combination of:

### 1. Theory

Understanding networking concepts, protocols, algorithms, architectures, and standards.

### 2. Demonstrations

Concepts are demonstrated using network topologies and configuration examples.

### 3. Hands-on Practicals

Students build and configure network topologies using Cisco Packet Tracer.

### 4. Troubleshooting

Students learn to identify and resolve:

* Incorrect IP addresses
* Incorrect subnet masks
* Interface shutdown
* Incorrect gateway configuration
* Routing configuration errors
* OSPF neighbor problems
* Cable/connectivity issues
* Incorrect network statements

---

## 🛠️ Software Requirements

### Cisco Packet Tracer

The practical exercises can be performed using **Cisco Packet Tracer**.

Students should install a recent version of Cisco Packet
