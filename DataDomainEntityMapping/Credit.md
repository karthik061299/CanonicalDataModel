# Domain to Entity Mapping - Credit Business Unit

## Source Systems Analysis

### Codefi System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Credit | - CreditApplication<br>- CreditScore<br>- RiskAssessment<br>- DecisionModel<br>- CreditPolicy<br>- ScorecardModel<br>- DecisionRule<br>- CreditDecision<br>- RiskFactor<br>- CreditAttribute<br>- CreditRating<br>- RiskSegment<br>- DecisionOutcome<br>- ModelVariable |
| 2 | Technology | - DecisionEngine<br>- PolicyRule |

### Moodys System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Credit | - CreditRating<br>- RiskAnalysis |
| 2 | Financial | - FinancialMetric |

**Business Unit Summary:**
- **Total Systems:** 2
- **Total Entities Mapped:** 17
- **Total Tables:** 19
- **Primary Domains:** Credit (88%), Technology (6%), Financial (6%)