

#  Penetration-Testing-on-OWASP-Juice-Shop

This repository contains a comprehensive **web application security assessment and threat mapping report** for **OWASP Juice Shop**.

OWASP Juice Shop is a modern, intentionally vulnerable web application designed to demonstrate real-world security flaws commonly found in contemporary web applications. This project simulates **practical attack scenarios** aligned with the **OWASP Top 10** and focuses on identifying, exploiting, and analyzing security weaknesses in a realistic, API-driven application environment.

---

## Vulnerabilities


| # | Vulnerability | Severity | Impact (Short) | Mitigation (Short) |
|---|--------------|----------|----------------|-------------------|
| 1 | Broken Access Control | High | Allows unauthorized users to access restricted or administrative functionalities, leading to privilege escalation. | Enforce server-side authorization checks and implement proper role-based access control (RBAC). |
| 2 | Broken Authentication | High | Enables brute-force and credential-stuffing attacks, resulting in unauthorized account access. | Apply rate limiting, account lockout mechanisms, and multi-factor authentication (MFA). |
| 3 | Sensitive Data Exposure | High | Exposes confidential user or system data, leading to data breaches and compliance violations. | Encrypt sensitive data, restrict access to APIs/files, and avoid storing data in plain text. |
| 4 | CAPTCHA Bypass | Medium | Allows automated abuse such as spam submissions or brute-force attempts at scale. | Implement server-side CAPTCHA validation and add rate limiting. |
| 5 | Security Misconfiguration | Medium | Leaks internal application details that assist attackers in reconnaissance and attack planning. | Disable debug modes, hide error details, and properly configure security headers. |

---

##  What’s Inside the Report?

The detailed **OWASP Juice Shop security assessment report** included in this repository covers:

- Introduction & Executive Summary  
- Testing Tools and Methodology  
- Technical Explanation of Each Vulnerability  
- Proof of Concept (PoC)    
- Risk Analysis & Impact
- Mitigation Strategies and Recommendations
- Real-World Scenarios  
- Conclusion 
---

## 🎯 Purpose of This Project

This project is intended for:
- Cybersecurity students
- Understanding modern OWASP Top 10 vulnerabilities
- Penetration testing and VAPT practice    
- Academic references and security portfolios  

All testing was conducted in a **controlled lab environment** using intentionally vulnerable software.

---

⚠️ **Disclaimer:**  
This repository is strictly for educational and learning purposes. The techniques demonstrated should only be applied to systems you own or have explicit authorization to test.
