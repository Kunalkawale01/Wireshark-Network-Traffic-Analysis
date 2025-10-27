## Author
**Kunal Kawale**  
Cybersecurity Trainee | SOC Project  
📅 Date: October 27, 2025

# Wireshark-Network-Traffic-Analysis
As part of the Cybersecurity Internship Project, this task involved performing network traffic capture and analysis using the tool Wireshark. The goal was to understand how data travels across a network, identify the protocols in use, and analyze packet-level communication between systems.

# Task 5: Capture and Analyze Network Traffic Using Wireshark

## Objective
Capture live network packets and identify basic protocols and traffic types using Wireshark.

## Tools Used
- **Wireshark** (Free network protocol analyzer)
- **Operating System:** Windows / Linux
- **Protocols Observed:** DNS, HTTP, ICMP, TCP, UDP
- 
## Steps Performed

### 1. Installed Wireshark
Downloaded and installed from [wireshark.org](https://www.wireshark.org/).

### 2. Started Capture
- Opened Wireshark and selected active network interface (Wi-Fi).
- Began live capture.

### 3. Generated Network Traffic
- Visited several websites (e.g., google.com, wikipedia.org)
- Ran command: `ping google.com` to generate ICMP traffic.

### 4. Stopped Capture
After one minute of data collection, stopped capture and saved it as:

## Protocols Identified

| Protocol | Description | Example |
|-----------|--------------|----------|
| **DNS** | Resolves domain names into IP addresses. | Query: `A www.google.com` |
| **HTTP** | Web traffic for browsing sites. | GET request to `wikipedia.org` |
| **ICMP** | Used for ping operations. | Echo request/reply to `8.8.8.8` |
| **TCP** | Reliable connection protocol. | SYN/ACK handshake |
| **UDP** | Connectionless data transfer. | DNS queries over UDP 53 |

## Observations
- DNS queries occur before HTTP requests.
- TCP three-way handshake observed.
- ICMP packets seen during ping.
- Mix of UDP (DNS) and TCP (HTTP) traffic.
  
## Files in This Repository

| File / Folder | Description |
|----------------|--------------|
| `captures/network_capture.pcap` | Raw packet capture file |
| `report/Wireshark_Report.pdf` | Detailed analysis report |
| `screenshots/` | Evidence of packet filters |
| `README.md` | Documentation file |

## Outcome
Hands-on experience in:
- Packet capturing with Wireshark  
- Protocol identification  
- Network traffic analysis  

**Result:** Improved understanding of TCP/IP communication and protocol behavior.
