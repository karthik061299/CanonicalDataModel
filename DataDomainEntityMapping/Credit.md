# Data Domain to Entity Mapping - Credit Business Unit

## Source Systems Analysis

### Source System: Codefi
**System Functionality:** Manages credit portfolio management, risk analytics, and loan performance monitoring.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Loan | - Loan<br>- Portfolio<br>- Exposure<br>- Provision<br>- Allowance<br>- Covenant<br>- Monitoring |
| 2 | Customer | - Borrower |
| 3 | Credit | - CreditRisk<br>- RiskRating<br>- Default<br>- Loss<br>- Recovery<br>- Model<br>- Forecast |
| 4 | Product | - Collateral<br>- Valuation |
| 5 | Compliance | - Delinquency |
| 6 | Workflow | - Alert |
| 7 | Analytics | - Report<br>- Metric<br>- KPI<br>- Stress<br>- Scenario<br>- Analytics |

### Source System: Moodys
**System Functionality:** Manages credit ratings, risk assessment, and financial analysis services.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Credit | - Rating<br>- CreditScore<br>- RiskAssessment<br>- Issuer<br>- Security<br>- Obligation<br>- Analysis<br>- Outlook<br>- WatchList<br>- Upgrade<br>- Downgrade<br>- Methodology<br>- Factor<br>- Model |
| 2 | Reference | - Industry<br>- Sector<br>- Geography |
| 3 | Accounting | - Financial<br>- Metric<br>- Benchmark |
| 4 | Analytics | - Report<br>- Peer<br>- Trend<br>- Forecast<br>- Data |