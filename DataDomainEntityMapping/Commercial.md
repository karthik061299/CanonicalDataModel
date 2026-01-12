# Domain to Entity Mapping - Commercial Business Unit

## Source Systems Analysis

### Aspire (Leasing) System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Loan | - Lease<br>- LeaseAgreement<br>- LeaseSchedule<br>- LeaseTermination<br>- Renewal<br>- LeaseAmendment<br>- EndOfLease<br>- LeaseAccounting |
| 2 | Customer | - Lessee<br>- Lessor |
| 3 | Property | - Asset<br>- Equipment<br>- AssetValuation<br>- AssetReturn |
| 4 | Payment | - LeasePayment<br>- PaymentFrequency<br>- SecurityDeposit |
| 5 | Financial | - Residual<br>- Depreciation<br>- InterestRate<br>- TaxTreatment |
| 6 | Vendor | - MaintenanceContract<br>- Insurance |
| 7 | Product | - LeaseType<br>- PurchaseOption |

### Cadence System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Loan | - CommercialLoan<br>- CreditFacility<br>- Commitment<br>- Drawdown<br>- Repayment<br>- LoanModification<br>- Refinancing<br>- Syndication<br>- Participation<br>- LoanDocument |
| 2 | Customer | - Borrower<br>- Relationship<br>- LoanOfficer |
| 3 | Property | - Collateral<br>- LienPosition |
| 4 | Credit | - CreditAnalysis<br>- RiskRating<br>- CreditReview |
| 5 | Financial | - FinancialStatement<br>- InterestCalculation<br>- Fee |
| 6 | Document | - Covenant<br>- Guarantee |
| 7 | Compliance | - ComplianceCheck<br>- RegulatoryReport |

### Epiq System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Legal | - BankruptcyCase<br>- Debtor<br>- Creditor<br>- Claim<br>- Trustee<br>- Court<br>- Filing<br>- Petition<br>- Schedule<br>- Plan<br>- Disclosure<br>- Meeting<br>- Objection<br>- Motion<br>- Order<br>- Distribution<br>- Recovery<br>- Priority<br>- SecuredClaim<br>- UnsecuredClaim<br>- AdministrativeClaim<br>- Liquidation<br>- Reorganization |
| 2 | Property | - Asset<br>- Liability |

### Salesforce System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Customer | - Account<br>- Contact<br>- Lead<br>- Territory<br>- Team<br>- Relationship |
| 2 | Marketing | - Opportunity<br>- Campaign<br>- Pipeline<br>- Forecast |
| 3 | Operations | - Case<br>- Activity<br>- Task<br>- Event<br>- Workflow<br>- Approval |
| 4 | Product | - Product<br>- Quote<br>- Contract<br>- Order |
| 5 | Communication | - Interaction<br>- Note<br>- Attachment |
| 6 | Analytics | - Dashboard<br>- Report |

**Business Unit Summary:**
- **Total Systems:** 4
- **Total Entities Mapped:** 75
- **Total Tables:** 1,879
- **Primary Domains:** Loan (24%), Customer (16%), Legal (31%), Property (8%), Marketing (8%), Operations (8%), Others (5%)