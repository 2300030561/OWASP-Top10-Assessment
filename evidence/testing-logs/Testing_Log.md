# Security Testing Log

## Project
Website OWASP Top 10:2025 Security Assessment

## Target
DVWA - Local Lab

## Testing Environment
Ubuntu WSL2 and Local DVWA Application

## Evidence Reference
Master PDF: `evidence/DVWA_Security_Testing_Evidence_Organized.pdf`

## Testing Records

| Test ID | Test Name | Evidence Page | Observation |
|---|---|---:|---|
| T-01 | SQL Injection | 1 | SQL query output observed |
| T-02 | Command Injection | 2 | Command execution output observed |
| T-03 | Reflected XSS | 5 | Input page captured |
| T-04 | Stored XSS | 6 | JavaScript alert observed |
| T-05 | Local File Inclusion | 3 | File inclusion test captured |
| T-06 | File Upload | 4 | Upload success message observed |
| T-07 | Insecure CAPTCHA | 12 | API key configuration error observed |
| T-08 | Weak Session IDs | 8 | Session cookie information captured |
| T-09 | DOM XSS | 7 | JavaScript alert observed |
| T-10 | CSRF | 9 | Password change success message observed |
| T-11 | Brute Force | 10-11 | Successful and failed login responses captured |

## Testing Notes

- Testing was performed against the local DVWA environment.
- Screenshots are consolidated in the master evidence PDF.
- CAPTCHA testing was blocked by missing API configuration.
- Screenshots document observations, not automatic vulnerability confirmation.
- Final severity and vulnerability status require individual validation.

## Overall Status

Evidence Collection: Completed

Assessment Validation: In Progress
