# Task 2 — Analyze a Phishing Email Sample

**Date:** 2025-10-22   

## Sample Used
- Phishing email file: `Phishing-sample.eml`
- Phishing screenshot: `Phishing-sample.png`

---

## Evidence Screenshots
| Tool Used | Screenshot |
|------------|------------|
| EML Analyzer (Email Header Analysis) | `EML_Analyzer.png` |
| Google Admin Toolbox - Message Header Analyzer | `Google_Admin_Toolbox.png` |
| VirusTotal - Domain/IP/URL Reputation Check | `virus_total.png` |
| MXToolbox - Email Header & DNS Check | `Mxtoolbox.png` |

---

## Email Header Details

**From (display & envelope):**  
- Display name (`From:`): `Microsoft account team ,_<no-reply@access-accsecurity.com>`  
- Envelope sender (`Return-Path:`): `bounce@thcultarfdes.co.uk`  
- Sending IP (`X-Sender-IP`): `89.144.44.2`

**To:**  
- `phishing@pot`

**Reply-To (Suspicious):**  
- `sotrecognizd@gmail.com`

---

## Suspicious Links / URLs Found
| Type | URL |
|------|-----|
| Fake Reply Link | `mailto:sotrecognizd@gmail.com?&cc=sotrecognizd@gmail.com&Subject=Report+The+User` |
| Malicious Contact Link | `mailto:sotrecognizd@gmail.com?&cc=sotrecognizd@gmail.com&subject=unusual signin activity&body=Report The User` |
| Fake Unsubscribe Link | `mailto:sotrecognizd@gmail.com?&cc=sotrecognizd@gmail.com&Subject=Unsubscribe+me` |
| Tracking Pixel | `http://thebandalisty.com/track/o43062rdzGz18708448Gdrw1821750fYo33632dSjh176` |

**Other malicious domains observed:**
- `access-accsecurity.com`
- `thcultarfdes.co.uk`
- `thebandalisty.com`

**SPF/DMARC Failure:**
- `Received-SPF: None`
- No DKIM signature
- DMARC verification failed

---

## Phishing Indicators Found
- ⚠️ **Fake sender identity** pretending to be Microsoft  
- ⚠️ **Free Gmail reply-to** used for data theft  
- ⚠️ **Tracking pixel** to collect victim IP and device info  
- ⚠️ **Urgent phishing message** asking for account verification  
- ⚠️ **External redirection links** to unknown domains  
- ⚠️ **Grammar errors & bad layout**  
- ⚠️ **No email authentication** (SPF/DKIM/DMARC failed)  

---


## Interview Questions (Short Answers)

**Q1. What is phishing?**  
A cyberattack using fake emails/webpages to steal sensitive data like passwords or OTPs.

**Q2. How to identify a phishing email?**  
Check sender email, link URLs, grammar, urgency, domain mismatch, and header data.

**Q3. What is email spoofing?**  
Fake email headers are used to impersonate a trusted sender.

**Q4. What should you do if you get a phishing email?**  
Don’t interact, report it, and verify from the official website.

**Q5. Why is phishing dangerous?**  
Can lead to account takeover, money loss, and data theft.

**Q6. How to verify email sender authenticity?**  
Check SPF/DKIM/DMARC, email headers, official sources.

**Q7. Tools used for analysis?**  
- Google Admin Toolbox  
- MXToolbox  
- VirusTotal  
- EML Analyzer  

**Q8. How do attackers trick users?**  
Using urgency, fear, fake warnings, impersonation, and emotional manipulation.


