# 🔐 Cisco SD-WAN Lab (EVE-NG)

## 📌 Overview
This project demonstrates the implementation of a Cisco SD-WAN architecture using EVE-NG. The lab simulates a secure WAN environment with centralized management and control.

## 🧠 Objectives
- Deploy SD-WAN components (vManage, vSmart, vEdge)
- Establish secure overlay tunnels
- Implement basic policies
- Monitor network traffic

## 🏗 Architecture
![Architecture](diagrams/architecture.png)

## ⚙️ Technologies Used
- Cisco SD-WAN (vManage, vSmart, vEdge)
- EVE-NG
- Linux

## 🔧 Lab Setup
- vManage for centralized management
- vSmart as control plane
- vEdge routers as data plane
- Secure communication using IPsec tunnels

## 🧠 SD-WAN Architecture

- vBond: Authentication and orchestration
- vSmart: Control plane (OMP routing)
- vManage: Centralized management

## 🔐 Network Segmentation
- VPN 0: Transport network
- VPN 512: Management network

## 📸 Screenshots

### 🔹 Topology
![Topology](screenshots/topology.png)

### 🔹 vManage Dashboard
![vManage](screenshots/vmanage.png)

### 🔹 Policies
![Policies](screenshots/policies.png)

## 🔐 Security Features
- Encrypted tunnels (IPsec)
- Centralized policy control
- Segmentation

## 🧪 Testing
- Connectivity tests (ping between sites)
- Policy enforcement verification

## 📚 What I Learned
- SD-WAN architecture design
- Network segmentation
- Centralized network management
- Secure WAN deployment

## 🚀 Future Improvements
- Add advanced security policies
- Integrate firewall (Palo Alto)
- Automate deployment
## 📄 Documentation

A detailed report of this project is available here:

👉 [View Full Report](docs/sdwan-report.pdf)

## 👤 Author
Abdellah Alouane
