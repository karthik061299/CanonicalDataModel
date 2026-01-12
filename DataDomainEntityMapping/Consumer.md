# Domain to Entity Mapping - Consumer Business Unit

## Source Systems Analysis

### Account Aggregation System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Account | - ExternalAccount<br>- AccountLink<br>- Balance<br>- AccountType<br>- BalanceHistory<br>- AccountOwner<br>- AccountStatus |
| 2 | Transaction | - Transaction<br>- TransactionCategory<br>- SyncStatus<br>- SyncLog |
| 3 | Vendor | - Institution<br>- DataProvider<br>- InstitutionMapping |
| 4 | Security | - AccountCredential |
| 5 | Operations | - AggregationSession<br>- AccountRefresh<br>- ConnectionStatus<br>- RefreshSchedule<br>- ErrorLog<br>- AccountMetadata<br>- DataFeed<br>- AccountVerification<br>- AggregationRule<br>- DataQuality |

### Actimize System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Compliance | - Alert<br>- Case<br>- SuspiciousActivity<br>- MonitoringRule<br>- WatchList<br>- PEPScreening<br>- SanctionsList<br>- TransactionPattern<br>- BehaviorProfile<br>- RiskIndicator<br>- CaseManagement<br>- AlertDisposition<br>- FalsePositive<br>- EscalationRule<br>- ComplianceReport<br>- AuditTrail<br>- CustomerDueDiligence<br>- TransactionMonitoring<br>- RegulatoryFiling |
| 2 | Customer | - Customer |
| 3 | Transaction | - Transaction |
| 4 | Risk | - RiskScore<br>- Scenario<br>- Investigation<br>- RiskRating |

### Aithnet System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Security | - User<br>- AuthenticationSession<br>- Credential<br>- AuthenticationMethod<br>- Token<br>- BiometricData<br>- DeviceRegistration<br>- AuthenticationLog<br>- SecurityPolicy<br>- AccessAttempt<br>- MultiFactorAuth<br>- PasswordPolicy<br>- SessionManagement<br>- IdentityVerification<br>- AuthenticationProvider<br>- TrustScore<br>- DeviceFingerprint<br>- RiskAssessment<br>- AuthenticationChallenge<br>- SecurityQuestion<br>- OTPGeneration<br>- AuthenticationRule<br>- AccessControl<br>- IdentityProofing<br>- AuthenticationEvent |

### Andera System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Customer | - Application<br>- Applicant<br>- JointOwner<br>- BeneficiaryInformation |
| 2 | Account | - Account<br>- AccountOpening<br>- AccountConfiguration |
| 3 | Document | - Document<br>- ElectronicSignature<br>- DisclosureDocument<br>- DocumentUpload |
| 4 | Operations | - ApplicationStatus<br>- ApplicationWorkflow<br>- ApplicationReview<br>- OnboardingStep<br>- ApplicationData |
| 5 | Product | - ProductSelection |
| 6 | Payment | - FundingSource<br>- FundingMethod |
| 7 | Compliance | - IdentityVerification<br>- ComplianceCheck<br>- CreditCheck<br>- CustomerConsent<br>- ApplicationDecision<br>- VerificationStatus |

### ARM System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Loan | - Mortgage<br>- RateAdjustment<br>- RateCap<br>- AdjustmentPeriod |
| 2 | Financial | - InterestRate<br>- Index<br>- Margin |
| 3 | Payment | - PaymentSchedule |

### BlackKnight System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Loan | - Loan<br>- LoanModification<br>- Foreclosure<br>- DefaultManagement<br>- PrincipalBalance<br>- InterestAccrual<br>- PaymentHistory<br>- LoanStatus<br>- ServicingTransfer |
| 2 | Customer | - Borrower |
| 3 | Payment | - Payment<br>- ServicingActivity |
| 4 | Account | - EscrowAccount |
| 5 | Property | - PropertyTax<br>- Insurance |

### CLOS System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Document | - ClosingPackage<br>- LoanDocument<br>- ClosingDisclosure<br>- TitleInsurance<br>- DocumentSigning<br>- PropertyDeed<br>- MortgageNote<br>- ClosingChecklist<br>- PostClosingAudit<br>- DocumentRecording |
| 2 | Operations | - Settlement<br>- ClosingAgent<br>- SigningAppointment<br>- FundsDisbursement<br>- RecordingInformation<br>- NotaryService<br>- FinalWalkthrough<br>- KeyDelivery<br>- ClosingStatus<br>- SettlementDate |
| 3 | Financial | - ClosingCost<br>- SettlementStatement<br>- WireInstruction |
| 4 | Account | - Escrow |
| 5 | Compliance | - ClosingCondition |

### Comergence System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Loan | - LoanApplication<br>- LoanProduct<br>- LoanEstimate<br>- LoanApproval<br>- LoanCommitment<br>- LoanSubmission |
| 2 | Customer | - Borrower<br>- LoanOfficer |
| 3 | Property | - Property<br>- Appraisal |
| 4 | Credit | - Underwriting<br>- CreditReport<br>- UnderwritingDecision |
| 5 | Financial | - LoanPricing<br>- RateLock |
| 6 | Operations | - ApplicationMilestone<br>- ApplicationStatus<br>- ApplicationWorkflow<br>- DocumentCollection<br>- QualityControl |
| 7 | Document | - Disclosure<br>- ClosingDisclosure |
| 8 | Compliance | - ComplianceCheck<br>- Condition |
| 9 | Reference | - IncomeVerification<br>- AssetVerification |

### Compass System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Channel | - Branch<br>- Location |
| 2 | Operations | - ServiceRequest |

### DST System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - DataTransfer<br>- TransferJob<br>- DataSource<br>- TargetSystem<br>- TransferLog<br>- DataMapping<br>- TransferSchedule<br>- DataValidation<br>- ErrorHandling<br>- TransferStatus<br>- DataPackage<br>- TransferProtocol<br>- DataFormat<br>- TransferHistory<br>- DataReconciliation<br>- TransferMetrics<br>- DataQuality<br>- TransferConfiguration |

### Enrollment System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Customer | - EnrollmentApplication<br>- Customer<br>- CustomerProfile<br>- CustomerPreference<br>- CustomerSegment |
| 2 | Product | - Product<br>- Service<br>- ProductSelection<br>- ProductConfiguration<br>- ProductBundle |
| 3 | Operations | - EnrollmentStatus<br>- EnrollmentDate<br>- EnrollmentChannel<br>- VerificationStep<br>- EnrollmentWorkflow<br>- ServiceActivation<br>- EnrollmentHistory<br>- ActivationDate<br>- EnrollmentSource<br>- EnrollmentCampaign<br>- EnrollmentMetrics |
| 4 | Document | - ServiceAgreement<br>- EnrollmentDocument<br>- CustomerConsent |
| 5 | Financial | - EnrollmentFee |

### Experian System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Credit | - CreditReport<br>- CreditScore<br>- CreditInquiry<br>- Tradeline<br>- PublicRecord<br>- Collection<br>- CreditBureau<br>- ConsumerIdentity<br>- CreditHistory<br>- PaymentHistory<br>- CreditUtilization<br>- Delinquency<br>- Bankruptcy<br>- Foreclosure<br>- CreditLimit<br>- AccountStatus<br>- CreditAlert<br>- DisputeRecord<br>- FraudAlert<br>- SecurityFreeze<br>- CreditMonitoring<br>- RiskScore<br>- IdentityVerification<br>- CreditAttribute<br>- ScoreFactors |

### GME System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Payment | - ExchangeTransaction<br>- ForeignExchange<br>- TransferRequest<br>- ExchangeOrder<br>- PaymentInstruction<br>- TransactionFee<br>- TransferStatus<br>- TransactionHistory |
| 2 | Customer | - Customer |
| 3 | Financial | - Currency<br>- ExchangeRate<br>- RateQuote<br>- SettlementAccount<br>- SpotRate<br>- ForwardContract<br>- HedgingInstrument<br>- CurrencyPair<br>- ExchangeMargin<br>- ExchangeLimit |
| 4 | Account | - BeneficiaryAccount |
| 5 | Vendor | - CounterpartyBank |
| 6 | Compliance | - ComplianceCheck<br>- RegulatoryReporting |
| 7 | Operations | - ExchangeContract<br>- ValueDate |

### HarlandClarke System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Product | - CheckOrder<br>- CheckDesign<br>- CheckSeries |
| 2 | Customer | - Customer |
| 3 | Operations | - OrderStatus<br>- OrderHistory |
| 4 | Communication | - ShippingAddress |
| 5 | Payment | - PaymentMethod |

### HRBlock System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Financial | - TaxReturn<br>- Taxpayer<br>- TaxForm<br>- Income<br>- Deduction<br>- TaxCredit<br>- RefundAccount<br>- FilingStatus<br>- TaxYear<br>- W2Form<br>- 1099Form<br>- TaxCalculation<br>- StateReturn<br>- FederalReturn<br>- TaxPayment<br>- RefundStatus<br>- Dependent<br>- AdjustedGrossIncome<br>- TaxLiability<br>- WithholdingAmount<br>- EstimatedTax<br>- TaxAmendment |
| 2 | Document | - TaxDocument |
| 3 | Operations | - AuditSupport<br>- TaxAdvice |

### Identity System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Security | - Identity<br>- IdentityDocument<br>- VerificationMethod<br>- BiometricData<br>- IdentityAttribute<br>- VerificationStatus<br>- IdentityProvider<br>- AuthenticationFactor<br>- IdentityProof<br>- KYCRecord<br>- IdentityCheck<br>- DocumentVerification<br>- LivenessCheck<br>- FaceRecognition<br>- IdentityScore<br>- VerificationHistory<br>- IdentityFraud<br>- IdentityTheft<br>- IdentityUpdate<br>- VerificationAttempt<br>- IdentityLink<br>- TrustedIdentity<br>- IdentityRisk<br>- VerificationRule |
| 2 | Customer | - Customer |

### InsightEngine System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Analytics | - CustomerInsight<br>- BehaviorPattern<br>- PredictiveModel<br>- AnalyticsMetric<br>- CustomerSegment<br>- PropensityScore<br>- ChurnPrediction<br>- LifetimeValue<br>- CustomerJourney<br>- Touchpoint<br>- EngagementScore<br>- ProductAffinity<br>- NextBestAction<br>- CampaignResponse<br>- CustomerProfile<br>- BehaviorScore<br>- RiskIndicator<br>- OpportunityScore<br>- CustomerPreference<br>- InteractionHistory<br>- ModelFeature<br>- PredictionOutcome<br>- SegmentationRule<br>- InsightReport<br>- AnalyticsWorkflow |

### IPL System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Transaction | - Transaction<br>- TransactionType<br>- TransactionStatus<br>- TransactionLog<br>- ProcessingQueue<br>- ClearingRecord<br>- ReconciliationEntry<br>- TransactionFee<br>- ProcessingError<br>- RetryLogic<br>- TransactionRoute<br>- TransactionLimit<br>- ProcessingMetrics |
| 2 | Account | - Account<br>- AccountBalance<br>- SettlementAccount |
| 3 | Customer | - Customer |
| 4 | Payment | - Payment<br>- PaymentMethod<br>- PaymentInstruction<br>- PaymentNetwork |
| 5 | Operations | - ProcessingRule<br>- SettlementBatch |

### IPL SQR System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Analytics | - Query<br>- Report<br>- ReportParameter<br>- QueryResult<br>- ReportDefinition<br>- ReportOutput<br>- ReportFormat<br>- ReportDistribution<br>- ReportMetadata<br>- ReportCache<br>- ReportHistory<br>- ReportSubscription<br>- ReportMetrics |
| 2 | Technology | - DataSource<br>- DataExtraction<br>- ReportSchedule<br>- QueryExecution<br>- DataFilter<br>- QueryTemplate<br>- DataAggregation<br>- DataTransformation<br>- DataValidation<br>- QueryLog<br>- QueryPerformance |

### Jack Henry System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Customer | - Customer |
| 2 | Account | - Account<br>- CheckingAccount<br>- SavingsAccount<br>- CertificateOfDeposit<br>- MoneyMarket |
| 3 | Transaction | - Transaction<br>- Deposit<br>- ACHTransaction<br>- WireTransfer<br>- CheckTransaction<br>- ATMTransaction |
| 4 | Loan | - Loan<br>- LoanApplication<br>- Collateral<br>- PaymentSchedule |
| 5 | Payment | - Payment |
| 6 | Channel | - Branch<br>- OnlineBanking<br>- MobileBanking |
| 7 | Product | - Product |
| 8 | Financial | - InterestRate<br>- Fee<br>- Card<br>- Statement |

### LoanDataMart System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Analytics | - LoanFact<br>- CustomerDimension<br>- ProductDimension<br>- DateDimension<br>- BranchDimension<br>- LoanBalance<br>- PaymentFact<br>- DelinquencyFact<br>- OriginationMetric<br>- PortfolioMetric<br>- PerformanceIndicator<br>- RiskMetric<br>- ProfitabilityMeasure<br>- LoanCharacteristic<br>- CustomerSegment<br>- ProductMix<br>- GeographyDimension<br>- TimeDimension<br>- LoanStatus<br>- AggregateBalance |

### LVF System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Loan | - LoanVerification<br>- LoanApproval |
| 2 | Operations | - FundingRequest<br>- VerificationCheck<br>- DisbursementInstruction<br>- FundingSource<br>- VerificationStatus<br>- FundingAccount<br>- VerificationDocument<br>- DisbursementSchedule<br>- FundingCondition<br>- VerificationResult<br>- FundingAuthorization<br>- VerificationRule<br>- DisbursementMethod<br>- FundingLimit<br>- VerificationLog<br>- FundingStatus<br>- VerificationException<br>- DisbursementConfirmation<br>- FundingReconciliation<br>- VerificationWorkflow<br>- FundingHistory<br>- VerificationMetrics<br>- DisbursementTracking |

### MassMaint System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Operations | - MaintenanceJob<br>- BatchUpdate<br>- DataRecord<br>- UpdateRule<br>- ProcessingBatch<br>- MaintenanceLog<br>- ValidationRule<br>- UpdateStatus<br>- ErrorRecord<br>- RollbackLog<br>- MaintenanceSchedule<br>- BatchConfiguration<br>- DataSelection<br>- UpdateCriteria<br>- ProcessingQueue<br>- MaintenanceHistory<br>- BatchMetrics<br>- DataBackup<br>- UpdateVerification<br>- MaintenanceApproval<br>- BatchExecution<br>- DataIntegrity<br>- UpdateAudit<br>- MaintenanceReport<br>- BatchReconciliation |

### MeridianLink System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Loan | - LoanApplication<br>- LoanProduct<br>- LoanApproval |
| 2 | Customer | - Applicant<br>- LoanOfficer |
| 3 | Credit | - CreditDecision<br>- CreditReport<br>- RiskAssessment<br>- CreditPolicy<br>- DecisionRules |
| 4 | Operations | - ApplicationWorkflow<br>- ApplicationStatus<br>- ApplicationReview<br>- ApplicationSubmission<br>- ApplicationMetrics |
| 5 | Document | - ApplicationDocument |
| 6 | Financial | - LoanPricing |
| 7 | Technology | - DecisionEngine |
| 8 | Reference | - IncomeVerification<br>- ApplicationData |

### MMA System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Account | - MoneyMarketAccount<br>- Balance<br>- BalanceHistory<br>- AccountOpening<br>- AccountClosure<br>- AccountMaintenance<br>- AccountRestriction |
| 2 | Customer | - Customer |
| 3 | Financial | - InterestRate<br>- InterestAccrual<br>- TierStructure<br>- RateSchedule<br>- InterestPayment<br>- AccountFee<br>- RateChange<br>- InterestCalculation<br>- RateIndex<br>- RateAdjustment |
| 4 | Transaction | - Transaction<br>- WithdrawalLimit<br>- TransactionLimit |
| 5 | Document | - AccountStatement |
| 6 | Reference | - MinimumBalance<br>- BalanceTier<br>- InterestPosting |

### NMLS System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Employee | - LoanOfficer |
| 2 | Compliance | - License<br>- LicenseStatus<br>- RegulatoryRequirement<br>- ComplianceRecord<br>- LicenseRenewal<br>- ContinuingEducation<br>- BackgroundCheck<br>- LicenseApplication<br>- StateRegistration<br>- LicenseExpiration<br>- ComplianceTraining<br>- DisciplinaryAction<br>- LicenseVerification<br>- RegistrationStatus<br>- ComplianceAudit<br>- LicenseHistory<br>- RegulatoryFiling<br>- LicenseTransfer<br>- ComplianceReport<br>- LicenseRevocation<br>- EducationCredit<br>- LicenseFee<br>- ComplianceMonitoring<br>- LicenseDocument |

### OCB System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Account | - BusinessAccount |
| 2 | Customer | - CommercialCustomer |
| 3 | Transaction | - Transaction |
| 4 | Payment | - Payment<br>- ACHBatch<br>- WireTransfer |
| 5 | Operations | - CashManagement<br>- AccountServices |

### OLB System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Channel | - OnlineUser<br>- LoginSession<br>- UserProfile<br>- SecuritySettings<br>- UserPreference<br>- SecurityQuestion<br>- DeviceRegistration<br>- NotificationPreference<br>- UserAuthentication |
| 2 | Account | - Account<br>- ExternalAccount<br>- AccountSummary |
| 3 | Transaction | - Transaction<br>- TransactionHistory |
| 4 | Payment | - BillPayment<br>- Transfer<br>- Payee<br>- ScheduledPayment<br>- BillPaySchedule<br>- QuickTransfer<br>- TransferLimit<br>- PaymentConfirmation |
| 5 | Communication | - AccountAlert |
| 6 | Document | - eStatement |
| 7 | Audit | - ActivityLog |

### Payveris System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Payment | - Payment<br>- PaymentMethod<br>- PaymentStatus |
| 2 | Customer | - Sender<br>- Recipient |

### PCLender System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Loan | - Loan<br>- LoanApplication<br>- LoanProduct<br>- LoanBalance<br>- LoanStatus<br>- LoanModification<br>- LoanServicing<br>- PrincipalBalance<br>- InterestAccrual<br>- LoanOrigination<br>- UnderwritingDecision<br>- LoanDisbursement<br>- PayoffQuote<br>- LoanRefinance<br>- DefaultManagement |
| 2 | Customer | - Borrower |
| 3 | Payment | - Payment<br>- PaymentSchedule<br>- PaymentHistory<br>- LateCharge |
| 4 | Property | - Collateral |
| 5 | Credit | - CreditScore |
| 6 | Financial | - InterestRate<br>- LoanFee |
| 7 | Risk | - Delinquency |

### Premover System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Customer | - CustomerMove<br>- AddressChange |

### Prevault System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Document | - CheckImage<br>- ImageQuality<br>- ImageArchive<br>- ImageEnhancement |
| 2 | Transaction | - DepositItem<br>- CheckCapture<br>- ItemProcessing<br>- DepositBatch<br>- MICRData<br>- ItemValidation<br>- CheckAmount<br>- ProcessingStatus<br>- ItemException<br>- ItemAdjustment<br>- ItemReturn<br>- DepositVerification<br>- ItemSorting<br>- DepositPosting<br>- ItemReconciliation<br>- ProcessingLog |
| 3 | Account | - DepositAccount |
| 4 | Operations | - DepositReceipt<br>- CaptureDevice<br>- ProcessingBatch<br>- CaptureMetrics<br>- ItemReconciliation |

### Proctor System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Operations | - Exam<br>- TestTaker<br>- ProctorSession<br>- TestSchedule<br>- ExamResult<br>- ProctorLog<br>- TestQuestion<br>- ExamAttempt<br>- ProctorAlert<br>- TestScore<br>- ExamSecurity<br>- ProctorObservation<br>- TestEnvironment<br>- ExamIncident<br>- ProctorReport<br>- TestCompletion<br>- ExamViolation<br>- ProctorVerification<br>- TestRecording |

### Qualtrics System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Marketing | - Survey<br>- Response<br>- Question<br>- Respondent<br>- SurveyDistribution<br>- FeedbackScore<br>- SurveyResult |

### Quantarium System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Property | - PropertyValuation<br>- Property<br>- ValuationModel<br>- MarketData |

### RAF System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Risk | - RiskScore<br>- RiskFactor<br>- RiskAssessment<br>- RiskCategory<br>- RiskModel<br>- RiskAdjustment<br>- RiskMetric<br>- RiskProfile<br>- RiskCalculation<br>- RiskIndicator<br>- RiskWeight<br>- RiskParameter |

### Rakuten System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Marketing | - Reward<br>- Cashback<br>- Offer<br>- RewardRedemption<br>- LoyaltyProgram |
| 2 | Customer | - Customer |
| 3 | Transaction | - Transaction |
| 4 | Vendor | - Merchant |

### Refi System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Loan | - RefinanceApplication<br>- ExistingLoan<br>- NewLoan<br>- RefinanceApproval<br>- RefinanceType<br>- LoanPayoff<br>- LoanComparison |
| 2 | Customer | - Borrower |
| 3 | Property | - Property<br>- Appraisal<br>- EquityPosition<br>- LoanToValue |
| 4 | Financial | - RateComparison<br>- RefinanceAnalysis<br>- CostBenefit<br>- LoanTerms<br>- ClosingCost<br>- RateLock<br>- RefinanceSavings |
| 5 | Operations | - ApplicationStatus<br>- UnderwritingReview<br>- FundingDate |
| 6 | Credit | - CreditCheck |
| 7 | Document | - RefinanceDisclosure |
| 8 | Reference | - RefinanceReason |

### RIS System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Investment | - InvestmentAccount<br>- Security<br>- Trade<br>- Position<br>- Order<br>- Portfolio<br>- MarketData<br>- AssetAllocation<br>- TradeExecution<br>- SecurityHolding<br>- DividendPayment<br>- CapitalGain<br>- TradingFee<br>- OrderStatus<br>- TradeConfirmation<br>- MarginAccount<br>- InvestmentStrategy |
| 2 | Customer | - Customer |
| 3 | Transaction | - Transaction |
| 4 | Account | - AccountBalance<br>- CashBalance |
| 5 | Document | - AccountStatement |
| 6 | Analytics | - PortfolioPerformance |
| 7 | Reference | - InvestmentGoal<br>- RiskTolerance |

### SBLOC System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Loan | - CreditLine<br>- LoanBalance |
| 2 | Investment | - Collateral<br>- SecurityPosition<br>- CollateralValuation<br>-