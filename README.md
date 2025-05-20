# FUTURE-CS_03

# TASK-03: Wi-Fi Security Assessment of Home Network

## 📌 Introduction

This project involves a security assessment of my personal home Wi-Fi network. The main objective was to evaluate its defenses against unauthorized access, identify potential vulnerabilities, and recommend improvements to enhance overall security.

---

## 🛠️ Tools Used

- **Wireshark** – For monitoring wireless network traffic and identifying any unencrypted data or suspicious activity.
- **Nmap** – For scanning the local network to identify active devices and open ports.

---

## 🔍 Methodology

### 1. Wi-Fi Traffic Analysis (Wireshark)
- Launched Wireshark and selected the wireless network interface.
- Captured wireless packets to analyze traffic patterns.
- Inspected packet contents for any unencrypted or suspicious data.

### 2. Network Scanning (Nmap)
- Detected active devices on the local network:
  ```bash
  sudo nmap -sn 192.168.0.1/24




