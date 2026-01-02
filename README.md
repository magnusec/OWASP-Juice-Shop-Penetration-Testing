

# 🛡️ Penetration-Testing-on-OWASP-Juice-Shop

This repository contains a comprehensive **web application security assessment and threat mapping report** for **OWASP Juice Shop**.

OWASP Juice Shop is a modern, intentionally vulnerable web application designed to demonstrate real-world security flaws commonly found in contemporary web applications. This project simulates **practical attack scenarios** aligned with the **OWASP Top 10** and focuses on identifying, exploiting, and analyzing security weaknesses in a realistic, API-driven application environment.

---

## 🕵️‍♂️ Identified Vulnerabilities

### 🧃 OWASP Juice Shop Vulnerabilities

| # | Vulnerability | Affected URL | Severity | Description |
|---|--------------|--------------|----------|-------------|
| 1 | Broken Access Control | /administration | High | Allows unauthorized users to access restricted or administrative functionalities. |
| 2 | Broken Authentication | /login | High | Enables brute-force and credential-stuffing attacks due to weak authentication controls. |
| 3 | Sensitive Data Exposure | /ftp | High | Exposes sensitive files, credentials, or confidential data without proper access protection. |
| 4 | CAPTCHA Bypass | /contact | Medium | CAPTCHA protection can be bypassed due to weak or missing backend validation. |
| 5 | Security Misconfiguration | /rest/products/ | Medium | Verbose error messages and exposed headers leak internal configuration and framework details. |

---

## 📘 What’s Inside the Report?

The detailed **OWASP Juice Shop security assessment report** included in this repository covers:

- ✅ Introduction & Executive Summary  
- ✅ Testing Tools and Methodology  
- ✅ Technical Explanation of Each Vulnerability  
- ✅ Proof of Concept (PoC) and Exploitation Flow  
- ✅ Real-World Attacker Scenarios  
- ✅ Risk Analysis & Impact Assessment  
- ✅ Mitigation Strategies and Security Recommendations  
- ✅ Conclusion and Strategic Security Insights  

---

## 🎯 Purpose of This Project

This project is intended for:
- Cybersecurity students and learners  
- Penetration testing and VAPT practice  
- Understanding modern OWASP Top 10 vulnerabilities  
- Academic submissions and security portfolios  

All testing was conducted in a **controlled lab environment** using intentionally vulnerable software.

---

⚠️ **Disclaimer:**  
This repository is strictly for educational and learning purposes. The techniques demonstrated should only be applied to systems you own or have explicit authorization to test.
