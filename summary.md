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

### JPMorgan

- Develop and maintain scalable data pipelines within Databricks using Python, PySpark, and Spark SQL, ingesting data from multiple sources (including Snowflake) for processing and transformation.

- Build curated datasets and data models in Databricks to support BI reporting, scorecards, and analytics for Business Banking (SMB) customers.

- Enable tracking of key metrics, including customer behavior, portfolio performance, and financial product KPIs, through optimized data solutions.

- Orchestrate end-to-end workflows using Airflow, ensuring data reliability, quality, and timely delivery across environments.

- Support CI/CD processes using Jenkins to enable automated deployment and integration of data pipelines in AWS-based environments.

- Collaborate with US-based Consumer Finance and Technology teams, contributing to cross-regional delivery of Business Banking data initiatives.

- ### Ring

- As a Data Engineer at Ring (a subsidiary of Amazon), responsible for building and maintaining high-volume, scalable data pipelines supporting both batch and real-time processing. Using Python, SQL, Apache Airflow and AWS ecosystem, I contributed to the ingestion, transformation, and delivery of data into a petabyte-scale Amazon Redshift data warehouse and S3-backed data lake.

Key Contributions:
• Developed and maintained over 2,000 daily and hourly ETL pipelines, populating 200+ curated datasets that powered business-critical analytics and reporting.
• Supported a petabyte-scale Redshift cluster, serving as the data foundation for 7,000+ Tableau extract refreshes daily and ~20,000 ad hoc queries across the business.
• Built reliable data workflows using Apache Airflow (MWAA) and PySpark/SparkSQL, ensuring efficient data delivery, recovery, and monitoring at scale.
• Implemented real-time streaming pipelines leveraging MSK, AWS Kinesis, Lambda, and API Gateway to enable low-latency data consumption.
• Led integrations with external partners (e.g., Zendesk, SendGrid) to ingest third-party data into the data warehouse, enhancing downstream analytics and visibility.
• Utilized Logstash, Elasticsearch, and Kibana for observability and operational monitoring of data pipelines and system health.

- Technologies & Tools:
Languages & Processing: Python, SQL, PySpark/SparkSQL
Workflow Orchestration: Apache Airflow (MWAA)
Streaming & Messaging: MSK, AWS Kinesis, Lambda, API Gateway, Cognito, Firehose, DynamoDB
Data Platforms: Amazon Redshift (Petabyte-scale), Amazon S3, EMR, Athena
Monitoring: Logstash, Elasticsearch, Kibana
Visualization Support: Tableau (7K+ extracts/day), ad hoc querying

### Personal

 - Relevar necesidades de la tribu y traducirlas en iniciativas analíticas de alto impacto que empujen los OKRs.

- Ser el referente de datos para el equipo de Producto, acompañando la evolución hacia decisiones basadas en información.

- Analizar el comportamiento del cliente in-app para identificar palancas que mejoren el engagement, la retención y la monetización del negocio.

✔️ Desarrollar segmentaciones avanzadas de clientes para potenciar la relevancia de contenidos, ofertas y mensajes.

✔️ Crear y automatizar dashboards de métricas clave (churn, adopción, tiempos), asegurando que la información sea accionable y escalable.

✔️ Priorizar el backlog bajo metodología Agile, equilibrando demandas urgentes con proyectos de análisis profundo.

✔️ Comunicar hallazgos y desvíos de manera efectiva (storytelling) a stakeholders, transformando datos complejos en narrativas claras.

✔️ Promover una cultura self-service + data-driven, democratizando el acceso a los datos y capacitando al equipo en el uso de herramientas analíticas.

-  Empatía con el usuario para hacer foco en resolver sus problemas a través de los datos.

-  Soy Data Engineer especializado en diseñar arquitecturas escalables, optimizar procesos de datos críticos y aplicar metodologías de Ingeniería de Software para construir plataformas robustas. 

A lo largo de mi carrera, he evolucionado desde el análisis y Machine Learning hasta el liderazgo técnico en proyectos de gran escala. Mis principales hitos incluyen:
• Arquitectura y Liderazgo: Lideré un equipo para migrar de bitbucket a github y cambiando el enfoque a Data Mesh, centralizando el CI/CD e impactando más de 800 modelos de dbt y 1000 DAGs de Airflow.  
• Performance: Fui pieza clave en la migración core hacia Snowflake en el sector financiero, reduciendo tiempos de procesamiento de ETLs de 5 horas a 30 minutos.  
• Configuration-as-Code: Implementé la generación dinámica de DAGs mediante YAML y Jinja, empoderando a Data Analysts y Scientists para gestionar sus propios pipelines de forma autónoma.

Stack Tecnológico: Python, SQL | AWS, Snowflake, PostgreSQL | Apache Airflow, dbt, PySpark | CI/CD (GitHub/GitLab/Bitbucket), Docker.  

Lidere iniciativas clave para la modernización de la plataforma de datos y la automatización de procesos críticos del negocio:
• Participé activamente en la migración core de bases de datos desde PostgreSQL hacia Snowflake. Esto generó una mejora drástica en el rendimiento de las consultas, optimizando procesos que tardaban 5 horas a solo 30 minutos, y reduciendo otros de 2 horas a 10 minutos.  
• Lideré la creación de pipelines de ETL robustos utilizando Python, Airflow y SQL. Estos pipelines automatizaron reportes impositivos y procesaron información sensible como la central de deudores, gestión de préstamos y el cálculo del perfil de riesgo de los clientes.  
• Desarrollé y optimicé la arquitectura Cloud en AWS, administrando y consultando recursos mediante S3 y Athena.  
• Implementé la creación dinámica de DAGs en Apache Airflow, estandarizando el código y agilizando significativamente los tiempos de desarrollo y despliegue de todo el equipo.

Como Data Engineer, asumí el mayor desafío técnico de mi carrera liderando iniciativas estratégicas de reestructuración y optimización de procesos a nivel organizacional:
• Lideré un equipo de 7 personas en el proyecto de validaciones automáticas de dbt y Airflow, gestionando el ciclo de vida ágil (planificación, priorización, weeklys y retrospectivas).
• Dirigí la reestructuración y migración completa de 6 repositorios desde Bitbucket hacia GitHub, impactando a una escala de más de 800 modelos de dbt y 1000 DAGs de Airflow. Esto implicó rediseñar la arquitectura hacia un enfoque Data Mesh (orientado por dominios), crear los scripts de migración y trasladar todos los pipelines de CI/CD.
• Optimicé radicalmente la estructura de validaciones (CI/CD): centralicé los scripts de validación en un único repositorio core, eliminando la redundancia que existía por proyecto y facilitando el despliegue de nuevas features para todo el equipo de datos.
• Desarrollé una herramienta interna para la generación dinámica de DAGs en Airflow impulsada por archivos YAML. Implementé templates personalizados con Jinja y utilicé dag-factory, logrando un enfoque 100% por configuración (Configuration-as-Code). Esto empoderó a Data Analysts y Data Scientists para crear sus propios pipelines de forma autónoma, y permitió que cualquier actualización en un template impacte globalmente sin necesidad de modificar código DAG por DAG.
• Creé el proceso de aprobación automática de Pull Requests para DAGs y modelos de dbt, integrando validaciones y notificaciones en tiempo real mediante Slack.
• Implementé soluciones en AWS, destacando la generación de archivos para Backup de Amazon QuickSight mediante AWS Lambda y scripts de recuperación con Python.  
• Construí y normalicé procesos de ingesta de datos desde APIs y Google Sheets utilizando Python, Airflow y S3. Además, generé la documentación oficial de buenas prácticas para la construcción de modelos en dbt.

- Reduced critical SLA breaches 80% (15 → 3/year) by engineering centralized monitoring across 15+ cloud and on-premise ETL pipelines using GCP Monitoring, Cloud Logging, and custom alerting scripts.

- Owned production support and on-call incident response (1–5 incidents/week) for pipelines processing up to 50 GB/day, including a high-volume pipeline ingesting 100M records/day from MySQL, SQL Server, and flat files into BigQuery

- Architected a scalable data extraction and processing framework using Airflow, BigQuery, and Cloud Run — used daily by 3 teams to serve 10+ clients, fully operational for 3+ years. 

- Built a statistical anomaly detection system that surfaced hidden data quality failures across multiple client datasets.

- Led full Terraform IaC adoption across all GCP resources: BigQuery, Cloud Build, Composer, Monitoring, Pub/Sub, Cloud SQL, GCS, Scheduler — enabling version-controlled CI/CD pipelines.

- Deployed and owned an Apache Superset BI instance adopted across all teams for operational reporting.

- Delivered internal training on Python, GCP, Terraform, and pipeline engineering to junior/mid engineers.

Stack: GCP · BigQuery · Dataflow · Cloud Composer · Apache Airflow · Cloud Run · Pub/Sub · Terraform · Python · SQL · Docker · CI/CD · Cloud Monitoring

- Designed a high-volume IoT streaming pipeline: GCP Pub/Sub → Dataflow → Cloud Functions → Workflows → Cloud Storage data lake + InfluxDB time-series DB.

- Built production RESTful APIs (FastAPI + OpenAPI/Swagger) for real-time and aggregated sensor data retrieval. 

- Deployed a containerized anomaly detection service (Docker + Cloud Run) applying statistical rules to time-series data — automated daily monitoring with zero manual intervention.

- Engineered a solar energy output forecasting model using Python (FB Prophet) and weather APIs, integrated into client-facing systems.  

Stack: GCP · Pub/Sub · Dataflow · Cloud Functions · Cloud Run · Docker · FastAPI · InfluxDB · Python · FB Prophet

 Pipelines: Diseñar e implementar procesos de ingesta/transformación en arquitecturas modernas. 
🔹 Integración: Asegurar que los datos de diversas fuentes sean consistentes y accesibles. 🔹 Performance: Optimizar constantemente los flujos para una entrega eficiente.

Own end-to-end data platform architecture for a high-volume e-commerce and sports-collectibles business, spanning ingestion, lakehouse storage, warehouse modeling, streaming, orchestration, and the underlying cloud infrastructure — across 14+ services.

Designed and maintained an Apache Iceberg–based lakehouse on AWS Glue Data Catalog (PyIceberg), including upsert/merge logic, a disaster-recovery framework for weekly backups and table recovery, and OPTIMIZE/compaction jobs to keep table runtimes manageable.

Own Shopify order ingestion end-to-end: migrated to Shopify's GraphQL Bulk API fixed OOM issues and built a TypeScript/Fastify service generating Oracle finance and ECOMM reports from Shopify data across multiple locales. 

Built ingestion and curation pipelines for Amazon, Walmart Marketplace, Magento, Airtable, Genesys and a live foreign-exchange rate feed.

Integrated marketing/product data sources (Braze, Salesforce, Amplitude, Algolia, AppsFlyer, MaxMind) into the warehouse, including automated Braze-triggered customer messaging jobs.

Built a real-time Segment-to-Snowflake event pipeline (Kinesis Firehose + Lambda transform), and published the pattern as a versioned, reusable Terraform module for org-wide adoption.

Built and operate Airflow (Astronomer) DAGs for ops metrics reporting, dbt test orchestration, missing-event monitoring, and GeoIP mapping automation, with Slack-based alerting wired into each.

Built a Scrapy-based web-scraping platform (deployed via AWS CDK/ECR) for sports data ingestion (Sportradar, MLB, Fangraphs, Beckett), including Cloudflare-bypass handling and Slack-based failure alerting.

Manage Snowflake infrastructure via Terraform: RBAC (roles, warehouses, service users), OAuth security integrations for ERP system access, and schema/database provisioning across business units.

Maintain AWS CDK Pipelines infrastructure-as-code across ingestion, curation, and reporting stacks, with full pytest/snapshot-test coverage as a deployment gate.


🔹 Actualmente estoy en el sector de Data Onboarding en Mercado Pago midiendo y analizando el comportamiento de usuarios en la billetera digital.

🔹 Especializado en analytics engineering, modelado de datos y optimización de pipelines analíticos, con foco en métricas core de producto como onboarding, activación y hábito. Experiencia definiendo KPIs, diseñando frameworks de A/B testing y acompañando decisiones de negocio basadas en datos.

🔹 He trabajado en la integración de MCPs dentro de plataformas internas de orquestación de workflows, colaborando estrechamente con equipos de backend, data y producto.

🔹 Actualmente estoy orientando mi carrera hacia Applied AI y sistemas basados en LLMs, buscando combinar una base sólida en datos, métricas, experimentación y arquitectura backend para construir soluciones de IA prácticas, medibles y escalables.

- Engineered and maintained ETL data pipelines, ensuring seamless data flow and integrity throughout the data lifecycle.

- Conducted comprehensive data quality tests to validate the accuracy, completeness, and consistency of the data, guaranteeing high-quality data outputs for downstream consumption.

- Defined key metrics and KPIs for the marketing team, leveraging data insights to drive informed decision-making and optimize marketing strategies for enhanced customer engagement and acquisition.

- - Used SQL and custom frameworks to generate DAGs and perform complex data transformations. Innovatively incorporated additional features to enhance functionality and efficiency.

- Conducted meticulous data modeling to guarantee optimal structures for streamlined processing and insightful analysis, ensuring seamless integration with existing systems.

- Ensured data quality by executing rigorous testing and debugging procedures, maintaining impeccable standards throughout all stages of the data lifecycle.

- Leveraged Kubernetes and Docker to facilitate streamlined deployment processes, providing crucial on-call maintenance support to uphold system integrity and availability.

- Utilized Spark for select tasks, harnessing its capabilities to enhance processing speed and scalability in specific job scenarios.

- Led the end-to-end design and maintenance of ETL pipelines, leveraging a comprehensive tech stack including SQL, Python, Spark, dbt, and Airflow to ensure robust data processing and transformation.

- Spearheaded data warehouse design and modeling initiatives, optimizing data structures and architectures to facilitate efficient and scalable data processing workflows.

- Collaborated closely with cross-functional teams to understand business requirements and translate them into innovative data solutions, driving organizational success through data-driven insights.

- Orchestrated the implementation of Snowflake, a cutting-edge data warehousing platform, to establish a scalable infrastructure for data storage and advanced analytics capabilities.

- Leveraged AWS services to manage and process large volumes of data, ensuring high availability, reliability, and security of critical data assets.

- Pioneered the integration of real-time data ingestion and processing capabilities using Apache Pulsar, enabling timely insights and decision-making based on up-to-the-minute data.

https://www.linkedin.com/in/juanafanadordataengineer/

https://www.linkedin.com/in/cruzpinedafabian/

### Specialist Data Engineer & Tech Lead

Como Tech Lead y Specialist Data Engineer me encuentro a cargo de las definiciones y direcciones de las mejores prácticas técnicas y de arquitectura para el equipo. Doy soporte y mentorías para nuestros ingenieros de datos al igual que miembros de otros equipos.
Me encuentro a cargo de las code reviews y de generar patrones saludables para mejoras del código. Estoy a cargo del desarrollo de las habilidades técnicas del equipo al igual que en la toma de decisiones/desarrollo sobre que herramientas de trabajo utilizar. Y me encuentro diseñando y construyendo frameworks al igual que herramientas personalizadas que orquestan agentes autónomos de IA al igual que soluciones mediante Spec Driven Develpment.
Asisto en refinar el alcance técnico de las soluciones junto a nuestro P.O.; mantengo alineados los criterios de gobernanza de datos con nuestros referentes y colaboro con nuestros partners externos y stakeholders donde sea necesario.

### Senior Data Engineer & Data Product Owner
Como Data Product Owner y Senior Data Engineer, lidero la definición y evolución de productos de datos que conectan Infraestructura, Analytics, Strategy y Operations, traduciendo necesidades de negocio en soluciones escalables apalancado en metodologías ágiles.
Tengo ownership end-to-end sobre el ciclo de vida de los productos de datos: desde el diseño de arquitectura hasta su implementación, operación en producción y mantenimiento posterior.
Diseño y desarrollo soluciones sobre GCP, utilizando prácticas de Infrastructure as Code (Terraform) y, automatizaciones con Python y Bash, asegurando escalabilidad, confiabilidad y eficiencia operativa.
Además, soy responsable de la construcción, administración y monitoreo de pipelines de datos y del mantenimiento del data warehouse a nivel regional, garantizando calidad, disponibilidad y gobierno de la información para la toma de decisiones.
Al igual que el desarrollo técnico de los miembros de mi equipo y terceros.

### Senior B.I. Analyst | Data Developer
Soy el Analista Senior dentro del Equipo de Mejora Continua a cargo de proveer información analítica para nuestros proyectos, buscar puntos de partida para nuevas mejoras, insights de negocio, al igual que soporte a las células de proyectos especiales, soporte operativo y cross. Dentro de mis responsabilidades también me encargo del desarrollo de nuestro ecosistema de datos e infraestructura, crear procesos de automatización a distintos niveles. Creación de dashboards, administración de nuestro sandbox al igual que la gestión de documentación y armado de modelos de datos a nivel Regional (Latam). El último año en el rol también estuve encargado de liderar el equipo de BI.

• Designed and optimized analytical models in BigQuery, supporting large-scale fintech reporting and data products. 

• Built robust and incremental ETL pipelines using SQL and Python, processing high-volume datasets with strong performance.

• Developed event-driven ingestion workflows using Pub/Sub and BigQuery to enable near-real-time data availability.

• Transformed raw and semi-structured data into business-ready models aligned with analytics and product needs.

• Implemented data quality validations and monitoring to ensure consistency, accuracy, and SLA compliance.

• Designed and maintained scalable data ingestion pipelines under a Medallion Architecture (Bronze / Silver / Gold), building Batch, Microbatch, and Near-Real-Time (NRT) flows on AWS (S3, EMR, Kinesis, SQS, Lambda) architectures.

• Developed and optimized ETL/ELT processes using Python, SQL, and DBT, implementing incremental models, reusable macros, documentation, and automated tests to ensure data quality and long-term maintainability.

• Created and orchestrated Airflow DAGs to execute DBT models and custom data processing scripts.

• Collaborated with product, analytics, and engineering teams to translate business requirements into scalable data solutions aligned with data product roadmaps.

• Designed and implemented data integrations between the data lake and external platforms for tracking and engagement (Amplitude, Braze), enabling behavioral analytics, user segmentation, and real-time activation workflows.

• Took ownership of data initiatives across multiple business units, leading technical design and reviewing implementations to ensure performance and best practices.

-Data Analytics Engineer in the banking industry, working with AWS-based architectures, leveraging services across the AWS ecosystem to build scalable and reliable data platforms. I orchestrate data workflows using Apache Airflow and design transformation layers with DBT within a modern data lake architecture.

- Optimized DBT models that were failing due to excessive data processing, redesigning transformations and implementing an SCD (Slowly Changing Dimensions) -based framework that reduced execution time by ~50% for critical workloads.

- Designed and implemented batch and near real-time ingestion pipelines, using AWS Kinesis and Firehose. 

- Developed Python-based scripts to extract data from APIs and ingest it into the Data Lake.

- Contributed to CI/CD improvements by implementing automated PR validation workflows in GitHub, using Docker images, enforcing code quality standards for DBT models and Airflow DAGs. This reduced PR approval time drastically and allowed the team to focus only on high-impact changes.

- Continuously leverage AI-driven solutions and applied AI tools and agents to optimize data workflows and enhance personal and team productivity. 

- Contributed to the development of GitHub Actions to standardize deployment processes.

Defined and led the design of enterprise data architectures on AWS for enterprise environments, in regulated fintech and banking contexts, enabling scalable, governed, and metadata-driven platforms adopted across diverse business domains.

Key achievements:
• Architected a cloud-native Lakehouse on AWS (Terraform, Spark, Iceberg, Airflow) with real-time ingestion via Kinesis Streams/Firehose for event-driven integrations, consolidating 100+ business domains and reducing dataset delivery time from 4 weeks to 3 days.

• Directed the modernization from on-premise to AWS, establishing Infrastructure-as-Code standards with Terraform and reducing environment provisioning time from 5 days to 2 hours, with over 80 % of infrastructure managed as code.

• Defined reusable architecture patterns and domain ownership models aligned with Data Mesh principles, decreasing dependencies on the central team from 10+ to 1 request per month and strengthening data accountability org-wide.

• Established metadata-driven governance with AWS Glue, Lake Formation, and LF-Tags, integrating AI-assisted validation (Amazon Bedrock) to achieve 70% metadata completeness and reduce downstream inconsistencies by 30%.

• Embedded FinOps principles into architectural design decisions, optimizing cloud resource usage and reducing monthly AWS spend by 20% through rightsizing, automation, and governance.

Leading the design and implementation of a metadata-driven Databricks Lakehouse modernization for a renewable energy analytics platform, establishing scalable ingestion, governance, and deployment standards.

Key achievements:

• Designed reusable ingestion frameworks for APIs, files, and database tables using Databricks Asset Bundles and data contracts, reducing source-specific implementation effort by ~50% and shortening the onboarding of 
new entities from 2–3 days to less than 1 day.

• Defined auditable ingestion patterns for incremental loads, historical backfills, full-source reconciliation, deduplication, and soft deletes, improving consistency and traceability across 20+ ingested entities.

• Standardized Unity Catalog governance through automated metadata, tagging, and access-control synchronization, automating ~80% of recurring governance configuration and enabling consistent security policies across environments.

• Strengthened platform reliability through automated validation, deployment workflows, test coverage, and operational metrics, reducing pre-deployment validation time by ~40%.
