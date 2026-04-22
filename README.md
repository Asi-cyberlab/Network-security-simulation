# 🌐 Network Security Simulation

## 🔐 asi-cyberlab Project

This project is a **network security simulation** built using Cisco Packet Tracer, demonstrating practical implementation of networking and cybersecurity concepts in a simulated enterprise environment.

---

## 🧪 Project Overview

The network was designed to simulate a **multi-department organisation** with secure communication, segmentation, and controlled access between departments.

The project focuses on combining **network engineering fundamentals** with **cybersecurity practices**.

---

## 🏢 Network Structure

### Departments:
- Developers Network  
- Business Analysts Network  
- Test Engineers (VLAN 10)  
- UI Designers (VLAN 20)  
- Shared Resources (VLAN 30)  

---

## 🌐 Key Features

### 🔢 Subnetting
- Implemented using VLSM  
- Multiple subnets created for different departments  
- Efficient IP address allocation  

---

### 📡 DHCP Configuration
- DHCP servers configured per department  
- Automatic IP assignment verified  
- Separate IP pools for each network segment  

---

### 🌍 DNS Server
- Central DNS server configured  
- Users can access the web server using:http://wwwproduction.com
- - Confirms successful name resolution  

---

### 🧩 VLAN Configuration
- VLAN 10 → Test Engineers  
- VLAN 20 → UI Designers  
- VLAN 30 → Shared Resources  

✔ Inter-VLAN routing configured  
✔ Controlled communication between VLANs  

---

### 🔒 Access Control (ACLs)
- Access-list implemented to restrict traffic  
- VLAN 10 and VLAN 20 communication controlled  
- Demonstrates network segmentation and security  

---

### 🌐 NAT (Network Address Translation)
- NAT configured on router  
- Internal private IPs translated to public IPs  
- Verified using:
- 
---

### 🔁 Routing Protocols
- RIP Version 2 configured  
- OSPF configured  
- Route redistribution implemented  

✔ Backup route configured for redundancy  

---

### ⚠️ Security Concepts Applied
- Network segmentation using VLANs  
- Access control using ACLs  
- NAT for internal network protection  
- Recommendation of DMZ for staging server  
- SIEM concept for monitoring and threat detection  

---

## 📂 Files

- `network-simulation.pkt` → Cisco Packet Tracer simulation file  
- `README.md` → Project documentation  
- `screenshots/` → Network visuals  

---

## 📥 How to Run the Project

1. Download the `.pkt` file  
2. Install Cisco Packet Tracer  
3. Open the file  
4. Explore configurations (routers, VLANs, ACLs, NAT)

---

## 🎯 Learning Outcomes

- Network design and subnetting  
- VLAN configuration and inter-VLAN routing  
- DHCP and DNS setup  
- Access control using ACLs  
- NAT implementation  
- Routing protocols (RIP & OSPF)  
- Basic cybersecurity architecture principles  

---

## 🚀 Conclusion

This project demonstrates the implementation of a **secure and structured enterprise network**, combining both networking and cybersecurity concepts.

---

## 🔐 asi-cyberlab

✨ *Building, testing, and securing systems one project at a time.*
