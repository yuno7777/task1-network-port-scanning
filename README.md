# Elevate Labs Task

# Task No 1 Network Port Scanning using Nmap

## Task Overview
This task involved scanning the local network to discover open ports on connected devices using **Nmap**. It helped build basic skills in **network reconnaissance**, understanding **IP addressing**, and identifying potential **security risks**.

---

##  Objective
To perform a **TCP SYN scan** on the local network and analyze open ports to understand network exposure and vulnerabilities.

---

##  Tools Used
- [Nmap](https://nmap.org/download.html) – for scanning IP range

---

##  Steps Performed

1. **Identified Local IP Range**
   - Used `ipconfig`/`ifconfig` to find local IP 

2. **Ran Nmap TCP SYN Scan**
    ```bash
   nmap -sS 'Ip Address' -oN scan_results.txt

