# Information Gathering on Websites Using Linux

## Introduction
Information gathering is the initial phase of ethical hacking where penetration testers or hackers collect valuable data about a target. This step is crucial to understanding potential vulnerabilities, as it allows testers to map network structures, identify devices, and detect potential weaknesses.

This project demonstrates how to gather information using Linux tools like Nmap, Macchanger, Netstat, and Wireshark, providing practical insights into network security.

---

## Goals
- Understand and demonstrate the use of essential cybersecurity tools.
- Collect and analyze information from target systems.
- Gain proficiency in identifying open ports, operating systems, services, and network traffic.

---

## Tools and Requirements
- **Operating System**: Kali Linux
- **Tools**: 
  - Nmap
  - Macchanger
  - Netstat
  - Wireshark
- **Additional Requirements**: A separate Windows machine for testing.

---

## Labs Overview

### **Lab 1: Nmap**
**Objective**: Scan a target machine to retrieve:
- IP address
- Operating System details
- Open ports
- Running services

**Commands**:
- `nmap -O <target-ip>`: Retrieve OS details.
- `nmap -p- <target-ip>`: Identify open ports.
- `nmap -sV <target-ip>`: Detect services.

---

### **Lab 2: Macchanger**
**Objective**: Change the MAC address of your machine.

**Commands**:
- `macchanger -s eth0`: Display current MAC address.
- `macchanger -r eth0`: Set a random MAC address.

---

### **Lab 3: Netstat**
**Objective**: Analyze network connections on a Windows machine.
- Enumerate all ports: `netstat -a`
- Display the routing table: `netstat -r`

---

### **Lab 4: Wireshark**
**Objective**: Inspect network traffic using Wireshark.
- Identify protocols in network traffic.
- Locate the protocol used for data transmission.
- Monitor TCP Streams and retrieve actual data transmitted.

**Pre-requisite**: Configure Kali VM and the Windows machine to be on the same bridged network.

---

## Learning Outcomes

- Proficiency in using Linux tools for network reconnaissance.
- Ability to analyze and interpret network traffic.
- Understanding of ethical hacking methodologies for information gathering.

---

## Disclaimer

This repository is intended solely for educational purposes. The tools and techniques demonstrated are to be used only in authorized environments and with proper permissions. Unauthorized use of these techniques on systems or networks without consent is illegal and may result in severe penalties under cybersecurity laws.
The authors and contributors are not responsible for any misuse of the information provided. Always follow ethical hacking guidelines and respect privacy and legal boundaries.
