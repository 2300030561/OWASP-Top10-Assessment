# Website OWASP Top 10:2025 Security Assessment Report

## 1. Executive Summary

This project evaluates the security of the Damn Vulnerable Web Application (DVWA) in an authorized local lab environment.

The assessment follows the OWASP Top 10:2025 framework and focuses on identifying common web application security weaknesses, documenting observations, and providing remediation recommendations.

## 2. Assessment Details

| Item | Details |
|---|---|
| Project | Website OWASP Top 10:2025 Security Assessment |
| Target | Damn Vulnerable Web Application (DVWA) |
| Environment | Local Lab |
| Testing Platform | Ubuntu WSL and Web Browser |
| Framework | OWASP Top 10:2025 |
| Assessment Status | In Progress |

## 3. Scope

Testing was restricted to the locally hosted DVWA application.

Public websites, third-party applications, and unauthorized systems were excluded.

## 4. Assessment Methodology

The assessment followed these phases:

1. Preparation and scope definition
2. Target application review
3. Security testing
4. Evidence collection
5. Findings documentation
6. Risk assessment
7. Remediation recommendations

## 5. Testing Summary

The following DVWA areas were included in the testing activity:

- SQL Injection
- Command Injection
- Local File Inclusion
- File Upload
- Cross-Site Scripting
- Session Management
- Cross-Site Request Forgery
- Brute Force
- CAPTCHA

Detailed results must be verified against the testing log and supporting evidence.

## 6. OWASP Top 10:2025 Coverage
| ID | OWASP Category | Assessment Status |
|---|---|---|
| A01 | Broken Access Control | Not Tested |
| A02 | Security Misconfiguration | Not Tested |
| A03 | Software Supply Chain Failures | Not Tested |
| A04 | Cryptographic Failures | Not Tested |
| A05 | Injection | Partially Tested - Evidence Review |
| A06 | Insecure Design | Not Tested |
| A07 | Authentication Failures | Partially Tested - Evidence Review |
| A08 | Software or Data Integrity Failures | Not Tested |
| A09 | Security Logging and Alerting Failures | Not Tested |
| A10 | Mishandling of Exceptional Conditions | Not Tested |
Note: DVWA testing does not automatically cover every OWASP category. Status must be updated only when the relevant assessment and evidence are complete.

## 7. Preliminary Findings

The following observations were recorded during DVWA testing:

- SQL Injection
- Command Injection
- Local File Inclusion
- File Upload behavior
- Cross-Site Scripting behavior
- Weak Session ID behavior
- CSRF behavior
- Brute Force behavior

Final severity and confirmation status require evidence review.

## 8. Remediation Recommendations

Recommended security controls include:

- Use parameterized queries to prevent SQL Injection.
- Avoid unsafe operating system command execution.
- Validate file paths and uploaded files.
- Apply context-aware output encoding to prevent XSS.
- Generate secure session identifiers.
- Implement CSRF protection.
- Apply login rate limiting and multi-factor authentication.
- Configure secure application headers.
- Maintain appropriate security logging and exception handling.

## 9. Evidence

All collected DVWA testing screenshots are consolidated into the master evidence PDF.

### Master Evidence PDF

Filename: `DVWA_Security_Testing_Evidence_Organized.pdf`

Location: `evidence/`

Total Pages: 12

### Evidence Documentation

- Evidence Register: `evidence/Evidence_Register.md`
- Testing Log: `evidence/testing-logs/Testing_Log.md`
- Supporting SQL Injection PDF: `evidence/SQL_Injection_Evidence.pdf`

The master PDF contains screenshots covering SQL Injection, Command Injection, File Inclusion, File Upload, XSS, Session Management, CSRF, Brute Force, and CAPTCHA.

Each screenshot is referenced in the Evidence Register.
## 10. Limitations

- The assessment was limited to a local DVWA lab.
- Not all OWASP Top 10:2025 categories were tested.
- CAPTCHA testing was limited by missing API configuration.
- Findings require supporting evidence before final severity confirmation.
- No production application was assessed.

## 11. Conclusion

The project provided practical experience in web application security testing using DVWA and the OWASP Top 10:2025 framework.

It also demonstrated the importance of evidence collection, risk documentation, and remediation planning.

Further testing is required to complete the remaining OWASP categories and finalize the assessment.

## 12. Project Status

Assessment: In Progress

Documentation: Prepared

Evidence Review: Pending

Final Validation: Pending
