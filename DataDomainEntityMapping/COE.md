# Data Domain to Entity Mapping - COE Business Unit

## Source Systems Analysis

### Source System: AD
**System Functionality:** Manages Active Directory user authentication, authorization, and identity management services.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Security | - User<br>- Group<br>- SecurityGroup<br>- UserAccount<br>- Permission<br>- Role<br>- Policy<br>- Authentication<br>- AccessControl |
| 2 | Reference | - OrganizationalUnit<br>- Domain<br>- Computer<br>- Directory |

### Source System: AdminPortal
**System Functionality:** Manages administrative portal for system configuration, user management, and operational controls.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Security | - Administrator<br>- User<br>- Role<br>- Permission<br>- AccessControl<br>- SecurityPolicy |
| 2 | Technology | - Configuration<br>- SystemSetting<br>- ApplicationAccess |
| 3 | Audit | - AuditLog<br>- Session |
| 4 | Analytics | - Dashboard<br>- Report |
| 5 | Workflow | - UserProfile<br>- Notification |

### Source System: ADO
**System Functionality:** Manages Azure DevOps for software development, version control, and project management.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - Project<br>- Repository<br>- Branch<br>- Commit<br>- PullRequest<br>- Build<br>- Release<br>- Pipeline<br>- Artifact<br>- Deployment |
| 2 | Workflow | - WorkItem<br>- Sprint<br>- Task<br>- UserStory<br>- Epic<br>- TestCase<br>- Bug |
| 3 | Employee | - Team<br>- Developer |
| 4 | Audit | - CodeReview |

### Source System: Archive
**System Functionality:** Manages enterprise data archival, retention, and historical data storage operations.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Document | - ArchivedRecord<br>- Document<br>- ArchiveLocation<br>- ArchiveIndex<br>- Metadata<br>- ArchiveStatus<br>- BackupSet<br>- HistoricalData |
| 2 | Compliance | - RetentionPolicy<br>- RetentionSchedule<br>- ComplianceRule<br>- LegalHold<br>- ArchivePolicy<br>- DataRetention |
| 3 | Technology | - DataSource<br>- StorageMedia<br>- StorageQuota |
| 4 | Workflow | - ArchiveJob<br>- ArchiveRequest<br>- RetrievalRequest<br>- DataLifecycle<br>- DispositionRule |
| 5 | Reference | - DataClassification |
| 6 | Audit | - ArchiveLog<br>- ArchiveAudit |

### Source System: DataMart
**System Functionality:** Manages departmental data marts for analytics, reporting, and business intelligence.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Analytics | - FactTable<br>- DimensionTable<br>- Measure<br>- Metric<br>- TimeDimension<br>- CustomerDimension<br>- ProductDimension<br>- GeographyDimension<br>- AggregatedData<br>- SummaryTable<br>- Report<br>- Dashboard<br>- KPI<br>- DataModel<br>- AnalyticsView<br>- BusinessMetrics<br>- PerformanceIndicator |
| 2 | Technology | - ETLProcess<br>- DataSource<br>- DataRefresh |

### Source System: Decisions
**System Functionality:** Manages business rules engine and automated decision-making workflows.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Workflow | - DecisionRule<br>- BusinessRule<br>- RuleSet<br>- Condition<br>- Action<br>- DecisionTable<br>- Workflow<br>- RuleExecution<br>- DecisionLog<br>- RuleVersion<br>- Parameter<br>- Expression<br>- RuleCategory<br>- DecisionOutcome<br>- RuleValidation<br>- RulePriority<br>- DecisionContext<br>- RuleEngine |
| 2 | Compliance | - PolicyRule<br>- ComplianceRule |

### Source System: DocuSign
**System Functionality:** Manages electronic signature, document workflow, and digital agreement processes.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Document | - Document<br>- Envelope<br>- Template<br>- Agreement<br>- Field<br>- Tab<br>- CustomField |
| 2 | Workflow | - Workflow<br>- Signer<br>- Recipient<br>- SigningSession<br>- Status<br>- Notification |
| 3 | Security | - Signature<br>- Authentication<br>- Certificate |
| 4 | Audit | - AuditTrail |
| 5 | Reference | - Brand<br>- Account<br>- User |

### Source System: DWSupport
**System Functionality:** Manages data warehouse support operations, ETL monitoring, and data quality management.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - ETLJob<br>- DataLoad<br>- JobSchedule<br>- DataSource<br>- TargetTable<br>- Transformation<br>- DataLineage<br>- JobExecution<br>- PerformanceMetrics<br>- JobDependency<br>- DataRefresh<br>- SystemHealth<br>- Metadata |
| 2 | Workflow | - DataQualityRule<br>- DataValidation<br>- DataIssue<br>- Resolution<br>- SupportTicket<br>- Monitoring<br>- Alert<br>- ChangeRequest |
| 3 | Audit | - ErrorLog<br>- ReconciliationReport<br>- FailureAnalysis<br>- AuditLog |

### Source System: EnterpriseBI
**System Functionality:** Manages enterprise business intelligence platform for reporting, analytics, and data visualization.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Analytics | - Report<br>- Dashboard<br>- Dataset<br>- DataSource<br>- Visualization<br>- Metric<br>- KPI<br>- DataModel<br>- Calculation<br>- Filter<br>- Bookmark<br>- Theme<br>- ReportHistory<br>- ExportFormat<br>- AlertRule<br>- DataRefresh |
| 2 | Security | - User<br>- Permission |
| 3 | Technology | - Workspace<br>- Gateway<br>- Tenant<br>- License |
| 4 | Workflow | - Subscription<br>- Schedule<br>- ReportParameter |

### Source System: ETL
**System Functionality:** Manages extract, transform, and load processes for data integration and warehousing.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - ETLPackage<br>- DataFlow<br>- SourceConnection<br>- TargetConnection<br>- Transformation<br>- DataMapping<br>- JobSchedule<br>- ExecutionLog<br>- ErrorHandling<br>- DataValidation<br>- LookupTable<br>- StagingTable<br>- ControlTable<br>- Parameter<br>- Variable<br>- Configuration<br>- JobDependency<br>- DataLineage<br>- PerformanceMetrics |
| 2 | Audit | - AuditTrail |

### Source System: Evo
**System Functionality:** Manages evolution and change management for enterprise systems and applications.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Workflow | - ChangeRequest<br>- Release<br>- Version<br>- Deployment<br>- Environment<br>- Configuration<br>- TestCase<br>- Approval<br>- Impact<br>- Rollback<br>- Schedule<br>- Stakeholder<br>- Documentation<br>- RiskAssessment<br>- ChangeLog |

### Source System: ExcelETL
**System Functionality:** Manages Excel-based data extraction, transformation, and loading for business users.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - ExcelFile<br>- Worksheet<br>- DataRange<br>- Column<br>- Row<br>- Mapping<br>- Transformation<br>- ValidationRule<br>- LoadJob<br>- SourceFile<br>- TargetTable<br>- ErrorLog<br>- Template<br>- Schedule<br>- FileLocation<br>- DataType<br>- Formula<br>- ProcessLog<br>- Configuration<br>- User |

### Source System: ExcelFile – Essentia
**System Functionality:** Manages essential Excel file processing and data extraction operations.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - ExcelFile<br>- Worksheet<br>- DataExtract<br>- FileMetadata<br>- ProcessLog<br>- ValidationResult<br>- ErrorRecord<br>- Configuration<br>- Template<br>- DataMapping |

### Source System: Five9
**System Functionality:** Manages cloud contact center operations, call routing, and customer service interactions.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Channel | - Call<br>- Agent<br>- Campaign<br>- Queue<br>- Interaction<br>- CallDisposition<br>- Script<br>- Skill<br>- Schedule<br>- Recording<br>- Dialer<br>- IVR<br>- Transfer<br>- Conference<br>- Voicemail<br>- SMS<br>- Email<br>- Chat<br>- Ticket |
| 2 | Customer | - Customer |
| 3 | Analytics | - Report<br>- PerformanceMetrics<br>- QualityScore |
| 4 | Employee | - Supervisor |
| 5 | Workflow | - SLA |

### Source System: FraudLinks
**System Functionality:** Manages fraud detection, investigation, and case management for financial crimes.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Fraud | - FraudCase<br>- Alert<br>- Investigation<br>- Evidence<br>- Rule<br>- Score<br>- Pattern<br>- Investigator<br>- CaseStatus<br>- Resolution<br>- RiskLevel<br>- FraudType<br>- SuspiciousActivity<br>- Report<br>- Link<br>- Network<br>- Timeline |
| 2 | Transaction | - Transaction |
| 3 | Customer | - Customer |
| 4 | Account | - Account |

### Source System: Intranet
**System Functionality:** Manages internal employee portal for communications, documents, and collaboration.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Employee | - User<br>- Department<br>- Team |
| 2 | Document | - Page<br>- Content<br>- Document<br>- Policy<br>- Procedure<br>- Form |
| 3 | Channel | - Announcement<br>- News<br>- Calendar<br>- Event<br>- Comment<br>- Like<br>- Notification<br>- Feedback |
| 4 | Workflow | - Workflow |
| 5 | Technology | - Tag<br>- Category<br>- Search<br>- Navigation<br>- Permission<br>- Site<br>- Widget |

### Source System: Outsystems
**System Functionality:** Manages low-code application development platform for rapid application delivery.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - Application<br>- Module<br>- Entity<br>- Screen<br>- Action<br>- Process<br>- Integration<br>- Environment<br>- Deployment<br>- Version<br>- API<br>- Database<br>- Theme<br>- Component<br>- Widget<br>- Timer<br>- Email<br>- Site<br>- Reference<br>- Extension<br>- Log<br>- Configuration<br>- License |
| 2 | Security | - Role<br>- User |

### Source System: OSPRDI
**System Functionality:** Manages OutSystems production and development infrastructure monitoring and operations.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - Application<br>- Environment<br>- Server<br>- Service<br>- Log<br>- Error<br>- Performance<br>- Request<br>- Response<br>- Database<br>- Integration<br>- Deployment<br>- Monitoring<br>- Alert<br>- Metric<br>- User<br>- Session<br>- Configuration<br>- Health<br>- Availability<br>- Capacity<br>- Incident<br>- Maintenance<br>- Backup<br>- Recovery |

### Source System: ReportServer
**System Functionality:** Manages enterprise reporting server for scheduled reports and distribution.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Analytics | - Report<br>- Execution<br>- Snapshot<br>- History<br>- Cache<br>- Catalog |
| 2 | Workflow | - Subscription<br>- Schedule<br>- Delivery<br>- Format<br>- Job |
| 3 | Security | - User<br>- Permission<br>- Role |
| 4 | Technology | - Folder<br>- DataSource<br>- Parameter<br>- Configuration<br>- Log<br>- Alert |

### Source System: SharePoint
**System Functionality:** Manages document management, collaboration, and content management platform.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Document | - Site<br>- Library<br>- Document<br>- Folder<br>- List<br>- Item<br>- Version<br>- ContentType<br>- Metadata<br>- Page<br>- WebPart<br>- RecycleBin |
| 2 | Security | - User<br>- Group<br>- Permission |
| 3 | Workflow | - Workflow<br>- Approval<br>- Comment<br>- Tag<br>- View<br>- Alert<br>- Subscription |
| 4 | Technology | - Search<br>- Term<br>- Taxonomy |

### Source System: Snow
**System Functionality:** Manages software asset management, license compliance, and IT asset tracking.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - Asset<br>- Software<br>- License<br>- Computer<br>- Installation<br>- Product<br>- Version<br>- Entitlement<br>- Usage<br>- Discovery<br>- Inventory |
| 2 | Compliance | - Compliance<br>- Audit |
| 3 | Vendor | - Contract<br>- Vendor |
| 4 | Employee | - User |
| 5 | Accounting | - Cost<br>- Allocation |
| 6 | Workflow | - Request<br>- Approval |

### Source System: SYNRGVD01
**System Functionality:** Manages Synergy virtual desktop infrastructure and remote access services.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - VirtualDesktop<br>- Application<br>- Pool<br>- Host<br>- Connection<br>- Resource<br>- Policy<br>- Profile<br>- License<br>- Performance<br>- Monitoring<br>- Log<br>- Configuration<br>- Image<br>- Snapshot<br>- Provisioning |
| 2 | Security | - User<br>- Session<br>- AccessControl<br>- Authentication |

### Source System: WS repo
**System Functionality:** Manages web services repository for API management and service integration.

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - WebService<br>- API<br>- Endpoint<br>- Method<br>- Request<br>- Response<br>- Schema<br>- Contract<br>- Version<br>- Consumer<br>- Provider<br>- Log<br>- Monitoring<br>- Documentation<br>- Test<br>- Environment<br>- Configuration |
| 2 | Security | - Authentication<br>- Authorization<br>- Security |