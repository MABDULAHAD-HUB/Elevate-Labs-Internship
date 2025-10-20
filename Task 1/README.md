# Task 1 — Scan Your Local Network for Open Ports

**Date:** 2025-10-20 

## Tools
Nmap, Wireshark

## Commands run (with notes)
- Host discovery:  
  `nmap -sn 192.168.1.0/24 -oN discovery.txt`  
- Basic SYN scan :  
  `nmap -sS <Target_IP> -oN scan_basic.txt`
  
## Files included
- discovery.txt
- scan_basic.txt
- screenshots/ss1.png (nmap scan screenshot)
- screenshots/ss2.png (Wireshark screenshot)

## Short interview answers
Q1: What is an open port?  
A: A port on a host where a service is listening and accepting network connections.

Q2: How does Nmap perform a TCP SYN scan?  
A: It sends a SYN packet; if SYN/ACK returns, the port is open (Nmap sends RST to avoid completing the handshake).

Q3: Risks of open ports?  
A: They expose services that attackers can exploit if unpatched, misconfigured, or using default credentials.

Q4: Difference between TCP and UDP scanning?  
A: TCP uses connection handshakes (more reliable); UDP sends datagrams and infers state from responses or ICMP messages (slower, less reliable).

Q5: How to secure open ports?  
A: Close unused ports/services, use firewalls and ACLs, patch, enforce strong authentication, and use VPN for remote access.
