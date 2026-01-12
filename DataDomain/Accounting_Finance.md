# Business Unit: Accounting & Finance

## Source System Analysis

| Business Unit | Source System Name | System Functionality | Top 20-25 Key Entity Names | Total Number of Tables |
|--------------|-------------------|---------------------|---------------------------|----------------------|
| Accounting & Finance | Access Data | Data access and reporting tool for financial data extraction and analysis. | <ul><li>Report</li><li>Query</li><li>DataSource</li><li>User</li><li>Permission</li><li>AccessLog</li></ul> | 6 |
| Accounting & Finance | CashSuite | Cash management system for liquidity, payments, and treasury operations management. | <ul><li>CashAccount</li><li>Payment</li><li>Transaction</li><li>LiquidityPool</li><li>CashPosition</li><li>Forecast</li><li>Reconciliation</li><li>BankAccount</li><li>Transfer</li><li>Settlement</li><li>CashFlow</li><li>Treasury</li><li>InvestmentVehicle</li><li>InterestRate</li><li>Fee</li><li>Counterparty</li><li>PaymentMethod</li><li>Currency</li><li>ExchangeRate</li><li>CashReserve</li></ul> | 37 |
| Accounting & Finance | COA | Chart of accounts system managing general ledger structure and account hierarchies. | <ul><li>Account</li><li>AccountType</li><li>AccountHierarchy</li><li>GeneralLedger</li><li>SubLedger</li><li>CostCenter</li><li>Department</li><li>BusinessUnit</li><li>AccountCategory</li><li>AccountGroup</li><li>FinancialStatement</li><li>BalanceSheet</li><li>IncomeStatement</li><li>JournalEntry</li><li>AccountMapping</li><li>Segment</li><li>Dimension</li><li>AccountAttribute</li><li>AccountStatus</li><li>FiscalPeriod</li></ul> | 38 |
| Accounting & Finance | Oracle | Enterprise resource planning system for financial accounting and reporting operations. | <ul><li>GeneralLedger</li><li>AccountsPayable</li><li>AccountsReceivable</li><li>FixedAsset</li><li>Budget</li></ul> | 5 |

### System Functionality Reasoning
- **Access Data**: Small table count suggests a data access/reporting utility for financial data extraction
- **CashSuite**: Core treasury and cash management system based on business unit alignment
- **COA**: Chart of Accounts system managing the general ledger structure
- **Oracle**: Enterprise ERP system for comprehensive financial management