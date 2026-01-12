# Data Domain to Entity Mapping - Compliance Business Unit

## Source Systems Analysis

### Source System: Archer
**System Functionality:** Manages governance, risk, and compliance programs across enterprise operations.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Compliance | - Risk<br>- Control<br>- Assessment<br>- Issue<br>- Finding<br>- Action<br>- Policy<br>- Regulation<br>- Audit<br>- Incident<br>- Violation<br>- Remediation<br>- Mitigation<br>- Framework<br>- Requirement<br>- Evidence<br>- Test<br>- Exception<br>- Compliance |
| 2 | Workflow | - Approval<br>- Workflow |
| 3 | Document | - Document |
| 4 | Analytics | - Report<br>- Dashboard<br>- KRI |

### Source System: DDC
**System Functionality:** Manages due diligence checks, vendor screening, and third-party risk assessment.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Vendor | - Vendor<br>- ThirdParty<br>- Contract<br>- Relationship |
| 2 | Compliance | - DueDiligence<br>- Screening<br>- Assessment<br>- RiskRating<br>- Review<br>- Approval<br>- Questionnaire<br>- Response<br>- Finding<br>- Remediation<br>- Monitoring<br>- Renewal<br>- Compliance |
| 3 | Document | - Document |
| 4 | Audit | - AuditTrail<br>- Report |

### Source System: Fincen
**System Functionality:** Manages FinCEN reporting, suspicious activity reports, and anti-money laundering compliance.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Compliance | - SAR<br>- CTR<br>- Alert<br>- Investigation<br>- Report<br>- Filing<br>- Regulation<br>- Threshold<br>- Pattern<br>- RiskScore<br>- Disposition<br>- Narrative<br>- Subject<br>- Activity<br>- Documentation<br>- Submission<br>- Status |
| 2 | Transaction | - Transaction |
| 3 | Customer | - Customer |
| 4 | Account | - Account |