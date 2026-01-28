# Task 1 – Vulnerability Assessment Report

This repository contains Task 1 submission for the **Future Interns Cyber Security Internship**.

The objective of this task is to perform a basic vulnerability assessment on a legal testing website and document the findings in a professional manner.

---

## 🌐 Target Website
https://testphp.vulnweb.com  
(This is a legal and intentionally vulnerable testing website.)

---

## 🛠 Tools Used
- Nmap
- OWASP ZAP (Passive Scan)
- Browser Developer Tools
- Canva (for report design)

---

## 🔍 Vulnerabilities Identified

### 1. Open Network Ports
- **Risk Level:** Low  
- **Description:** Open ports allow attackers to identify running services.
- **Recommendation:** Close unused ports and configure firewall rules.

---

### 2. Missing Security Headers
- X-Frame-Options
- Content-Security-Policy
- **Risk Level:** Medium  
- **Impact:** Clickjacking and script injection attacks.
- **Recommendation:** Configure proper HTTP security headers.

---

### 3. Insecure Cookies
- Secure and HttpOnly flags missing.
- **Risk Level:** Medium  
- **Impact:** Session hijacking.
- **Recommendation:** Enable Secure and HttpOnly flags.

---

### 4. Input Validation Issues
- Unsanitized user inputs.
- **Risk Level:** Medium  
- **Impact:** XSS and SQL Injection.
- **Recommendation:** Validate and sanitize all inputs.

---

## 📊 Risk Summary

| Vulnerability | Risk |
|--------------|------|
| Open Ports | Low |
| Missing Headers | Medium |
| Insecure Cookies | Medium |
| Input Validation | Medium |

---

## 📚 Key Learnings
- Vulnerability identification
- Risk classification
- Security documentation
- Ethical testing practices

---

## ⚠ Disclaimer
All testing was conducted only on a legal testing website for educational purposes.

---

## ✅ Task Status
✔ Completed  
✔ GitHub Documented  
✔ Internship Ready
