# FUTURE_CS_02
Cyber Security Internship -Task 2 Phishing Email Detection

## Task 1 - OWASP ZAP Scan

Tool Used: OWASP ZAP 2.17.0  
Target: http://testphp.vulnweb.com  

### Vulnerabilities Found:

- Cross Site Scripting (Reflected) – 19
- SQL Injection
- SQL Injection – MySQL (9)
- Absence of Anti-CSRF Tokens
- Content Security Policy Not Set
- XSLT Injection (2)
- Missing Anti-clickjacking Header

### Risk Level: High

### Business Impact:
These vulnerabilities may allow attackers to steal user data, execute malicious scripts, or compromise the database.

[View Full ZAP Report](ZAP%20by%20Checkmarx%20Scanning%20Report.html)

## Risk Explanation

The presence of SQL Injection and Cross-Site Scripting vulnerabilities indicates critical security weaknesses.
These issues can lead to data theft, session hijacking, and full system compromise.
Immediate remediation is required.

