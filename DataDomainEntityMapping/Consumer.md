# Data Domain to Entity Mapping - Consumer Business Unit

## Source Systems Analysis

### Source System: Account Aggregation
**System Functionality:** Manages aggregation of external customer accounts for consolidated financial view.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Account | - ExternalAccount<br>- AccountBalance<br>- AccountType |
| 2 | Customer | - Customer |
| 3 | Reference | - Institution |
| 4 | Transaction | - Transaction |
| 5 | Technology | - Connection<br>- Credential<br>- Aggregation<br>- Refresh<br>- Status<br>- Provider<br>- API<br>- Token<br>- Session<br>- Error |
| 6 | Investment | - Holdings<br>- Investment |
| 7 | Loan | - Loan<br>- CreditCard<br>- Mortgage |
| 8 | Audit | - History<br>- Verification |
| 9 | Security | - Security |

### Source System: Actimize
**System Functionality:** Manages anti-money laundering detection