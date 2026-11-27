# OWASP Top 10:2025 – Web Application Security Assessment

A hands-on web application security assessment project conducted using Damn Vulnerable Web Application (DVWA) in an authorized local testing environment.

## Project Overview

This project focuses on evaluating web application security weaknesses using the OWASP Top 10:2025 framework.

It includes practical security testing, evidence collection, vulnerability documentation, risk analysis, and remediation recommendations.

## Objectives

- Understand common web application vulnerabilities.
- Perform authorized security testing in a local lab.
- Identify and analyze potential security risks.
- Collect and organize testing evidence.
- Document findings and remediation recommendations.
- Understand the OWASP Top 10:2025 framework.

## Technologies & Tools

- Python 3
- Ubuntu Linux (WSL2)
- Damn Vulnerable Web Application (DVWA)
- Git and GitHub
- Nmap

## Project Structure

```text
OWASP-Top10-Assessment/
│
├── checklists/
│   └── OWASP_Top10_2025_Checklist.md
│
├── documentation/
│   ├── Assessment_Methodology.md
│   ├── Rules_of_Engagement.md
│   └── Scope_and_Asset_Register.md
│
├── evidence/
│   ├── DVWA_Security_Testing_Evidence_Organized.pdf
│   ├── SQL_Injection_Evidence.pdf
│   └── Evidence_Register.md
│
├── findings/
│   └── Finding_Register.md
│
├── remediation/
│   └── Remediation_Recommendations.md
│
├── reports/
│   └── Final_Assessment_Report.md
│
├── requirements.txt
├── .gitignore
└── README.md
```

## Assessment Activities

The project covers testing activities involving:

- SQL Injection
- Command Injection
- Local File Inclusion
- File Upload
- Cross-Site Scripting (XSS)
- Session Management
- Cross-Site Request Forgery (CSRF)
- Brute Force Authentication Testing

Testing results and supporting evidence are maintained separately.

## Documentation

| Document | Purpose |
|---|---|
| OWASP Checklist | Tracks assessment coverage |
| Rules of Engagement | Defines authorized testing boundaries |
| Scope and Asset Register | Identifies in-scope assets |
| Assessment Methodology | Explains the testing approach |
| Finding Register | Records security findings |
| Evidence Register | Maps tests to supporting evidence |
| Remediation Recommendations | Suggests security improvements |
| Final Assessment Report | Summarizes the assessment |

## Assessment Status

**Status: In Progress**

- Environment Setup: Completed
- Documentation Preparation: Completed
- Evidence Review: Pending
- OWASP Coverage Verification: Pending
- Final Validation: Pending

## Important Notes

- Testing is restricted to the authorized local DVWA environment.
- Not all OWASP Top 10:2025 categories have been assessed.
- Untested categories must remain marked as Not Tested.
- Findings must have supporting evidence.
- Remediation recommendations are documented separately.
- Remediation implementation has not been verified.

## Disclaimer

This project is intended strictly for educational purposes and authorized security testing.

Never perform security testing against systems without explicit permission.
