# Task 7 – Web Application Vulnerability Testing

## Overview
This task focuses on performing basic web application vulnerability testing
using an intentionally vulnerable application. The objective is to understand
how common vulnerabilities can be identified using interception and analysis
tools.

## Tools Used
- Burp Suite Community Edition
- Google Chrome
- FoxyProxy Extension
- OWASP Juice Shop (Vulnerable Web Application)

## Target Application
- OWASP Juice Shop  
- URL: https://juice-shop.herokuapp.com/

## Vulnerabilities Tested
- SQL Injection (SQLi)
- Cross-Site Scripting (XSS)

## Methodology
1. Configured Burp Suite as an intercepting proxy.
2. Routed browser traffic through Burp using FoxyProxy.
3. Intercepted and analyzed HTTP requests.
4. Tested login functionality for SQL Injection.
5. Tested search functionality for Cross-Site Scripting (XSS).
6. Observed application responses and request data.
7. Documented findings with screenshots and analysis.

## Files Included
- `analysis.txt` – Observations during vulnerability testing
- `report.md` – Detailed vulnerability assessment report
- `screenshots/` – Proof of testing and intercepted requests

## Outcome
This task provided hands-on experience with web application security testing,
request interception, and understanding common OWASP Top 10 vulnerabilities.
