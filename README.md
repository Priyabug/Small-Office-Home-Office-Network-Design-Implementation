# Small-Office-Home-Office-Network-Design-Implementation

# 🏢 ABC Company – Branch Network Design Proposal

## 🌍 Company Overview

**XYZ Company** is a fast-growing enterprise based in **Eastern Australia**, serving over **2 million customers globally**. The company specializes in the **buying and selling of food items**, with operations primarily managed from its **headquarters**.

---

## 📍 Branch Expansion Project – Bonalbo Village

To extend its reach, XYZ Company is planning to open a new **branch office near Bonalbo village**. The company is seeking **young IT graduates** to design and implement a standalone network for this branch.

---

## 🧩 Network Design Requirements

The network for the Bonalbo branch must meet the following specifications:

### 🛠 Hardware Requirements
- Use of **one Cisco Router** and **one Cisco Switch**
- All networking equipment must be **Cisco-branded**

### 🏢 Departmental Structure
- **Admin / IT**
- **Finance / HR**
- **Customer Service / Reception**

### 🌐 Network Architecture
- Each department must be assigned to a **separate VLAN**
- Each department must also support a **wireless network** for user access
- All **host devices** (wired and wireless) must obtain **IPv4 addresses automatically** (via DHCP)
- Devices in **all departments must be able to communicate** with each other (inter-VLAN routing required)

  ![image](https://github.com/user-attachments/assets/f24ec492-9ad2-4bbf-8e73-4c0cdb8b8762)


---

## ✅ Project Objectives Summary

| Feature                             | Requirement                          |
|------------------------------------|--------------------------------------|
| Router                             | 1 Cisco Router                       |
| Switch                             | 1 Cisco Switch                       |
| VLAN Segmentation                  | 3 VLANs (one per department)         |
| Wireless Access                    | Required per department              |
| IP Address Assignment              | DHCP (IPv4)                          |
| Inter-department Communication     | Must be enabled                      |
| Network Separation from HQ         | Operates independently               |

---

## ⚙️ Technologies Implemented

This project showcases a range of essential networking technologies and configurations using Cisco equipment in a simulated environment.

---

### 🧩 Network Infrastructure

- 🛠️ **Creating a Simple Network**  
  Built a basic topology using a **Cisco Router** and an **Access Layer Switch**.

- 🔌 **Correct Cabling**  
  Connected routers, switches, and host devices using **appropriate cable types** (straight-through and crossover).

---

### 🧱 Layer 2 Configurations

- 🏷️ **VLAN Creation & Port Assignment**  
  Defined multiple **VLANs** and assigned switch ports to specific VLAN IDs to isolate departmental traffic.

- 🧮 **Subnetting & IP Addressing**  
  Subnetted the IP network to align with VLAN requirements and assigned **logical IP schemes**.

---

### 🌐 Layer 3 Configurations

- 🔁 **Inter-VLAN Routing (Router-on-a-Stick)**  
  Configured **sub-interfaces** on a single router interface to enable communication between VLANs.

- 📡 **DHCP Configuration**  
  Implemented a **DHCP server on the router** to provide automatic IP addressing to host devices.

---

### 📶 Wireless Networking

- 📲 **WLAN Setup (Cisco Access Point)**  
  Configured **wireless access** for each department using a Cisco Access Point for mobile connectivity.

---

### 🖥️ Host & Network Testing

- 🧾 **Static & Dynamic Host Configurations**  
  Configured host devices using both **static IPs** and **DHCP assignments**.

- ✅ **Testing & Verification**  
  Verified end-to-end connectivity using tools like `ping` and **simulation mode** in Packet Tracer.

---

### Conclusion

> 💡 This project is an excellent opportunity for aspiring IT professionals to showcase practical skills in network design, VLAN configuration, inter-VLAN routing, DHCP setup, and wireless deployment—all within a real-world scenario.

