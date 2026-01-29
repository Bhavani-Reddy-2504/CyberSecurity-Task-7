# Vulnerability Assessment Report  
**Task 7 – Web Application Vulnerability Testing**

---

## Target Application
- Application Name: OWASP Juice Shop
- Type: Intentionally Vulnerable Web Application
- Purpose: Security Testing Practice

---

## Tool Used
- Burp Suite Community Edition

---

## Vulnerability 1: SQL Injection (SQLi)

### Description
SQL Injection occurs when user input is not properly validated or sanitized
before being processed by the backend database. Attackers can manipulate SQL
queries by injecting malicious input.

### Testing Performed
- Targeted the login functionality.
- Entered a SQL injection payload in the email field.
- Intercepted the login request using Burp Suite.

### Payload Used
```sql
' OR 1=1--
