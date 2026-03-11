# phishing-email-analysis-lab

## Overview
This lab demonstrates how to analyze a suspicious email to determine whether it is a phishing attempt. The investigation focuses on identifying common phishing indicators such as sender spoofing, suspicious links, and brand impersonation.

---

## Scenario
A user receives an email claiming to be from **Coca-Cola** offering a free *Portable Blender & Juicer* as part of a loyalty program. The message encourages the recipient to click a button labeled **"GET STARTED NOW!"** to claim the reward.

---

## Investigation Steps

### 1. Email Inspection
The email was visually inspected for signs of phishing such as urgency, suspicious rewards, and brand impersonation.

Evidence:

evidence/email-overview.png


---

### 2. Sender Analysis
The sender claims to be Coca-Cola, but the email address uses an unrelated domain.

Example sender:


email_Gep2pQ76g78@opmajvpqjcg.georgs-faescht.com


This domain is not associated with Coca-Cola.

Evidence:

evidence/sender-details.png


---

### 3. Link Analysis
Hovering over the **GET STARTED NOW!** button reveals a long URL hosted on **cloudfront.net**, which is unrelated to the legitimate Coca-Cola domain.

Example:


https://d15k2d11r6f0rl.cloudfront.net/
...


Evidence:

evidence/phishing-link-analysis.png


---

### 4. Domain Reputation Check
The URL was analyzed using **VirusTotal** to determine whether it had been flagged as malicious.

Result:

0 / 95 security vendors flagged the URL


Even though it was not flagged, the suspicious context and domain mismatch still indicate phishing behavior.

Evidence:

evidence/domain-reputation-check.png


---

## Key Phishing Indicators Identified

- Sender domain unrelated to the brand being impersonated
- Too-good-to-be-true promotional offer
- Suspicious external link
- Brand impersonation (Coca-Cola)

---

## Conclusion

This email is **highly likely to be a phishing attempt** designed to lure users into visiting a malicious or fraudulent website.

Even though the URL was not flagged by security vendors, the combination of suspicious indicators strongly suggests malicious intent.

---

## Skills Demonstrated

- Phishing email analysis
- Sender domain investigation
- Link inspection
- Threat intelligence lookup (VirusTotal)
- Security investigation documentation

---
# Author

Femi Ijatoye  
Security+ Certified  
Cybersecurity / SOC Analyst Portfolio Project
