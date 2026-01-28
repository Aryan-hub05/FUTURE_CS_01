# Vulnerability Assessment Report – Task 1

This repository contains a Vulnerability Assessment Report prepared as part of the **Future Interns Cyber Security Internship**.

The objective of this task is to identify common security vulnerabilities in a live web application, classify their risk levels, and provide clear remediation steps in a business-friendly manner.

---

## 🔍 Target Website
https://testphp.vulnweb.com  
*(Legal and intentionally vulnerable testing website)*

---

## 🛠 Tools Used
- Nmap
- OWASP ZAP (Passive Scan)
- Browser Developer Tools
- Canva (Report Design)

---

## 🚨 Vulnerabilities Identified

### 1. Open Network Ports
- **Risk Level:** Low  
- **Impact:** Allows attackers to identify running services  
- **Fix:** Close unused ports and configure firewall rules

---

### 2. Missing Security Headers
- X-Frame-Options  
- Content-Security-Policy  
- **Risk Level:** Medium  
- **Impact:** Clickjacking and script injection  
- **Fix:** Configure proper HTTP security headers

---

### 3. Insecure Cookies
- Missing Secure & HttpOnly flags  
- **Risk Level:** Medium  
- **Impact:** Session hijacking  
- **Fix:** Enable Secure and HttpOnly attributes

---

### 4. Input Validation Issues
- Unsanitized input fields  
- **Risk Level:** Medium  
- **Impact:** XSS and SQL Injection attacks  
- **Fix:** Validate user input and use prepared statements

---

## 📊 Risk Summary

| Vulnerability | Risk |
|--------------|------|
| Open Ports | Low |
| Missing Headers | Medium |
| Insecure Cookies | Medium |
| Input Validation | Medium |

---

## 🔐 Recommendations
- Implement HTTP security headers
- Secure cookies properly
- Validate all user inputs
- Perform regular vulnerability assessments

---

## 📚 Key Learnings
- Web vulnerability identification
- Risk classification
- Security documentation
- Ethical security testing

---

## ⚠ Disclaimer
All testing was conducted on a legal, intentionally vulnerable website for educational purposes only. No unauthorized systems were tested.

---

## ✅ Internship Task Status
✔ Task Completed  
✔ Eligible for Certificate  
✔ GitHub Verified
