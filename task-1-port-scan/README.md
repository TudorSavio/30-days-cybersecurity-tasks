# 🔍 Task 1: Nmap Port Scan and Wireshark Analysis

## 📌 Objective
To scan the local network for open ports and analyze network traffic using Nmap and Wireshark.

## 🛠 Tools Used
- Nmap
- Wireshark

## 📄 Files Included
- `scan_results.txt` – Output from Nmap scan
- `scan_capture.pcapng` – Packet capture file (optional)
- `screenshot.png` – Screenshot of terminal (optional)

## 🧪 Nmap Command Used
```bash
nmap -sS 192.168.1.0/24 -oN scan_results.txt
