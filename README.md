Web Application Security Testing using DVWA
📌 Project Overview

This project focuses on identifying, exploiting, and understanding common web application vulnerabilities using Damn Vulnerable Web Application (DVWA) in a controlled environment.

The goal is to gain hands-on experience in ethical hacking, understand real-world attack techniques, and learn secure coding practices to defend against them.

🎯 Objectives

Understand OWASP Top 10 vulnerabilities

Perform real-world web application security testing

Learn how attackers exploit vulnerabilities

Implement mitigation strategies

Gain experience using professional security tools

🧪 Lab Environment
Component	Description
OS	Kali Linux
Web Server	Apache
Database	MariaDB
Backend	PHP
Application	DVWA (Damn Vulnerable Web Application)
Tools Used	Burp Suite, Browser DevTools
🛠️ Vulnerabilities Covered
✅ 1. SQL Injection (SQLi)

Extracted database information

Authentication bypass

Demonstrated query manipulation

Mitigation using prepared statements

✅ 2. Blind SQL Injection

Identified data through true/false responses

Demonstrated logic-based inference

Highlighted risks of hidden vulnerabilities

✅ 3. Cross-Site Scripting (XSS)

Stored XSS

Reflected XSS

Demonstrated script execution and cookie access

✅ 4. Cross-Site Request Forgery (CSRF)

Forced password change using forged requests

Demonstrated lack of CSRF token protection

✅ 5. File Inclusion (LFI / RFI)

Tested local file inclusion vulnerabilities

Explained why RFI is disabled in modern PHP versions

Demonstrated secure file handling practices

✅ 6. Burp Suite – Intercept & Modify Requests

Intercepted HTTP requests

Modified parameters in real time

Analyzed request–response behavior

🧠 Learning Outcomes

Practical understanding of OWASP Top 10 vulnerabilities

Ability to identify insecure coding practices

Experience using Burp Suite for web testing

Knowledge of secure application development

Awareness of ethical hacking principles

🔐 Security Mitigation Techniques

Input validation and sanitization

Prepared statements (Parameterized queries)

Content Security Policy (CSP)

CSRF tokens

Secure session handling

Principle of least privilege
