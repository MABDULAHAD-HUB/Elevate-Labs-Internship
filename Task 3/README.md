# Task 3 – Perform a Basic Vulnerability Scan on Your PC.

## Environment
- **Attacker (scanner):** Kali Linux with OpenVAS (GVM)  
- **Target:** Metasploitable2 VM  
- **Scan profile used:** Full and fast  

---

## How I Ran the Scan (short)
1. Started GVM: `sudo gvm-start`  
2. Opened Greenbone Web UI at `https://127.0.0.1:9392` and logged in.  
3. Created a new **Target** for the Metasploitable2 IP.  
4. Created a **Task** using the "Full and fast" scan config and launched it.  
5. Waited for completion  and exported the report (PDF). Screenshots saved in `/screenshots`.

---


## Interview Answers

Q1: What is vulnerability scanning?  
A: It is the process of automatically scanning systems to find security weaknesses and missing patches.

Q2: Difference between vulnerability scanning and penetration testing?  
A: Scanning finds vulnerabilities automatically, while penetration testing tries to exploit them manually to assess real risk.

Q3: What are some common vulnerabilities in personal computers?  
A: Outdated software, weak passwords, open ports, missing patches, and disabled firewalls/antivirus.

Q4: How do scanners detect vulnerabilities?  
A: They compare system information with known vulnerability databases (like CVE) and check for outdated or misconfigured services.

Q5: What is CVSS?  
A: The Common Vulnerability Scoring System, a standard scale (0–10) used to rate the severity of vulnerabilities.

Q6: How often should vulnerability scans be performed?  
A: Regularly—weekly or monthly—and after major updates or system changes.

Q7: What is a false positive in vulnerability scanning?  
A: When a scanner reports a vulnerability that doesn’t actually exist on the target system.

Q8: How do you prioritize vulnerabilities?  
A: Based on CVSS score, severity level (Critical/High/Medium), exploitability, and business impact.


