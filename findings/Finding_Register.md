# Security Findings Register

## Project
Website OWASP Top 10:2025 Security Assessment

## Target
Local DVWA Application

| ID | Finding | Evidence ID | Test Result | Initial Severity | Status |
|---|---|---|---|---|---|
| F-01 | SQL Injection | E-01 | SQL query output observed | Pending Validation | Evidence Review |
| F-02 | Command Injection | E-02 | Command execution output observed | Pending Validation | Evidence Review |
| F-03 | Local File Inclusion | E-03 | File inclusion test captured | Pending Validation | Evidence Review |
| F-04 | File Upload | E-04 | Upload success message observed | Pending Validation | Observation |
| F-05 | Reflected XSS | E-05 | Input page captured | Pending Validation | Evidence Review |
| F-06 | Stored XSS | E-06 | JavaScript alert observed | Pending Validation | Evidence Review |
| F-07 | DOM XSS | E-07 | JavaScript alert observed | Pending Validation | Evidence Review |
| F-08 | Weak Session IDs | E-08 | Session cookie information captured | Pending Validation | Evidence Review |
| F-09 | CSRF | E-09 | Password change success message observed | Pending Validation | Evidence Review |
| F-10 | Brute Force | E-10 | Failed and successful login responses captured | Pending Validation | Evidence Review |
| F-11 | Insecure CAPTCHA | E-11 | Testing blocked by missing API configuration | N/A | Not Verified |## Important Notes

- Severity classifications are preliminary.
- Findings must be supported by screenshots and testing logs.
- Tested does not automatically mean vulnerable.
- File Upload and XSS results require evidence review.
- CAPTCHA could not be fully assessed because of missing API configuration.

## Assessment Status
In Progress
