# 🔐 Task 6 – Web Application Security Audit

## 📌 Overview
This repository contains **Task 6**, which focuses on performing a **basic web application security audit** on a **legal test website**.  
The task aims to identify common vulnerabilities, analyze security risks, and provide practical recommendations using standard cybersecurity tools.

⚠️ **Important:**  
All testing was performed on **authorized and intentionally vulnerable test applications only**.  
No real or production websites were tested.

---

## 🎯 Objective
- Conduct a security audit of a test web application  
- Identify vulnerabilities and security risks  
- Analyze possible exploitation points  
- Provide security recommendations  
- Gain hands-on experience with web security tools  

---

## 🧪 Target Application
- **URL:** http://testphp.vulnweb.com  
- **Type:** Intentionally vulnerable test web application  
- **Purpose:** Educational and security testing  

---

## 🛠️ Tools Used
- **OWASP ZAP** – Automated and passive vulnerability scanning  
- **Kali Linux** – Testing environment  
- **Manual Testing** – Basic input validation checks  

---

## 🔍 Methodology
1. Selected a legal test web application  
2. Performed information gathering to identify pages and inputs  
3. Conducted automated scanning using OWASP ZAP  
4. Analyzed detected vulnerabilities  
5. Performed safe manual testing  
6. Collected evidence (screenshots)  
7. Documented vulnerabilities and recommendations  

---

## 🚨 Vulnerabilities Identified
- Server information disclosure via HTTP headers  
- Missing security headers (CSP, X-Frame-Options, etc.)  
- Insecure input validation  
- Outdated server technology disclosure  

> **Note:**  
These vulnerabilities are intentionally present for learning purposes.

---

## 🛡️ Security Recommendations
- Disable information disclosure headers (e.g., `X-Powered-By`)  
- Implement proper input validation and sanitization  
- Use HTTPS to secure data transmission  
- Configure essential security headers  
- Regularly update server and application components  

---

## 📸 Evidence
This repository includes:
- OWASP ZAP scan screenshots  
- Vulnerability alerts and evidence  
- Scan progress and results  

---

## 🧠 What I Learned
From this task, I learned how to perform a basic web application security audit using OWASP ZAP. I gained practical experience in identifying vulnerabilities, analyzing risks, and documenting findings professionally. This task improved my understanding of real-world web security assessment workflows.

---

## ⚖️ Disclaimer
This project was conducted strictly for **educational purposes**.  
All testing was performed on **authorized and intentionally vulnerable test environments only**.

---

## 👤 Author
**Sayed Sardar Ali Shah**  
Software Engineering Student | Cybersecurity Enthusiast
