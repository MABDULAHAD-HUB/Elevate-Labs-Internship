# Task 6 - Create a Strong Password and Evaluate Its Strength

## 🛠 Tools Used
- **Password Strength Checker:** https://passwordmeter.com  
- **Bitwarden Password Strength Checker:** https://bitwarden.com/password-strength/
---
## Sample Password Test Results

| No. | Password Example       | Length | Characters Used                          |
|-----|------------------------|--------|-------------------------------------------|
| 1   | password               | 8      | lowercase only                            |
| 2   | pass123                | 7      | lowercase + numbers                       |
| 3   | Pass1234              | 8      | upper + lower + numbers                   |
| 4   | P@ssw0rd              | 8      | mix + symbol                              |
| 5   | S3cure!Key            | 10     | strong mix                                |
| 6   | My#Secret#2025        | 14     | long + strong                             |
| 7   | @H4d$A!_Pr0j3ct#98    | 18     | very strong + random                      |

## Best Password Practices
- Use **minimum 12–16 characters**
- Include **uppercase + lowercase + numbers + symbols**
- Avoid predictable passwords like `password123`
- Do **not reuse passwords** on multiple accounts
- Turn on **Two-Factor Authentication (2FA)**
- Use a **password manager** like Bitwarden or LastPass

## Common Password Attacks

**Brute Force Attack**  
A brute force attack tries *every possible* combination of characters until the correct password is found. It is guaranteed to succeed given enough time and computing power, but the time required grows exponentially with password length and character set. Attackers often use GPU-accelerated tools to speed up guessing.
- GeeksforGeeks — Brute Force Attack. https://www.geeksforgeeks.org/computer-networks/brute-force-attack/ 
  
**Dictionary Attack**  
A dictionary attack tests passwords from a precompiled list of common words, leaked passwords, and variants. Since many users choose predictable words or simple variations, dictionary attacks tend to succeed much faster than brute force for typical weak passwords.
- GeeksforGeeks — What is a Dictionary Attack? https://www.geeksforgeeks.org/computer-networks/what-is-a-dictionary-attack/
---

##  Interview Answers

**Q1: What makes a password strong?**  
A strong password is long (at least 12 characters), includes uppercase and lowercase letters, numbers, symbols, and avoids common words or patterns.

**Q2: What are common password attacks?**  
Common password attacks include brute force attacks, dictionary attacks, phishing, keylogging, and credential stuffing.

**Q3: Why is password length important?**  
Password length increases security because longer passwords take much more time to crack using brute force methods.

**Q4: What is a dictionary attack?**  
A dictionary attack uses a list of common words or leaked passwords to guess weak passwords quickly.

**Q5: What is multi-factor authentication (MFA)?**  
MFA adds an extra verification step (like OTP, email code, or fingerprint) in addition to the password for better security.

**Q6: How do password managers help?**  
Password managers securely store and generate strong, unique passwords for each account so users don’t have to remember them.

**Q7: What are passphrases?**  
Passphrases are long passwords made from random words (e.g., `river-sun-battery-phone`) that are secure and easy to remember.

**Q8: What are common mistakes in password creation?**  
Using weak passwords, reusing passwords, including personal details, using dictionary words, and not enabling 2FA are common mistakes.



