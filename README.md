

## Weeks 5 & 6: Ethical Hacking, Security Audits & Secure Deployment

**Intern Name:** Maha

**Project:** Web Application Security Assessment

**Environment:** Kali Linux, OWASP Juice Shop

**Repository:** Cybersecurity-Internship

---

## 🗓️ Week 5: Ethical Hacking & Exploiting Vulnerabilities

### 🎯 Objective

To understand ethical hacking techniques, identify common web vulnerabilities in a controlled environment, and apply proper security fixes according to best practices.

---

### 🛠️ Tools Used

* Kali Linux
* OWASP Juice Shop
* Burp Suite Community Edition
* SQLMap
* Browser Developer Tools

---

### 🔍 Activities Performed

#### 1. Reconnaissance

* Identified application endpoints and services.
* Observed login functionality and API routes.
* Monitored HTTP/HTTPS traffic using Burp Suite Proxy.

#### 2. SQL Injection Testing

* Used SQLMap to test login and input fields.
* Attempted common SQL injection payloads.
* Result: No exploitable SQL injection vulnerabilities were found.

**Mitigation Observed:**

* Prepared statements were implemented.
* User input validation was enforced.

#### 3. CSRF (Cross-Site Request Forgery) Testing

* Intercepted login requests using Burp Suite.
* Removed authentication cookies and replayed requests.
* Requests without valid tokens/cookies were rejected.

**Conclusion:**
CSRF protection was properly implemented, and unauthorized requests failed.

---

### 📌 Week 5 Outcome

* No critical vulnerabilities found.
* Application followed secure authentication and session handling.
* Ethical hacking techniques were successfully practiced in a safe lab.

<img width="1920" height="1079" alt="Screenshot_2025-12-28_02_34_26" src="https://github.com/user-attachments/assets/500d6463-eccd-4ede-9465-6e06a498ee5a" />

<img width="1920" height="1079" alt="Screenshot_2025-12-28_02_51_35" src="https://github.com/user-attachments/assets/6b5afa58-ebb9-4463-ad10-a389cd3c8333" />

<img width="1920" height="1079" alt="Screenshot_2025-12-28_02_57_35" src="https://github.com/user-attachments/assets/7416c05d-c4af-47ef-ab5e-9773723b217b" />

<img width="1920" height="1079" alt="Screenshot_2025-12-28_02_57_46" src="https://github.com/user-attachments/assets/02419160-2daa-44da-90f1-9d7acce3505c" />

<img width="1920" height="1079" alt="Screenshot_2025-12-28_02_59_09" src="https://github.com/user-attachments/assets/bdae59d9-9b93-4412-b9b2-d5a3421b3ec7" />

<img width="1920" height="1079" alt="Screenshot_2025-12-28_03_00_48" src="https://github.com/user-attachments/assets/ec7c6b90-1e30-4a93-a66a-9fd71ad6580b" />

<img width="1920" height="1079" alt="Screenshot_2025-12-28_03_00_58" src="https://github.com/user-attachments/assets/e33f6b7e-bbe5-4be7-be6d-e915f159902a" />

<img width="1920" height="1079" alt="Screenshot_2025-12-28_03_11_28" src="https://github.com/user-attachments/assets/52bba97b-3841-426d-8e6f-58e4f51e6d1b" />

## 🗓️ Week 6: Advanced Security Audits & Secure Deployment

### 🎯 Objective

To conduct comprehensive security audits, verify OWASP Top 10 compliance, and prepare the application for secure deployment.

---

### 🛠️ Tools Used

* OWASP ZAP
* Nikto
* Lynis
* Burp Suite
* Docker Security Best Practices

---

### 🔐 Security Audits Performed

#### 1. OWASP ZAP Scan

* Passive vulnerability scanning.
* Checked for XSS, insecure headers, and misconfigurations.
* No high-risk vulnerabilities detected.

#### 2. Nikto Web Server Scan

* Analyzed server configurations.
* Verified outdated components and headers.
* No critical server misconfigurations found.

#### 3. Lynis Audit

* Conducted system-level security audit.
* Reviewed system hardening and permissions.
* Recommendations were followed for improved security posture.

---

### 🚀 Secure Deployment Practices

* Enabled dependency and security updates.
* Followed Docker image hardening guidelines.
* Reduced attack surface by minimizing exposed services.

---

### 🧪 Final Penetration Testing

* Re-tested critical endpoints using Burp Suite.
* Verified previous findings were fixed or non-exploitable.
* No new vulnerabilities introduced.

---

## 📋 Compliance Check

✔ OWASP Top 10 best practices followed
✔ Secure authentication mechanisms
✔ Input validation and output encoding
✔ Proper session and cookie handling

---

## 🏁 Final Conclusion

This project successfully demonstrated practical ethical hacking, vulnerability assessment, and remediation techniques. The application was tested against common web attacks and was found to be securely implemented according to industry standards. The internship enhanced hands-on cybersecurity skills and understanding of real-world defensive security practices.

---

