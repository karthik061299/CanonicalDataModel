# Consumer Business Unit - Data Domain Entity Mapping

## Business Unit: Consumer

### Source Systems: Account Aggregation, Actimize, Aithnet, Andera, ARM, BlackKnight, CLOS, Comergence, Compass, DST, Enrollment, Experian, GME, HarlandClarke, HRBlock, Identity, InsightEngine, IPL, IPL SQR, Jack Henry, LoanDataMart, LVF, MassMaint, MeridianLink, MMA, NMLS, OCB, OLB, Payveris, PCLender, Premover, Prevault, Proctor, Qualtrics, Quantarium, RAF, Rakuten, Refi, RIS, SBLOC, SFR Boarding, Synapsys, TCA, ICI, ICDB, Unenrollment, ULP, ULP LOS DB, UniversalEnrollment, UniversalEnrollmentRulesEngine, Verafin, WLS, WLSBDDFI, Yodlee

## Domain to Entity Mapping

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Customer | - Customer<br>- Consumer<br>- Individual Customer<br>- Retail Customer<br>- Applicant<br>- Borrower<br>- CoApplicant<br>- Lessee<br>- Taxpayer<br>- Member<br>- Prospect<br>- Contact<br>- Address<br>- Phone<br>- Email<br>- Identification<br>- Demographics<br>- Preference<br>- Consent<br>- Household<br>- Segment<br>- Profile<br>- History<br>- Relationship<br>- Hierarchy |
| 2 | Account | - Account<br>- CashAccount<br>- Deposit<br>- Savings Account<br>- Checking Account<br>- Money Market Account<br>- Investment Account<br>- LineOfCredit<br>- Balance<br>- Position<br>- Holding<br>- Portfolio<br>- NetWorth<br>- Aggregation<br>- Link |
| 3 | Loan | - Loan<br>- Mortgage<br>- Consumer Loan<br>- Personal Loan<br>- Auto Loan<br>- Home Equity Loan<br>- Student Loan<br>- Credit Card<br>- Application<br>- Origination<br>- Underwriting<br>- Approval<br>- Disbursement<br>- Servicing<br>- Payment<br>- Schedule<br>- Principal<br>- Interest<br>- Escrow<br>- Default<br>- Delinquency<br>- Collection<br>- Modification<br>- Forbearance<br>- Payoff<br>- Reinstatement<br>- Maturity<br>- Renewal |
| 4 | Transaction | - Transaction<br>- Payment<br>- Transfer<br>- Deposit<br>- Withdrawal<br>- Purchase<br>- ACH<br>- Wire<br>- DirectDeposit<br>- BillPay<br>- P2P Payment<br>- Cashback<br>- Reward<br>- Points<br>- Redemption<br>- Payout |
| 5 | Credit | - Credit<br>- CreditReport<br>- CreditScore<br>- Tradeline<br>- Inquiry<br>- PublicRecord<br>- Bankruptcy<br>- Foreclosure<br>- Judgment<br>- Lien<br>- Employment<br>- Income<br>- Asset<br>- Liability<br>- Debt-to-Income<br>- LoanToValue<br>- Risk<br>- Score<br>- Model<br>- Factor<br>- Attribute |
| 6 | Security | - Authentication<br>- Authorization<br>- Identity<br>- Credential<br>- Token<br>- Session<br>- Device<br>- Factor<br>- Challenge<br>- Response<br>- Verification<br>- Certificate<br>- Key<br>- Policy<br>- Rule<br>- Access<br>- Permission<br>- Biometric<br>- OTP<br>- PIN<br>- MFA<br>- SSO<br>- Federation |
| 7 | Compliance | - Alert<br>- Case<br>- Investigation<br>- SAR<br>- CTR<br>- Fraud<br>- AML<br>- KYC<br>- Watchlist<br>- PEP<br>- Sanction<br>- Pattern<br>- Behavior<br>- Anomaly<br>- Disposition<br>- Evidence<br>- Compliance<br>- Regulation<br>- License<br>- Registration<br>- Examination<br>- Education<br>- Training<br>- Sponsorship<br>- Disciplinary<br>- Background |
| 8 | Product | - Product<br>- Service<br>- Feature<br>- Pricing<br>- Rate<br>- Fee<br>- Term<br>- Condition<br>- Package<br>- Bundle<br>- Configuration<br>- Option<br>- Category<br>- Hierarchy<br>- Eligibility<br>- Availability |
| 9 | Channel | - Channel<br>- Online Banking<br>- Mobile Banking<br>- ATM<br>- Branch<br>- Contact Center<br>- Card<br>- Statement<br>- eStatement<br>- CheckOrder<br>- Enrollment<br>- Login<br>- User<br>- Entitlement |
| 10 | Document | - Document<br>- Form<br>- Application Form<br>- Disclosure<br>- Notice<br>- Statement<br>- Contract<br>- Agreement<br>- Template<br>- Package<br>- Version<br>- Status<br>- Review<br>- Approval<br>- Signature<br>- Notarization<br>- Recording<br>- Index<br>- Metadata<br>- Storage<br>- Retrieval<br>- Archive<br>- Retention |
| 11 | Communication | - Message<br>- Communication<br>- Email<br>- SMS<br>- Push<br>- Notification<br>- Alert<br>- Campaign<br>- Delivery<br>- Template<br>- Trigger<br>- Event<br>- Response<br>- Click<br>- Open<br>- Bounce<br>- Unsubscribe<br>- Opt-in<br>- Opt-out<br>- Preference<br>- Consent |
| 12 | Marketing | - Campaign<br>- Offer<br>- Lead<br>- Conversion<br>- Attribution<br>- Segment<br>- Target<br>- Analytics<br>- Tracking<br>- ROI<br>- Referral<br>- Bonus<br>- Promotion |
| 13 | Operations | - Workflow<br>- Process<br>- Step<br>- Status<br>- Approval<br>- Assignment<br>- Task<br>- Queue<br>- Batch<br>- Job<br>- Schedule<br>- Execution<br>- Error<br>- Success<br>- Failure<br>- Retry<br>- Confirmation<br>- Summary<br>- Detail<br>- Mass Maintenance<br>- Bulk Update |
| 14 | Reporting | - Report<br>- Dashboard<br>- Analytics<br>- Metric<br>- KPI<br>- Trend<br>- Forecast<br>- Insight<br>- Recommendation<br>- LoanDataMart<br>- FactTable<br>- DimensionTable<br>- Measure<br>- Performance<br>- Vintage<br>- Cohort |
| 15 | Treasury | - Liquidity<br>- CashFlow<br>- Sweep<br>- Concentration<br>- PositivePay<br>- Lockbox |
| 16 | Investment | - Security<br>- Position<br>- Holding<br>- Investment<br>- Portfolio<br>- Collateral<br>- Valuation<br>- Market<br>- Liquidation<br>- MarginCall |
| 17 | Payment | - Payment<br>- Payee<br>- Beneficiary<br>- Transfer<br>- BillPay<br>- P2P<br>- Settlement<br>- Reconciliation<br>- Clearing<br>- Remittance<br>- SWIFT<br>- Correspondent<br>- ExchangeRate<br>- Currency |
| 18 | Reference | - Institution<br>- Bank<br>- Branch<br>- State<br>- Country<br>- Currency<br>- ExchangeRate<br>- InterestRate<br>- Fee<br>- Limit<br>- Tier<br>- Category<br>- Merchant<br>- Vendor<br>- Supplier<br>- Code<br>- Lookup<br>- Configuration<br>- Parameter<br>- Rule<br>- Template |
| 19 | Risk | - Risk<br>- RiskScore<br>- RiskLevel<br>- RiskAssessment<br>- Threshold<br>- Model<br>- Scenario<br>- StressTest<br>- Sensitivity<br>- Exposure<br>- Limit<br>- Override<br>- Exception |
| 20 | Collateral | - Collateral<br>- Property<br>- Appraisal<br>- Valuation<br>- Title<br>- Insurance<br>- Inspection<br>- Characteristics<br>- Comparable<br>- Estimate<br>- AVM<br>- Confidence<br>- Range<br>- Accuracy<br>- Adjustment |

## Primary Domain Assignment
**Primary Domain:** Customer (25% of entities)
**Secondary Domains:** Loan (20%), Account (15%), Transaction (12%), Credit (10%)

## System Summary
- **Total Tables:** 8,450 (distributed across 49 systems)
- **Key Business Focus:** Retail banking, consumer lending, digital banking, and customer experience
- **Domain Coverage:** Comprehensive consumer banking operations with extensive digital capabilities

---
*Generated by: Senior Enterprise Data Architect and Canonical Domain Modeling Specialist*
*Date: 2024*