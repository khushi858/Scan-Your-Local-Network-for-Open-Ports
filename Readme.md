# 🕵️‍♂️ Nmap Local Network Scanning Task

## 📌 Task Overview
This task involves scanning the local network using **Nmap** to discover active devices, open ports, and running services.  
The goal is to understand the basics of network reconnaissance and potential security risks.

---

## 🛠 Tools Used
- **Nmap** (Network Mapper) → [https://nmap.org/download.html](https://nmap.org/download.html)
- **Wireshark** (Optional for packet analysis) → [https://www.wireshark.org/](https://www.wireshark.org/)

---

## 🔍 Steps Followed

### **1. Install Nmap**
- **Windows:** Download installer from [Nmap.org](https://nmap.org/download.html) and install with default settings.
- **Linux (Ubuntu/Debian):**
  ```bash
  sudo apt update && sudo apt install nmap -y

##  Identify Local IP Range

-  **Windows:**
```bash
ipconfig

- **Linux:**
```bash
ifconfig
#or
ip a

### Run TCP SYN Scan

```bash
nmap -sS 192.168.1.0/24

-sS → Stealth SYN scan
192.168.1.0/24 → Scan all IPs in the subnet

