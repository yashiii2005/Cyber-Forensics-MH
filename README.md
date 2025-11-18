# 🔐 Cyber Forensics Practicals – Documentation

This repository contains the practical implementation and analysis of various Cyber Forensics tasks including network command demonstrations, forensic imaging, data recovery, and packet analysis.

---

## 📍 Student Details
**Name:** Yahsasvi Goswami  
**Roll No:** 2022/1315  
**Course:** B.Sc. Physical Science with Computer Science

---

## 📗 Index
| S.No | Practical Title |
|------|----------------|
| 1 | Demonstration of Windows Network related Commands |
| 2 | Demonstration of Linux Network related Commands |
| 3 | Data Recovery using Autopsy Tool |
| 4 | Creating Forensic Image using FTK Imager |
| 5 | Capturing & Analysing Network Packets using Wireshark |
| 6 | Analysis of Windows Registry |

---

## 🖥️ 1. Demonstration of Windows Network Commands

| Command | Description |
|---------|------------|
| `ping` | Tests network connectivity and measures response time |
| `ipconfig` | Shows network interface configuration including IP |
| `netstat` | Shows active connections, ports, routing table |
| `systeminfo` | Displays OS, hardware & configuration details |
| `getmac` | Displays MAC addresses of network adapters |
| `nslookup` | Queries DNS information for domain addresses |
| `whoami` | Displays the logged-in username |
| `route print` | Displays routing table entries |

---

## 🐧 2. Demonstration of Linux Network Commands

| Command | Description |
|---------|------------|
| `arp` | Shows ARP table mappings (IP ↔ MAC) |
| `hostname` | Displays or sets the system name |
| `netstat` / `ss` | Shows network connections & port usage |
| `tracepath` / `traceroute` | Shows packet route to destination |
| `whoami` | Displays current user information |
| `whois` | Shows domain registration information |
| `nslookup` / `dig` | DNS query tools |
| `mtr` | Real-time network path + ping analysis |
| `ping` | Tests network connectivity |
| `grep` | Searches text patterns inside files |

---

## 🕵️ 3. Data Recovery using Autopsy Tool

### Steps Performed:
1. Created a **New Case** with case details
2. Added evidence source (local disk)
3. Selected ingest modules (Recent Activity, Hash Lookup, Keyword Search, PhotoRec Carver)
4. Autopsy automatically analyzed filesystem
5. Recovered deleted files and viewed content
6. Explored timeline, artifacts, recycle bin & deleted data

---

## 💾 4. Creating Forensic Image using FTK Imager

### Major Steps
- Selected **Contents of a Folder** as evidence type
- Added case info (Case Number, Examiner, Evidence Number)
- Chose destination location and filename
- Selected format `.ad1`
- Enabled **Hash verification (MD5/SHA1)** & directory listing
- Completed imaging process & confirmed integrity

### Output Files Generated
