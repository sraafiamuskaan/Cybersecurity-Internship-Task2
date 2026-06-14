# Task 2 – Network Security & Scanning

## Cybersecurity Internship – ApexPlanet Software Pvt. Ltd.

### Submitted By

Raafia Muskaan

## Overview

This repository contains the deliverables for **Task 2: Network Security & Scanning** completed as part of the Cybersecurity Internship at ApexPlanet Software Pvt. Ltd.

The task focused on reconnaissance, network scanning, vulnerability assessment, packet analysis, attack simulation, and firewall configuration using industry-standard cybersecurity tools.

## Objectives

* Perform network reconnaissance and information gathering.
* Identify active hosts, open ports, and running services.
* Conduct vulnerability assessment on a target system.
* Analyze network traffic using packet capture techniques.
* Simulate a SYN flood attack for educational purposes.
* Configure firewall rules to restrict network access.
* Document findings and security observations.

## Tools & Technologies Used

* Kali Linux
* Metasploitable2
* Oracle VirtualBox
* Nmap
* Nessus Essentials
* Wireshark
* hping3
* iptables

## Activities Performed

### 1. Network Reconnaissance

* WHOIS Lookup
* NSLOOKUP
* Banner Grabbing
* Connectivity Testing using Ping

### 2. Port & Service Scanning

* TCP SYN Scan (`-sS`)
* UDP Scan (`-sU`)
* Service Version Detection (`-sV`)
* Operating System Detection (`-O`)
* Aggressive Scan (`-A`)

### 3. Vulnerability Assessment

* Installed and configured Nessus Essentials
* Scanned Metasploitable2
* Analyzed vulnerability severity levels:

  * Critical
  * High
  * Medium
  * Low

### 4. Packet Analysis using Wireshark

* HTTP Traffic Analysis
* DNS Traffic Analysis
* FTP Credential Capture
* Protocol Inspection

### 5. SYN Flood Simulation

* Generated TCP SYN packets using hping3
* Captured traffic using Wireshark
* Analyzed SYN flood behavior

### 6. Firewall Configuration

* Created iptables firewall rules
* Blocked HTTP traffic on Port 80
* Demonstrated scan blocking
* Restored connectivity after testing

## Key Findings

* Multiple vulnerable services were discovered on Metasploitable2.
* Open services included FTP, Telnet, SMB, and HTTP.
* Nessus identified several Critical and High-risk vulnerabilities.
* FTP credentials were transmitted in plaintext, highlighting the importance of secure protocols.
* Wireshark successfully captured and analyzed network traffic.
* Firewall rules effectively blocked targeted services and scan attempts.

## Learning Outcomes

Through this task, I gained practical experience in:

* Network reconnaissance techniques
* Port and service enumeration
* Vulnerability assessment methodologies
* Network packet analysis
* Attack simulation and traffic monitoring
* Firewall rule creation and testing
* Security reporting and documentation

## Conclusion

This task provided hands-on exposure to real-world network security assessment techniques. By using tools such as Nmap, Nessus, Wireshark, hping3, and iptables, I developed a deeper understanding of how security professionals identify vulnerabilities, analyze traffic, and implement defensive controls within a network environment.
