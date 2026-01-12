# Domain to Entity Mapping - AAS Business Unit

## Source System: ALF (Alternative Asset Lending)

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Loan | - Loan<br>- LoanApplication<br>- LoanSchedule<br>- LoanModification<br>- LoanOrigination<br>- LoanServicing<br>- LoanDocument<br>- LoanOfficer<br>- RepaymentPlan<br>- LoanDisbursement |
| 2 | Customer | - Borrower<br>- Guarantor |
| 3 | Property | - Collateral<br>- AssetValuation<br>- SecurityInterest<br>- LienPosition |
| 4 | Payment | - Payment<br>- PaymentSchedule |
| 5 | Credit | - CreditAssessment<br>- UnderwritingCriteria |
| 6 | Financial | - InterestRate<br>- EscrowAccount |
| 7 | Risk | - Portfolio<br>- DefaultEvent<br>- Forbearance<br>- Restructuring |
| 8 | Document | - Covenant |

**Primary Domain Distribution:**
- Loan: 10 entities (40%)
- Customer: 2 entities (8%)
- Property: 4 entities (16%)
- Payment: 2 entities (8%)
- Credit: 2 entities (8%)
- Financial: 2 entities (8%)
- Risk: 4 entities (16%)
- Document: 1 entity (4%)

**Total Entities Mapped:** 25
**Total Tables in System:** 68