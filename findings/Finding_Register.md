# Security Findings Register

## Project
Website OWASP Top 10:2025 Security Assessment

## Target
Local DVWA Application

| ID | Finding | Test Result | Initial Severity | Status |
|---|---|---|---|---|
| F-01 | SQL Injection | Confirmed | High | Identified |
| F-02 | Command Injection | Confirmed | High | Identified |
| F-03 | Local File Inclusion | Confirmed | High | Identified |
| F-04 | File Upload | Upload Accepted | To Be Reviewed | Observation |
| F-05 | Reflected XSS | Tested | To Be Reviewed | Evidence Review |
| F-06 | Stored XSS | Tested | To Be Reviewed | Evidence Review |
| F-07 | DOM XSS | Tested | To Be Reviewed | Evidence Review |
| F-08 | Weak Session IDs | Predictable Pattern Observed | Medium | Identified |
| F-09 | CSRF | Password Change Tested | To Be Reviewed | Evidence Review |
| F-10 | Brute Force | Failed and Successful Attempts | Medium | Identified |
| F-11 | Insecure CAPTCHA | Testing Blocked by Missing API Key | N/A | Not Verified |

## Important Notes

- Severity classifications are preliminary.
- Findings must be supported by screenshots and testing logs.
- Tested does not automatically mean vulnerable.
- File Upload and XSS results require evidence review.
- CAPTCHA could not be fully assessed because of missing API configuration.

## Assessment Status
In Progress
