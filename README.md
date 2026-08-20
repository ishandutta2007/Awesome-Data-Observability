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

- **[Monte Carlo](https://www.montecarlodata.com/)**  

  Leading enterprise data observability platform offering automated monitoring across freshness, volume, schema, and distribution, with strong lineage and incident workflows.



- **[Bigeye](https://www.bigeye.com/)**  

  Data observability and AI trust platform focused on SQL-native metrics, data SLAs, lineage, and cost/anomaly detection for modern data stacks.



- **[Acceldata](https://www.acceldata.io/)**  

  Comprehensive data observability solution covering data quality, pipeline reliability, and cost monitoring across hybrid and multi-cloud environments.



- **[Metaplane](https://www.metaplane.dev/)**  

  User-friendly data observability platform known for rapid setup, automated monitors, and strong usability for warehouse-centric teams.



- **[Soda](https://www.soda.io/)**  

  Data quality and observability platform with an open-source core (Soda Core), supporting code-first checks, contracts, and collaborative workflows.



- **[Anomalo](https://www.anomalo.com/)**  

  ML-native data observability platform specializing in unsupervised anomaly detection and value-level monitoring with minimal configuration.



- **[Datafold](https://www.datafold.com/)**  

  Data quality and CI-oriented platform focused on data diffing, regression testing, and proactive pipeline validation.



- **[Observe](https://www.observeinc.com/)**  

  Observability platform that extends into data and application monitoring with unified telemetry and investigation capabilities.



- **[Databand (IBM)](https://www.ibm.com/)**  

  Data pipeline observability and reliability platform (now part of IBM) for monitoring ETL/ELT jobs and data workflows.



- **[Telmai](https://www.telmai.io/)**  

  Data quality and observability solution emphasizing continuous monitoring and anomaly detection for enterprise data assets.



- **[WhyLabs](https://whylabs.ai/)**  

  AI and data observability platform focused on monitoring data drift, model performance, and data quality for ML systems.



- **[Validio](https://validio.io/)**  

  Data quality and observability platform with strong support for real-time and batch monitoring use cases.



- **[Elementary](https://www.elementary-data.com/)**  

  dbt-native data observability solution available as open-source or cloud service, focused on rapid monitoring for analytics engineers.



- **[Observe Inc.](https://www.observeinc.com/)**  

  Unified observability platform that includes data-related monitoring capabilities alongside broader system telemetry.



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
