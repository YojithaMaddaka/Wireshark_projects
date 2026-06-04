# 🌐 Wireshark Traffic Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Wireshark-blue?style=for-the-badge&logo=wireshark"/>
  <img src="https://img.shields.io/badge/Platform-Kali%20Linux-orange?style=for-the-badge&logo=linux"/>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>
</p>

---

## 📖 Overview
This project demonstrates **packet capture and protocol analysis** using Wireshark.  
It highlights how to inspect traffic flows such as **ICMP, DNS, HTTP, and TLS** to understand network communication and security.

---

## 🚀 Steps to Follow
1. 🔍 **Connectivity Test** – Ping `wikipedia.org`  
2. 📡 **Packet Capture** – Capturing traffic on `eth0`  
3. 🎯 **Filters Applied**
   - ICMP (ping)
   - DNS queries
   - HTTP requests
   - TCP/TLS streams  
4. 🧩 **Analysis**
   - Protocol breakdown
   - Handshake inspection
   - Application data

---

## 🖼️ Screenshots
- ✅ Ping output  
- ✅ ICMP packets  
- ✅ DNS resolution  
- ✅ HTTP GET request  
- ✅ TLS handshake  

*(Screenshots are stored in the `screenshots/` folder for reference.)*

---

## 🎯 Conclusion
Wireshark provides **deep visibility into network communication**, making it invaluable for:
- 🛠️ Diagnostics  
- 🔐 Cybersecurity learning  
- 📡 Protocol analysis  

---

## ✅ Final Outcome
- Successfully captured and analyzed traffic on `eth0`.  
- Applied filters to isolate ICMP, DNS, HTTP, and TLS flows.  
- Interpreted packet details at each layer (Ethernet, IP, TCP/UDP, TLS, HTTP).  
- Documented findings with screenshots for reproducibility.  

---

## 📂 Repository Structure
```plaintext
Wireshark-Traffic-Analysis/
│── README.md
│── captures/
│    └── traffic_capture.pcapng
│── screenshots/
│    ├── tcp_stream.png
│    ├── dns_query.png
│    ├── http_request.png
│    └── icmp_ping.png
│── filters/
│    └── common_filters.txt
│── Wireshark_Traffic_Analysis.pcapng   <-- Main capture file in repository
