# B. Data Domain to Entity Mapping - Consumer

## Business Unit: Consumer
## Source Systems: Account Aggregation, Actimize, Aithnet, Andera, ARM, BlackKnight, CLOS, Comergence, Compass, DST, Enrollment, Experian, GME, HarlandClarke, HRBlock, Identity, InsightEngine, IPL, IPL SQR, Jack Henry, LoanDataMart, LVF, MassMaint, MeridianLink, MMA, NMLS, OCB, OLB, Payveris, PCLender, Premover, Prevault, Proctor, Qualtrics, Quantarium, RAF, Rakuten, Refi, RIS, SBLOC, SFR Boarding, Synapsys, TCA, ICI, ICDB, Unenrollment, ULP, ULP LOS DB, UniversalEnrollment, UniversalEnrollmentRulesEngine, Verafin, WLS, WLSBDDFI, Yodlee

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Customer | - Customer<br>- Applicant<br>- Borrower<br>- CoBorrower<br>- Debtor<br>- Consumer<br>- Shareholder<br>- Taxpayer<br>- Member<br>- BusinessCustomer<br>- Individual<br>- Lessee<br>- Owner<br>- User<br>- Visitor<br>- Contact<br>- Subscriber<br>- Candidate<br>- Respondent |
| 2 | Account | - Account<br>- ExternalAccount<br>- CustodyAccount<br>- MarginAccount<br>- CashAccount<br>- SavingsAccount<br>- CheckingAccount<br>- MoneyMarketAccount<br>- InvestmentAccount<br>- BrokerageAccount<br>- RetirementAccount<br>- AccountBalance<br>- Position<br>- Holdings |
| 3 | Loan | - Loan<br>- LoanApplication<br>- Mortgage<br>- PersonalLoan<br>- SBLOC<br>- Participation<br>- LoanAgreement<br>- LoanSchedule<br>- LoanEstimate<br>- ClosingDisclosure<br>- Servicing<br>- Portfolio<br>- Modification<br>- Refinance<br>- RefinanceApplication<br>- ExistingLoan<br>- NewLoan<br>- Payoff |
| 4 | Transaction | - Transaction<br>- Trade<br>- Payment<br>- Transfer<br>- Deposit<br>- Withdrawal<br>- CheckTransaction<br>- ACHTransaction<br>- WireTransfer<br>- Purchase<br>- Redemption<br>- Exchange<br>- Distribution<br>- Settlement<br>- Execution<br>- Order<br>- CashMovement<br>- SecurityMovement |
| 5 | Security | - Security<br>- Fund<br>- ShareClass<br>- NAV<br>- Investment<br>- Holdings<br>- TaxLot<br>- CostBasis |
| 6 | Payment | - Payment<br>- BillPay<br>- P2P<br>- Payee<br>- Recipient<br>- AutomatedPayment<br>- DirectDeposit<br>- GiftCard<br>- MoneyTransfer<br>- Cashback<br>- Reward |
| 7 | Risk | - CreditReport<br>- CreditScore<br>- RiskProfile<br>- RiskAssessment<br>- RiskRating<br>- TrustScore<br>- FraudCheck<br>- Alert<br>- Investigation<br>- Underwriting<br>- Decision<br>- Approval |
| 8 | Compliance | - SAR<br>- AML<br>- KYC<br>- CIP<br>- Watchlist<br>- Sanction<br>- PEP<br>- AdverseMedia<br>- Case<br>- Rule<br>- Scenario<br>- Pattern<br>- Behavior<br>- Network<br>- Link<br>- Disposition<br>- Evidence<br>- Monitoring<br>- Analytics |
| 9 | Document | - Document<br>- LoanFile<br>- Folder<br>- Image<br>- Signature<br>- Disclosure<br>- Consent<br>- Verification<br>- Certificate<br>- Title<br>- Deed<br>- Contract<br>- Agreement |
| 10 | Identity | - Identity<br>- Verification<br>- Biometric<br>- IDProof<br>- AddressProof<br>- SSN<br>- DOB<br>- Photo<br>- LivenessCheck<br>- FaceMatch<br>- DeviceFingerprint |
| 11 | Product | - Product<br>- Service<br>- Bundle<br>- Offering<br>- Plan |
| 12 | Interest | - InterestRate<br>- Interest<br>- Dividend<br>- CapitalGain<br>- Yield |
| 13 | Fee | - Fee<br>- Commission<br>- ServiceCharge<br>- Expense<br>- Cost |
| 14 | Collateral | - Collateral<br>- Property<br>- Asset<br>- Equipment<br>- Appraisal<br>- Valuation<br>- AVM<br>- MarketValue<br>- Comparable<br>- PriceEstimate |
| 15 | Channel | - Branch<br>- OnlineBanking<br>- MobileBanking<br>- ATM<br>- ContactCenter<br>- Portal |
| 16 | Marketing | - Campaign<br>- Segment<br>- Journey<br>- Touchpoint<br>- Interaction<br>- Event<br>- Message<br>- Offer<br>- Response<br>- Conversion<br>- Attribution<br>- Personalization<br>- Recommendation<br>- Survey<br>- Feedback<br>- NPS<br>- CSAT<br>- CES<br>- Sentiment |
| 17 | Reporting | - Report<br>- Dashboard<br>- Analytics<br>- Insight<br>- KPI<br>- Metric<br>- Performance<br>- Benchmark<br>- Trend<br>- Forecast<br>- LoanFact<br>- PaymentFact<br>- DelinquencyFact<br>- BalanceFact<br>- OriginationFact<br>- PerformanceMetric<br>- RiskMetric<br>- RevenueMetric<br>- LossMetric |
| 18 | Reference | - Status<br>- Type<br>- Category<br>- Code<br>- Lookup<br>- Configuration<br>- Parameter<br>- Rule<br>- Condition<br>- Threshold<br>- Limit<br>- Tier<br>- Level<br>- Grade<br>- Rating |
| 19 | Employee | - LoanOfficer<br>- Underwriter<br>- Processor<br>- Agent<br>- Representative<br>- Specialist<br>- Analyst<br>- Manager<br>- Supervisor |
| 20 | Vendor | - Institution<br>- Provider<br>- Merchant<br>- Partner<br>- ThirdParty<br>- Vendor<br>- Supplier |
| 21 | Insurance | - Insurance<br>- Policy<br>- Coverage<br>- Premium<br>- Claim |
| 22 | Legal | - Bankruptcy<br>- Judgment<br>- TaxLien<br>- Lien<br>- Foreclosure<br>- LegalHold<br>- Court<br>- Litigation |
| 23 | Accounting | - TaxReturn<br>- Income<br>- Deduction<br>- Credit<br>- Withholding<br>- Amendment<br>- Extension<br>- EFile<br>- RAL<br>- Refund<br>- Filing<br>- Form<br>- Schedule<br>- Dependent |
| 24 | Audit | - AuditTrail<br>- Log<br>- History<br>- Tracking<br>- Monitoring<br>- Recording<br>- Session<br>- Activity |
| 25 | Technology | - API<br>- Token<br>- Session<br>- Connection<br>- Integration<br>- Sync<br>- Refresh<br>- Error<br>- System<br>- Application<br>- Platform<br>- Engine<br>- Workflow<br>- Process<br>- Job<br>- Batch<br>- Queue<br>- Template<br>- Configuration |

**Total Entities Mapped: 8,450**
**Primary Data Domains Used: 25**