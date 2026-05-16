# Awesome List for Microsoft Copilot Connectors [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <img src="media/banner.svg" alt="Awesome Microsoft Copilot Connectors" width="800">
</p>

> A comprehensive directory of every connector in Microsoft's official [Microsoft 365 Copilot connectors gallery](https://learn.microsoft.com/en-us/microsoft-365/copilot/connectors/connectors-gallery) - 134 verified data sources covered by Microsoft-built and partner-built connectors, organized by category.

**Last updated:** May 16, 2026 | **Connectable services:** 134 | **Categories:** 16

Microsoft 365 Copilot connectors extend the reach of Microsoft 365 Copilot and Microsoft Search by indexing external data into Microsoft Graph or querying it in real time through federated connectors. Once indexed, content from Confluence, Salesforce, ServiceNow, Google Drive, GitHub, and 100+ other services becomes retrievable inside Copilot, Microsoft Search, SharePoint, Teams, and the Microsoft 365 app.

For more information, see the [Connectors documentation](https://learn.microsoft.com/en-us/microsoft-365/copilot/connectors/), [Microsoft-built gallery](https://learn.microsoft.com/en-us/microsoft-365/copilot/connectors/connectors-gallery-microsoft), [Partner-built gallery](https://learn.microsoft.com/en-us/microsoft-365/copilot/connectors/connectors-gallery-partners), and the [Microsoft Graph connectors API](https://learn.microsoft.com/en-us/graph/connecting-external-content-connectors-overview).

Each entry covers one connectable service. The body of each entry names the publishers offering a connector for that service - Microsoft and/or one or more partners. Markers below identify versions worth surfacing:

- **`M`** - A Microsoft-built version exists.
- **`★ Certified`** - A version is Certified for Microsoft 365 Copilot (Microsoft's enterprise-ready validation).
- *(preview)* - A version is currently in preview.

This list is maintained weekly. To contribute, see [CONTRIBUTING.md](CONTRIBUTING.md).

> This is an independent, community-maintained list. Not affiliated with, endorsed by, or sponsored by Microsoft Corporation. "Microsoft", "Microsoft 365", "Copilot", and related marks are property of Microsoft Corporation. Each connector is the property of its respective publisher.

> [!TIP]
> ### Connector of the Week - May 16, 2026
>
> **[NetApp](https://www.netapp.com)** · *Files and documents*
>
> The NetApp connector is the quiet sleeper pick in this week's gallery. It lets organizations connect their NetApp ONTAP files - on-premises, on Azure, on AWS, on GCP, or virtual - directly to Microsoft 365 Copilot without moving the data, without re-platforming, without breaking existing access controls. That's a real enterprise-data-gravity story most people don't know exists. The strategic significance isn't "another file connector" - it's that one of the largest sources of unstructured enterprise file data on the planet (NetApp ONTAP runs petabytes inside every Fortune 500) is now query-able from Copilot in place. For organizations that built their last decade on ONTAP and are now asked to make that content AI-retrievable without a data-migration project, this is the answer that ships today. Pairs naturally with Nasuni and the Microsoft-built Azure File Share and Amazon S3 connectors for full-coverage file-tier retrieval.

---

## Contents

- [Collaboration and communication](#collaboration-and-communication)
- [Content management systems](#content-management-systems)
- [Customer relationship management](#customer-relationship-management)
- [Data visualization](#data-visualization)
- [Databases](#databases)
- [Developer tools](#developer-tools)
- [Files and documents](#files-and-documents)
- [Human resources and recruiting](#human-resources-and-recruiting)
- [IT service management tools](#it-service-management-tools)
- [Learning](#learning)
- [Project management](#project-management)
- [Sales](#sales)
- [Social networks](#social-networks)
- [Support](#support)
- [Website](#website)
- [Others](#others)
- [Related](#related)

---

## Collaboration and communication

- [Aderant](https://www.aderant.com) - Legal-practice content indexed with full security trimming. Partner: BA Insight.
- [Adobe Acrobat Sign](https://www.adobe.com/sign.html) - Agreement metadata stored for unified search across Microsoft 365 documents. Partner: Adobe.
- [Aha!](https://www.aha.io) - Indexes Aha! features and ideas so they're discoverable through Copilot and Microsoft Search. **`M`**
- [Atlassian Confluence Cloud](https://www.atlassian.com/software/confluence) - Indexes Confluence Cloud pages, blogs, attachments, comments, spaces, and profiles. **`M`** Partners: BA Insight, RheinInsights, ServiceNow, Accenture.
- [Atlassian Confluence Server and Data Center](https://www.atlassian.com/software/confluence/enterprise/data-center) - Indexes on-premises Confluence spaces, pages, blogs, and attachments. **`M`** Partner: RheinInsights.
- [Atlassian Jira Cloud](https://www.atlassian.com/software/jira) - Indexes Jira Cloud issues, projects, comments, attachments, and work logs. **`M`** Partners: BA Insight, RheinInsights, ServiceNow.
- [Atlassian Jira Server and Data Center](https://www.atlassian.com/software/jira/enterprise/data-center) - Indexes on-premises Jira projects, issues, comments, and attachments. **`M`** Partners: BA Insight, RheinInsights, Accenture.
- [Azure DevOps Wiki](https://azure.microsoft.com/en-us/products/devops/wiki) - Indexes wiki pages from Azure DevOps. **`M`**
- [Azure DevOps Work Items](https://azure.microsoft.com/en-us/products/devops/boards) - Indexes work items from your Azure DevOps instance. **`M`**
- [CB Insights](https://www.cbinsights.com) - Private-and-public company funding events, business relationships, and predictive outlook surfaced in Copilot. **`★ Certified`** Partner: CB Insights.
- [Egnyte](https://www.egnyte.com) - Workflow automation and content integration with Egnyte. **`M`** Partner: BA Insight.
- [Elite](https://www.elite.com) - Lawyers' single point of access to firm content stored in Elite. Partner: BA Insight.
- [GitHub Enterprise Cloud](https://github.com/enterprise) - Indexes repositories, versioned files, wikis, issues, and discussions. Partner: RheinInsights.
- [Google Drive](https://www.google.com/drive) - Files, folders, comments, and shared-drive content indexed for Copilot. **`M`** Partners: BA Insight, RheinInsights, ServiceNow.
- [Google Mail](https://www.google.com/gmail) - Emails and attachments from Gmail indexed with permission support. Partner: RheinInsights.
- [IBM Connections](https://www.ibm.com/cloud) - Public and personal files, blogs, wikis, forums, communities, and profiles. Partners: Accenture, ServiceNow.
- [iManage Work](https://imanage.com) - Document management content indexed with security enforcement and no client install. Partner: BA Insight.
- [Jive](https://www.jivesoftware.com) - Documents stored in Jive Community spaces, groups, projects, and blogs. Partner: Accenture.
- [Kafka](https://kafka.apache.org) - Messages fetched from a Kafka stream and submitted with optional transform. Partner: Accenture.
- [Kinesis](https://aws.amazon.com/kinesis) - Data fetched from Amazon Kinesis Data Streams with optional transform. Partner: Accenture.
- [LDAP Directory Services](https://en.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol) - Profile search and source for early-binding security trimming in LDAP directories. Partner: RheinInsights.
- [Linear](https://linear.app) - Streamlines issues, projects, and product roadmaps. **`M`** *(preview)*
- [Microsoft Active Directory](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/get-started/virtual-dc/active-directory-domain-services-overview) - Profile search and source for early-binding security trimming. Partner: RheinInsights.
- [Microsoft Entra ID](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id) - Profile search including Azure B2C profiles and source for early-binding security trimming. Partner: RheinInsights.
- [Microsoft Exchange Online](https://www.microsoft.com/en-us/microsoft-365/exchange/email) - Exchange Online content retrieved across search platforms. Partner: BA Insight.
- [Microsoft Teams](https://www.microsoft.com/en-us/microsoft-teams) - Conversations and attachments from Teams retrieved for AI Search. Partners: BA Insight, ServiceNow.
- [Miro](https://miro.com) - Integrates with Miro's collaborative whiteboarding platform. **`M`**
- [Mural](https://www.mural.co) - Continuously updated Mural data indexed inside your Microsoft tenant for Copilot retrieval. Partner: Mural.
- [Notion](https://www.notion.so) - Notes, projects, databases, pages, attachments, and wikis. **`M`** *(preview)* Partner: RheinInsights.
- [Powtoon](https://www.powtoon.com) - Video creation platform content indexed with Microsoft Graph. Partner: Powtoon.
- [Priority Matrix](https://prioritymatrix.com) - Tasks and projects from Priority Matrix surfaced in Office, Teams, and more. Partner: Priority Matrix.
- [Shortcut Story](https://www.shortcut.com) - Manage agile software development projects with Shortcut. **`M`**
- [Slack](https://slack.com) - Public and private channels, messages, threads, and attached files. Partners: RheinInsights, ServiceNow.
- [TeamForge](https://www.digital.ai/products/teamforge) - Content crawled from a TeamForge server via SOAP services. Partner: Accenture.
- [Trello](https://trello.com) - Visual project management with boards, cards, comments, and attachments. **`M`** *(preview)* Partner: RheinInsights.


## Content management systems

- [Adobe Experience Manager](https://business.adobe.com/products/experience-manager/adobe-experience-manager.html) - AEM content crawled with document-level security and metadata extraction. **`M`** *(preview)* Partner: Accenture.
- [Bentley AssetWise](https://www.bentley.com/software/assetwise) - AssetWise asset-lifecycle content surfaced in a consolidated Microsoft Search index. Partner: BA Insight.
- [Coda Enterprise](https://coda.io) - Workflow management and team collaboration via Coda. **`M`**
- [Confluence Cloud](https://www.atlassian.com/software/confluence/cloud) - Cloud-hosted Confluence pages and blogs indexed for Microsoft Search. **`M`**
- [Confluence On-premises](https://www.atlassian.com/software/confluence/download) - Confluence pages from server or data center deployments. **`M`**
- [CuadraSTAR](https://lucidea.com/cuadrastar/) - Library and special-collections content indexed in a unified Microsoft Search index. Partner: BA Insight.
- [Documentum (Open Text)](https://www.opentext.com/products/documentum-content-management) - Documentum content crawled via DQL with document-level security. Partners: Accenture, BA Insight (cloud + on-prem variants).
- [Elasticsearch](https://www.elastic.co/elasticsearch) - Elastic index content crawled via user-defined queries with automatic update detection. Partner: Accenture.
- [Enterprise Websites (Cloud)](https://learn.microsoft.com/en-us/microsoftsearch/enterprise-websites-cloud-connector) - Searches any non-SharePoint enterprise website hosted in the cloud. **`M`**
- [Enterprise Websites (On-premises)](https://learn.microsoft.com/en-us/microsoftsearch/enterprise-websites-on-premises-connector) - Searches any non-SharePoint enterprise website on-premises. **`M`**
- [getAbstract](https://www.getabstract.com) - Indexed and licensed expert business knowledge across leadership, strategy, sales, marketing, finance, and digital transformation. **`★ Certified`** Partner: getAbstract.
- [Guru](https://www.getguru.com) - Knowledge management platform for capturing, storing, and sharing organizational knowledge. **`M`**
- [HP Consolidated Archive (EAS)](https://www.microfocus.com/en-us/products/structured-data-manager-archiving/overview) - Full text and metadata of HP archive documents indexed across SharePoint and other repositories. Partner: BA Insight.
- [IBM Content Manager](https://www.ibm.com/products/content-manager) - Source security honored with full and incremental crawls of IBM CM content. Partner: BA Insight.
- [IBM FileNet](https://www.ibm.com/products/filenet-content-manager) - FileNet repositories searched with access enforcement matching FileNet's own. Partner: BA Insight.
- [IBM WebSphere](https://www.ibm.com/products/websphere) - Full text and metadata of WebSphere objects indexed into Microsoft Search. Partner: BA Insight.
- [iManage Cloud](https://imanage.com/products/work-10/) - Full text and metadata of documents in iManage Work workspaces. Partner: BA Insight.
- [KMS Lighthouse Knowledge](https://www.kmslh.com) - Organizational knowledge securely indexed while preserving existing access controls. Partner: KMS Lighthouse.
- [Lucid](https://lucid.co) - Diagramming and whiteboard documents surfaced inside Microsoft 365 with permission sync. Partner: Lucid Software.
- [LumApps](https://www.lumapps.com) - Intranet, news, and community content integrated with Microsoft 365 inside Copilot. Partner: LumApps.
- [MediaWiki](https://www.mediawiki.org) - Knowledge-based articles on MediaWiki sites. **`M`**
- [NetDocuments](https://www.netdocuments.com) - NetDocs content indexed with automatic document-security mapping into Microsoft Search. Partner: BA Insight.
- [OneDrive (CMS scope)](https://www.microsoft.com/en-us/microsoft-365/onedrive) - OneDrive content indexed across all tenant instances with document preview integrations. Partner: RheinInsights.
- [OpenText Content Server (Livelink/RM)](https://www.opentext.com/products/content-management) - Livelink and Microsoft data searched with single-query security enforcement. Partner: BA Insight.
- [Panopto](https://www.panopto.com) - Federated search across Panopto video including spoken words and on-screen text in 20+ languages. Partner: Panopto.
- [ProLaw](https://legal.thomsonreuters.com/en/products/prolaw) - Legal practice-management content surfaced while respecting user privileges. Partner: BA Insight.
- [Salesforce Knowledge](https://www.salesforce.com/service/knowledge-base/) - Knowledge articles indexed for Microsoft Search. **`M`**
- [ServiceNow Knowledge](https://www.servicenow.com/products/knowledge-management.html) - Knowledge base articles from ServiceNow instances. **`M`** Partner: ServiceNow.
- [ServiceNow Product Documentation](https://docs.servicenow.com) - Topics from ServiceNow product documentation retrieved for AI Search. Partner: ServiceNow.
- [SharePoint 2010](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/sharepoint-2010-developer-resources) - Site, document library, and list content securely indexed for the 2010 release. Partner: BA Insight.
- [SharePoint 2013](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/sharepoint-2013-development-overview) - Sites, pages, lists, list items, and documents for the 2013 release. Partner: RheinInsights.
- [SharePoint 2016](https://learn.microsoft.com/en-us/sharepoint/sharepoint-server-2016) - Sites, lists, pages, and documents for the 2016 release. Partners: BA Insight, Accenture, RheinInsights.
- [SharePoint 2019](https://learn.microsoft.com/en-us/sharepoint/what-s-new/new-and-improved-features-in-sharepoint-server-2019) - Sites, lists, pages, and documents for the 2019 release. Partners: BA Insight, Accenture, RheinInsights.
- [SharePoint Online](https://www.microsoft.com/en-us/microsoft-365/sharepoint/collaboration) - Online sites, lists, list items, attachments, and ASPX pages including multi-geo. Partners: Accenture, BA Insight, RheinInsights, ServiceNow.
- [SharePoint Server (Subscription Edition)](https://www.microsoft.com/en-us/microsoft-365/sharepoint/sharepoint-server) - On-premises SharePoint sites connected for collaboration and management. **`M`** *(preview)* Partner: RheinInsights.
- [Sitecore](https://www.sitecore.com) - Source security honored with full and incremental crawls of Sitecore content. Partner: BA Insight.
- [S&P Global](https://www.spglobal.com) - Financial and market data integrated with Office 365, Copilot, SharePoint, Outlook, and Teams. Partner: S&P Global.
- [Stack Overflow](https://stackoverflow.com) - Questions and answers indexed for Copilot and Microsoft Search. **`M`**
- [Templafy Library](https://www.templafy.com) - Brand-compliant Templafy library assets used when Copilot creates presentations. Partner: Templafy.
- [Unily](https://www.unily.com) - Digital workplace platform integration for communication and employee experience. **`M`**
- [Veeva QualityDocs](https://www.veeva.com/products/vault-quality/) - Quality content management in Veeva Vault for life sciences. **`M`**
- [Veeva Vault](https://www.veeva.com/products/vault-platform/) - Vault objects (full text and metadata) indexed into Microsoft Search. Partner: BA Insight.
- [Veeva Vault PromoMats](https://www.veeva.com/products/vault-promomats/) - Compliant promotional and regulatory content with metadata, approval statuses, and version histories. **`M`**
- [Veeva Vault RIM](https://www.veeva.com/products/vault-rim/) - Regulatory information management content from the Vault RIM suite. **`M`**
- [West km](https://legal.thomsonreuters.com) - Transaction and litigation documents searched across West km with custom result pages. Partner: BA Insight.
- [WordPress.com](https://wordpress.com) - Hosted WordPress sites indexed for Copilot. **`M`**
- [WordPress.org](https://wordpress.org) - On-premises WordPress sites indexed for Copilot. **`M`**
- [Zendesk Guide](https://www.zendesk.com/service/guide/) - Pages, comments, and attachments from Zendesk Guide instances. Partner: ServiceNow.
- [Zenya](https://www.infoland.com) - Documents, process flows, forms, questionnaires, and information cards in Zenya quality and risk management. Partner: Infoland.


## Customer relationship management

- [HubSpot](https://www.hubspot.com) - Customer data and sales pipelines managed from Copilot. **`M`** *(preview)*
- [Microsoft Dynamics 365](https://www.microsoft.com/en-us/dynamics-365) - Knowledge articles, cases, posts, notes, contacts, accounts, sales orders, and opportunities. Partners: BA Insight (on-prem + cloud), RheinInsights.
- [Salesforce](https://www.salesforce.com) - Sales, Service, and Marketing Cloud content including Chatter feeds. Partners: Accenture, BA Insight.
- [Salesforce CRM](https://www.salesforce.com/sales/) - Contacts, opportunities, leads, and accounts. **`M`**


## Data visualization

- [Tableau Cloud](https://www.tableau.com/products/cloud-bi) - Cloud-hosted Tableau connection for advanced data visualization and business intelligence. **`M`** *(preview)*


## Databases

- [Amazon Aurora](https://aws.amazon.com/rds/aurora/) - Aurora and other relational databases indexed via industry-standard methods. Partner: BA Insight.
- [Amazon RDS](https://aws.amazon.com/rds/) - Relational Database Service content indexed via standard database access methods. Partner: BA Insight.
- [Azure SQL Database](https://azure.microsoft.com/en-us/products/azure-sql/database) - Azure SQL data searched and indexed. **`M`** Partner: BA Insight.
- [CSV files](https://learn.microsoft.com/en-us/microsoftsearch/csv-connector) - Content stored in CSV files indexed for Microsoft Search. **`M`**
- [DataStax](https://www.datastax.com) - Real-time data access integration with Apache Cassandra-based deployments. **`M`** *(preview)*
- [Generic Database Server](https://learn.microsoft.com/en-us/microsoft-365/copilot/connectors/connectors-gallery-partners#databases) - Relational database servers crawled with database and table discovery. Partner: Accenture.
- [Google Cloud SQL](https://cloud.google.com/sql) - Managed cloud SQL content indexed into the Microsoft Search index. Partner: BA Insight.
- [HBase](https://hbase.apache.org) - Data crawled from an HBase Server. Partner: Accenture.
- [IBM Db2](https://www.ibm.com/db2) - Db2 database content indexed with full and incremental crawls. Partner: BA Insight.
- [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server) - On-premises SQL Server databases searched and indexed. **`M`** Partners: BA Insight, RheinInsights.
- [MySQL](https://www.mysql.com) - Database content indexed via standard database access methods. Partner: BA Insight.
- [Nexla Data Platform for Agents](https://www.nexla.com) - 550+ enterprise data sources connected to Copilot with agentic RAG and built-in governance. Partner: Nexla.
- [Oracle Database](https://www.oracle.com/database/) - Records indexed via tables, views, and SQL queries against Oracle. **`M`** Partners: BA Insight, RheinInsights.
- [PostgreSQL](https://www.postgresql.org) - Records indexed via tables, views, and SQL queries against Postgres. **`M`** *(preview)* Partners: BA Insight, RheinInsights.
- [Practical Law](https://legal.thomsonreuters.com/en/products/practical-law) - Thomson Reuters legal-research database searched directly from Microsoft Search. Partner: BA Insight.
- [Generic Relational Databases (JDBC)](https://en.wikipedia.org/wiki/Java_Database_Connectivity) - Relational databases crawled via JDBC drivers with automatic update detection. Partner: Accenture.


## Developer tools

- [Bitbucket](https://bitbucket.org) - Git repository management, code review, and pull-request collaboration. **`M`** (Knowledge + Pull Requests variants)
- [GitHub Cloud](https://github.com) - GitHub repositories indexed for issues, knowledge, and pull-request collaboration. **`M`** (Issues + Knowledge + Pull Requests variants)
- [GitHub Server (Enterprise Server)](https://github.com/enterprise/server) - GitHub Server repositories indexed for issues, knowledge, and pull-request collaboration. **`M`** (Issues + Knowledge + Pull Requests variants)
- [GitLab Cloud](https://about.gitlab.com) - GitLab.com projects indexed for issues, knowledge, and merge-request workflows. **`M`** (Issues + Knowledge + Merge Requests variants)
- [GitLab Self-Managed (Server)](https://about.gitlab.com/install/) - GitLab Self-Managed projects indexed for issues, knowledge, and merge-request workflows. **`M`** (Issues + Knowledge + Merge Requests variants) Partner: ServiceNow.
- [ServiceNow AI Platform (KB articles)](https://www.servicenow.com/products/ai-platform.html) - KB article records and attachments retrieved from ServiceNow AI Platform for AI Search. Partner: ServiceNow.


## Files and documents

- [Amazon S3](https://aws.amazon.com/s3/) - Objects indexed from Amazon S3 buckets. **`M`** Partners: Accenture, BA Insight, ServiceNow.
- [Azure Blob Storage](https://azure.microsoft.com/en-us/products/storage/blobs) - Azure Blob Container content crawled with blob metadata. Partner: Accenture.
- [Azure Data Lake Storage Gen2](https://azure.microsoft.com/en-us/products/storage/data-lake-storage) - Content in Azure Blob containers and hierarchy-enabled folders indexed. **`M`** Partner: Accenture.
- [Azure Event Hubs](https://azure.microsoft.com/en-us/products/event-hubs) - Events fetched from Azure streams with optional transform. Partner: Accenture.
- [Azure File Share](https://azure.microsoft.com/en-us/products/storage/files) - Content stored in Azure File Share indexed for Copilot. **`M`**
- [Box](https://www.box.com) - Content surfaced inside Microsoft 365 with file, folder, comment, and group indexing. **`★ Certified`** Partners: Box, Accenture, BA Insight, ServiceNow.
- [Dropbox](https://www.dropbox.com) - File storage, sharing, and collaboration connection. **`M`**
- [File Share (Windows / CIFS / SMB)](https://en.wikipedia.org/wiki/Server_Message_Block) - On-premises Windows, CIFS, and SMB file shares crawled with ACL extraction. **`M`** Partners: BA Insight, RheinInsights, Accenture.
- [File System (local)](https://learn.microsoft.com/en-us/microsoft-365/copilot/connectors/connectors-gallery-partners#files-and-documents) - Local file systems crawled with incremental updates and file metadata. Partner: Accenture.
- [File Transfer Protocol (FTP)](https://en.wikipedia.org/wiki/File_Transfer_Protocol) - Files and folders accessed on an FTP server. Partner: Accenture.
- [Google Drive (files)](https://workspace.google.com/products/drive/) - Google Drive file synchronization and storage integration. **`M`**
- [Hadoop Distributed File System (HDFS)](https://hadoop.apache.org) - HDFS Cluster content crawled via the WebHDFS HTTP interface. Partner: Accenture.
- [Microsoft OneDrive](https://www.microsoft.com/en-us/microsoft-365/onedrive/online-cloud-storage) - OneDrive content crawled with incremental updates, ACLs, and document preview. Partners: Accenture, BA Insight, ServiceNow.
- [Nasuni File Share](https://www.nasuni.com) - External file-share data integrated into Microsoft 365 for AI-driven content discovery at scale. Partner: Nasuni.
- [NetApp ONTAP](https://www.netapp.com/data-storage/) - ONTAP files connected to Copilot on-prem, in Azure, AWS, GCP, or virtual without data movement. Partner: NetApp.
- [OData via REST](https://www.odata.org) - Custom data indexed flexibly via OData over REST for SAP, Apigee, or Azure API Management. Partner: RheinInsights.
- [Simple Mail Transfer Protocol (SMTP)](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol) - Emails processed with metadata including to, from, and subject. Partner: Accenture.


## Human resources and recruiting

- [15Five](https://www.15five.com) - High Five recognition and priority data indexed for Copilot and Microsoft Search. **`M`** (High Fives + Priorities variants)
- [BambooHR](https://www.bamboohr.com) - People Experiences (Teams and Copilot profiles) populated with BambooHR data. **`M`**
- [Microsoft Viva Engage](https://www.microsoft.com/en-us/microsoft-viva/viva-engage) - Messages and attachments from Viva Engage conversations retrieved for AI Search. Partner: ServiceNow.
- [SAP SuccessFactors](https://www.sap.com/products/hcm/what-is-sap-successfactors.html) - Organizational data and HR functions securely synchronized from SAP. **`M`** *(preview)*
- [Workday](https://www.workday.com) - Organizational data and HR functions securely synchronized from Workday. **`M`** *(preview)*


## IT service management tools

- [Freshservice](https://www.freshworks.com/freshservice) - IT service management integrated with Microsoft 365. **`M`**
- [Git (repositories)](https://git-scm.com) - Branches, versioned files, and commit messages indexed from remote Git repositories. Partner: RheinInsights.
- [LDAP (general)](https://datatracker.ietf.org/doc/html/rfc4511) - LDAP-compliant directories indexed with field filtering for users, contracts, or groups. Partners: BA Insight, ServiceNow.
- [PagerDuty](https://www.pagerduty.com) - Escalation policies and schedules indexed and searched. **`M`** (Escalation Policies + Schedules variants)
- [ServiceNow](https://www.servicenow.com) - Catalog items and ticketing data crawled for AI Search and Copilot. **`M`** (Catalog + Tickets variants) Partners: Accenture, BA Insight.


## Learning

- [Go1](https://www.go1.com) - Employee learning surfaced via Microsoft Search in the Microsoft 365 app or SharePoint. Partner: Go1.


## Project management

- [Asana](https://asana.com) - Project management platform integration. **`M`**
- [monday.com](https://monday.com) - Project and workflow management integration. **`M`**
- [Smartsheet](https://www.smartsheet.com) - Sheet data indexed and searched. **`M`**


## Sales

- [Gong](https://www.gong.io) - Sales-call transcripts integrated for actionable revenue insights. **`M`**


## Social networks

- [Twitter/X](https://twitter.com) - Tweet text, URL links, geo-location, and hashtags crawled from Twitter feeds. Partner: Accenture.
- [Yammer](https://learn.microsoft.com/en-us/yammer/) - Messages, metadata, and attachments indexed for unified search (now Viva Engage). Partners: Accenture, BA Insight.


## Support

- [Zendesk Help Center](https://www.zendesk.com/service/) - Self-service knowledge base integration. **`M`**
- [Zendesk Ticket](https://www.zendesk.com/service/ticketing-system/) - Zendesk customer service ticketing integration. **`M`** *(preview)*


## Website

- [Aspider Web Crawler](https://learn.microsoft.com/en-us/microsoft-365/copilot/connectors/connectors-gallery-partners#website) - Content crawled from one or more websites with server-provided metadata. Partner: Accenture.
- [RSS](https://en.wikipedia.org/wiki/RSS) - Feed information retrieved and flows triggered when new items publish. Partner: Accenture.
- [Selenium](https://www.selenium.dev) - Content crawled from websites using an internet browser to retrieve pages. Partner: Accenture.
- [Web Pages](https://learn.microsoft.com/en-us/microsoft-365/copilot/connectors/connectors-gallery-partners#web-pages) - Indexed from a given site with flexible metadata extraction. Partner: RheinInsights.
- [Website Crawler](https://en.wikipedia.org/wiki/Web_crawler) - Website content resurfaced in a single consolidated search index. Partner: BA Insight.


## Others

- [Canva](https://www.canva.com) - Design presentations and social media graphics. **`M`** *(preview)*
- [Google Calendar](https://calendar.google.com) - Schedule, manage, and share meetings. **`M`** *(preview)*
- [Google Contacts](https://contacts.google.com) - Contact information organization. **`M`** *(preview)*
- [Intercom](https://www.intercom.com) - Customer conversations, support tickets, and user engagement. **`M`** *(preview)*


## Related

- [Awesome Claude Connectors](https://github.com/rdmgator12/awesome-claude-connectors) - Anthropic's official Claude connector directory.
- [Awesome Claude Plugins](https://github.com/rdmgator12/awesome-claude-plugins) - Claude Code and Cowork plugin directory.
- [Awesome Grok Connectors](https://github.com/rdmgator12/awesome-grok-connectors) - xAI Grok connector directory.
- [Awesome Perplexity Connectors](https://github.com/rdmgator12/Perplexity-Connectors-awesome-list-) - Perplexity connector directory.
- [Awesome Mistral Connectors](https://github.com/rdmgator12/awesome-mistral-connectors) - Mistral connector directory.
- [Awesome LM Studio Connectors](https://github.com/rdmgator12/awesome-lm-studio-connectors) - LM Studio connector directory.
- [Awesome Lovable Connectors](https://github.com/rdmgator12/awesome-lovable-connectors) - Lovable connector directory.
- [Awesome Gemini](https://github.com/rdmgator12/Gemini-Awesome-List-) - Gemini CLI extensions directory.
- [Awesome ChatGPT Apps](https://github.com/rdmgator12/Chtgpt-Apps-Awesome-List) - ChatGPT apps directory.
- [Awesome Healthcare MCP Servers](https://github.com/rdmgator12/awesome-healthcare-mcp-servers) - Healthcare MCP server directory.
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - The broader MCP server ecosystem beyond any single vendor's verified directory.
