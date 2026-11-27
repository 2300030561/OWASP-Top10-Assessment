# OWASP Top 10:2025 – Web Application Security Assessment

A hands-on web application security assessment project using Damn Vulnerable Web Application (DVWA) in an authorized local testing environment.

## Project Overview

This project focuses on identifying, analyzing, and documenting web application security weaknesses using the OWASP Top 10:2025 framework.

The assessment includes practical vulnerability testing, evidence collection, risk documentation, and remediation recommendations.

## Objectives

- Understand common web application vulnerabilities.
- Perform authorized security testing in a local lab.
- Analyze potential security risks and impacts.
- Maintain testing logs and supporting evidence.
- Prepare vulnerability findings and remediation recommendations.
- Understand the OWASP Top 10:2025 security framework.

## Technologies & Tools

- Python 3
- Ubuntu Linux (WSL2)
- Damn Vulnerable Web Application (DVWA)
- Git and GitHub
- Nmap
- OWASP ZAP (if used during assessment)

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
│   ├── Evidence_Register.md
│   └── testing-logs/
│       └── Testing_Log.md
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
└── README.md
```

## Assessment Activities

The project includes testing activities involving:

- SQL Injection
- Command Injection
- Local File Inclusion
- File Upload
- Cross-Site Scripting (XSS)
- Session Management
- Cross-Site Request Forgery (CSRF)
- Brute Force Authentication Testing

Testing results and evidence are documented separately.

## Documentation

| Document | Purpose |
|---|---|
| OWASP Checklist | Tracks assessment coverage |
| Rules of Engagement | Defines authorized testing boundaries |
| Scope and Asset Register | Identifies in-scope assets |
| Assessment Methodology | Explains testing approach |
| Finding Register | Records security observations |
| Evidence Register | Maps tests to supporting evidence |
| Testing Log | Records testing activities |
| Remediation Recommendations | Suggests security improvements |
| Final Assessment Report | Summarizes the assessment |

## Important Assessment Notes

- Testing is restricted to the authorized local DVWA environment.
- Not all OWASP Top 10:2025 categories have been assessed.
- Untested categories remain marked as Not Tested.
- Findings require supporting evidence and validation.
- Recommendations are documented; implementation is not yet verified.

## Current Project Status

**Status: In Progress**

- Environment Setup: Completed
- Documentation: Prepared
- Evidence Review: Pending
- OWASP Coverage Verification: Pending
- Final Validation: Pending

## Disclaimer

This project is intended for educational purposes and authorized security testing only.

Do not use these testing techniques against systems without explicit permission.
