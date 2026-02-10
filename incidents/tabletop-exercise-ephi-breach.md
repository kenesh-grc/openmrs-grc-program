# Tabletop Exercise – ePHI Data Breach (OpenMRS)

## 1. Scenario Overview
A security alert indicates unauthorized access to the OpenMRS production database hosted in AWS. The database contains electronic Protected Health Information (ePHI).

## 2. Objectives
- Validate incident response procedures
- Assess HIPAA breach response readiness
- Identify gaps in controls and communication

## 3. Timeline of Events
| Time | Event |
|-----|------|
| 09:15 | SIEM alert triggered for unusual database queries |
| 09:20 | IT Operations confirms suspicious activity |
| 09:30 | Incident Response Team activated |
| 10:00 | Affected database isolated |
| 11:30 | Forensic review initiated |

## 4. Roles Involved
- Incident Response Lead
- GRC Analyst
- IT Operations
- Legal & Compliance

## 5. Decisions Made
- Disabled compromised credentials
- Restricted database access
- Initiated HIPAA breach assessment

## 6. Communications
- Internal notification to leadership
- Legal consultation regarding breach notification requirements

## 7. Evidence Collected
- Audit logs
- Access records
- System snapshots

## 8. Outcome
The incident was classified as a **High Severity** event involving confirmed ePHI exposure.

## 9. Lessons Learned
- Improve database access monitoring
- Enforce MFA for administrative accounts
- Conduct more frequent access reviews

## 10. Action Items
| Action | Owner | Due Date |
|------|-------|----------|
| Enable MFA for DB admins | IT Ops | 30 days |
| Update access review process | GRC | 45 days |
