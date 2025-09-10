# Web Application Penetration Testing Report – SURE ProED

This repository contains the **Web Application Penetration Testing (VAPT) Report** created as part of an internship project at **SURE ProED – Innovation & Entrepreneurship Hub for Educated Rural Youth (IERY)**.  
The project focused on identifying security vulnerabilities in three web applications and providing actionable recommendations for mitigation.

---

## 📑 Project Overview

- **Domain:** Cybersecurity  
- **Objective:** To perform a Web Application Security Assessment and document vulnerabilities, risks, and remediation steps.  
- **Mentor:** Mr. Nishchay Gaba (OSCP Certified Penetration Tester)  
- **Period:** February 2025 – August 2025  
- **Intern:** Meghashyam Ravuru  

---

## 🛡️ Scope of Testing

- **Applications Tested:**  
  - DVWA (Damn Vulnerable Web Application)  
  - bWAPP (Buggy Web Application)  
  - Acunetix Test PHP Site  

- **Methodology:**  
  - Reconnaissance  
  - Vulnerability Scanning  
  - Manual Validation  
  - Risk Assessment (No exploitation beyond approved scope)

---

## 🔎 Summary of Findings

| Severity | Count |
|---------|-------|
| **Critical** | 12 |
| **High** | 7 |
| **Medium** | 5 |
| **Low** | 1 |
| **Total** | 25 |

Vulnerabilities include (but are not limited to):  
- Remote File Inclusion (RFI)  
- SQL Injection & Authentication Bypass  
- OS Command Injection  
- Cross-Site Scripting (XSS)  
- CSRF, IDOR, CORS Misconfigurations  
- Session Hijacking & Improper Session Management  
- Use of End-of-Life (EOL) Software  

---

## 🛠️ Recommendations

The report includes remediation steps such as:  
- Input validation & sanitization  
- Secure session management practices  
- Rate-limiting and brute-force protection  
- Using HTTPS (TLS) for all endpoints  
- Upgrading EOL software & hardening server configuration  

---

## 📜 Legal Disclaimer

This report is for **educational and internal use only**.  
It contains sensitive findings and must not be used for malicious purposes.  
The author and SURE ProED are not liable for misuse of this information.

---

## 📧 Contact

For queries or collaboration:

**Meghashyam Ravuru**  
📍 Andhra Pradesh    
🔗 https://linkedin.com/in/meghashyam-ravuru

---
