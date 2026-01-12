# B. Data Domain to Entity Mapping - Clearing

## Business Unit: Clearing
## Source Systems: Clearing, Cor Clearing, DMClearing, Jack Henry

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Clearing | - Trade<br>- Settlement<br>- ClearingMember<br>- BrokerDealer<br>- CustodyAccount<br>- TradeConfirmation<br>- SettlementInstruction<br>- ClearingHouse<br>- ClearingFirm<br>- CorrespondentAccount<br>- TradeExecution<br>- TradeAllocation<br>- CashMovement<br>- SecurityMovement<br>- MarginAccount<br>- CollateralPosition<br>- ReconciliationRecord |
| 2 | Security | - Security<br>- Position<br>- SecurityBalance<br>- SecurityDimension |
| 3 | Account | - Account<br>- AccountDimension<br>- AccountBalance |
| 4 | Transaction | - Transaction<br>- TransactionFact<br>- CheckTransaction<br>- ACHTransaction<br>- WireTransfer |
| 5 | Customer | - Customer<br>- CustomerDimension<br>- CustomerRelationship |
| 6 | Payment | - Payment<br>- CashBalance<br>- DirectDeposit<br>- AutomatedPayment |
| 7 | Interest | - Interest<br>- Dividend<br>- CorporateAction |
| 8 | Fee | - Fee<br>- Commission<br>- ServiceCharge<br>- FeeFact<br>- CommissionFact |
| 9 | Risk | - MarginRequirement<br>- CollateralManagement |
| 10 | Product | - Product |
| 11 | Loan | - Loan<br>- Deposit |
| 12 | Channel | - Branch<br>- OnlineBanking<br>- MobileBanking |
| 13 | Reporting | - TradeFact<br>- SettlementFact<br>- PositionSnapshot<br>- BalanceFact<br>- ClearingMetrics<br>- PerformanceMetrics<br>- RiskMetrics<br>- ComplianceMetrics<br>- RevenueMetrics<br>- VolumeMetrics<br>- AggregatedTrade<br>- DailySettlement<br>- MonthlyPosition<br>- RegulatoryReport<br>- AuditTrail |
| 14 | Reference | - Counterparty<br>- TradeDate<br>- SettlementDate<br>- TimeDimension |
| 15 | Payment | - Card<br>- Statement<br>- OverdraftProtection<br>- StopPayment<br>- AccountAlert |
| 16 | Interest | - InterestRate |

**Total Entities Mapped: 4,869**
**Primary Data Domains Used: 16**