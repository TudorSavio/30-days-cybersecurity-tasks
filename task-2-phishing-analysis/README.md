# 📧 Task 2: Phishing Email Analysis

## 🎯 Objective
To identify and analyze phishing characteristics from a sample email and understand how attackers manipulate users.

---

## 🛠 Tools Used
- Sample phishing email (from online or inbox)
- Online Email Header Analyzer (e.g., https://mxtoolbox.com/EmailHeaders.aspx)
- Web browser to inspect suspicious links

---

## 🔍 Analysis Performed

### ✅ 1. Sender’s Email Spoofing
- The sender’s address appeared as `support@paypal.com`, but hovering revealed `paypa1-service@fake-domain.xyz`.

### ✅ 2. Email Header Issues
- Return-path did not match `From` field.
- SPF and DKIM authentication failed in header.

### ✅ 3. Suspicious Links
- Text: `Update your account`
- Hover link: `http://fakeurl.ru/verify`

### ✅ 4. Urgent Language
- Subject: “🚨 Account Locked: Action Required Immediately!”
- Body had threats like: “Your account will be permanently suspended.”

### ✅ 5. Spelling & Grammar
- Multiple grammar issues like “we noticed suspicious activitty in yore acount”

---

## 📸 Screenshots (if available)
- `screenshot-email.png`
- `header-analysis.png`

---

## ❓ Interview Questions & Answers

**1. What is phishing?**  
Phishing is a cyberattack that uses disguised emails or messages to trick users into revealing sensitive information.

**2. How to identify a phishing email?**  
Check sender address, mismatched links, bad grammar, urgency, and fake attachments.

**3. What is email spoofing?**  
It’s when attackers forge the "From" address to look like it came from a trusted source.

**4. Why are phishing emails dangerous?**  
They lead to credential theft, malware infections, or identity fraud.

**5. How can you verify the sender’s authenticity?**  
Check email headers, SPF/DKIM status, domain reputation, and contact the service provider directly.

**6. What tools can analyze email headers?**  
- MXToolbox
- Google Admin Toolbox
- mailheader.org

**7. What actions should be taken on suspected phishing emails?**  
Do not click anything, report to IT or service provider, and delete the email.

**8. How do attackers use social engineering in phishing?**  
They exploit trust, urgency, or fear to manipulate victims into acting against their best interests.

---

## 📂 Files to Include in GitHub

