# MIT – Network Redesign Project

## 📖 Project Overview
This project was carried out as part of the **Data Communication and Networking course** at the Mekelle Institute of Technology (MIT).  
The MIT management requested a **redesign of the institute’s network** using both **switches** and **routers**, ensuring proper **functionality and security**.  

The new design connects:
- **MIT local network**
- **Mekelle University (MU) network**
- **Global Internet (via US Datacenter services)**  

The implementation was done using **Cisco Packet Tracer**, with full device configuration and service deployment.

---

## 🎯 Project Requirements & Implementation

### Applications 
- ✅ **E-student, MU, and MIT website** hosted in MU  
- ✅ **Gmail and Facebook** hosted in a US Datacenter simulation  

### Services 
1. **VLANs** – Used to logically segment departments within MIT  
2. **DNS** – Resolves MIT, MU, Gmail, and Facebook domains to IP addresses  
3. **DHCP** – Provides dynamic IP addresses to end devices within VLANs  
4. **Telnet** – Remote management of routers and switches  
5. **SNMP** – Used for network monitoring and communication with admin network  

### Routing
- **Dynamic Routing:** Implemented using **OSPF** for efficient and scalable routing  
- **Inter-VLAN Routing:** Configured using a router-on-a-stick approach to allow communication between VLANs  

### Security & Management 
- **Admin Network:** A dedicated network segment created for administrators  
- Admins remotely manage devices using **SNMP** (monitoring) and **Telnet** (configuration access)  

### IP Addressing 
- **IPv4 Addressing Scheme:** Used subnetting to conserve IP addresses  
- **NAT/PAT Implementation:** Configured at the edge router to translate private MIT addresses into public addresses for internet access  

---

## 🖥️ Network Components
- **Switches (Layer 2 & Layer 3)** – VLAN segmentation, inter-VLAN routing  
- **Routers** – OSPF, NAT/PAT, interconnection to MU and US Datacenter  
- **Servers** – DNS, DHCP, E-student, MIT, MU, Gmail, and Facebook simulation  
- **End Devices (PCs)** – Users, Admins, Agents  
- **Admin Network** – Secure remote monitoring and management  

---

## 📂 Deliverables
1. **Packet Tracer File**  
   - Contains complete network design and configurations (`MIT_Network.pkt`)  

2. **Video Explanation (20–40 mins)**  
   - Step-by-step walkthrough of network design and configuration  
   - Demonstrates working applications, services, and connectivity
  
   - AND DM me if you need the vidio ,get the links from my profile 

3. **README.md (this file)**  
   - Documentation of project requirements, design choices, and implementation details  

---

## 🚀 How to Run the Project
1. Open the provided `.pkt` file in **Cisco Packet Tracer**.  
2. Start the simulation and test connectivity:  
   - Access MIT & MU websites from PCs  
   - Resolve Gmail and Facebook domains via DNS  
   - Test IP assignment via DHCP  
   - Verify NAT/PAT by accessing external networks  
   - Use Telnet to configure routers and switches remotely  
   - Use SNMP tools for monitoring  

---

## 🔐 Security Considerations
- VLANs isolate traffic between departments  
- NAT/PAT hides internal IPs from external exposure  
- Telnet access restricted to Admin VLAN only
- port security
- SNMP configured with community strings for monitoring security  

---

## 👨‍💻 Author
**Haile Tassew**  
Information Technology Student – Mekelle Institute of Technology  
