About
This repository contains Vulnerability Assessment and Penetration Testing (VAPT) reports from my independent security research. Each report covers a different target application found during bug bounty research or authorised testing. All reports are documented following professional penetration testing standards — including CVSS scoring, CWE mapping, and remediation guidance.

Reports

ReportTarget TypeSeverityVulnerabilityRCE via Leaked Credentials & xp_cmdshellCorporate Web Application🔴 CriticalPlain-text DB credentials in a public archive leading to full Remote Code Execution via xp_cmdshell

phpinfo()Page ExposureUniversity Portal🟠 MediumUnauthenticated phpinfo() page disclosing PHP 7.4.33 (EOL), OS version, kernel build, and internal pathsWordPress User Enumeration

WordPress Website🟠 MediumREST API endpoint /wp-json/wp/v2/users exposing all registered usernames without any authentication

Missing Permissions-Policy HeaderGovernment Web Portal🔵 LowMissing Permissions-Policy header allowing browser feature abuse when chained with XSS

Each report targets a separate, independent application. All domain names, IP addresses, usernames, and credentials are fully redacted in all published versions.


Responsible Disclosure

All vulnerabilities were identified through ethical security research
Affected organisations were notified before any public disclosure
No user data was accessed, stored, or misused at any point
Reports are shared here strictly for educational and portfolio purposes


Contact
Blog: medium.com/@dhivagar
LinkedIn: linkedin.com/in/dhivagar
