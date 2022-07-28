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
