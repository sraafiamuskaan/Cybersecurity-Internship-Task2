# Task 2 – Network Security & Scanning

## ApexPlanet Software Pvt. Ltd. – Cybersecurity Internship

### Submitted By

Raafia Muskaan

---

## Objective

The objective of this task was to perform network reconnaissance, port scanning, vulnerability assessment, packet analysis, and firewall configuration using industry-standard cybersecurity tools.

---

## Tools Used

* Kali Linux
* Metasploitable2
* Nmap
* Nessus Essentials
* Wireshark
* hping3
* iptables
* Oracle VirtualBox

---

## Activities Performed

### 1. Network Reconnaissance

* WHOIS Lookup
* NSLOOKUP
* Banner Grabbing
* Connectivity Testing using Ping

### 2. Port & Service Scanning

* TCP SYN Scan
* UDP Scan
* Service Version Detection
* Operating System Detection
* Aggressive Nmap Scan

### 3. Vulnerability Assessment

* Installed Nessus Essentials
* Scanned Metasploitable2
* Identified Critical, High, Medium, and Low vulnerabilities

### 4. Packet Analysis using Wireshark

* HTTP Traffic Analysis
* DNS Traffic Analysis
* FTP Credential Capture
* Protocol Inspection

### 5. SYN Flood Simulation

* Generated TCP SYN packets using hping3
* Captured and analyzed packets using Wireshark

### 6. Firewall Configuration

* Created iptables rules
* Blocked HTTP traffic on port 80
* Demonstrated scan blocking
* Restored connectivity by removing firewall rules

---

## Key Findings

* Multiple vulnerable services were discovered including FTP, Telnet, SMB, and HTTP.
* Nessus identified several critical and high-risk vulnerabilities.
* FTP transmitted credentials in plaintext, demonstrating the risks of unencrypted protocols.
* Firewall rules successfully blocked access to selected services and prevented scan attempts.

---

## Repository Contents

* Task2_Report.pdf
* nmap_report.txt
* Screenshots
* README.md

---

## Conclusion

This task provided hands-on experience in network reconnaissance, vulnerability assessment, packet analysis, and firewall management. Practical exposure to Nmap, Nessus, Wireshark, hping3, and iptables strengthened understanding of real-world cybersecurity assessment techniques.
