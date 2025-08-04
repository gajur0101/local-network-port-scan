# local-network-port-scan
Network scanning task using Nmap

## 🎯 Objective
Perform a reconnaissance scan on a local network using Nmap to identify open ports and assess potential security risks.

## 🛠️ Tools Used
- Nmap

## 🧪 Steps Taken

1. Identified local subnet using `ip a` → `192.168.1.0/24`
2. Ran a TCP SYN scan using:
   
   sudo nmap -sS 192.168.1.0/24 -oN nmap/nmap-scan-results.txt
