# Task 2 — Analyze a Phishing Email Sample

**Date:** 2025-10-22

## Sample Used
- Phishing screenshot: `Phishing-sample.png`


## Phishing Indicators Found (short)
- **Fake sender email** — `outlooo.teeam@outlook.com` (typos / extra characters).  
- **Generic greeting** — “Dear Outlook user” (not personalized).  
- **Urgency / pressure** — Claims “blocked incoming mails” and forces verification.  
- **Suspicious verification link** — `http://spapparelsindia.in/Aprons/outlook.com/login.html` (non-Microsoft domain).  
- **Domain mismatch** — Link domain unrelated to Microsoft.  
- **Brand impersonation** — Uses Outlook/Microsoft logo and wording to appear legitimate.  
- **Grammar / formatting errors** — Unprofessional text and punctuation issues.

## Quick Actions / Recommendations
1. **Do not click** the link or open attachments.  
2. **Report** the email to your IT/security team or email provider.  
3. **If clicked or credentials entered:** immediately change password from a known-good device and enable MFA.  
4. **Preserve evidence** (screenshot/raw headers) for reporting.

## Short interview answers
Q1: What is phishing?  
A: Phishing is a cyberattack where fake emails, messages, or websites are used to trick people into revealing sensitive information like passwords, banking data, or personal details.

Q2: How to identify a phishing email?  
A: Look for suspicious sender addresses, spelling or grammar errors, urgent or threatening language, fake links, unexpected attachments, and mismatched domains.

Q3: What is email spoofing?  
A: Email spoofing is the act of forging the sender's address to make an email appear to come from a trusted source, like a bank or company, to deceive the receiver.

Q4: What should you do on receiving such an email?  
A: Do not interact, report it, and verify via official channels.

Q5: Why are phishing emails dangerous?  
A: They can steal login credentials, financial data, install malware, take over accounts, or lead to identity theft and financial loss.

Q6: How can you verify the sender’s authenticity?  
A: Check the domain of the email address, inspect email headers, hover over links to verify URLs, contact the sender through official channels, and check SPF/DKIM/DMARC validation.

Q7: What tools can analyze email headers?  
A: Tools like MXToolbox Header Analyzer, Google Message Header Tool, MessageHeader, or built-in commands like whois, nslookup, and dig.

Q8: How do attackers use social engineering in phishing?  
A: They manipulate emotions like fear, urgency, curiosity, or trust to trick users into acting quickly—like clicking malicious links or giving their passwords.



