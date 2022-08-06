# dp-900
Note
 + Azure Analysis Services is a fully managed platform as a service (PaaS) that provides enterprise-grade data models in the cloud. 
Use advanced mashup and modeling features to combine data from multiple data sources, define metrics, and secure your data in a single, trusted tabular semantic data model.
The data model provides an easier and faster way for users to perform ad hoc data analysis using tools like Power BI and Excel.
 + Azure Databricks is a data analytics platform optimized for the Microsoft Azure cloud services platform. 
 Azure Databricks offers three environments for developing data intensive applications: Databricks SQL, Databricks Data Science & Engineering, 
 and Databricks Machine Learning.
   - Azure data bricks is a compute service that helps Azure Data Factory to transform data visually

+ In the world of big data, raw, unorganized data is often stored in relational, non-relational, and other storage systems. However, on its own, raw data doesn't have the proper context or meaning to provide meaningful insights to analysts, data scientists, or business decision makers.

  Big data requires a service that can orchestrate and operationalize processes to refine these enormous stores of raw data into actionable business insights. Azure Data Factory is a managed cloud service that's built for these complex hybrid extract-transform-load (ETL), extract-load-transform (ELT), and data integration projects.

  Usage scenarios
  For example, imagine a gaming company that collects petabytes of game logs that are produced by games in the cloud. The company wants to analyze these logs to gain insights into customer preferences, demographics, and usage behavior. It also wants to identify up-sell and cross-sell opportunities, develop compelling new features, drive business growth, and provide a better experience to its customers.

  To analyze these logs, the company needs to use reference data such as customer information, game information, and marketing campaign information that is in an on-premises data store. The company wants to utilize this data from the on-premises data store, combining it with additional log data that it has in a cloud data store.

  To extract insights, it hopes to process the joined data by using a Spark cluster in the cloud (Azure HDInsight), and publish the transformed data into a cloud data warehouse such as Azure Synapse Analytics to easily build a report on top of it. They want to automate this workflow, and monitor and manage it on a daily schedule. They also want to execute it when files land in a blob store container.

  Azure Data Factory is the platform that solves such data scenarios. It is the cloud-based ETL and data integration service that allows you to create data-driven workflows for orchestrating data movement and transforming data at scale. Using Azure Data Factory, you can create and schedule data-driven workflows (called pipelines) that can ingest data from disparate data stores. You can build complex ETL processes that transform data visually with data flows or by using compute services such as Azure HDInsight Hadoop, Azure Databricks, and Azure SQL Database.

  Additionally, you can publish your transformed data to data stores such as Azure Synapse Analytics for business intelligence (BI) applications to consume. Ultimately, through Azure Data Factory, raw data can be organized into meaningful data stores and data lakes for better business decisions.

+ Power BI dashboard, also known as Canvas, is a single page that tells a story with the
help of visualizations. The visualizations that are present on the Power BI Dashboard
are known as Tiles. Once you select a tile, you will move to the report page where
that visualization was created.

+ Let’s understand the different types of data analytics to find how Diagnostic analytics is the correct option here.
    - Descriptive Analytics explains what happened in the past. It provides context to the businesses and helps to understand how it is performing. It can be     represented as data visualizations such as charts, graphs, dashboards, and reports.
   - Diagnostic Analytics explains why something has happened in the past. It takes the descriptive data to the next level and provides a deeper analysis of why something
   happened. It is also known as root cause analysis and includes data discovery, data mining, drill down, and drill through.
   - Predictive Analytics predicts what’s most likely to happen in the future. It takes historical data and uses a machine learning model to predict what will happen next.
   - Prescriptive Analytics explains the actions to take to affect the upcoming results. It takes predictive data to the next level and suggests actions to be performed along with the outline of potential implications

+ The Azure production network is segregated into three primary VLANs in a logical manner:
   The FC VLAN: It contains supporting systems and trusted Fabric Controllers
   The Main VLAN: It interconnects the untrusted customer nodes
   The Device VLAN: It contains a trusted network and all other infrastructure devices
+ Azure Synapse Analytics is an analytics engine that allows you to ingest, prepare, manage, and serve data for immediate BI and machine learning needs. It combines enterprise data warehousing and big data analytics
+ A data analyst uses various techniques and tools for collating data from different sources to visualize the data in an understandable and relevant format. Data analysts use the visualization tools for the transformation of data into graphical formats that can help in finding useful patterns in the data
+ The Data Definition Language is the ideal choice for creating database schema alongside defining certain constraints. On the other hand, the Data Manipulation
Language or DML helps update the rows in a table, known as a tuple.

Azure Database for MySQL is the best choice for Azure database in the given case as it delivers high elastic scaling and availability to open-source web and mobile
applications with a managed community MySQL database service or migrate MySQL workloads to the cloud

Single server is the best option to set up and run a single SQL Server database within no time. It doesn’t work for linked servers


+ Data stored in Azure Storage Zone-redundant storage (ZRS) is replicated across multiple availability zones
  Explanation:  Zone-redundant storage (ZRS) - Three synchronous copies in three AZs in the primary region
 + IaaS (Infrastructure as a Service): Database Administrator is responsible for OS upgrades and patches, Database software and upgrades, scaling of compute & storage, Availability and Durability
 
 + Azure Cosmos DB Table API supports both read replica's and multi region writes , where as Azure Table Storage does NOT.
 + Azure SQL Database is recommended to minimize operational overheads for running SQL Server in Azure
 + Archive: Rarely accessed data stored for min. 180 days. Lowest storage cost BUT Highest access cost. Access latency - In hours.
 + Semi Structured Column-Family Database - Azure Cosmos DB Cassandra API
 + Advantage: Star schemas are de-normalized and are easier to query
 + Power BI Report Builder: Standalone tool to author paginated reports
 + Dashboard: Single page - visualizations from one or more reports. Created using Power BI Service.
 + Gremlin: Graph. Store complex relationships between data.
 + Features in Azure SQL Managed Instance NOT provided by Azure SQL Database: Cross-database queries (and transactions) within a single SQL Server instance, Database Mail, Built in SQL Server Agent
 + You can restrict access to Azure SQL Database (allow only a specific range of IP addresses/virtual network) using server level firewall
 + Read only database replica help you offload reporting apps and other read workloads (from live OLTP database
 + In Azure Data Factory, which of these can be used to schedule pipelines? =>  Triggers: Trigger pipeline at a specific times
 + Azure Databricks: Process data from Azure Blob storage, Azure Data Lake Store, Hadoop storage, flat files, databases, and data warehouses
 + Azure Synapse Analytics - End-to-end analytics solutions. Data integration + Enterprise data warehouse + Data analytics.
 + You can pause the SQL pool in Azure Synapse Analytics to reduce costs
 + ELT (Extract, Load, and Transform): Data is stored before it is transformed. Uses an iterative approach (multiple steps) to process data in target system. Advantage: Does NOT use a separate transformation engine.\
 + When using Azure Data Factory for batch processing, processed data can be stored in relational databases, NoSql databases or in Azure Blob Storage
 + Clustered: Data in table is stored in the order of the index key values. Remember: Only one clustered index per table ( Why? - data rows can only be sorted in one way).
 + Azure Files: File shares for cloud and on-premises. Supports Server Message Block (SMB) and Network File System (NFS) protocols.
 + Control flow: Orchestrate pipeline activity based on output of another pipeline activity
+ Linked Service: Used to connect to an external source. Connect to different sources like Azure Storage Blob, SQL Databases etc
+ Data Control Language (DCL): Manage permissions and other controls Data Definition Language (DDL): Create and modify structure of database objects. Create:\
+ Create a database or its constituent objects (Table, View, Index etc).
+Predictive analytics: What will happen?. Predict probability based on historical data.
 Example: What will be the future demand?. Example: Calculate probability of something happening in future
+>Cognitive analytics: Make analytic tools to think like humans.
 Combine traditional analytics techniques with AI and ML features. 
Examples - Speech to text (transcription or subtitles), text to speech, 
Video Analysis, Image Analysis, Semantic Analysis of Text (Analyze reviews)
+ ARM templates are text files that contain the definitions of resources to deploy, and they are in JSON (JavaScript Object Notation) format

+ Which of the following Azure database services has guaranteed 100% compatibility with SQL Server running in your own environment? SQL Server in a VM
+ Azure Data Studio is a cross-platform database tool for data professionals using on-premises and cloud data platforms on Windows, macOS, and Linux.
You can use Azure Data Studio to connect to an Azure SQL Database server. You'll then run Transact-SQL (T-SQL) statements to create and query Azure SQL databases.
+ Azure Data Studio to create SQL notebook
+  Cosmos DB, HDInsight are non-relational databases.
+ Azure Synapse Analytics is for data warehousing, not for Online Transaction Processing
+ Azure Files offers native cloud file sharing services based on the SMB protocol.
+ Linked services are much like connection strings, which define the connection information needed for Data Factory to connect to external resources.

