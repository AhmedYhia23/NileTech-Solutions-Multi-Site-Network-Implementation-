# 🚀 *NileTech Solutions – Multi-Site Company*
Enterprise multi-site network design for a simulated company (HQ &amp; Branch) implementing hierarchical architecture, OSPF routing, VLAN segmentation, HSRP, advanced security, IPv6, and centralized wireless using Cisco Packet Tracer.


I designed and implemented a *full Enterprise Network Infrastructure* simulating a real-world company with a *Headquarters (HQ)* and a *Branch Office, following industry best practices for **scalability, redundancy, security, and wireless mobility*.

🏢 *Company Scenario:*
NileTech Solutions – A technology company operating across multiple sites, requiring a secure, highly available, and well-structured network.

<img width="1402" height="559" alt="Topology" src="https://github.com/user-attachments/assets/4090fc1e-52c5-47f6-9274-cfae12493f31" />

---


### 🔧 *Project Scope & Technologies Implemented*

#### 🏗️ *Network Architecture*

* Hierarchical Network Design (*Core / Distribution / Access*)
* Redundant Core and Distribution layers
* Layer 2 & Layer 3 EtherChannel
* Inter-VLAN Routing
* HSRP for default gateway redundancy
* Rapid Spanning Tree Protocol (RSTP)

#### 🌐 *Routing*

* Static Routing
* Dynamic Routing using *OSPF*

#### 🧩 *VLANs & Segmentation*

* VLAN-based wired and wireless segmentation
* Voice VLANs for IP Phones
* Separate VLAN for Wireless users

---

### 🔐 *Security Implementation*

* Extended ACLs for controlled inter-department traffic
* Port Security on Access ports
* DHCP Snooping to prevent rogue DHCP servers
* Dynamic ARP Inspection (DAI) to mitigate ARP spoofing attacks
* Secure device access using:

  * Encrypted enable secrets (Type 9 / Type 5)
  * Local user authentication
  * Console security with inactivity timeout & logging synchronization

---

### 🛠️ *Network Services*

* DHCP
* DNS
* NTP
* SNMP
* Syslog
* FTP
* Secure remote access using *SSH*
* NAT for Internet connectivity

---

### 📡 *Wireless Infrastructure*

* Centralized Wireless Architecture using *WLC*
* Dynamic Interface mapped to a dedicated Wireless VLAN
* Secure WLAN using *WPA2-PSK (AES)*
* Lightweight Access Points (LWAPs) successfully registered to the WLC

---

### 🌍 *IPv6*

* IPv6 addressing and configuration across the network

---

📌 *Tools Used:* Cisco Packet Tracer

💡 This project reflects a *real enterprise production-like environment*, combining routing, switching, security, services, IPv6, and wireless technologies into a single cohesive network design.
