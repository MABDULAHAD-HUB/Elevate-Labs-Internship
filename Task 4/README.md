# Task 3 – Setup and Use a Firewall on Windows/Linux

## Objective
Configure firewall rules to improve system security by:
- Allowing SSH traffic on secure port **22**
- Blocking insecure Telnet traffic on port **23**

---

## Windows Firewall (GUI) – Steps Performed
1. Opened **Windows Defender Firewall with Advanced Security** using `wf.msc`.
2. Viewed existing **Inbound Rules**.
3. Created a new inbound rule to **block Telnet**:
   - Rule Type: Port
   - Protocol: TCP
   - Port: 23
   - Action: Block the connection
   - Name: `Block Telnet Port 23`
4. Created a rule to **allow SSH**:
   - Protocol: TCP
   - Port: 22
   - Action: Allow the connection
   - Name: `Allow SSH Port 22`
5. Tested Telnet block rule using PowerShell:
   ```powershell
   Test-NetConnection -ComputerName localhost -Port 23

## Linux UFW (Uncomplicated Firewall)
1. Checked UFW status: `sudo ufw status`
2. Allowed SSH on port 22 (to avoid losing remote access): `sudo ufw allow 22/tcp`
3. Blocked Telnet on port 23: `sudo ufw deny 23/tcp`
4. Verified firewall rules: `sudo ufw status numbered`
5. Removed Telnet block rule: `sudo ufw delete deny 23/tcp`
---
## Interview Answers
Q1: What is a firewall?  
A: A firewall is a security device or software that filters network traffic based on defined rules to protect systems from unauthorized access.

Q2: Difference between stateful and stateless firewall?  
A: Stateful firewalls track active connections and make decisions based on context, while stateless firewalls filter packets individually without connection tracking.

Q3: What are inbound and outbound rules?  
A: Inbound rules control incoming traffic to a system, while outbound rules control outgoing traffic from a system.

Q4: How does UFW simplify firewall management?  
A: UFW provides an easy command-line interface to manage iptables rules on Linux with simple allow/deny commands.

Q5: Why block port 23 (Telnet)?  
A: Telnet is insecure and sends data in plain text, making it vulnerable to sniffing and attacks.

Q6: What are common firewall mistakes?  
A: Allowing unnecessary ports, not blocking unused services, weak default rules, and no rule documentation.

Q7: How does a firewall improve network security?  
A: It controls and filters traffic, blocks unauthorized access, and prevents attacks like port scanning and malware communication.

Q8: What is NAT in firewalls?  
A: NAT (Network Address Translation) hides internal IP addresses by translating them to a public IP for secure internet communication.
