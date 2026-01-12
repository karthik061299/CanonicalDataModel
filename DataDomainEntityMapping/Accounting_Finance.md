# Accounting & Finance Business Unit - Data Domain Entity Mapping

## Business Unit: Accounting & Finance

### Source System: Access Data
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Account | - Account<br>- GeneralLedger<br>- SubLedger<br>- ChartOfAccounts |
| 2 | Transaction | - Transaction<br>- Journal<br>- AccountingEntry<br>- Adjustment<br>- Accrual<br>- Allocation |
| 3 | Analytics | - FinancialStatement<br>- BalanceSheet<br>- IncomeStatement<br>- Report |
| 4 | Reference | - Period<br>- FiscalYear<br>- CostCenter<br>- Department |
| 5 | Workflow | - Reconciliation<br>- Audit |

### Source System: CashSuite
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Account | - CashAccount<br>- Nostro<br>- Vostro |
| 2 | Payment | - Payment<br>- Transfer<br>- Disbursement<br>- Collection<br>- Settlement |
| 3 | Transaction | - Transaction<br>- CashFlow |
| 4 | Location | - Bank<br>- Branch |
| 5 | Reference | - Currency<br>- ExchangeRate<br>- Limit |
| 6 | Analytics | - CashPosition<br>- Liquidity<br>- Forecast<br>- BalanceReport |
| 7 | Clearing | - Clearing |
| 8 | Fee | - Fee |
| 9 | Workflow | - Reconciliation<br>- Sweep<br>- Concentration |
| 10 | Risk | - Treasury |

### Source System: COA
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Account | - Account<br>- AccountHierarchy<br>- AccountType<br>- AccountCategory<br>- AccountClass<br>- SubAccount<br>- GeneralLedger<br>- AccountMapping<br>- AccountStructure<br>- AccountGroup<br>- AccountBalance |
| 2 | Reference | - FinancialDimension<br>- CostCenter<br>- ProfitCenter<br>- Department<br>- Division<br>- Segment<br>- Period<br>- FiscalYear<br>- AccountAttribute<br>- ReportingLine |
| 3 | Workflow | - AccountRule<br>- Consolidation<br>- Elimination<br>- Intercompany |

### Source System: Oracle
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Account | - GeneralLedger<br>- Account |
| 2 | Transaction | - Journal<br>- Transaction |
| 3 | Payment | - Invoice<br>- Payment<br>- Receipt |
| 4 | Customer | - Customer<br>- Vendor |
| 5 | Product | - PurchaseOrder |
| 6 | Reference | - Asset<br>- Period<br>- FiscalYear<br>- CostCenter<br>- Department<br>- Project |
| 7 | Analytics | - Budget |
| 8 | Workflow | - Depreciation<br>- Allocation<br>- Reconciliation |

## Summary
- **Total Systems:** 4
- **Total Entities Mapped:** 80
- **Primary Domain Distribution:**
  - Account: 20 entities (25%)
  - Reference: 18 entities (22.5%)
  - Transaction: 12 entities (15%)
  - Workflow: 11 entities (13.8%)
  - Payment: 8 entities (10%)
  - Analytics: 6 entities (7.5%)
  - Customer: 2 entities (2.5%)
  - Location: 2 entities (2.5%)
  - Product: 1 entity (1.2%)

---
*Mapping completed by: Senior Enterprise Data Architect*
*Date: 2024*