FUTURE_CS_01
Web Application Vulnerability Assessment
Task Overview

This repository contains a vulnerability assessment report conducted on a publicly accessible demo website as part of a cybersecurity internship task. The assessment was performed using ethical and non-intrusive security testing techniques.

Target Website

URL: http://testphp.vulnweb.com

Type: Public demo website

Authentication: Not required

Tools Used

OWASP ZAP (Passive Scan)

Browser Developer Tools

Nmap (Service Version Scan)

Findings Summary

Low-risk security issues

Medium-risk security issues

No high-risk vulnerabilities were identified

Report

Web_Application_Vulnerability_Assessment_Report.pdf

Screenshots

All supporting screenshots related to OWASP ZAP findings, Browser Developer Tools verification, and Nmap scan results are available in the screenshots/ folder.

Recommendations

Implement essential HTTP security headers such as Content-Security-Policy and X-Frame-Options.

Secure cookies using HttpOnly and Secure attributes.

Avoid exposing unnecessary server or application information.

Perform periodic security scans using standard security tools.

Disclaimer

This assessment was conducted strictly for educational purposes on a publicly available demo website. No exploitation or malicious activity was performed.
