# Domain to Entity Mapping - Compliance Business Unit

## Source Systems Analysis

### Archer System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Compliance | - RiskAssessment<br>- Control<br>- Policy<br>- Regulation<br>- ComplianceRequirement<br>- ComplianceReport<br>- RegulatoryChange<br>- ComplianceObligation<br>- ComplianceMonitoring<br>- RegulatoryExamination |
| 2 | Risk | - RiskRegister<br>- RiskIndicator<br>- RiskMitigation<br>- RiskOwner<br>- RiskScenario |
| 3 | Audit | - Issue<br>- Finding<br>- Remediation<br>- AuditTrail<br>- ControlTest<br>- ControlDeficiency<br>- ControlEffectiveness |
| 4 | Operations | - ControlFramework<br>- ControlOwner<br>- PolicyException |

### DDC System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Customer | - Customer |
| 2 | Compliance | - DueDiligenceCheck<br>- KYCDocument<br>- VerificationStatus<br>- RiskProfile<br>- ScreeningResult<br>- ComplianceFlag |
| 3 | Document | - DocumentReview |

### Fincen System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Compliance | - SARReport<br>- SuspiciousActivity<br>- FilingStatus |
| 2 | Transaction | - Transaction |

**Business Unit Summary:**
- **Total Systems:** 3
- **Total Entities Mapped:** 32
- **Total Tables:** 2,356
- **Primary Domains:** Compliance (69%), Risk (16%), Audit (16%), Operations (9%), Customer (3%), Document (3%), Transaction (3%)