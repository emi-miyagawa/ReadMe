# Operations Automation (Google Apps Script)

This repository contains Google Apps Script (GAS) tools designed to reduce operational friction, standardize workflows, and improve execution efficiency in back-office and business operations.

---

## 🔧 Key Projects

### 1. Email Automation (auto_email)

**Overview**  
Automatically generates email drafts from spreadsheet data.

**Problem**  
Manual email creation required repetitive copy-paste and caused inconsistencies.

**Solution**  
- Structured spreadsheet input
- Automated draft generation via GAS

**Impact**  
- Reduced email creation time from ~2–3 min/email to <30 sec  
- Enabled batch processing (30–50 emails/session)  
- Reduced formatting inconsistencies

**Trade-offs**  
- Chose draft-based generation instead of auto-send to allow human validation and customization  
- Prioritized accuracy and flexibility over full automation
---

### 2. Address Validation (validate_address)

**Overview**  
Validates address data before direct mail (DM) sending.

**Problem**  
Incomplete addresses caused delivery failures and operational waste.

**Solution**  
- Detect missing or invalid address components  
- Flag high-risk records before sending

**Impact**  
- Reduced undeliverable mail  
- Prevented unnecessary logistics cost  
- Improved data quality

---

### 3. Gift Card Email Generator (gift-card-url)

**Overview**  
Generates email content for sending Amazon gift cards.

**Problem**  
Manual composition led to inefficiencies and formatting inconsistencies.

**Solution**  
- Template-based email generation  
- Standardized output format

**Impact**  
- Reduced human error  
- Improved processing speed  
- Ensured consistent messaging

---

## 🧠 Design Principles

- Translate ambiguous tasks into structured workflows  
- Prioritize scalability and repeatability over manual effort  
- Balance strict rules with exception handling  
- Design for non-technical users

---

## 🛠 Tech Stack

- Google Apps Script (JavaScript)
- Google Sheets

---
