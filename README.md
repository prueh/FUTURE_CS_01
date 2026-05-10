# Vulnerability Assessment & Technical Audit (Task 01)

##  Project Overview
This project was completed as part of the *Future Interns Cybersecurity Internship. The objective was to perform a black-box security audit on the **OWASP Juice Shop* web application to identify common misconfigurations and security gaps.

##  Tools Used
* *Nmap:* Used for network reconnaissance and port scanning.
* *OWASP ZAP:* Utilized as a DAST (Dynamic Application Security Testing) tool for automated vulnerability scanning.
* *Browser DevTools:* Used for manual verification of HTTP response headers and tech-stack fingerprinting.

##  Key Findings
1. *Missing Content-Security-Policy (CSP):* The application lacks a CSP header, increasing the risk of Cross-Site Scripting (XSS) attacks.
2. *Information Disclosure:* Response headers revealed the use of Heroku and Express, providing attackers with infrastructure details.
3. *Missing Anti-Clickjacking Headers:* The absence of X-Frame-Options allows the site to be embedded in malicious iframes.

##  Repository Structure
* FUTURE_CS_01.html: The interactive report presentation.
* nmap.png: Screenshot of the network reconnaissance phase.
* zap_scan.png: Screenshot of the automated DAST scan.
* csp_alert.png: Documentation of the missing CSP vulnerability.
* headers.png: Screenshot showing infrastructure fingerprinting.

##  How to View the Report
1. Download the entire repository as a ZIP file.
2. Extract the folder.
3. Open FUTURE_CS_01.html in any web browser (Chrome or Firefox recommended).

##  Author
*Prudence*
Future Interns Cybersecurity Intern
