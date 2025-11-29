# 🌐 AuroraShield Enterprise Network  
### **Advanced Multi-Layer Redundant Cisco Infrastructure**  
#### Designed & Engineered by *Imeda Sheriphadze – IT & Software Specialist | Neural Architect & AI Visioneer*

---

## 📘 Overview  
AuroraShield Enterprise Network is a fully engineered, production-grade Cisco infrastructure project built without Windows Server, relying entirely on Cisco’s native capabilities.  
The architecture demonstrates enterprise-level design principles, including:

- 🔹 Multi-layer hierarchical design (Core / Distribution / Access)  
- 🔹 Full Protection Mechanism using Cisco 7206VXR routers  
- 🔹 OSPF Dynamic Routing with MD5 authentication  
- 🔹 Highly redundant /30 routed interconnects  
- 🔹 Strict VLAN segmentation & role-based access  
- 🔹 Intelligent traffic control and selective Internet access  
- 🔹 Security-driven L2/L3 infrastructure  
- 🔹 Scalable IT Services Zone (Web, FTP, 1C servers)

This repository represents a complete CCNP/CCIE-grade project prepared for Cisco-level review, documentation, and submission.

---

## 🏛 Architecture Summary  

### **Core Layer (vIOS21, vIOS22)**
- OSPF Area 0 Backbone  
- Redundant routed links  
- Central aggregation for all Access switches  
- Loopback-based Router-ID structure  

### **Distribution Layer (vIOS23, vIOS24)**
- Aggregation point for management and services  
- Policy enforcement  
- OSPF adjacency filtering  
- Secure handoff to Core  

### **Access Layer (Switch17, Switch18, Switch19, Switch20)**
- VLAN-based segmentation  
- DHCP Snooping / Dynamic ARP Inspection  
- BPDU Guard / Port Security  
- Operator and Administration workstations  

### **Protection Routers (Cisco 7206VXR cluster)**
- Mesh triangular redundancy  
- /30 WAN transport links  
- WAN security perimeter  
- Gateway for AdminRouter  

### **IT Services Zone**
- VLAN 90 – Administrator  
- VLAN 92 – WEB Server  
- VLAN 93 – FTP Server  
- VLAN 94 – 1C Server  
- Protected, isolated, role-based accessibility  

---

## 🔐 Security Architecture  

### **Layer 2 Protections**
- DHCP Snooping  
- IP Source Guard  
- Dynamic ARP Inspection  
- STP Root Guard & BPDU Guard  
- Port Security per VLAN role  

### **Layer 3 / WAN Security**
- Edge ACLs  
- NAT Control  
- OSPF MD5 authentication  
- Internet access restricted ONLY for specific VLANs:  
  **10, 20, 30, 40, 50, 60, 70, 80, 90, 92**

### **Administrative Security**
- Local AAA  
- SSHv2-only remote access  
- Separated management VLAN 77 (no Internet)  

---

## 🧩 VLAN Structure

| VLAN | Description | Internet |
|------|-------------|----------|
| 10 | Operators 1 | ✔ |
| 20 | Operators 2 | ✔ |
| 30 | Operators 3 | ✔ |
| 40 | Operators 4 | ✔ |
| 50 | Administration 1 | ✔ |
| 60 | Administration 2 | ✔ |
| 70 | Administration 3 | ✔ |
| 80 | Administration 4 | ✔ |
| 90 | Main Administrator | ✔ |
| 92 | Web Server | ✔ |
| 93 | FTP Server | ✖ |
| 94 | 1C Server | ✖ |
| 77 | Management VLAN | ✖ |

---

## 📂 Repository Structure  


---

## 🖼 Network Topology  
*(Insert your project PNG diagram here – recommended)*  


---

## 🧾 Documentation Package  

All official project documents are available inside **Final_PDF**:

- 📘 **Full Cisco-Style Documentation**  
- 📄 **Business & Technical Explanation**  
- 📨 **Cisco Motivation Letter**  
- 🎞 **Final Presentation (PPTX/PDF)**  
- 🗂 **Submission-ready structure**

This package meets Cisco’s requirements for enterprise project submission.

---

## 🏆 Project Highlights  

- ✔ Fully redundant architecture  
- ✔ Zero Windows Server dependency  
- ✔ All functions handled directly by Cisco devices  
- ✔ Security-first design  
- ✔ Fast OSPF convergence  
- ✔ Clean separation of roles  
- ✔ Professional documentation & repository  
- ✔ CCNP/CCIE-level complexity  

---

## 👤 Author  
**Imeda Sheriphadze**  
IT & Software Specialist  
Neural Architect & AI Visioneer  

📧 **isheriphadze@gmail.com**  
📞 **+995 (555) 45-92-70**  
📲 Telegram: **@NeuroFusionHub**

---

## 💠 Final Note  
AuroraShield represents a real-world, production-grade enterprise network built with precision, discipline, and professional engineering standards.  
This repository serves as a submission-ready portfolio for Cisco certification and enterprise-level demonstration.

---
