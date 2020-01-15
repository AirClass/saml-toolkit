# Security Policy

## Supported Versions
ALL

## Service Level Agreement with Lenovo
The operating assumption is such that all identified vulnerabilities need to be reported, assessed, and captured in JIRA 
according to Lenovo's Security Risk SLAs (service level agreement). The SLAs are defined below, upon identifying a vulnerability
use the table to determine risk and assessment and remediation timelines.

| Risk Classification | JIRA Priority | Semi-QV (1-100) | Semi-QV (1-10) | SLA for assessment | SLA for fix deploy |
| ------------------- | ------------- | --------------- | -------------- | ------------------ | ------------------ |
| Critical/Very High  | Blocker       | 96-100          | 10             | 24 hours           | 7 days             |
| High                | Critical      | 80-95           | 8-9            | 48 hours           | 30 days            |
| Modertate           | Major         | 21-79           | 5-8            | 7 days             | 3 months           |
| Low/Very Low        | Trivial       | 1-20            | 0-5            | 14 days            | **6 months         |

** Projects may decline to address issue of low/very low severity. Justification must be provided and documented.

## Reporting a Vulnerability
Vulernabilities should be reported/captured in Jira. Based on the risk classification, a Jira issue is to be created with
the appropriate priority using the Jira "Priority" field. Priority may change after assessment.  Using the Jira "Label" field 
set the value to "Security".  Within the "Acceptance Criteria" or equivalent field ensure the following criteria are documented:
- Assessment time (based on risk classification)
- Remediation time or due date (based on risk classification)
- CVE/CWE/NVD/Mitre number/record (for remediation guidelines to follow)
- Upgrade to the fixed version

