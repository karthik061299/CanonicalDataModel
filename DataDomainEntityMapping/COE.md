# Domain to Entity Mapping - COE Business Unit

## Source Systems Analysis

### AD (Active Directory) System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Security | - User<br>- Group<br>- OrganizationalUnit<br>- Domain<br>- Computer<br>- SecurityPolicy<br>- AccessControl<br>- Permission<br>- Role<br>- Authentication<br>- UserProfile<br>- GroupMembership |

### AdminPortal System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Security | - Administrator<br>- UserManagement |
| 2 | Operations | - Configuration<br>- SystemSetting |
| 3 | Audit | - AccessLog<br>- AuditTrail |

### ADO (Azure DevOps) System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - Project<br>- Repository<br>- Pipeline<br>- Build<br>- Release<br>- WorkItem<br>- Sprint<br>- Backlog<br>- Commit<br>- PullRequest<br>- Branch<br>- TestCase<br>- Deployment<br>- Artifact<br>- Board |

### Archive System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Document | - ArchivedDocument<br>- RetentionPolicy<br>- ArchiveLocation<br>- RetrievalRequest<br>- DocumentMetadata<br>- StorageMedia<br>- ArchiveDate<br>- ExpirationDate<br>- ComplianceTag<br>- AccessHistory<br>- RestorePoint<br>- BackupSet<br>- ArchiveIndex<br>- DocumentType<br>- RetentionSchedule<br>- LegalHold<br>- DispositionRule<br>- ArchiveStatus<br>- StorageLocation<br>- DataClassification |

### DataMart System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Analytics | - Dimension<br>- Fact<br>- Measure<br>- DataModel<br>- Aggregate<br>- Hierarchy<br>- Attribute<br>- Metric<br>- KPI<br>- Report<br>- Dashboard<br>- Calculation<br>- Filter<br>- Parameter<br>- Query |
| 2 | Technology | - ETLProcess<br>- DataSource<br>- DataRefresh<br>- DataQuality<br>- BusinessRule |

### Decisions System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Operations | - DecisionRule<br>- BusinessRule<br>- Workflow<br>- Process<br>- Task<br>- Condition<br>- Action<br>- RuleSet<br>- DecisionTable<br>- ProcessInstance<br>- WorkflowStep<br>- Approval<br>- Escalation<br>- Notification<br>- ProcessVariable<br>- RuleExecution<br>- DecisionLog<br>- ProcessMetrics |

### DocuSign System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Document | - Envelope<br>- Document<br>- Signer<br>- Signature<br>- Template<br>- Workflow<br>- Recipient<br>- SigningSession<br>- AuditTrail<br>- Certificate<br>- Field<br>- Tab<br>- Status<br>- Notification<br>- Authentication<br>- CompletedDocument<br>- SigningOrder |

### DWSupport System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - DataSource<br>- ETLJob<br>- DataLineage<br>- Metadata<br>- DataQuality<br>- JobSchedule<br>- ErrorLog<br>- PerformanceMetric<br>- DataProfile<br>- Dependency<br>- Transformation<br>- LoadStatistics<br>- DataCatalog<br>- BusinessGlossary<br>- DataOwner<br>- DataSteward<br>- DataDomain<br>- QualityRule<br>- Incident<br>- Resolution<br>- ChangeRequest<br>- Documentation<br>- SupportTicket<br>- MonitoringAlert<br>- SystemHealth |

### EnterpriseBI System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Analytics | - Report<br>- Dashboard<br>- Dataset<br>- DataSource<br>- Visualization<br>- KPI<br>- Metric<br>- Dimension<br>- Measure<br>- Filter<br>- Parameter<br>- Calculation<br>- Bookmark<br>- Alert<br>- Export<br>- Snapshot<br>- RefreshHistory<br>- UsageStatistics |
| 2 | Security | - User<br>- Workspace<br>- Folder<br>- Permission |
| 3 | Operations | - Subscription<br>- Schedule<br>- DataModel |

### ETL System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - ETLJob<br>- DataSource<br>- DataTarget<br>- Transformation<br>- Mapping<br>- Schedule<br>- JobExecution<br>- ErrorHandling<br>- DataFlow<br>- Connection<br>- Package<br>- Task<br>- Variable<br>- Parameter<br>- LogEntry<br>- Performance<br>- Dependency<br>- Validation<br>- DataQuality<br>- Checkpoint |

### Evo System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - Application<br>- Module<br>- Component<br>- Version<br>- Deployment<br>- Environment<br>- Configuration<br>- Release<br>- Build<br>- Dependency<br>- Change<br>- Issue<br>- Feature<br>- Bug<br>- TestCase<br>- Documentation |

### ExcelETL System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - Workbook<br>- Worksheet<br>- DataRange<br>- Mapping<br>- Transformation<br>- ValidationRule<br>- ImportJob<br>- DataSource<br>- TargetTable<br>- ErrorLog<br>- Schedule<br>- Template<br>- Formula<br>- DataType<br>- Column<br>- Row<br>- Cell<br>- Format<br>- Macro<br>- RefreshConnection |

### ExcelFile – Essentia System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Document | - ExcelFile<br>- FileMetadata<br>- Version<br>- AccessControl<br>- FileLocation<br>- Owner<br>- ModificationHistory<br>- FileSize<br>- FileType<br>- StoragePath |

### Five9 System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Channel | - Call<br>- Agent<br>- Campaign<br>- Contact<br>- Queue<br>- Skill<br>- Disposition<br>- Recording<br>- Script<br>- IVR<br>- CallFlow<br>- Schedule<br>- Performance<br>- Quality<br>- Survey<br>- Interaction<br>- Channel<br>- Session<br>- Metric<br>- Report |

### FraudLinks System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Compliance | - FraudCase<br>- Alert<br>- Investigation<br>- Pattern<br>- Anomaly<br>- RiskFactor<br>- Disposition<br>- Evidence<br>- Suspect<br>- Victim<br>- FraudType<br>- Status<br>- Resolution<br>- Workflow<br>- Analyst |
| 2 | Transaction | - Transaction<br>- Rule<br>- Score |

### Intranet System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Communication | - Page<br>- Content<br>- Announcement<br>- News<br>- Event<br>- Comment<br>- Like<br>- Share<br>- Navigation<br>- Search |
| 2 | Employee | - User<br>- Department |
| 3 | Document | - Document<br>- Policy<br>- Procedure<br>- Form<br>- Link<br>- Category<br>- Tag |
| 4 | Security | - Permission |

### Outsystems System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - Application<br>- Module<br>- Screen<br>- Entity<br>- Action<br>- Process<br>- Integration<br>- Role<br>- Theme<br>- Resource<br>- Extension<br>- Timer<br>- Email<br>- Site<br>- Environment<br>- Deployment<br>- Version<br>- Dependency<br>- Log |
| 2 | Security | - User |

### OSPRDI System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Operations | - Project<br>- Research<br>- Innovation<br>- Experiment<br>- Result<br>- Researcher<br>- Publication<br>- Patent<br>- Collaboration<br>- Funding<br>- Milestone<br>- Deliverable<br>- Resource<br>- Equipment<br>- Data<br>- Analysis<br>- Report<br>- Review<br>- Approval<br>- Budget |

### ReportServer System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Analytics | - Report<br>- Schedule<br>- Subscription<br>- Parameter<br>- DataSource<br>- Dataset<br>- Snapshot<br>- Execution<br>- Cache<br>- Folder<br>- Delivery<br>- Format<br>- History<br>- Log<br>- Performance<br>- Configuration<br>- Catalog<br>- Resource |
| 2 | Security | - Permission<br>- User |

### SharePoint System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Document | - Site<br>- Library<br>- List<br>- Document<br>- Folder<br>- Item<br>- Version<br>- Workflow<br>- ContentType<br>- Column<br>- View<br>- Page<br>- WebPart<br>- Search<br>- Metadata<br>- Tag<br>- Taxonomy<br>- Term<br>- Navigation<br>- Alert<br>- Subscription<br>- Audit |
| 2 | Security | - User<br>- Group<br>- Permission |

### Snow System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - Asset<br>- License<br>- Software<br>- Hardware<br>- Computer<br>- Contract<br>- Purchase<br>- Deployment<br>- Compliance<br>- Audit<br>- Usage<br>- Cost<br>- Allocation<br>- Renewal<br>- Maintenance<br>- Inventory<br>- Discovery<br>- Reconciliation |
| 2 | Employee | - User |
| 3 | Vendor | - Vendor |

### SYNRGVD01 System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - VirtualDesktop<br>- Session<br>- Host<br>- Pool<br>- Image<br>- Application<br>- Resource<br>- Connection<br>- Policy<br>- Performance<br>- Monitoring<br>- License<br>- Storage<br>- Network<br>- Security<br>- Configuration<br>- Deployment<br>- Maintenance<br>- Backup |
| 2 | Security | - User |

### WS repo System
| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - WebService<br>- API<br>- Endpoint<br>- Method<br>- Request<br>- Response<br>- Schema<br>- Contract<br>- Version<br>- Documentation<br>- Consumer<br>- Provider<br>- Authentication<br>- Authorization<br>- Monitoring<br>- Log<br>- Performance<br>- Error<br>- Throttling<br>- Rate Limit |

**Business Unit Summary:**
- **Total Systems:** 23
- **Total Entities Mapped:** 400+
- **Total Tables:** 4,127
- **Primary Domains:** Technology (45%), Analytics (15%), Document (12%), Security (10%), Operations (8%), Communication (5%), Others (5%)