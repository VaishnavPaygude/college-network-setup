# 🎓 College Network Design & Implementation

**Tool:** Cisco Packet Tracer  

## 📜 Project Overview
This project demonstrates the design and implementation of a **college campus network** using **Cisco Packet Tracer**.  
The network connects multiple departments and facilities, ensuring secure, segmented, and efficient communication.

## 🏫 Network Layout
The network connects the following areas:
- 🖥️ Computer Labs
- 🏢 Administrative Offices
- 🧑‍💼 Principal’s Office
- 📚 Library
- 🗄️ Server Room

## ⚙️ Features & Configurations
- **VLANs** for department-wise segmentation.
- **Router-on-a-Stick** for inter-VLAN communication.
- **IP Addressing & Subnetting** for efficient network utilization.
- **Port Security** on switches to prevent unauthorized access.
- **Internet Simulation** via cloud/ISP devices.
- **Connectivity Testing** using `ping` and `traceroute`.

## 🛠️ Technologies Used
- Cisco Packet Tracer
- VLAN (Virtual Local Area Network)
- Inter-VLAN Routing
- IP Subnetting
- Port Security
- TCP/IP Protocols

## 📂 Project Files
- `college_network.pkt` → Cisco Packet Tracer network topology file
- `configurations.txt` → Switch/Router configuration commands

## 🚀 How to Use
1. Open **Cisco Packet Tracer**.
2. Load the `college_network.pkt` file.
3. Review device configurations from the CLI.
4. Test connectivity with:
   ```bash
   ping <destination_IP>
   traceroute <destination_IP>
