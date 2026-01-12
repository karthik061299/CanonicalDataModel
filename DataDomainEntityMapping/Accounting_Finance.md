# Data Domain to Entity Mapping - Accounting & Finance Business Unit

## Source Systems Analysis

### Source System: Access Data
**System Functionality:** Manages ad-hoc financial data queries and reporting for accounting operations.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Account | - Account |
| 2 | Transaction | - Transaction |
| 3 | Accounting | - JournalEntry<br>- GeneralLedger<br>- SubLedger<br>- FinancialStatement<br>- BalanceSheet<br>- IncomeStatement<br>- CashFlow<br>- Budget<br>- Forecast<br>- ChartOfAccounts<br>- AccountingPeriod<br>- FiscalYear |
| 4 | Reference | - CostCenter<br>- Department |
| 5 | Analytics | - Report<br>- Query |
| 6 | Technology | - DataSource<br>- User |

### Source System: CashSuite
**System Functionality:** Manages cash operations, liquidity management, and treasury functions for financial institution.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Account | - CashAccount<br>- CashBalance |
| 2 | Transaction | - CashTransaction<br>- Deposit<br>- Withdrawal<br>- Transfer<br>- TellerTransaction<br>- VaultTransaction |
| 3 | Channel | - Vault<br>- ATM<br>- Branch |
| 4 | Reference | - Currency<br>- Denomination<br>- CashLimit<br>- CashReserve |
| 5 | Accounting | - CashPosition<br>- CashForecast<br>- Reconciliation<br>- LiquidityPosition |
| 6 | Workflow | - CashOrder<br>- CashDelivery<br>- CashierSession<br>- CashManagement |
| 7 | Analytics | - CashReport |
| 8 | Audit | - AuditTrail |

### Source System: COA
**System Functionality:** Manages chart of accounts structure and account hierarchies for financial reporting.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Account | - Account<br>- AccountType<br>- AccountCategory<br>- AccountHierarchy<br>- AccountGroup<br>- SubAccount<br>- AccountSegment<br>- AccountAttribute<br>- AccountBalance<br>- AccountPeriod<br>- AccountStatus<br>- AccountOwner<br>- AccountDescription |
| 2 | Accounting | - GeneralLedger<br>- AccountMapping<br>- FiscalYear |
| 3 | Reference | - CostCenter<br>- ProfitCenter<br>- BusinessUnit<br>- Department<br>- ReportingLine<br>- ConsolidationRule<br>- AccountVersion |
| 4 | Workflow | - AccountRule<br>- AccountValidation |

### Source System: Oracle
**System Functionality:** Manages enterprise financial accounting, reporting, and general ledger operations.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Accounting | - GeneralLedger<br>- JournalEntry<br>- SubLedger<br>- FinancialPeriod<br>- FiscalYear<br>- Budget<br>- BalanceSheet<br>- IncomeStatement<br>- CashFlow |
| 2 | Account | - Account |
| 3 | Transaction | - Transaction<br>- Payment |
| 4 | Vendor | - Vendor<br>- Invoice<br>- Payable |
| 5 | Customer | - Customer<br>- Receivable |
| 6 | Reference | - Asset<br>- Liability<br>- Equity |