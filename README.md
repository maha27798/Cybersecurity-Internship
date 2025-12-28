

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

---

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

