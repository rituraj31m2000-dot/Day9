
# Ransomware Awareness – Day 9 | Cyber Security Internship

**Intern:** Ritu Raj
**Organization:** Veda Technology
**Track:** Cyber Security (Level 1 – Day 9)
**Tools Used:** Browser, Google Docs

## Objective
Understand ransomware risks and prevention by studying the attack lifecycle at a conceptual level and identifying defensive controls.

## What is Ransomware?
Ransomware is malware that encrypts a victim's files (or locks their system) and demands payment, usually in cryptocurrency, in exchange for the decryption key. Modern variants also steal data first ("double extortion") and threaten to leak it.

## Ransomware Attack Lifecycle (Conceptual)
1. **Initial Access** – phishing emails, malicious attachments, exposed RDP, unpatched software, stolen credentials
2. **Execution** – the malicious payload runs on the victim's machine
3. **Privilege Escalation and Lateral Movement** – attacker gains higher access and spreads across the network
4. **Data Exfiltration** – sensitive data is stolen for extortion
5. **Encryption** – files are encrypted and backups are targeted
6. **Ransom Demand** – ransom note is displayed with payment instructions

## Ransomware Prevention Checklist
### Backups
- [ ] Follow the 3-2-1 rule (3 copies, 2 media types, 1 offline/offsite)
- [ ] Keep at least one backup offline or immutable
- [ ] Test restoring backups regularly

### Patching and Updates
- [ ] Keep OS, browsers and applications updated
- [ ] Patch known vulnerabilities quickly
- [ ] Remove or replace unsupported software

### Identity and Access
- [ ] Enable MFA on all accounts, especially email, admin and remote access
- [ ] Use strong, unique passwords with a password manager
- [ ] Apply least privilege: users get only the access they need
- [ ] Separate admin accounts from daily-use accounts

### Email and User Awareness
- [ ] Train users to spot phishing
- [ ] Filter spam and block risky attachments (macros, .exe, .js)
- [ ] Report suspicious emails instead of opening them

### Endpoint and Network Security
- [ ] Use antivirus/EDR with real-time protection
- [ ] Disable unused services and close exposed RDP ports
- [ ] Segment the network to limit spread
- [ ] Monitor logs for unusual activity

### Incident Readiness
- [ ] Maintain an incident response plan
- [ ] Know who to call and how to isolate infected machines quickly
- [ ] Do not rely on paying the ransom; payment does not guarantee recovery

## Interview Questions

**Q1. What is ransomware?**
Malware that encrypts or locks a victim's data and demands a ransom for access. Many variants also steal data to threaten a public leak.

**Q2. Why are backups important?**
Backups let an organization restore data without paying the ransom. They must be tested, and at least one copy should be offline or immutable so ransomware cannot encrypt it too.

**Q3. What is least privilege?**
Giving users, apps and systems only the minimum access needed for their job. If an account is compromised, the damage and spread of ransomware stay limited.

## Key Takeaways
- Most ransomware attacks begin with phishing, weak credentials or unpatched systems.
- Backups, patching, MFA and least privilege together greatly reduce risk.
- Preparation and user awareness matter as much as technical tools.

## Outcome
Studied the ransomware lifecycle conceptually, prepared a prevention checklist and answered the core interview questions on ransomware, backups and least privilege.

*This task is for educational and defensive awareness purposes only.*
