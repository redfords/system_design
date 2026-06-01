• Designing and building production-grade data platforms on Snowflake and Azure supporting analytics, operational reporting, and near real-time use cases

• Led the design and deployment of a Snowflake Cortex AI marketing analytics solution that standardized Google Ads performance diagnostics, automated executive reporting, and reduced manual analysis across the marketing department

• Built the full medallion transformation layer in dbt, generating all bronze, silver, and gold Snowflake tables from raw
source data

• Implementing scalable ingestion and transformation pipelines using Python, SQL, Spark (PySpark), Azure Data Factory and Airflow

• Integrating enterprise and SaaS data sources including Salesforce, NetSuite, Google Ads, Microsoft Dynamics 365 Finance & Operations, and API/SFTP-based feeds

• Developing efficient batch and near real-time ingestion architectures, replacing full-refresh patterns and significantly reducing processing time and costs

• Modeling complex datasets using dimensional modeling, medallion architecture, and Data Vault concepts to enable analytics and AI-driven workloads

• Supporting production stability through monitoring, troubleshooting, and continuous optimization of data pipelines

• Built a greenfield internal data platform within a Microsoft-based data stack supporting financial and reporting workloads

• Developed SQL-driven processing workflows acting as a backend data layer for validation, transformation, and persistence

• Implemented batch and incremental pipelines using Python, Spark (PySpark / SparkSQL) and SQL

• Designed dimensional data models to support finance and analytics use cases

• Owned production reliability through issue investigation, root-cause analysis, and remediation

• Maintained and extended on-premise data pipelines using SQL Server and SSIS to support operational and analytical reporting

• Enhanced analytical data models and integrated new datasets into Power BI dashboards

• Designed dimensional data warehouse structures using Kimball modeling principles

• Led early cloud modernization efforts by delivering POC solutions using Azure Data Lake, Azure Data Factory and Azure Synapse

• Migrated selected workloads from SSIS to cloud-based and PySpark-driven pipelines

• Supported analytics reliability by resolving data quality issues and optimizing existing pipelines

• Supported enterprise BI environments by debugging and optimizing ETL workflows

• Assisted in legacy analytics migrations, including SAP Business Objects data model analysis

• Developed and maintained dashboards using Power BI and Qlik

• Automated reporting workflows using Excel and Visual Basic macros

- Built and maintained large-scale data pipelines processing TB-scale healthcare impression and event data, supporting analytics and BI reporting across the organization
- Developed distributed PySpark jobs to ingest high-volume event streams from healthcare publishers (e.g. WebMD) via Kafka, orchestrated with Airflow and Luigi on a hybrid on-premise/cloud platform (HDFS/Hive + GCP/BigQuery)
- Delivered analytics-ready data models to BigQuery and Looker, serving downstream analytics teams and business intelligence consumers
- Implemented observability and data lineage practices using New Relic, OpenLineage, Marquez, and OpsGenie — improving pipeline traceability and incident response across the platform
- Used dbt to manage transformations, enforce data contracts, and maintain schema consistency across a complex distributed system (on-prem Kubernetes + GCP)

- - Led project to design and deliver a modern data platform on AWS, Kubernetes, Airflow, Airbyte, and dbt — covering architecture, pipeline development, and ongoing operations
- Drove a company-wide AWS cost optimization initiative, cutting annual infrastructure spend by 73% through resource rightsizing, pipeline efficiency improvements, and architectural redesign
- Refactored 300+ Python/Airflow pipelines, achieving significant gains in both runtime performance and reliability — reducing failures and improving end-to-end data quality across the platform
Implemented a data governance and quality framework aligned with GDPR requirements, establishing data standards, validation rules, and lineage practices that enabled trustworthy, audit-ready datasets
- Built an AI-powered data assistant using AWS Bedrock and RAG architecture, enabling stakeholders to query company datasets in natural language — removing dependency on ad-hoc SQL requests to the data team

- My main responsibility along with my team was to built out our data lake on AWS and Databricks using Delta Lake to manage the storage. I organized the data into clear layers—from raw ingestion to analytics-ready tables—and used partitioning to keep the pipelines fast and reliable as our data volume grew.

Managed our data stack using a mix of Spark, Hive, Docker, and Kubernetes to ensure we could process large volumes of data efficiently.

At the same time I was responsible for the following initiatives:

- Led the CCPA Compliance initiative from a technical and coordination standpoint. This involved mapping out PII across all company silos, building the API for user data requests, and working across teams to ensure we could properly delete or obfuscate data when requested.
- Created a dedicated ODS replica for the Analytics team, giving them a high-performance environment to run heavy queries without risking production database stability.
- Automated the entire data infrastructure using Terraform (IaC) and CI/CD, and put the necessary monitoring and alerting in place so we could catch issues before they impacted the business.
- Introduced real-time streaming with Kafka, shifting the business away from batch-only processing and allowing teams to make decisions based on live data.

- Architected a token price-discovery platform, managing the full lifecycle from data extraction to the delivery of advanced analytical tools.
Created automated crawlers for data enrichment, transforming raw, fragmented source data into a high-trust analytics product.

• Created 5 guided courses on data processing with Spark, Hive and Kubernetes
• Designed hands-on learning experiences focused on real-world data engineering workflows

- First data member on several projects, taking ownership from the initial Proof of Concept (POC) and the early-stage implementation of the company’s data platform, to launching to production.

- Facilitated the migration from on-premise to AWS, setting up the core cloud infrastructure and implementing basic CI/CD and monitoring for data workflows.

- Built the initial data stack using AWS services, including Kinesis for streaming and S3/Athena for batch processing, to transition the company toward a cloud-based data lake.

- Designed foundational data models and used Glue Crawlers to automate the discovery and organization of raw datasets.

- Developed the team’s first automated reports in QuickSight, translating raw data into visual insights for internal stakeholders.

- Supported Machine Learning initiatives by preparing training datasets and creating a basic API to serve model predictions to the mobile application.

- Handled end-to-end data tasks, from managing the Postgres database to ensuring PII data was handled securely according to basic governance standards.

Other internal initiatives:
• Led training programs on modern data architecture (4-month program)
• Mentored engineers and participated in technical interviews

* Developed automation workflows using N8N to eliminate repetitive manual tasks, including automatic data extraction from Jira — replacing ad-hoc Excel downloads with scheduled, hands-free pipelines.
* Designed strategic fraud monitoring dashboards adopted across multiple companies within the group, accelerating anomaly detection and improving operational decision-making.
*Identified fraudulent behavior patterns at a multi-company scale and translated them into concrete risk mitigation strategies.
* Developed a Direct Query consultation mode that transformed a dashboard into a forensic search engine, enabling analysts to investigate specific individuals by consolidating data from multiple tables in real time.
* Optimized Amazon QuickSight datasets improving efficiency and reducing load and processing times.
* Implemented data quality monitoring logic to detect deviations and ensure information reliability in production.

* * Identified that an onboarding screen was generating unnecessary user friction, leading to a redesign that increased credit card activation by 60%.
* Analyzed recurring error patterns in the app pipeline, achieving a 30% reduction in production error rate.
* Designed and maintained a dimensional Data Mart connected to AWS Athena, consumed daily by the Product team for business decision-making.
* Developed and maintained Power BI dashboards for business users, translating technical data into actionable visualizations for non-technical stakeholders.
* Implemented automated data refresh to ensure daily availability without manual intervention.
* Developed new entities and code improvements in AWS (Cloud9, Lambda), validating deployments via CodePipeline.
* Verified data quality and ingestion integrity across multiple sources (Athena, DynamoDB, Teradata, BigQuery) ensuring production data reliability.

* * Automated daily data processes through BigQuery stored procedures, reducing manual work from a full day to zero — freeing the team to focus on higher-value tasks.
* Designed and maintained Looker dashboards consumed across the entire company, eliminating recurring ad-hoc data requests that previously required manual extraction.
* Managed and analyzed large volumes of personal and credit data using BigQuery (GCP) and Hue (Impala/Hive), ensuring quality and integrity through SQL-based QA processes.
* Developed queries across multiple engines (Oracle, BigQuery, Hue) to support cross-functional data needs at scale.
* Created process documentation in Confluence, standardizing team workflows and reducing onboarding friction for new members.

* - Architected and optimized scalable data models and ETL pipelines, leveraging GCP and BigQuery to handle complex datasets and deliver actionable insights efficiently.
- Developed and launched dynamic, user-friendly dashboards and visualizations in Tableau and Looker, enabling stakeholders to make informed, data-driven decisions.
- Ensured data integrity and compliance through rigorous data governance, defining clear ownership structures, documenting data lineage, managing metadata, and implementing policy tagging for regulatory adherence.
- Implemented proactive monitoring solutions with tools like MonteCarlo, minimizing downtime and ensuring the health and reliability of critical data processes.
- Fostered a culture of innovation and analytics by leading training sessions, mentoring teams, and promoting the adoption of advanced analytics tools and best practices.
- Demonstrated strong problem-solving and communication skills by translating complex technical concepts into actionable business strategies, ensuring alignment across technical and non-technical stakeholders.

⚒️ Tools and skills:
GCP | BigQuery | Tableau | Looker | GitHub | DataDog | Kibana | Postman | Python (Pandas, Matplotlib, Seaborn, Scikit-learn) | SQL | Jira | Data Governance | Data Visualization

Created a unified customer database to achieve cross-selling between separate departments enhancing, normalizing and validating  data with external sources such as Google Maps API, local governmental entities and third party tools.
Maintained more than 50 ETLs from different tools and databases such as SQL Server, Oracle database, IBM DataStage, and Microsoft SSIS.
Analyzed more than 500 tables and ETLs using DataCleaner to create data quality standards across the whole organization.

Created and maintained the company's main data warehouse using BigQuery. Improving overall performance of  dashboards, website and customer response by 300%.
Automated over 50 processes in 3 months using Google BigQuery and Google Cloud Functions (Python) relieving more than 20hs/week of time consuming data tasks.
Created QA reports, dashboards and monitors providing daily updates for the analytics team using Google BigQuery and Microsoft Power BI.
Managed and coached a 3 person team in the Data and Insights team using Asana as work management tool and achieving over 90% total satisfaction from team members and final users.

Developed, implemented and deployed 10 ingestion data pipelines for a Juice retail and subscription company using Airflow as orchestration tools and DBT as main transformation tool. Including SFTP, Fivetran native and custom connections.
Implemented 6 custom Fivetran connections to consume third party APIs using Lambda functions (Python).
Migrated legacy tables from AWS Redshift and ETLs from AWS Glue to Snowflake. Created using Airflow as main tool for the pipeline as well as S3 to store backup files and DBT as transformation tools.
Created backfill process/logic to recover lost data from a failed legacy AWS Glue process retrieving 95% of the total lost data.
Implement new data architecture with a unified database (snowflake), new sources (third party APIs), easy to build pipelines and documentation with goods practices and a guide for future scalability

https://www.linkedin.com/in/hectorbe/

https://www.linkedin.com/in/lucas-mariano-contreras-251b9411b/

https://www.linkedin.com/in/georgina-de-bellis/

I worked as part of the data engineering team on a large-scale operational monitoring and diagnostic platform used to support decision-making across thousands of oil wells.

My role focused on data platform design and evolution, including:

Designing and evolving the system’s data model and data architecture, with a focus on scalability, clarity, and long-term maintainability.

Building and maintaining ETL processes to transform raw operational data into reliable and consistent datasets.

Integrating multiple heterogeneous data sources, including SQL Server, PostgreSQL, Oracle databases, and external APIs.

Applying technical and operational business rules to convert raw data into key indicators used for monitoring, alerts, rankings, and automated diagnostics.

Refactoring existing data workflows into a more centralized, modular, and maintainable data model, improving system efficiency and scalability.

Automating technical and operational workflows, including calculations, validations, and simulations for different extraction systems.

Collaborating closely with functional and operational teams, contributing to both technical design and business logic from a data engineering perspective.

https://www.linkedin.com/in/florencia-robledo-viano/

### Cloud Data Engineer

● Certified as a Professional Cloud Data Engineer.
● Delivered solutions based on Google Cloud Platform products for client-facing projects, including customers such as AT&T and Telus. Performed data analysis, hosted workshops, designed and proposed data architectures and constructed data pipelines, all focused on solving the customers’ needs.
● Guided clients in consulting projects by leveraging knowledge in GCP, including products such as: Dialogflow, BigQuery, Cloud Composer, Cloud Logging, Cloud Monitor, Cloud Functions, Cloud SQL, Cloud Storage and Data Loss Prevention.

JPMorgan

- Develop and maintain scalable data pipelines within Databricks using Python, PySpark, and Spark SQL, ingesting data from multiple sources (including Snowflake) for processing and transformation.

- Build curated datasets and data models in Databricks to support BI reporting, scorecards, and analytics for Business Banking (SMB) customers.

- Enable tracking of key metrics, including customer behavior, portfolio performance, and financial product KPIs, through optimized data solutions.

- Orchestrate end-to-end workflows using Airflow, ensuring data reliability, quality, and timely delivery across environments.

- Support CI/CD processes using Jenkins to enable automated deployment and integration of data pipelines in AWS-based environments.

- Collaborate with US-based Consumer Finance and Technology teams, contributing to cross-regional delivery of Business Banking data initiatives.
