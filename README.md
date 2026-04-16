# Vulnerability Assessment Report
# Cyber security task 1 at future interns
This report is for Cyber security project task 1 at future interns, where i did a vulnerability assessment on a live web application.
# Objectives
- Identify common web vulnerabilities
- Perform network-level scanning
- Classify risks (Low / Medium / High)
- Provide remediation recommendations
# Target Website
https://demo.testfire.net/
# Tools Used
- OWASP ZAP (Zed Attack Proxy) – Web vulnerability scanning
- Nmap – Network scanning and port & analysis
- Browser Developer Tools – Traffic inspection
# Methodology
Conducted Nmap scan to identify filtered ports
Performed Spider Scan using OWASP ZAP to discover pages
Executed Aotomated Scan to detect vulnerabilities
Analyzed and classified findings based on severity
# Results/Findings
- Missing Security Headers (X-Frame-Options, CSP)
- Cookie Security Issues (Missing Secure Flag)
- Server Information Disclosure
- Cross-Domain Script Inclusion
  # Conclusion/Recommendations
- Avoiding server information exposure
- Perform regular security testing
- Implementation of proper security headers
- emphasis on using HTTPS and secure cookies
- Following the guidelines of OWASP Top 10.
