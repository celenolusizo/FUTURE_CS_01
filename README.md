# Web Application Vulnerability Assessment Report
# Author
Nolusizo Cele

# Cyber security task 1 at future interns
This report is for Cyber security project task 1 at future interns, where i did a vulnerability assessment on a live web aapplication, conducted on the intentionally vulnerable testing platform demo.testfire.net.a canva pdf format is available.

# Objectives
- Identify common web vulnerabilities
- Perform network-level scanning
- Classify risks (Low / Medium / High)
- Provide remediation rrecommendation.
  
# Target Website
https://demo.testfire.nnet

# Scope
This task follows strict ethical guidelines.

Allowed
Public-facing pages only, Passive scanning, Header checks and Configuration analysis.

Not Allowed
Login bypass, Exploitation, Brute force attacks, Denial-of-Service (DoS) and Any activity that can harm the website

# Tools Used
- OWASP ZAP (Zed Attack Proxy) – Web vulnerability scanning
- Nmap – Network scanning and port & analysis
- BBrowser DeveloperTools – Traffic iinspection

# Methodology
-Conducted Nmap scan to identify filtered ports 
-Performed Spider Scan using OWASP ZAP to discover ppages
- Executed Aotomated Scan to detect vvulnerabilities
- Analyzed and classified findings based on sseverity

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
