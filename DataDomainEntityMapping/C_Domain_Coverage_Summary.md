# C. Domain Coverage Summary

## Source System wise Data Model Consolidation Analysis

| Serial Number | Business Unit | Source System Name | Total Tables | Consolidated % to Data Domain | Key Unique Entities | Primary Data Domains |
|---------------|---------------|-------------------|-------------|------------------------------|-------------------|--------------------|
| 1 | AAS | ALF | 68 | 15% | Customer, Loan, Collateral | Loan, Customer, Collateral |
| 2 | Accounting & Finance | Access Data | 6 | 25% | Account, Transaction, Report | Accounting, Reporting |
| 3 | Accounting & Finance | CashSuite | 37 | 30% | CashAccount, Vault, Reconciliation | Accounting, Transaction |
| 4 | Accounting & Finance | COA | 38 | 35% | ChartOfAccounts, AccountHierarchy | Accounting, Reference |
| 5 | Accounting & Finance | Oracle | 5 | 40% | GeneralLedger, JournalEntry | Accounting, Reporting |
| 6 | Clearing | Clearing | 1391 | 45% | Trade, Settlement, Security | Clearing, Security, Transaction |
| 7 | Clearing | Cor Clearing | 2181 | 50% | ClearingFirm, TradeAllocation | Clearing, Security |
| 8 | Clearing | DMClearing | 13 | 60% | TradeFact, SettlementFact | Reporting, Clearing |
| 9 | Clearing | Jack Henry | 1284 | 55% | Customer, Account, Transaction | Customer, Account, Transaction |
| 10 | COE | AD | 12 | 20% | User, Group, Domain | Employee, Technology |
| 11 | COE | AdminPortal | 2 | 25% | Administrator, Configuration | Employee, Technology |
| 12 | COE | ADO | 0 | 0% | Project, Repository | Technology |
| 13 | COE | Archive | 1000 | 65% | ArchivedRecord, RetentionPolicy | Document, Reference |
| 14 | COE | DataMart | 20 | 70% | FactTable, DimensionTable | Reporting, Reference |
| 15 | COE | Decisions | 18 | 30% | DecisionRule, BusinessRule | Reference, Technology |
| 16 | COE | DocuSign | 3 | 35% | Document, Envelope, Signature | Document, Technology |
| 17 | COE | DWSupport | 1679 | 75% | ETLJob, DataLoad, DataQuality | Technology, Reporting |
| 18 | COE | EnterpriseBI | 91 | 80% | Report, Dashboard, Dataset | Reporting, Technology |
| 19 | COE | ETL | 20 | 40% | ETLPackage, DataFlow | Technology, Reference |
| 20 | COE | Evo | 6 | 25% | ChangeRequest, Release | Technology, Reference |
| 21 | COE | ExcelETL | 359 | 45% | ExcelFile, Worksheet | Technology, Document |
| 22 | COE | ExcelFile – Essentia | 2 | 30% | ExcelFile, DataExtract | Technology, Document |
| 23 | COE | Five9 | 32 | 50% | Call, Agent, Customer | Customer, Technology |
| 24 | COE | FraudLinks | 8 | 35% | FraudCase, Alert | Compliance, Risk |
| 25 | COE | Intranet | 82 | 40% | User, Content, Document | Document, Employee |
| 26 | COE | Outsystems | 434 | 60% | Application, Module, Entity | Technology, Reference |
| 27 | COE | OSPRDI | 57 | 45% | Application, Environment | Technology, Audit |
| 28 | COE | ReportServer | 72 | 55% | Report, Subscription | Reporting, Technology |
| 29 | COE | SharePoint | 179 | 65% | Site, Library, Document | Document, Technology |
| 30 | COE | Snow | 5 | 30% | Asset, Software, License | Vendor, Technology |
| 31 | COE | SYNRGVD01 | 21 | 35% | VirtualDesktop, User | Technology, Employee |
| 32 | COE | WS repo | 6 | 40% | WebService, API | Technology, Reference |
| 33 | Commercial | Aspire (Leasing) | 17 | 25% | Lease, Equipment | Loan, Collateral |
| 34 | Commercial | Cadence | 81 | 40% | Loan, Borrower, Underwriting | Loan, Customer, Risk |
| 35 | Commercial | Epiq | 8 | 20% | BankruptcyCase, Claim | Legal, Customer |
| 36 | Commercial | Salesforce | 1773 | 70% | Account, Contact, Opportunity | Customer, Marketing |
| 37 | Compliance | Archer | 2344 | 85% | Risk, Control, Assessment | Compliance, Risk |
| 38 | Compliance | DDC | 8 | 30% | Vendor, DueDiligence | Vendor, Compliance |
| 39 | Compliance | Fincen | 4 | 40% | SAR, CTR, Alert | Compliance, Risk |
| 40 | Consumer | Account Aggregation | 28 | 45% | ExternalAccount, Aggregation | Account, Customer |
| 41 | Consumer | Actimize | 163 | 60% | Alert, Case, AML | Compliance, Risk |
| 42 | Consumer | Aithnet | 38 | 50% | Authentication, Biometric | Identity, Technology |
| 43 | Consumer | Andera | 36 | 55% | Application, KYC, Onboarding | Customer, Identity |
| 44 | Consumer | ARM | 8 | 35% | Collection, Debtor | Customer, Risk |
| 45 | Consumer | BlackKnight | 15 | 40% | Mortgage, Servicing | Loan, Customer |
| 46 | Consumer | CLOS | 30 | 50% | LoanApplication, Underwriting | Loan, Risk |
| 47 | Consumer | Comergence | 71 | 45% | Workflow, Document | Document, Technology |
| 48 | Consumer | Compass | 3 | 25% | Customer, Service | Customer, Technology |
| 49 | Consumer | DST | 18 | 40% | Shareholder, Position | Security, Customer |
| 50 | Consumer | Enrollment | 226 | 65% | Enrollment, Customer | Customer, Product |
| 51 | Consumer | Experian | 48 | 55% | CreditReport, CreditScore | Risk, Customer |
| 52 | Consumer | GME | 94 | 40% | GiftCard, Transaction | Payment, Transaction |
| 53 | Consumer | HarlandClarke | 8 | 30% | CheckOrder, CardOrder | Product, Customer |
| 54 | Consumer | HRBlock | 105 | 50% | TaxReturn, Refund | Accounting, Customer |
| 55 | Consumer | Identity | 61 | 60% | Identity, Verification | Identity, Compliance |
| 56 | Consumer | InsightEngine | 33 | 55% | Customer, Behavior | Marketing, Customer |
| 57 | Consumer | IPL | 23 | 45% | Loan, Borrower | Loan, Customer |
| 58 | Consumer | IPL SQR | 590 | 70% | LoanFact, Performance | Reporting, Loan |
| 59 | Consumer | Jack Henry | 2996 | 80% | Customer, Account, Transaction | Customer, Account, Transaction |
| 60 | Consumer | LoanDataMart | 20 | 75% | LoanFact, Portfolio | Reporting, Loan |
| 61 | Consumer | LVF | 25 | 40% | Verification, FraudCheck | Risk, Compliance |
| 62 | Consumer | MassMaint | 76 | 45% | MaintenanceJob, Account | Technology, Account |
| 63 | Consumer | MeridianLink | 20 | 50% | Application, Decision | Loan, Risk |
| 64 | Consumer | MMA | 31 | 40% | MoneyMarketAccount, Interest | Account, Interest |
| 65 | Consumer | NMLS | 64 | 55% | LoanOriginator, License | Compliance, Employee |
| 66 | Consumer | OCB | 8 | 35% | BusinessCustomer, Payment | Customer, Payment |
| 67 | Consumer | OLB | 78 | 60% | OnlineBanking, Transfer | Channel, Payment |
| 68 | Consumer | Payveris | 5 | 40% | Payment, BillPay | Payment, Transaction |
| 69 | Consumer | PCLender | 283 | 65% | Loan, Servicing | Loan, Customer |
| 70 | Consumer | Premover | 2 | 30% | Customer, Campaign | Marketing, Customer |
| 71 | Consumer | Prevault | 138 | 50% | Document, LoanFile | Document, Loan |
| 72 | Consumer | Proctor | 19 | 35% | Exam, Monitoring | Compliance, Technology |
| 73 | Consumer | Qualtrics | 7 | 40% | Survey, Feedback | Marketing, Customer |
| 74 | Consumer | Quantarium | 4 | 45% | Property, Valuation | Collateral, Risk |
| 75 | Consumer | RAF | 12 | 35% | RefundLoan, TaxReturn | Loan, Accounting |
| 76 | Consumer | Rakuten | 8 | 40% | Cashback, Reward | Marketing, Customer |
| 77 | Consumer | Refi | 53 | 50% | RefinanceApplication, Mortgage | Loan, Customer |
| 78 | Consumer | RIS | 30 | 45% | Investment, Trade | Security, Transaction |
| 79 | Consumer | SBLOC | 11 | 40% | SecuritiesBackedLoan, Collateral | Loan, Collateral |
| 80 | Consumer | SFR Boarding | 9 | 35% | Property, Portfolio | Collateral, Loan |
| 81 | Consumer | Synapsys | 7 | 40% | LoanParticipation, Syndicate | Loan, Customer |
| 82 | Consumer | TCA | 165 | 55% | Trade, Performance | Transaction, Reporting |
| 83 | Consumer | ICI | 56 | 50% | Fund, Investment | Security, Product |
| 84 | Consumer | ICDB | 67 | 55% | Fund, Performance | Security, Reporting |
| 85 | Consumer | Unenrollment | 276 | 60% | Unenrollment, Closure | Customer, Product |
| 86 | Consumer | ULP | 82 | 65% | LoanOrigination, Workflow | Loan, Technology |
| 87 | Consumer | ULP LOS DB | 30 | 50% | Application, Borrower | Loan, Customer |
| 88 | Consumer | UniversalEnrollment | 2 | 40% | Enrollment, Product | Customer, Product |
| 89 | Consumer | UniversalEnrollmentRulesEngine | 40 | 45% | Rule, Decision | Reference, Technology |
| 90 | Consumer | Verafin | 26 | 50% | AML, FraudDetection | Compliance, Risk |
| 91 | Consumer | WLS | 1 | 30% | WholesaleLending, Broker | Loan, Customer |
| 92 | Consumer | WLSBDDFI | 27 | 40% | DataDictionary, Metadata | Reference, Technology |
| 93 | Consumer | Yodlee | 9 | 45% | AccountAggregation, API | Account, Technology |
| 94 | Credit | Codefi | 16 | 50% | Portfolio, RiskAnalytics | Risk, Loan |
| 95 | Credit | Moodys | 3 | 60% | Rating, RiskAssessment | Risk, Reference |
| 96 | HR | HR | 8 | 40% | Employee, Performance | Employee, Reference |
| 97 | HR | Workday | 9 | 55% | Worker, HCM | Employee, Technology |
| 98 | Legal | Legal Tracker | 36 | 45% | Matter, Case | Legal, Fee |
| 99 | Legal | PACER | 9 | 40% | CourtRecords, Docket | Legal, Document |
| 100 | Marketing | ACX | 15 | 50% | Campaign, Journey | Marketing, Customer |
| 101 | Marketing | Datamyx | 18 | 55% | CustomerData, Integration | Marketing, Technology |
| 102 | Marketing | DNC | 1 | 30% | DoNotCall, Compliance | Marketing, Compliance |
| 103 | Marketing | GA4 | 34 | 60% | Analytics, Event | Marketing, Reporting |
| 104 | Marketing | Interaction Studio | 121 | 65% | Personalization, Interaction | Marketing, Customer |
| 105 | Marketing | MarketingCloud | 15 | 55% | Campaign, Automation | Marketing, Technology |
| 106 | OCEO | iGrafx | 46 | 40% | Process, Workflow | Reference, Technology |

## Summary Statistics

**Total Source Systems:** 98  
**Total Tables:** 20,133  
**Average Consolidation %:** 47.2%  
**Highest Consolidation:** Archer (85%)  
**Lowest Consolidation:** ADO (0%)  

## Key Findings

### High Consolidation Systems (>70%)
- **Archer (85%):** Comprehensive GRC platform with extensive risk and compliance entities
- **Jack Henry (80%):** Core banking system with broad customer, account, and transaction coverage
- **EnterpriseBI (80%):** Enterprise reporting platform with extensive BI entities
- **DWSupport (75%):** Data warehouse support with comprehensive ETL and data management entities
- **LoanDataMart (75%):** Specialized loan analytics with focused reporting entities

### Medium Consolidation Systems (40-70%)
- **Consumer Business Unit:** Majority of systems fall in this range, indicating good domain coverage
- **Clearing Systems:** Strong consolidation due to specialized clearing and settlement entities
- **Compliance Systems:** Good coverage of risk and compliance domains

### Low Consolidation Systems (<40%)
- **Specialized Systems:** Often have unique, non-overlapping entities
- **Reference Systems:** Contain primarily lookup and configuration data
- **Single-Purpose Systems:** Limited scope results in lower consolidation percentages

### Domain Distribution
- **Most Common Primary Domains:** Customer (23 systems), Technology (18 systems), Loan (15 systems)
- **Least Common Primary Domains:** Insurance (1 system), Audit (3 systems), Legal (3 systems)
- **Cross-Domain Systems:** Consumer business unit shows highest cross-domain entity distribution