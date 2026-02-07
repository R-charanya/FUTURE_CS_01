# FUTURE_CS_01
# Web Application Vulnerability Assessment

## Internship Task – Web Security Testing

This repository contains the results of a web application vulnerability assessment conducted as part of my cybersecurity internship task.

## Objective
To perform vulnerability assessment on a publicly available demo web application using industry-standard security tools.

## Target Website
Demo Testfire Application  
http://demo.testfire.net/

## Tools Used
- Nmap (Network Scanning)
- OWASP ZAP (Vulnerability Scanner)
- Browser Developer Tools
- AJAX Spider (Application Crawling)

## Testing Activities
- Network port scanning using Nmap
- Automated vulnerability scanning using OWASP ZAP
- AJAX Spider crawling for dynamic content
- HTTP header inspection using Browser DevTools

## Vulnerabilities Observed
The scan identified the following issues:

- Missing Content Security Policy Header
- Missing Anti-clickjacking Header
- Cookie without HttpOnly flag
- Timestamp Disclosure
- Security header configuration weaknesses

No High-risk vulnerabilities were detected during testing. Issues observed were mainly medium and low risk.

## Repository Contents
- Vulnerability Assessment Report (PDF)
- Nmap scan results
- OWASP ZAP scan screenshots
- Browser DevTools analysis screenshots
- AJAX Spider crawl results

All screenshots are stored inside the **screenshots/** folder.

## Disclaimer
This assessment was conducted only on a publicly available demo application for educational purposes.
