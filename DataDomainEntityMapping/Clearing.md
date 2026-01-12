# Domain to Entity Mapping - Clearing Business Unit

## Source Systems Analysis

### Clearing System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Transaction | - Trade<br>- Settlement<br>- TradeConfirmation<br>- SettlementInstruction<br>- CashMovement<br>- SecurityMovement<br>- NetSettlement<br>- DVPInstruction<br>- SettlementCycle |
| 2 | Investment | - Security<br>- Position<br>- CorporateAction<br>- Dividend<br>- Interest |
| 3 | Account | - Account |
| 4 | Customer | - Client<br>- BrokerDealer<br>- Custodian<br>- ClearingMember |
| 5 | Risk | - Margin<br>- Collateral<br>- RiskExposure |
| 6 | Operations | - FailedTrade<br>- Reconciliation |
| 7 | Financial | - ClearingFee |

### Cor Clearing System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Transaction | - TradeExecution<br>- TradeCapture<br>- Allocation<br>- Affirmation<br>- SettlementDate<br>- TradeNovation<br>- PaymentVersusPayment<br>- DeliveryVersusPayment<br>- FreeOfPayment<br>- SettlementStatus |
| 2 | Account | - ClearingAccount |
| 3 | Customer | - Participant<br>- CentralCounterparty |
| 4 | Investment | - SecurityMaster |
| 5 | Risk | - MarginCall<br>- CollateralPosting<br>- MarkToMarket<br>- VariationMargin<br>- InitialMargin<br>- RiskParameter |
| 6 | Financial | - ClearingHouse<br>- DefaultFund<br>- GuaranteeFund<br>- ClearingFund<br>- SettlementBank |

### DMClearing System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Transaction | - TradeMatch<br>- TradeDate<br>- SettlementDate<br>- TradeValue<br>- TradeAmendment<br>- TradeCancellation<br>- TradeBreak<br>- TradeCorrection<br>- TradeStatus<br>- ClearingStatus<br>- SettlementMethod |
| 2 | Customer | - Counterparty |
| 3 | Investment | - Instrument<br>- Quantity<br>- Price |
| 4 | Financial | - Commission<br>- Fee<br>- SettlementCurrency<br>- ExchangeRate |
| 5 | Operations | - TradingVenue<br>- MarketSegment<br>- OrderBook<br>- ExecutionReport |

### Jack Henry System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Account | - Account<br>- AccountBalance |
| 2 | Customer | - Customer |
| 3 | Transaction | - Transaction<br>- Deposit<br>- Withdrawal<br>- Transfer<br>- Check<br>- ACHTransaction<br>- WireTransfer<br>- CardTransaction<br>- TransactionHistory |
| 4 | Payment | - InterestCalculation<br>- Fee<br>- ServiceCharge |
| 5 | Operations | - OverdraftProtection<br>- StopPayment<br>- HoldFunds<br>- DailyProcessing<br>- EndOfDay<br>- Reconciliation<br>- ComplianceCheck |
| 6 | Financial | - GLPosting |
| 7 | Document | - AccountStatement |
| 8 | Audit | - AuditTrail |

**Business Unit Summary:**
- **Total Systems:** 4
- **Total Entities Mapped:** 75
- **Total Tables:** 4,869
- **Primary Domains:** Transaction (40%), Investment (15%), Customer (12%), Risk (11%), Financial (11%), Operations (8%), Account (3%)