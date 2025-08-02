# VAPT-Project
Cyber Security VAPT project on DVWA using Burp Suite, XAMPP, and Firefox – IBM PBEL submission.

# VAPT-Project-DVWA
Cyber Security VAPT project on DVWA using Burp Suite, XAMPP, and Firefox – IBM PBEL submission.
# 🔐 VAPT Project – Damn Vulnerable Web Application (DVWA)

This repository contains the final submission for my **Vulnerability Assessment and Penetration Testing (VAPT)** project conducted as part of the **IBM–NASSCOM Project-Based Experiential Learning (PBEL)** Cyber Security Program.

---

## 📄 Project Overview

This project involved conducting a structured vulnerability assessment and penetration test on **DVWA (Damn Vulnerable Web Application)** — a deliberately insecure web application for testing common web vulnerabilities.

The objective was to: 
- Identify security flaws
- Exploit them ethically
- Document the technical process
- Recommend proper mitigations

The final report includes **screenshots**, **burp suite analysis**, **OWASP mappings**, and **step-by-step documentation** for each vulnerability.

---

## ✅ Deliverables

- 📘 `Arush_VAPT_Report.pdf` – Final project report with embedded screenshots and documentation
- 🧪 `csrf-poc.html` – CSRF Proof-of-Concept file generated using Burp Suite Professional
- 📄 `README.md` – Project summary and repository documentation 


---

## 🧪 Vulnerabilities Covered

| Sr. No | Vulnerability Title                                       | Severity | OWASP ID |
|--------|------------------------------------------------------------|----------|----------|
| 1      | SQL Injection                                              | Critical | A03      |
| 2      | Blind SQL Injection                                        | Critical | A03      |
| 3      | Command Injection                                          | Critical | A03      |
| 4      | Stored Cross-Site Scripting (XSS)                          | Critical | A03      |
| 5      | Reflected Cross-Site Scripting (XSS)                       | Critical | A03      |
| 6      | DOM-Based Cross-Site Scripting (XSS)                       | High     | A03      |
| 7      | CSP Bypass (Security Misconfiguration)                     | High     | A05      |
| 8      | File Inclusion (LFI)                                       | High     | A05      |
| 9      | File Upload (Unrestricted File Types)                      | Critical | A05      |
| 10     | Brute Force Login (Broken Access Control)                  | High     | A01      |
| 11     | Insecure Session IDs (Session Management)                  | High     | A07      |
| 12     | Missing HTTP Security Headers                              | Medium   | A05      |
| 13     | Cross-Site Request Forgery (CSRF)                          | High     | A01      |

---

## 🛠️ Tools & Technologies Used

- 💻 **DVWA** – Vulnerable test environment
- 🐘 **XAMPP** – Localhost web server for hosting DVWA
- 🔐 **Burp Suite Professional** – For intercepting and manipulating HTTP traffic
- 🌐 **Firefox with FoxyProxy** – For proxying traffic via Burp
- 🧪 **OWASP Testing Guidelines** – For referencing remediation strategies
- 💻 **Windows OS**

---

## 👨‍🏫 Program Info

- **Track:** Cyber Security  
- **Program:** IBM–NASSCOM Project-Based Experiential Learning (PBEL)  
- **Mentor:** Hrushikesh Dinkar  
- **Duration:** 60 hours (Instructor-led + Hands-on project)  
- **Mode:** Virtual Internship (Equivalent)

---

## 📌 Submission

This repository was created for final submission to the **IBM PBEL Portal**.  
It contains all required documentation, screenshots, PoC, and report.

---

## 📚 References

- [DVWA GitHub](https://github.com/digininja/DVWA)
- [Burp Suite Docs – PortSwigger](https://portswigger.net/burp)
- [OWASP Top 10 – 2021](https://owasp.org/www-project-top-ten/)
- [CSRF Attack Guide – OWASP](https://owasp.org/www-community/attacks/csrf)
- [Common File Upload Vulnerabilities](https://owasp.org/www-community/vulnerabilities/Unrestricted_File_Upload)
- [Cross-Site Scripting (XSS) Guide](https://owasp.org/www-community/attacks/xss/)
