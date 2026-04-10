# Operations Automation with Google Apps Script

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
- Chose draft-based generation instead of auto-send to allow human validation  
- Prioritized accuracy over full automation  

---

### 2. Address Validation (validate_address)

**Overview**  
Validates address data before direct mail (DM) sending.

**Problem**  
Incomplete addresses caused delivery failures.

**Solution**  
- Detect missing or invalid components  
- Flag high-risk records  

**Impact**  
- Reduced undeliverable DM by ~50% (estimated)  
- Saved ~1 hour/week in handling returns  

**Trade-offs**  
- Partial validation only  
- Requires manual confirmation for edge cases  

---

### 3. Gift Card Email Generator (gift_card)

**Overview**  
Generates standardized email content for sending gift cards.

**Problem**  
Manual composition caused inconsistency.

**Solution**  
- Template-based generation  

**Impact**  
- Reduced processing time  
- Improved consistency  

**Trade-offs**  
- Less flexibility for edge cases  

---

## 🧠 Design Principles

- Translate ambiguous tasks into structured workflows  
- Prioritize scalability and repeatability  
- Balance strict rules with exception handling  
- Design for non-technical users  

---

## 🛠 Tech Stack

- Google Apps Script (JavaScript)  
- Google Sheets
