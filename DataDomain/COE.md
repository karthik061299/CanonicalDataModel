# COE Business Unit - Source Systems Analysis

## Business Unit: COE

---

### Source System: AD

**System Functionality Description:** Active Directory managing user authentication, authorization, security groups, and enterprise identity management.

**Top 20-25 Key Entity Names:**
- User
- Group
- OrganizationalUnit
- SecurityPrincipal
- Domain
- UserAccount
- GroupMembership
- Permission
- AccessControl
- AuthenticationLog
- UserProfile
- SecurityGroup
- DistributionList
- ComputerAccount
- ServiceAccount
- PolicyObject
- TrustRelationship
- DirectoryObject
- UserAttribute
- GroupPolicy

**Total Number of Tables:** 12

---

### Source System: AdminPortal

**System Functionality Description:** Administrative portal for system configuration, user management, and operational control.

**Top 20-25 Key Entity Names:**
- Administrator
- UserRole
- Permission
- Configuration
- AuditLog
- SystemSetting
- AccessControl
- UserSession
- AdminAction
- SecurityPolicy

**Total Number of Tables:** 2

---

### Source System: ADO

**System Functionality Description:** Azure DevOps managing software development, project tracking, and continuous integration/deployment pipelines.

**Top 20-25 Key Entity Names:**
- Project
- WorkItem
- Repository
- Pipeline
- Build
- Release
- Sprint
- Backlog
- Task
- Bug
- Feature
- UserStory
- TestCase
- CodeCommit
- PullRequest
- Branch
- Artifact
- Deployment
- BuildDefinition
- ReleaseDefinition

**Total Number of Tables:** 0

---

### Source System: Archive

**System Functionality Description:** Enterprise data archival system managing historical records, retention policies, and compliance documentation.

**Top 20-25 Key Entity Names:**
- ArchivedDocument
- RetentionPolicy
- ArchiveRecord
- DocumentMetadata
- StorageLocation
- ArchiveJob
- RetentionSchedule
- ArchivedTransaction
- ComplianceRecord
- ArchiveIndex
- DocumentType
- ArchiveStatus
- RetrievalRequest
- LegalHold
- DispositionRule
- ArchiveLog
- DataClassification
- ArchiveVersion
- StorageMedia
- ArchivePolicy
- DocumentLifecycle
- ArchiveCatalog
- RestorationRecord
- ArchiveAudit
- RetentionException

**Total Number of Tables:** 1000

---

### Source System: DataMart

**System Functionality Description:** Departmental data warehouse storing aggregated business data for reporting and analytics.

**Top 20-25 Key Entity Names:**
- FactTable
- DimensionTable
- Measure
- Metric
- DataCube
- AggregateData
- TimeDimension
- CustomerDimension
- ProductDimension
- GeographyDimension
- SalesMetric
- PerformanceIndicator
- DataSnapshot
- AnalyticalView
- ReportingPeriod
- BusinessMetric
- DataGrain
- ConformedDimension
- FactlessFactTable
- BridgeTable

**Total Number of Tables:** 20

---

### Source System: Decisions

**System Functionality Description:** Business rules engine managing decision workflows, approval processes, and automated business logic.

**Top 20-25 Key Entity Names:**
- DecisionRule
- Workflow
- BusinessRule
- ApprovalProcess
- DecisionTree
- RuleCondition
- RuleAction
- WorkflowStep
- DecisionLog
- RuleExecution
- ApprovalRequest
- DecisionCriteria
- RuleSet
- WorkflowInstance
- DecisionOutcome
- RuleVersion
- ApprovalHierarchy
- DecisionMatrix

**Total Number of Tables:** 18

---

### Source System: DocuSign

**System Functionality Description:** Electronic signature platform managing document signing, workflow automation, and digital agreement processing.

**Top 20-25 Key Entity Names:**
- Envelope
- Document
- Signer
- Signature
- SigningSession
- Recipient
- Template
- Agreement
- AuditTrail
- SigningStatus
- Notification
- CustomField
- Tab
- Workflow
- CompletedDocument

**Total Number of Tables:** 3

---

### Source System: DWSupport

**System Functionality Description:** Data warehouse support system managing ETL processes, data quality, and warehouse maintenance operations.

**Top 20-25 Key Entity Names:**
- ETLJob
- DataLoad
- DataQualityRule
- ErrorLog
- LoadStatistics
- SourceMapping
- TransformationRule
- DataLineage
- JobSchedule
- DataValidation
- LoadHistory
- DataProfile
- MetadataRepository
- DependencyMap
- LoadMonitor
- DataQualityMetric
- ReconciliationReport
- WarehouseMetadata
- ProcessLog
- DataRefresh
- StagingTable
- LoadControl
- ErrorHandling
- PerformanceMetric
- MaintenanceJob

**Total Number of Tables:** 1679

---

### Source System: EnterpriseBI

**System Functionality Description:** Enterprise business intelligence platform providing reporting, dashboards, and analytical capabilities.

**Top 20-25 Key Entity Names:**
- Report
- Dashboard
- Dataset
- DataSource
- Visualization
- KPI
- Metric
- ReportSubscription
- UserReport
- ReportSchedule
- AnalyticalModel
- DataCube
- ReportParameter
- ReportSnapshot
- DashboardWidget
- ReportDistribution
- AnalyticsQuery
- ReportTemplate
- DataRefresh
- ReportUsage
- BIMetadata
- ReportFolder
- UserPreference
- ReportVersion
- AnalyticsWorkspace

**Total Number of Tables:** 91

---

### Source System: ETL

**System Functionality Description:** Extract, transform, load processes managing data integration, transformation, and loading operations.

**Top 20-25 Key Entity Names:**
- ETLJob
- DataSource
- DataTarget
- Transformation
- DataMapping
- LoadProcess
- ExtractProcess
- TransformProcess
- JobSchedule
- JobExecution
- ErrorLog
- DataFlow
- JobDependency
- LoadStatistics
- DataValidation
- JobParameter
- SourceConnection
- TargetConnection
- DataQuality
- JobMonitor

**Total Number of Tables:** 20

---

### Source System: Evo

**System Functionality Description:** Evolution platform managing system upgrades, version control, and application lifecycle management.

**Top 20-25 Key Entity Names:**
- Version
- Release
- Component
- Upgrade
- Configuration
- ChangeLog
- Deployment
- Environment
- BuildVersion
- ReleaseNote
- SystemComponent
- VersionHistory
- UpgradeScript
- ConfigurationItem
- ReleaseSchedule

**Total Number of Tables:** 6

---

### Source System: ExcelETL

**System Functionality Description:** Excel-based ETL system managing spreadsheet data extraction, transformation, and loading processes.

**Top 20-25 Key Entity Names:**
- ExcelFile
- Worksheet
- DataRange
- ColumnMapping
- DataExtract
- TransformationRule
- LoadTarget
- FileMetadata
- DataValidation
- ExcelTemplate
- DataSource
- LoadHistory
- ErrorLog
- FileVersion
- DataMapping
- ProcessLog
- SourceWorkbook
- TargetTable
- ValidationRule
- DataConversion
- FileSchedule
- LoadStatistics
- DataQuality
- ProcessControl
- FileArchive

**Total Number of Tables:** 359

---

### Source System: ExcelFile – Essentia

**System Functionality Description:** Essential Excel file management system for business data collection and reporting.

**Top 20-25 Key Entity Names:**
- ExcelDocument
- DataSheet
- FileMetadata
- DataEntry
- FileVersion
- DataValidation
- FileTemplate
- DataCollection
- FileRepository
- DataExport

**Total Number of Tables:** 2

---

### Source System: Five9

**System Functionality Description:** Cloud contact center platform managing customer interactions, call routing, and agent performance.

**Top 20-25 Key Entity Names:**
- Call
- Agent
- Campaign
- Contact
- CallQueue
- Interaction
- CallDisposition
- AgentState
- CallRecording
- IVRSession
- SkillGroup
- CallMetric
- ContactList
- AgentPerformance
- CallScript
- QueueStatistics
- InteractionHistory
- CampaignMetric
- AgentSchedule
- CallOutcome
- CustomerInteraction
- ServiceLevel
- CallTransfer
- WrapUpCode
- ContactCenter

**Total Number of Tables:** 32

---

### Source System: FraudLinks

**System Functionality Description:** Fraud detection and prevention system managing suspicious activity monitoring and investigation.

**Top 20-25 Key Entity Names:**
- FraudCase
- Alert
- Transaction
- SuspiciousActivity
- Investigation
- FraudRule
- RiskScore
- FraudPattern
- AlertQueue
- CaseStatus
- FraudIndicator
- InvestigationNote
- FraudType
- AlertDisposition
- RiskAssessment

**Total Number of Tables:** 8

---

### Source System: Intranet

**System Functionality Description:** Internal corporate portal managing employee communications, documents, and collaboration tools.

**Top 20-25 Key Entity Names:**
- Employee
- Document
- Announcement
- Department
- Page
- Content
- UserProfile
- News
- Policy
- Form
- Calendar
- Event
- Discussion
- Resource
- Link
- Category
- Comment
- Notification
- Workflow
- Permission
- Site
- Navigation
- Search
- Feedback
- Collaboration

**Total Number of Tables:** 82

---

### Source System: Outsystems

**System Functionality Description:** Low-code application development platform managing custom applications, workflows, and business processes.

**Top 20-25 Key Entity Names:**
- Application
- Module
- Entity
- Screen
- Process
- Integration
- User
- Role
- Workflow
- DataModel
- BusinessLogic
- WebService
- DatabaseTable
- UserInterface
- ApplicationVersion
- Deployment
- Environment
- Reference
- Action
- Timer
- EmailTemplate
- SiteProperty
- SystemLog
- SessionVariable
- ExceptionLog

**Total Number of Tables:** 434

---

### Source System: OSPRDI

**System Functionality Description:** OutSystems production and development infrastructure managing application hosting and environment configuration.

**Top 20-25 Key Entity Names:**
- Application
- Environment
- Server
- Deployment
- Configuration
- Module
- Version
- Infrastructure
- Resource
- Monitoring
- Performance
- LogEntry
- ApplicationPool
- DatabaseConnection
- ServiceEndpoint
- Certificate
- LoadBalancer
- HealthCheck
- BackupJob
- SecuritySetting
- NetworkConfiguration
- StorageResource
- DeploymentHistory
- EnvironmentVariable
- SystemMetric

**Total Number of Tables:** 57

---

### Source System: ReportServer

**System Functionality Description:** Centralized reporting server managing report generation, scheduling, and distribution.

**Top 20-25 Key Entity Names:**
- Report
- ReportExecution
- Subscription
- Schedule
- ReportParameter
- DataSource
- ReportSnapshot
- ReportHistory
- ReportFolder
- User
- ReportPermission
- ReportDefinition
- ExecutionLog
- ReportCache
- DeliveryMethod
- ReportFormat
- ReportSubscriber
- ScheduleJob
- ReportData
- ReportTemplate
- ErrorLog
- ReportVersion
- DataConnection
- ReportMetadata
- DistributionList

**Total Number of Tables:** 72

---

### Source System: SharePoint

**System Functionality Description:** Collaboration platform managing documents, workflows, team sites, and content management.

**Top 20-25 Key Entity Names:**
- Document
- Library
- List
- Site
- User
- Permission
- Folder
- ContentType
- Workflow
- Page
- ListItem
- DocumentVersion
- Metadata
- SiteCollection
- WebPart
- Group
- Navigation
- Search
- Taxonomy
- Column
- View
- Alert
- RecycleBin
- Approval
- SiteTemplate

**Total Number of Tables:** 179

---

### Source System: Snow

**System Functionality Description:** IT asset management system tracking software licenses, hardware inventory, and compliance.

**Top 20-25 Key Entity Names:**
- Asset
- License
- Software
- Hardware
- Computer
- User
- LicenseAllocation
- SoftwareInstallation
- Compliance
- Inventory
- AssetOwner
- LicenseAgreement
- SoftwareVersion
- AssetStatus
- ComplianceReport

**Total Number of Tables:** 5

---

### Source System: SYNRGVD01

**System Functionality Description:** Synergy virtual desktop infrastructure managing virtual machines and desktop environments.

**Top 20-25 Key Entity Names:**
- VirtualMachine
- Desktop
- User
- Session
- Host
- Pool
- Image
- Resource
- Connection
- Performance
- Configuration
- VirtualDisk
- NetworkAdapter
- UserProfile
- DesktopGroup
- ApplicationPool
- StorageResource
- Hypervisor
- SessionLog
- ResourceAllocation

**Total Number of Tables:** 21

---

### Source System: WS repo

**System Functionality Description:** Web services repository managing API definitions, service endpoints, and integration documentation.

**Top 20-25 Key Entity Names:**
- WebService
- Endpoint
- API
- ServiceDefinition
- Operation
- Repository
- Version
- Documentation
- ServiceContract
- Integration
- Schema
- MessageFormat
- ServiceMetadata
- Authentication
- ServiceLog

**Total Number of Tables:** 6