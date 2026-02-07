FUTURE_CS_01
WEB APPLICATION VULNERABILITY ASSESSMENT
TASK OVERVIEW

This repository contains a vulnerability assessment report conducted on a publicly accessible demo website as part of a cybersecurity internship task. The assessment was performed using ethical and non-intrusive security testing techniques.

TARGET WEBSITE

URL: http://testphp.vulnweb.com

TYPE: Public demo website

AUTHENTICATION: Not required

TOOLS USED

OWASP ZAP (Passive Scan)

Browser Developer Tools

Nmap (Service Version Scan)

FINDINGS SUMMARY

LOW-RISK security issues

MEDIUM-RISK security issues

NO HIGH-RISK vulnerabilities identified

REPORT

Web_Application_Vulnerability_Assessment_Report.pdf

SCREENSHOTS

All supporting screenshots related to OWASP ZAP findings, Browser Developer Tools verification, and Nmap scan results are available in the screenshots/ folder.

RECOMMENDATIONS

Implement essential HTTP security headers such as Content-Security-Policy and X-Frame-Options.

Secure cookies using HttpOnly and Secure attributes.

Avoid exposing unnecessary server or application information.

Perform periodic security scans using standard security tools.

DISCLAIMER

This assessment was conducted strictly for educational purposes on a publicly available demo website. No exploitation or malicious activity was performed.
