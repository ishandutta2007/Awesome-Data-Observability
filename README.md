# Awesome-Data-Observability

## Top Data Observability Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Data Quality Monitoring, Anomaly Detection, Freshness & Volume Checks, Schema Drift, Lineage, Incident Management & Pipeline Reliability*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Observability**. These tools continuously monitor data pipelines and warehouses for freshness, volume, schema, distribution, and quality issues, alerting teams before broken data reaches downstream consumers or AI systems.



**Examples** include Monte Carlo, Bigeye, Acceldata, Metaplane, Soda, Anomalo, Datafold, Observe, Databand, Telmai, WhyLabs, Validio, Elementary, and Observe Inc. (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for data quality testing, dbt-native monitoring, anomaly detection, and open observability frameworks — ideal for data engineering teams that want transparency, Git-based workflows, and full control over their data reliability stack.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Pricing | Free Tier Limits |
| :--- | :--- | :--- | :--- |
| **[Monte Carlo](https://www.montecarlodata.com/)** | Leading enterprise data observability platform offering automated monitoring across freshness, volume, schema, and distribution, with lineage and incident workflows. | Enterprise quote-based (starts at ~$25,000/year for small deployments of 30–100 tables) | No free tier; 14 to 30-day guided POC available on request (limited to scoped tables/sources) |
| **[Bigeye](https://www.bigeye.com/)** | Data observability and AI trust platform focused on SQL-native metrics, data SLAs, lineage, and cost/anomaly detection for modern data stacks. | Enterprise quote-based (starts at ~$45,000/year for ~100 tables) | No free tier; guided pilot workspace available on request (restricted monitor count & catalog sync limits) |
| **[Acceldata](https://www.acceldata.io/)** | Comprehensive data observability solution covering data quality, pipeline reliability, and compute/cost monitoring across hybrid/multi-cloud environments. | Enterprise quote-based (custom annual contract; starts at ~$40,000–$50,000/year) | No free tier; 14 to 30-day enterprise POC/trial available upon consultation |
| **[Metaplane](https://www.metaplane.dev/)** | User-friendly data observability platform known for rapid setup, automated monitors, and strong usability for warehouse-centric teams (Datadog company). | Free tier available; Pro plan starts at ~$10/monitored table/month (or custom tier) | Free forever plan: Up to 10 monitored tables, up to 4 users, schema change alerts, column-level lineage |
| **[Soda (Soda Cloud)](https://www.soda.io/)** | Data quality and observability platform with an open-source core (Soda Core), supporting code-first checks, contracts, and collaborative workflows. | Free tier available; Team tier starts at $750/month (includes 20 datasets, +$8/dataset) | Free forever plan: Up to 3 production datasets with basic pipeline testing and alerting |
| **[Anomalo](https://www.anomalo.com/)** | ML-native data observability platform specializing in unsupervised anomaly detection and deep table value-level monitoring with minimal configuration. | Enterprise quote-based (typically starts at ~$50,000+/year) | No free tier; 30-day scoped evaluation pilot available upon demo request |
| **[Datafold](https://www.datafold.com/)** | Data quality and CI-oriented platform focused on data diffing, regression testing, and proactive pipeline validation. | Cloud tier starts at $799/month (billed annually); Enterprise custom | 14-day free trial on Cloud; Free tier available with limited Data Diff runs and basic lineage |
| **[Databand (IBM watsonx.data)](https://www.ibm.com/)** | Data pipeline observability and reliability platform (now integrated into IBM watsonx.data) for monitoring ETL/ELT jobs and workflows. | IBM Resource Unit quote-based / watsonx subscription (typically starts at ~$1,000+/month) | 30-day free trial of IBM watsonx.data (including data observability components, cloud credits limited) |
| **[Telmai](https://www.telmai.io/)** | Data quality and observability solution emphasizing continuous monitoring and anomaly detection for enterprise data assets. | Enterprise quote-based (custom annual contract; starts at ~$30,000–$40,000/year) | No free tier; 14-day guided proof-of-concept trial available on request |
| **[WhyLabs](https://whylabs.ai/)** | AI and data observability platform for data drift and model performance (commercial SaaS discontinued in 2025; open-sourced `whylogs`/`langkit`). | $0 (Commercial SaaS sunset; fully free self-hosted open-source on GitHub) | Free forever / Open Source (unlimited self-hosted profiles via `whylogs` & `langkit`) |
| **[Validio](https://validio.io/)** | Data quality and observability platform with strong support for real-time streaming and batch monitoring use cases. | Enterprise quote-based (custom tiered based on monitored assets & data volume) | 14-day free trial: Full platform features, up to 10 users, no credit card required |
| **[Elementary (Cloud)](https://www.elementary-data.com/)** | dbt-native data observability solution available as managed cloud service, focused on rapid monitoring for analytics engineers. | Scale tier starts at ~$500–$650/month (based on seats and up to 1K tables); Enterprise custom | 30-day free trial of Elementary Cloud (full features, self-service sign-up) |
| **[Observe Inc.](https://www.observeinc.com/)** | Unified telemetry and data observability platform built on Snowflake, providing log, trace, metric, and data pipeline monitoring. | Ingestion-based: Logs from $0.49/GiB, Traces from $0.59/GiB, Metrics from $0.008/M data points | 14-day free trial: Full platform access with high-ceiling compute credits, no credit card required |



## Open-Source GitHub Projects

- **[Great Expectations (GX Core)](https://github.com/great-expectations/great_expectations)**  

  Leading open-source data quality platform for defining expectations, validating data, generating documentation, and integrating with pipelines.



- **[Soda Core](https://github.com/sodadata/soda-core)**  

  Open-source data quality and contracts engine that uses YAML/SQL checks and integrates with modern data stacks.



- **[Elementary](https://github.com/elementary-data/elementary)**  

  Open-source, dbt-native data observability tool for monitoring data pipelines, anomalies, and test results with minimal setup.



- **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)**  

  Open-source metadata, data quality, lineage, and observability platform that serves as a context layer for data and AI.



- **[Deequ](https://github.com/awslabs/deequ)**  

  Amazon’s open-source library for defining unit tests on large-scale data using Apache Spark.



- **[re_data](https://github.com/re-data/re-data)**  

  Open-source data quality and monitoring tool designed to catch issues early in dbt and warehouse environments.



- **[dbt tests & packages](https://github.com/dbt-labs/dbt-core)**  

  Built-in and community testing capabilities within dbt that form the foundation of many open data quality workflows.



- **[Marquez / OpenLineage](https://github.com/MarquezProject/marquez)**  

  Open-source lineage collection and metadata service that underpins observability and impact analysis.



- **[Provero and lightweight YAML-first validators](https://github.com/)**  

  Emerging open-source tools focused on simple, declarative data quality checks and local anomaly detection.



- **[MobyDQ, ydata-quality, and other validation libraries](https://github.com/)**  

  Specialized open-source projects for automating data quality checks across pipelines and development stages.



### Additional Strong Open-Source Options

- Apache Griffin (legacy but still referenced) and other Spark-based quality frameworks.

- Custom anomaly detection notebooks using statistical methods (Z-score, IQR, etc.) on warehouse metrics.

- Prometheus + Grafana or OpenTelemetry pipelines adapted for data freshness and volume metrics.

- Data contracts implementations and schema registry tools that enforce quality at the boundary.

- Lineage visualizers and impact analysis tools built on OpenLineage events.



**Frameworks for building custom systems**: Start with **Great Expectations** or **Soda Core** for explicit data tests, layer **Elementary** or **re_data** for dbt-native observability, collect lineage via **OpenLineage/Marquez**, and store results in an open metadata catalog such as **OpenMetadata**. Orchestrate checks in Airflow, Dagster, or dbt Cloud, and alert via Slack/PagerDuty. This stack delivers production-grade data reliability with full transparency and no vendor lock-in on the core logic.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Data observability is only as effective as the coverage and ownership of the monitors. Open-source tools excel at explicit testing and dbt-native workflows but typically require more engineering effort to achieve the automatic, organization-wide coverage of commercial platforms.

- Always combine automated checks with clear data ownership, SLAs, and incident response processes.



---

**Made for data engineers, analytics engineers, and platform teams who want trustworthy, observable data.**

Let's make data reliability open, testable, and under your control.
