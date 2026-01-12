# Canonical Data Domains

This document defines the enterprise-wide canonical data domains that are mutually exclusive and collectively exhaustive across all business units.

| Serial Number | Data Domain Name | Definition |
|--------------|------------------|------------|
| 1 | Customer | Encompasses all data related to individual and corporate customers, including demographics, identification, relationships, households, and customer hierarchies. This domain represents the core customer master data across retail, commercial, and institutional segments. |
| 2 | Account | Contains data on all financial accounts including deposit accounts, investment accounts, custody accounts, and their associated balances, statuses, and account-level attributes. This domain manages the relationship between customers and their financial holdings. |
| 3 | Loan | Manages all lending-related data including loan applications, originations, terms, schedules, collateral, and servicing information across consumer, commercial, and mortgage lending products. This domain tracks the complete loan lifecycle from application through payoff. |
| 4 | Transaction | Captures all financial transaction data including payments, transfers, deposits, withdrawals, trades, and settlements. This domain records the movement of funds and securities across accounts and systems with full audit trail and reconciliation capabilities. |
| 5 | Product | Defines all financial products and services offered including deposit products, loan products, investment products, cards, and service packages. This domain maintains product catalogs, features, pricing structures, and eligibility rules across all business lines. |
| 6 | Party | Represents all parties involved in financial relationships including borrowers, co-borrowers, guarantors, beneficiaries, trustees, and authorized signers. This domain manages party roles, relationships, and their connections to accounts and transactions. |
| 7 | Collateral | Contains data on all assets pledged as security for loans including real estate, vehicles, securities, equipment, and other tangible/intangible assets. This domain tracks collateral valuations, appraisals, lien positions, and insurance requirements. |
| 8 | Payment | Manages payment processing data including payment methods, schedules, instructions, beneficiaries, and payment status across all payment types (ACH, wire, check, card, P2P). This domain handles both inbound and outbound payment flows. |
| 9 | Credit | Encompasses credit-related data including credit scores, credit reports, credit decisions, credit limits, and credit risk assessments. This domain integrates with credit bureaus and manages creditworthiness evaluation across all lending products. |
| 10 | Document | Manages all business documents including loan documents, legal agreements, disclosures, statements, notices, and correspondence. This domain handles document generation, storage, retrieval, versioning, and retention policies. |
| 11 | Compliance | Contains regulatory compliance data including KYC/AML checks, sanctions screening, suspicious activity reports (SAR), currency transaction reports (CTR), and regulatory filings. This domain ensures adherence to banking regulations and reporting requirements. |
| 12 | Risk | Manages risk assessment and management data including risk scores, risk ratings, risk models, stress tests, and risk mitigation strategies. This domain covers credit risk, operational risk, market risk, and fraud risk across the enterprise. |
| 13 | Fraud | Contains fraud detection and prevention data including fraud alerts, fraud cases, fraud patterns, investigation records, and fraud rules. This domain manages anti-fraud operations across all channels and transaction types. |
| 14 | Employee | Encompasses human resources data including employee records, positions, compensation, benefits, performance reviews, and organizational structure. This domain manages workforce information and HR operations. |
| 15 | Channel | Manages customer interaction channels including online banking, mobile banking, branch, ATM, call center, and third-party channels. This domain tracks channel usage, preferences, and channel-specific configurations. |
| 16 | Marketing | Contains marketing campaign data including campaigns, offers, segments, customer journeys, responses, and attribution. This domain manages marketing operations, customer engagement, and campaign performance analytics. |
| 17 | Clearing & Settlement | Manages securities clearing, settlement, and custody operations including trades, clearing instructions, settlement cycles, and custody positions. This domain handles broker-dealer operations and investment services. |
| 18 | Treasury | Contains treasury and cash management data including liquidity positions, cash forecasts, vault operations, and treasury services. This domain manages institutional cash operations and treasury functions. |
| 19 | Legal | Encompasses legal matter data including cases, litigation, contracts, agreements, court filings, and legal spend. This domain manages legal operations, outside counsel coordination, and legal risk. |
| 20 | Reference Data | Contains master reference data including codes, rates, fees, limits, calendars, holidays, and configuration parameters. This domain provides standardized reference values used across all systems and business processes. |
| 21 | Analytics & Reporting | Manages analytical data including data marts, metrics, KPIs, reports, dashboards, and business intelligence assets. This domain supports decision-making through data aggregation, analysis, and visualization. |
| 22 | Technology Infrastructure | Contains IT infrastructure data including systems, applications, servers, databases, integrations, and technical configurations. This domain manages the technology landscape and system architecture. |
| 23 | Identity & Access | Manages identity, authentication, and authorization data including users, credentials, roles, permissions, and access policies. This domain ensures secure access control across all systems and channels. |
| 24 | Workflow & Process | Contains business process and workflow data including process definitions, tasks, approvals, routing rules, and process execution logs. This domain manages operational workflows and business process automation. |
| 25 | Third Party | Manages third-party relationship data including vendors, suppliers, service providers, partners, and their associated contracts, performance metrics, and compliance records. This domain handles external party management and vendor risk. |

---

**Total Domains Defined:** 25

**Coverage:** These domains collectively cover all business units including Consumer, Commercial, Clearing, Compliance, Credit, Marketing, HR, Legal, COE (Center of Excellence), AAS (Asset-Based Lending), Accounting & Finance, and OCEO (Office of the CEO).

**Principles:**
- **Mutually Exclusive:** Each domain has clear boundaries with no overlap
- **Collectively Exhaustive:** All business entities map to at least one primary domain
- **System Agnostic:** Definitions are independent of specific technology implementations
- **Business Aligned:** Domains reflect business capabilities and organizational structure
- **Scalable:** Framework supports future business growth and new products/services

---
*Generated by: Senior Enterprise Data Architect and Canonical Domain Modeling Specialist*