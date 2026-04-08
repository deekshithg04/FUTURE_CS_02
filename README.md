# 🎣 Phishing Email Detection & Awareness System  
### Cyber Security Task 2 (2026) – Future Interns

## 📌 Overview

This repository contains a **Phishing Email Detection & Awareness Report** completed as part of **Cyber Security Task 2 by Future Interns**.

The objective of this task was to **analyze multiple phishing email samples**, identify common attack patterns and red flags, classify each email by risk level, and present findings in a **clear, professional format** suitable for employee security awareness training.

This task strictly follows ethical guidelines and involves **no hacking, exploitation, or illegal activity**.

---

## 🎯 Objective

- Analyze real-world phishing email samples  
- Identify common phishing indicators and red flags  
- Classify email risk clearly (Safe / Suspicious / Phishing)  
- Explain how each attack works in simple, non-technical language  
- Create awareness guidelines that businesses and employees can actually use  

---

## ⚠️ Scope & Ethics

This assessment follows a **read-only, passive analysis approach**.

### ✅ Allowed
- Analysis of publicly available phishing email samples  
- Email header inspection using approved tools  
- URL and domain structure review (without clicking)  
- Risk classification and documentation  

### ❌ Not Allowed
- Clicking any malicious links  
- Downloading any attachments  
- Interacting with phishing infrastructure  
- Any harmful or illegal activity  

> This project demonstrates **security awareness education, not hacking**

---

## 🛠️ Tools Used

- **Google Admin Toolbox (Message Header Analyzer)** – Email header analysis & SPF/DKIM/DMARC inspection  
  → https://toolbox.googleapps.com/apps/messageheader/
- **MXToolbox Email Header Analyzer** – Deep header inspection and blacklist checks  
  → https://mxtoolbox.com/EmailHeaders.aspx
- **Browser DevTools** – Safe URL inspection and domain analysis without clicking  
- **Public Phishing Datasets (GitHub)** – Reference samples for analysis (study only)  

---

## 🔍 Methodology

The analysis was conducted using a safe, passive, read-only approach:

1. **Collected** phishing email samples from public educational datasets  
2. **Analyzed** email headers using Google Toolbox and MXToolbox  
3. **Inspected** sender domains and link structures without clicking  
4. **Identified** phishing indicators present in each email  
5. **Classified** each email as Safe, Suspicious, or Phishing  
6. **Documented** findings with clear explanations and attack descriptions  
7. **Created** prevention guidelines and Do's & Don'ts for employees  

No links were clicked, no attachments were opened, and no systems were interacted with.

---

## 📧 Email Samples Analyzed

| # | Email Subject | Attack Type | Risk Level | Classification |
|---|--------------|------------|-----------|---------------|
| 1 | Monthly Account Statement | Legitimate Communication | None | ✅ Safe |
| 2 | Important Notice Regarding Your Account | Link Baiting | Low–Medium | ⚠️ Suspicious |
| 3 | Urgent: Your Account Will Be Locked | Credential Harvesting | High | 🚨 Phishing |
| 4 | Unauthorized Transaction Detected | Financial Fear Attack | High | 🚨 Phishing |
| 5 | Congratulations! You Have Been Selected | Job Offer Scam | High | 🚨 Phishing |
| 6 | Delivery Attempt Failed | Package/Courier Scam | High | 🚨 Phishing |
| 7 | New Voice Message Received | Malware/Attachment Attack | High | 🚨 Phishing |

---

## 🚨 Key Findings Summary

| Classification | Count |
|---------------|-------|
| ✅ Safe | 1 |
| ⚠️ Suspicious | 1 |
| 🚨 Phishing (High Risk) | 5 |

---

## 🔎 Common Phishing Indicators Identified

### 🔴 High Risk Indicators
- Fake or misspelled sender domains  
- Urgency and fear-based language ("Act now", "24 hours", "Account locked")  
- Suspicious external links that don't match claimed senders  
- Requests for passwords, OTPs, or financial details  
- Unexpected attachments (especially .html, .exe, .zip)  

### 🟠 Medium Risk Indicators
- Generic greetings ("Dear User", "Dear Customer")  
- Vague descriptions of the "issue" without specific details  
- Links that look legitimate but lead to unverified domains  

### 🟡 Low–Medium Indicators
- Mild curiosity triggers without strong urgency  
- Poorly formatted or unusually worded emails  
- Mismatched branding or logos  

---

## 🧠 How Phishing Attacks Work

Phishing attacks succeed by exploiting **human psychology**, not technical vulnerabilities.

Common psychological tactics used:

- **Fear** – "Your account will be suspended"  
- **Urgency** – "Respond within 24 hours"  
- **Greed** – "You've won a prize / job offer"  
- **Curiosity** – "You have a new voice message"  
- **Trust** – Impersonating banks, IT departments, or courier services  

> The goal is always the same: make the user act **fast**, without thinking critically.

---

## 🛡️ Prevention Tips

- Always verify the sender's full email domain, not just the display name  
- Hover over links to preview the real destination before clicking  
- Never enter credentials on pages reached through email links  
- Contact organizations directly through official websites if in doubt  
- Never download unexpected attachments, especially unusual file types  
- Enable Multi-Factor Authentication (MFA) on all accounts  
- Report suspicious emails to your IT / security team immediately  

---

## ✅ Do's and Don'ts for Employees

### ✅ Do's
- Verify sender domains carefully before taking any action  
- Use official websites and apps — not links from emails  
- Report suspicious emails to your security team  
- Keep software and antivirus up to date  
- Attend regular security awareness training  

### ❌ Don'ts
- Don't click links from unexpected or urgent emails  
- Don't download attachments from unknown senders  
- Don't share passwords, OTPs, or bank details via email  
- Don't assume an email is safe because it looks professional  
- Don't rush — attackers want you to act before you think  

---

## 📄 Report

👉 Click below to view the full report:

[Open Phishing Detection & Awareness Report (PDF)](./PhishingDetectionAwarenessReport.pdf)

---

## 📂 Repository Contents

```
📁 Task2-Phishing-Detection/
├── PhishingDetectionAwarenessReport.pdf   ← Full analysis report
├── PhishingDetectionAwarenessReport.pptx  ← Presentation slides
├── sample_emails/
│   ├── email1_safe.txt
│   ├── email2_suspicious.txt
│   ├── email3_account_lock.txt
│   ├── email4_bank_alert.txt
│   ├── email5_job_offer.txt
│   ├── email6_delivery_scam.txt
│   └── email7_voicemail_scam.txt
└── README.md
```

---

## 📚 Reference Datasets (Study Only)

The following public GitHub repositories were used as educational references:

| Repository | Purpose |
|-----------|---------|
| [rf-peixoto/phishing_pot](https://github.com/rf-peixoto/phishing_pot) | Real phishing email samples |
| [autinerd/phishing-mail-examples](https://github.com/autinerd/phishing-mail-examples) | Header + body text samples |
| [sadat1971/Phishing_Email](https://github.com/sadat1971/Phishing_Email) | Labeled phishing dataset |
| [Phishing-Database/Phishing.Database](https://github.com/Phishing-Database/Phishing.Database) | Domain + URL threat dataset |

> ❗ Used for learning and study only — content was not copied or reused.

---

## 💡 Learning Outcome

- Learned how to analyze phishing emails like a real SOC analyst  
- Identified psychological manipulation techniques used by attackers  
- Practiced email risk classification (Safe / Suspicious / Phishing)  
- Understood email header fields: SPF, DKIM, DMARC, Reply-To, Return-Path  
- Developed skills applicable to SOC Analyst, Security Analyst, and GRC roles  

---

## 💼 Why This Task Is High-Value

- Used in real corporate security awareness training  
- Directly applicable to **SOC Analyst**, **Security Analyst**, and **GRC & Awareness** roles  
- Demonstrates ability to communicate technical findings to non-technical users  
- Can be converted into paid phishing awareness audits for businesses  

---

## 🧠 About the Task

Most successful phishing attacks happen not because of weak systems — but because **users don't know how to identify fake emails**.

This task addresses that gap by teaching:
- How phishing emails look and behave  
- How to identify red flags quickly  
- How to protect yourself and your organization  

---

## 📤 Final Deliverables

- Phishing Detection & Awareness Report (PDF)  
- Presentation Slides (PPTX)  
- Sample Email Evidence  
- GitHub Repository with README  

---

## 🌟 About Future Interns

Cyber Security Task 2 (2026)  
By Future Interns  
https://www.linkedin.com/company/future-interns

---

## 👨‍💻 Author

**Deekshith G**

---

## ⚠️ Disclaimer

This project is for **educational purposes only**.  
No malicious links were clicked, no attachments were opened, and no systems were exploited.  
All email samples used are from public educational datasets.
