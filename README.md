# DVWA OWASP ZAP Vulnerability Assessment

## Overview
Hands-on scan of Damn Vulnerable Web App (DVWA) at 172.17.0.2 using OWASP ZAP on Kali Linux.

## Setup
1. Launch ZAP: Applications > Web > OWASP ZAP.
2. Proxy browser to localhost:8080, import ZAP CA.
3. Access DVWA, login admin/password, browse modules.
4. Automated Scan on http://172.17.0.2/dvwa/.

## Findings
- SQL Injection (High)
- XSS (High)
- CSRF (Medium)

## Next Steps
Manual verification and remediation testing.
