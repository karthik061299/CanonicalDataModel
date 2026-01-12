# Data Domain to Entity Mapping - Clearing Business Unit

## Source Systems Analysis

### Source System: Clearing
**System Functionality:** Manages securities clearing, settlement, and custody operations for broker-dealers and investment advisors.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Clearing | - Trade<br>- Settlement<br>- TradeConfirmation<br>- SettlementInstruction<br>- ClearingHouse<br>- ClearingMember<br>- TradeDate<br>- SettlementDate |
| 2 | Investment | - Security<br>- Position<br>- SecurityBalance<br>- CorporateAction<br>- Dividend<br>- Interest |
| 3 | Account | - Account<br>- CustodyAccount<br>- CashBalance |
| 4 | Transaction | - Transaction |
| 5 | Customer | - Customer<br>- BrokerDealer<br>- Counterparty |
| 6 | Fee | - Fee<br>- Commission |
| 7 | Credit | - MarginRequirement<br>- CollateralManagement |

### Source System: Cor Clearing
**System Functionality:** Manages correspondent clearing services, trade processing, and back-office operations for financial institutions.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Clearing | - Trade<br>- Settlement<br>- ClearingFirm<br>- TradeExecution<br>- TradeAllocation<br>- TradeConfirmation<br>- SettlementInstruction |
| 2 | Account | - Account<br>- CorrespondentAccount<br>- MarginAccount |
| 3 | Customer | - Customer |
| 4 | Investment | - Security<br>- Position<br>- CollateralPosition<br>- CorporateAction<br>- Dividend<br>- Interest |
| 5 | Transaction | - Transaction<br>- CashMovement<br>- SecurityMovement |
| 6 | Fee | - Fee<br>- Commission |
| 7 | Compliance | - RegulatoryReport |
| 8 | Audit | - AuditTrail<br>- ReconciliationRecord |

### Source System: DMClearing
**System Functionality:** Manages data mart for clearing analytics, reporting, and business intelligence operations.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Analytics | - TradeFact<br>- SettlementFact<br>- AccountDimension<br>- SecurityDimension<br>- TimeDimension<br>- CustomerDimension<br>- TransactionFact<br>- PositionSnapshot<br>- BalanceFact<br>- FeeFact<br>- CommissionFact<br>- ClearingMetrics<br>- PerformanceMetrics<br>- RiskMetrics<br>- ComplianceMetrics<br>- RevenueMetrics<br>- VolumeMetrics<br>- AggregatedTrade<br>- DailySettlement<br>- MonthlyPosition |

### Source System: Jack Henry
**System Functionality:** Manages core banking operations including deposits, loans, and customer accounts for clearing activities.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Customer | - Customer<br>- CustomerRelationship |
| 2 | Account | - Account<br>- AccountBalance |
| 3 | Transaction | - Transaction<br>- CheckTransaction<br>- ACHTransaction<br>- WireTransfer<br>- AutomatedPayment<br>- DirectDeposit<br>- StopPayment |
| 4 | Loan | - Loan<br>- Payment |
| 5 | Product | - Deposit<br>- Product<br>- Card |
| 6 | Reference | - Branch<br>- InterestRate |
| 7 | Fee | - Fee<br>- ServiceCharge<br>- OverdraftProtection |
| 8 | Channel | - OnlineBanking<br>- MobileBanking |
| 9 | Document | - Statement |
| 10 | Workflow | - AccountAlert |