# 🛡️ Cybersecurity Homelab Project

![Homelab](https://upload.wikimedia.org/wikipedia/commons/6/66/Network_Diagram.png)

This project is inspired by Grand Collins and aims to create an **enterprise-level cybersecurity homelab** for **offensive and defensive security** training. The setup consists of various virtual machines and security tools to simulate real-world IT environments.

## 🚀 Project Overview

This homelab helps in understanding key security concepts by setting up an Active Directory (AD) environment with **Windows Server 2025, Windows 11 Enterprise, and Linux distributions** connected via NAT + Bridge networking.

---
## 📌 Network Topology
```
+-----------------+          +-----------------+
| Windows 11 Ent |          | Kali Linux     |
| Workstation    |  <-----> | (Attack Box)   |
+-----------------+          +-----------------+
          |                        |
          |                        |
+-----------------+          +-----------------+
| Windows Server |          | Security Onion |
| 2025 (AD, DNS) |          | (SIEM)         |
+-----------------+          +-----------------+
          |
          |
+-----------------+
| pfSense Firewall|
| (NAT & Bridge)  |
+-----------------+
```

---
## 🔧 Performed Tasks

✅ **Active Directory (AD) Setup** 🖥️  
✅ **Windows Server 2025 Configuration** ⚙️  
✅ **DNS & DHCP Server Setup** 🌍  
✅ **pfSense Firewall Configuration** 🔥  
✅ **Security Onion (SIEM) Monitoring** 📊  
✅ **Wazuh Deployment for Log Analysis** 🛡️  
✅ **Kali Linux for Penetration Testing** 🕵️  
✅ **Vulnerability Scanning with Nessus** 🔍  
✅ **OpenVPN Setup for Secure Remote Access** 🔑  
✅ **Exploring Threat Actor Behavior** 🎭  

---
## 📸 Screenshots
| Tool | Screenshot |
|------|-----------|
| **Windows Server 2025 AD** | ![Windows AD](https://via.placeholder.com/300x200?text=Windows+AD) |
| **pfSense Firewall** | ![pfSense](https://via.placeholder.com/300x200?text=pfSense) |
| **Security Onion** | ![Security Onion](https://via.placeholder.com/300x200?text=Security+Onion) |
| **Wazuh SIEM** | ![Wazuh](https://via.placeholder.com/300x200?text=Wazuh) |
| **Kali Linux Attack Box** | ![Kali](https://via.placeholder.com/300x200?text=Kali+Linux) |

---
## 🎓 Learning Outcomes

📌 **Security auditing and log analysis** 🔎  
📌 **Understanding of Active Directory security** 🏢  
📌 **Firewall and network security management** 🔥  
📌 **Exploring SIEM & intrusion detection** 🛡️  
📌 **Hands-on penetration testing & exploitation** 💻  

---
## 📂 Documentation

📖 Full documentation: [View Here](#) *(Add your documentation link here)*

---
## 📢 Credits
This project is inspired by **Grand Collins' Homelab Guide** and is expanded with additional security enhancements and configurations.

---
## 🤝 Contribute
💡 Feel free to fork, modify, and enhance this project. Contributions are welcome!

🌟 **Star this repo** if you find it useful! 🔥
