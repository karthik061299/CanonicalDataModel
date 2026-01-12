# Business Unit: COE

## Source System Analysis

| Business Unit | Source System Name | System Functionality | Top 20-25 Key Entity Names | Total Number of Tables |
|--------------|-------------------|---------------------|---------------------------|----------------------|
| COE | AD | Active Directory for enterprise identity and access management services. | <ul><li>User</li><li>Group</li><li>OrganizationalUnit</li><li>Computer</li><li>Domain</li><li>Permission</li><li>Role</li><li>Policy</li><li>SecurityGroup</li><li>DistributionList</li><li>Account</li><li>Authentication</li></ul> | 12 |
| COE | AdminPortal | Administrative portal for system configuration and user management. | <ul><li>Administrator</li><li>Configuration</li></ul> | 2 |
| COE | ADO | Azure DevOps for software development lifecycle and project management. | <ul><li>Project</li><li>WorkItem</li><li>Repository</li><li>Pipeline</li><li>Release</li><li>Build</li><li>TestCase</li><li>Bug</li><li>Task</li><li>Sprint</li></ul> | 0 |
| COE | Archive | Enterprise data archival system for long-term storage and compliance. | <ul><li>ArchivedDocument</li><li>ArchivedRecord</li><li>RetentionPolicy</li><li>ArchiveLocation</li><li>DocumentType</li><li>ArchiveMetadata</li><li>ComplianceRule</li><li>RetentionSchedule</li><li>DispositionRule</li><li>LegalHold</li><li>ArchiveIndex</li><li>StorageMedia</li><li>ArchiveJob</li><li>RetrievalRequest</li><li>AuditLog</li><li>AccessControl</li><li>EncryptionKey</li><li>BackupCopy</li><li>ArchiveStatus</li><li>DataClassification</li></ul> | 1,000 |
| COE | DataMart | Data mart for departmental analytics and business intelligence reporting. | <ul><li>Fact</li><li>Dimension</li><li>Measure</li><li>Hierarchy</li><li>Cube</li><li>Report</li><li>Dashboard</li><li>KPI</li><li>Metric</li><li>DataSource</li><li>ETLJob</li><li>DataQuality</li><li>BusinessRule</li><li>AggregateTable</li><li>TimeDimension</li><li>CustomerDimension</li><li>ProductDimension</li><li>GeographyDimension</li><li>FactTable</li><li>StarSchema</li></ul> | 20 |
| COE | Decisions | Business rules engine for automated decision-making and workflow management. | <ul><li>DecisionRule</li><li>BusinessRule</li><li>RuleSet</li><li>DecisionTable</li><li>Workflow</li><li>Condition</li><li>Action</li><li>RuleExecution</li><li>DecisionLog</li><li>RuleVersion</li><li>Parameter</li><li>RuleCategory</li><li>ValidationRule</li><li>ApprovalRule</li><li>ScoringModel</li><li>DecisionTree</li><li>RuleEngine</li><li>PolicyRule</li></ul> | 18 |
| COE | DocuSign | Electronic signature platform for document signing and contract management. | <ul><li>Envelope</li><li>Document</li><li>Signer</li></ul> | 3 |
| COE | DWSupport | Data warehouse support system for ETL operations and data integration. | <ul><li>ETLJob</li><li>DataSource</li><li>DataTarget</li><li>Transformation</li><li>DataFlow</li><li>Schedule</li><li>JobExecution</li><li>ErrorLog</li><li>DataQuality</li><li>DataLineage</li><li>Metadata</li><li>SourceTable</li><li>TargetTable</li><li>Mapping</li><li>ValidationRule</li><li>DataProfile</li><li>JobDependency</li><li>MonitoringMetric</li><li>AlertRule</li><li>PerformanceMetric</li><li>DataLoad</li><li>IncrementalLoad</li><li>FullLoad</li><li>ChangeDataCapture</li><li>DataArchive</li></ul> | 1,679 |
| COE | EnterpriseBI | Enterprise business intelligence platform for analytics and reporting. | <ul><li>Report</li><li>Dashboard</li><li>Dataset</li><li>DataSource</li><li>Visualization</li><li>KPI</li><li>Metric</li><li>Dimension</li><li>Measure</li><li>Cube</li><li>Query</li><li>User</li><li>Permission</li><li>Subscription</li><li>Schedule</li><li>Alert</li><li>Bookmark</li><li>Filter</li><li>Parameter</li><li>DataModel</li></ul> | 91 |
| COE | ETL | Extract Transform Load system for data integration and migration. | <ul><li>ETLJob</li><li>SourceSystem</li><li>TargetSystem</li><li>Transformation</li><li>DataMapping</li><li>Schedule</li><li>JobExecution</li><li>ErrorHandling</li><li>DataValidation</li><li>LoadStrategy</li><li>DataFlow</li><li>Package</li><li>Connection</li><li>Variable</li><li>Logging</li><li>Monitoring</li><li>Dependency</li><li>ChangeTracking</li><li>DataQuality</li><li>Reconciliation</li></ul> | 20 |
| COE | Evo | Evolution platform for application development and deployment. | <ul><li>Application</li><li>Module</li><li>Component</li><li>Version</li><li>Deployment</li><li>Environment</li></ul> | 6 |
| COE | ExcelETL | Excel-based ETL tool for data extraction and transformation. | <ul><li>Workbook</li><li>Worksheet</li><li>DataRange</li><li>Formula</li><li>Macro</li><li>DataConnection</li><li>PivotTable</li><li>Chart</li><li>Table</li><li>NamedRange</li><li>DataValidation</li><li>ConditionalFormat</li><li>ExternalData</li><li>Query</li><li>Parameter</li><li>RefreshSchedule</li><li>DataSource</li><li>Transformation</li><li>Template</li><li>DataModel</li></ul> | 359 |
| COE | ExcelFile – Essentia | Excel file management system for essential business data. | <ul><li>ExcelFile</li><li>FileMetadata</li></ul> | 2 |
| COE | Five9 | Cloud contact center platform for customer service operations. | <ul><li>Agent</li><li>Campaign</li><li>Call</li><li>Queue</li><li>Skill</li><li>Disposition</li><li>Script</li><li>Recording</li><li>Schedule</li><li>Report</li><li>Contact</li><li>Interaction</li><li>IVR</li><li>Workflow</li><li>PerformanceMetric</li><li>QualityScore</li><li>CallbackRequest</li><li>VoicemailMessage</li><li>ChatSession</li><li>EmailInteraction</li></ul> | 32 |
| COE | FraudLinks | Fraud detection and prevention system for risk management. | <ul><li>FraudCase</li><li>Alert</li><li>Rule</li><li>Investigation</li><li>Suspect</li><li>Transaction</li><li>Pattern</li><li>RiskScore</li></ul> | 8 |
| COE | Intranet | Internal corporate portal for employee communication and collaboration. | <ul><li>Page</li><li>Content</li><li>User</li><li>Department</li><li>Announcement</li><li>Document</li><li>News</li><li>Event</li><li>Policy</li><li>Procedure</li><li>Form</li><li>Directory</li><li>Team</li><li>Project</li><li>Resource</li><li>Link</li><li>Category</li><li>Tag</li><li>Comment</li><li>Notification</li></ul> | 82 |
| COE | Outsystems | Low-code application development platform for rapid application delivery. | <ul><li>Application</li><li>Module</li><li>Entity</li><li>Screen</li><li>Action</li><li>Process</li><li>Integration</li><li>Role</li><li>User</li><li>Environment</li><li>Version</li><li>Deployment</li><li>Database</li><li>WebService</li><li>Timer</li><li>Email</li><li>Theme</li><li>Extension</li><li>Site</li><li>Log</li><li>Configuration</li><li>Resource</li><li>Structure</li><li>StaticEntity</li><li>SystemEntity</li></ul> | 434 |
| COE | OSPRDI | OutSystems production infrastructure for application hosting. | <ul><li>Server</li><li>Application</li><li>Module</li><li>Environment</li><li>Deployment</li><li>Configuration</li><li>Monitoring</li><li>Log</li><li>Performance</li><li>Resource</li><li>Database</li><li>Service</li><li>Infrastructure</li><li>Network</li><li>Security</li><li>Backup</li><li>Alert</li><li>Incident</li><li>Capacity</li><li>Availability</li></ul> | 57 |
| COE | ReportServer | Centralized reporting server for enterprise report generation and distribution. | <ul><li>Report</li><li>ReportDefinition</li><li>DataSource</li><li>Dataset</li><li>Parameter</li><li>Schedule</li><li>Subscription</li><li>Snapshot</li><li>Execution</li><li>User</li><li>Permission</li><li>Folder</li><li>ReportHistory</li><li>CachePolicy</li><li>DataDrivenSubscription</li><li>SharedDataset</li><li>ReportPart</li><li>LinkedReport</li><li>ReportModel</li><li>DeliveryExtension</li></ul> | 72 |
| COE | SharePoint | Collaboration platform for document management and team sites. | <ul><li>Site</li><li>Library</li><li>Document</li><li>List</li><li>ListItem</li><li>Folder</li><li>User</li><li>Group</li><li>Permission</li><li>Workflow</li><li>ContentType</li><li>Column</li><li>View</li><li>WebPart</li><li>Page</li><li>Version</li><li>Metadata</li><li>Term</li><li>TermSet</li><li>SearchIndex</li><li>Alert</li><li>Approval</li><li>Task</li><li>Calendar</li><li>Discussion</li></ul> | 179 |
| COE | Snow | IT asset management system for software license and hardware tracking. | <ul><li>Asset</li><li>License</li><li>Software</li><li>Hardware</li><li>User</li></ul> | 5 |
| COE | SYNRGVD01 | Synergy virtual desktop infrastructure for remote access. | <ul><li>VirtualDesktop</li><li>User</li><li>Session</li><li>Application</li><li>Resource</li><li>Pool</li><li>Image</li><li>Host</li><li>Policy</li><li>Profile</li><li>Connection</li><li>Performance</li><li>License</li><li>Configuration</li><li>Monitoring</li><li>Log</li><li>Security</li><li>Network</li><li>Storage</li><li>Backup</li></ul> | 21 |
| COE | WS repo | Web services repository for API and service management. | <ul><li>WebService</li><li>API</li><li>Endpoint</li><li>Method</li><li>Version</li><li>Documentation</li></ul> | 6 |

### System Functionality Reasoning
- **AD**: Active Directory for identity management
- **AdminPortal**: Administrative interface for system management
- **ADO**: Azure DevOps for development operations (0 tables suggests metadata only)
- **Archive**: Large-scale archival system for compliance
- **DataMart**: Analytics data mart for business intelligence
- **Decisions**: Business rules engine for automated decisions
- **DocuSign**: Electronic signature platform
- **DWSupport**: Data warehouse support infrastructure
- **EnterpriseBI**: Enterprise BI platform
- **ETL**: Core ETL processing system
- **Evo**: Application evolution/development platform
- **ExcelETL**: Excel-based data integration
- **ExcelFile – Essentia**: Essential Excel file management
- **Five9**: Contact center platform
- **FraudLinks**: Fraud detection system
- **Intranet**: Internal collaboration portal
- **Outsystems**: Low-code development platform
- **OSPRDI**: OutSystems production infrastructure
- **ReportServer**: Centralized reporting platform
- **SharePoint**: Document management and collaboration
- **Snow**: IT asset management
- **SYNRGVD01**: Virtual desktop infrastructure
- **WS repo**: Web services repository