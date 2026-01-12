# Data Domain to Entity Mapping - Commercial Business Unit

## Source Systems Analysis

### Source System: Aspire (Leasing)
**System Functionality:** Manages commercial equipment leasing, financing, and asset management operations.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Loan | - Lease<br>- LeaseAgreement<br>- Payment<br>- LeaseSchedule<br>- LeaseType<br>- Term<br>- InterestRate<br>- LeaseEnd<br>- Renewal<br>- Buyout<br>- Return<br>- Disposition<br>- Contract<br>- Portfolio |
| 2 | Customer | - Lessee |
| 3 | Product | - Equipment<br>- Asset |
| 4 | Vendor | - Vendor |
| 5 | Accounting | - Invoice<br>- Depreciation<br>- ResidualValue |
| 6 | Insurance | - Security<br>- Insurance<br>- Maintenance |
| 7 | Document | - FinancialStatement |

### Source System: Cadence
**System Functionality:** Manages commercial loan origination, underwriting, and portfolio management.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Loan | - Loan<br>- Application<br>- LoanAgreement<br>- Disbursement<br>- Payment<br>- InterestRate<br>- Fee<br>- Servicing<br>- Portfolio |
| 2 | Customer | - Borrower<br>- LoanOfficer |
| 3 | Credit | - Underwriting<br>- CreditAnalysis<br>- CreditScore<br>- RiskRating<br>- Approval |
| 4 | Product | - Collateral |
| 5 | Document | - Appraisal<br>- FinancialStatement<br>- Covenant<br>- Guarantee<br>- Documentation<br>- Closing |
| 6 | Compliance | - Compliance<br>- Reporting |

### Source System: Epiq
**System Functionality:** Manages bankruptcy, restructuring, and claims administration for commercial lending.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Legal | - BankruptcyCase<br>- Debtor<br>- Creditor<br>- Claim<br>- Petition<br>- Schedule<br>- Plan<br>- Disclosure<br>- Trustee<br>- Court<br>- Hearing<br>- Motion<br>- Order<br>- Distribution<br>- Payment<br>- Objection<br>- Proof<br>- Notice<br>- Docket<br>- Document<br>- Status<br>- Recovery<br>- Administration |
| 2 | Reference | - Asset<br>- Liability |

### Source System: Salesforce
**System Functionality:** Manages customer relationship, sales pipeline, and commercial banking client engagement.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Customer | - Account<br>- Contact<br>- Lead<br>- Relationship |
| 2 | Marketing | - Opportunity<br>- Case<br>- Campaign<br>- Activity<br>- Task<br>- Event<br>- Email<br>- Call<br>- Meeting |
| 3 | Product | - Quote<br>- Contract<br>- Product<br>- PriceBook |
| 4 | Employee | - User<br>- Role<br>- Team |
| 5 | Reference | - Territory |
| 6 | Analytics | - Dashboard<br>- Report<br>- Forecast<br>- Pipeline |