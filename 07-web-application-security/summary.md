# Section 7: Web Application Security (OWASP Top 10)

## 🧭 Overview

This module introduces you to the **OWASP Top 10**, a widely accepted standard for the most critical web application security risks. Each category highlights real-world vulnerabilities that can be exploited by attackers to compromise web applications. You will learn how these issues arise, how to test for them, and how to remediate them.

## 📌 Key Concepts (OWASP Top 10)

| Risk                      | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| A01: Broken Access Control| Users can access data or functions they shouldn't                         |
| A02: Cryptographic Failures| Sensitive data exposed due to poor encryption practices                    |
| A03: Injection            | Code (SQL, Command) injected into application inputs                       |
| A04: Insecure Design      | Weak architecture lacking security controls                               |
| A05: Security Misconfig   | Default settings or misconfigured apps leak sensitive data                 |
| A06: Vulnerable Components| Using outdated libraries or frameworks                                     |
| A07: Identification Failures| Weak login or session management mechanisms                              |
| A08: Software Integrity Issues| Unverified code or supply chain attacks                                |
| A09: Logging & Monitoring Failures| No visibility into security events                                 |
| A10: SSRF (Server-Side Request Forgery)| Servers fetch unauthorized URLs or internal resources         |

---

## 🧪 Hands-On Lab Examples

### 🔐 SQL Injection (A03)

```sql
# Sample vulnerable login query
SELECT * FROM users WHERE username = '$user' AND password = '$pass';

# Injection example
' OR 1=1 --
```

### Screenshot
<img width="1758" height="1105" alt="image" src="https://github.com/user-attachments/assets/369cc49a-ff2c-48ff-bfb8-c9801d0873bf" />
