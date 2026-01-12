# Domain to Entity Mapping - Accounting & Finance Business Unit

## Source Systems Analysis

### Access Data System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Analytics | - Report<br>- Query<br>- Dashboard<br>- Metric<br>- DataModel |
| 2 | Technology | - DataSource<br>- DataExtract<br>- DataMapping<br>- Transformation<br>- Connection |
| 3 | Security | - User<br>- AccessControl |
| 4 | Operations | - Schedule<br>- Export<br>- Filter |
| 5 | Audit | - Audit |
| 6 | Reference | - Metadata<br>- Dimension<br>- Fact<br>- DataQuality |

### CashSuite System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Account | - CashAccount<br>- BankAccount<br>- CashPosition |
| 2 | Transaction | - CashTransaction<br>- FundTransfer<br>- FXTransaction<br>- SettlementInstruction<br>- PaymentOrder |
| 3 | Financial | - Liquidity<br>- CashFlow<br>- CashForecast<br>- InterestAccrual<br>- LiquidityRatio |
| 4 | Operations | - TreasuryOperation<br>- Reconciliation<br>- CashPooling<br>- CashConcentration |
| 5 | Investment | - InvestmentSecurity<br>- MoneyMarket<br>- HedgingInstrument |
| 6 | Credit | - Overdraft<br>- CreditLine<br>- CounterpartyExposure |
| 7 | Risk | - CollateralManagement |
| 8 | Payment | - Sweep |

### COA (Chart of Accounts) System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Financial | - Account<br>- AccountHierarchy<br>- AccountType<br>- GeneralLedger<br>- SubLedger<br>- AccountSegment<br>- FinancialStatement<br>- StatementLine<br>- IntercompanyAccount<br>- EliminationEntry<br>- CurrencyAccount |
| 2 | Operations | - CostCenter<br>- ProfitCenter<br>- Department<br>- Division<br>- BusinessUnit<br>- AccountCategory<br>- AccountGroup<br>- ConsolidationRule |
| 3 | Reference | - AccountMapping<br>- AccountAttribute<br>- AccountStatus<br>- AccountOwner<br>- ValidityPeriod |

### Oracle System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Financial | - GeneralLedger<br>- JournalEntry<br>- AccountsPayable<br>- AccountsReceivable<br>- Invoice<br>- FixedAsset<br>- Depreciation<br>- Budget<br>- Forecast<br>- FinancialPeriod<br>- CostAllocation<br>- Revenue<br>- Expense<br>- TaxCode<br>- BankAccount |
| 2 | Payment | - Payment |
| 3 | Vendor | - Vendor |
| 4 | Customer | - Customer |
| 5 | Operations | - Project<br>- Contract |

**Business Unit Summary:**
- **Total Systems:** 4
- **Total Entities Mapped:** 86
- **Total Tables:** 86
- **Primary Domains:** Financial (47%), Operations (19%), Technology (9%), Analytics (6%), Reference (6%), Others (13%)