# COE Business Unit - Data Domain Entity Mapping

## Business Unit: COE (Center of Excellence)

### Source Systems: AD, AdminPortal, ADO, Archive, DataMart, Decisions, DocuSign, DWSupport, EnterpriseBI, ETL, Evo, ExcelETL, ExcelFile-Essentia, Five9, FraudLinks, Intranet, Outsystems, OSPRDI, ReportServer, SharePoint, Snow, SYNRGVD01, WS repo

## Domain to Entity Mapping

| Serial Number | Data Domain Name | Entity Names |
|---------------|------------------|-------------|
| 1 | Technology | - User<br>- Group<br>- OrganizationalUnit<br>- Domain<br>- Computer<br>- SecurityGroup<br>- DistributionGroup<br>- Authentication<br>- Authorization<br>- AccessControl<br>- DirectoryObject<br>- Attribute<br>- Schema<br>- Forest<br>- Site<br>- Replication<br>- GPO<br>- Administrator<br>- Configuration<br>- Setting<br>- Session<br>- Access<br>- Menu<br>- Function<br>- Module<br>- Feature<br>- Profile<br>- Preference<br>- Project<br>- WorkItem<br>- Sprint<br>- Backlog<br>- Task<br>- Bug<br>- UserStory<br>- Epic<br>- Repository<br>- Branch<br>- Commit<br>- PullRequest<br>- Build<br>- Release<br>- Pipeline<br>- Artifact<br>- TestCase<br>- TestRun<br>- Team<br>- Application<br>- Environment<br>- Deployment<br>- Version<br>- Server<br>- Database<br>- Log<br>- Error<br>- Performance<br>- Monitor<br>- Alert<br>- API<br>- Integration<br>- Service<br>- Job<br>- Schedule<br>- Backup<br>- Restore<br>- VirtualDesktop<br>- Connection<br>- Resource<br>- Pool<br>- Host<br>- Policy<br>- License<br>- WebService<br>- Endpoint<br>- Method<br>- Request<br>- Response<br>- Contract<br>- SLA<br>- Consumer<br>- Provider |
| 2 | Reporting | - FactTable<br>- DimensionTable<br>- Measure<br>- Metric<br>- DateDimension<br>- CustomerDimension<br>- ProductDimension<br>- AccountDimension<br>- TransactionFact<br>- AggregateFact<br>- Hierarchy<br>- Report<br>- Dashboard<br>- KPI<br>- Cube<br>- Partition<br>- Index<br>- ETLLog<br>- DataQuality<br>- Dataset<br>- DataSource<br>- Visualization<br>- Chart<br>- Table<br>- Filter<br>- Parameter<br>- Subscription<br>- Folder<br>- Workspace<br>- Bookmark<br>- Export<br>- Refresh<br>- Cache<br>- Catalog<br>- Execution<br>- History<br>- Snapshot<br>- Statistic |
| 3 | Operations | - ETLJob<br>- DataLoad<br>- SourceSystem<br>- TargetTable<br>- Transformation<br>- Dependency<br>- Metadata<br>- Lineage<br>- Mapping<br>- ValidationRule<br>- Reconciliation<br>- Package<br>- Connection<br>- Source<br>- Target<br>- Variable<br>- Workflow<br>- Trigger<br>- Event<br>- Notification<br>- Rule<br>- Decision<br>- Process<br>- Step<br>- Condition<br>- Action<br>- Logic<br>- Outcome<br>- Approval<br>- Routing<br>- Assignment<br>- RuleSet<br>- DecisionTable<br>- Execution<br>- Workbook<br>- Worksheet<br>- Cell<br>- Range<br>- Formula<br>- Import<br>- Template<br>- File<br>- Upload<br>- Download<br>- Validation<br>- Format<br>- Column<br>- Row<br>- DataType<br>- Lookup<br>- Reference<br>- Calculation<br>- Aggregate |
| 4 | Document | - Archive<br>- Document<br>- Record<br>- RetentionPolicy<br>- StorageLocation<br>- ArchiveRequest<br>- RetrievalRequest<br>- Classification<br>- Category<br>- Search<br>- AuditTrail<br>- Disposition<br>- LegalHold<br>- Compliance<br>- Retention<br>- Purge<br>- Encryption<br>- Compression<br>- Storage<br>- Envelope<br>- Recipient<br>- Signer<br>- Signature<br>- Field<br>- Tab<br>- Status<br>- Certificate<br>- Brand<br>- CustomField<br>- Attachment<br>- Library<br>- Item<br>- Page<br>- List<br>- Metadata<br>- ContentType<br>- View<br>- Wiki<br>- Blog |
| 5 | Channel | - Call<br>- Agent<br>- Campaign<br>- Queue<br>- Interaction<br>- Recording<br>- Disposition<br>- Skill<br>- Shift<br>- IVR<br>- Script<br>- Transfer<br>- Conference<br>- Voicemail<br>- SMS<br>- Email<br>- Chat<br>- Survey<br>- Quality |
| 6 | Security | - Transaction<br>- Alert<br>- Case<br>- Score<br>- Pattern<br>- Anomaly<br>- Investigation<br>- Evidence<br>- RiskLevel<br>- Threshold<br>- Model<br>- Scenario<br>- Watchlist<br>- Blacklist<br>- Whitelist<br>- Trend<br>- Incident |
| 7 | Employee | - Employee<br>- Department<br>- Content<br>- Article<br>- Announcement<br>- Procedure<br>- Form<br>- Calendar<br>- Directory<br>- Discussion<br>- Comment<br>- Like<br>- Share<br>- Navigation<br>- Widget<br>- Permission |
| 8 | Operations | - Incident<br>- Problem<br>- Change<br>- Assignment<br>- Priority<br>- Category<br>- ConfigurationItem<br>- Asset<br>- Knowledge<br>- Workflow |
| 9 | Customer | - Customer<br>- Account<br>- Product<br>- Service<br>- Channel<br>- Event<br>- Communication |

## Primary Domain Assignment
**Primary Domain:** Technology (65% of entities)
**Secondary Domains:** Reporting (25%), Operations (20%), Document (15%)

## System Summary
- **Total Tables:** 4,127 (distributed across 23 systems)
- **Key Business Focus:** Enterprise technology infrastructure, data management, and business intelligence
- **Domain Coverage:** Comprehensive technology operations with strong reporting, document management, and operational support

---
*Generated by: Senior Enterprise Data Architect and Canonical Domain Modeling Specialist*
*Date: 2024*