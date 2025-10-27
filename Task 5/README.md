# Task 5 - Capture and Analyze Network Traffic Using Wireshark
## Tools Used
- **Wireshark** (Free Network Packet Analyzer)

---
## Steps Performed
1. Installed Wireshark from https://www.wireshark.org/.
2. Selected the active network interface (Wi-Fi/Ethernet).
3. Started live capture.
4. Generated network traffic:
   - Browsed websites to generate **HTTP** and **TLS (HTTPS)** traffic.
   - Domain resolution automatically created **DNS** packets.
   - Used `ping google.com` to generate **ICMP** traffic.
5. Stopped capture after 1 minute.
6. Applied filters to analyze packets.
7. Saved capture file as `network_capture.pcap`.

## 📦 Protocols Identified
| Protocol | Purpose |
|----------|----------|
| **HTTP** | Unencrypted web traffic over port 80 |
| **DNS**  | Resolves domain names to IP addresses |
| **TLS**  | Encrypted HTTPS communication over port 443 |
| **ICMP** | Used for network testing (ping) |


## 🔎 Filters Used
| Protocol | Wireshark Display Filter |
|----------|---------------------------|
| **HTTP** | `http` |
| **DNS**  | `dns` |
| **TLS**  | `tls` |
| **ICMP** | `icmp` |
---

## Interview Answers
Q1: What is Wireshark used for?  
A: Wireshark is used for network packet analysis and troubleshooting.

Q2: What is a packet?  
A: A packet is a small unit of data transmitted across a network.

Q3: How to filter packets in Wireshark?  
A: Packets are filtered using display filters like http, dns, or icmp.

Q4: What is the difference between TCP and UDP?  
A: TCP is reliable and connection-oriented, while UDP is faster but connectionless.

Q5: What is a DNS query packet?  
A: It is a request sent to a DNS server to resolve a domain name to an IP address.

Q6: How can packet capture help in troubleshooting?  
A: It helps identify network delays, errors, and connectivity issues.

Q7: What is a protocol?  
A: A protocol is a set of rules that define how data is transmitted and received.

Q8: Can Wireshark decrypt encrypted traffic?  
A: No, it cannot decrypt encrypted traffic unless the necessary keys are provided.
