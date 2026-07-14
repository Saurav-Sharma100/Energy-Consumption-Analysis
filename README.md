# Energy Consumption Analysis Dashboard

## Project Summary

A cloud-based analytics solution developed using **Snowflake** and **Tableau** to monitor renewable energy consumption, evaluate monthly usage patterns, and measure cost savings across different energy sources. The project combines cloud data warehousing, SQL-based data preparation, and interactive Tableau visualizations to support sustainability reporting and operational decision-making.

---

# Dashboard Preview

> *<img width="1801" height="899" alt="Image" src="https://github.com/user-attachments/assets/633c8610-a04b-4a3c-860d-534994de7738" />*

---

# Project Snapshot

| Category | Details |
|----------|---------|
| **Project Type** | Business Intelligence Dashboard |
| **Tool** | Tableau Desktop |
| **Domain** | Energy & Sustainability Analytics |
| **Primary Data Source** | Snowflake |
| **Data Preparation** | Snowflake SQL |
| **Dashboard** | Energy Consumption Analysis |
| **Deployment** | Tableau Cloud |
| **Primary Analysis** | Energy Usage, Cost Savings & Sustainability Performance |

---

# Project Overview

Organizations investing in renewable energy require continuous visibility into energy consumption patterns, operational efficiency, and cost savings to evaluate the effectiveness of sustainability initiatives. Interactive analytics enable stakeholders to monitor energy usage trends while identifying opportunities to optimize resource utilization and reduce operational costs.

This project delivers a cloud-based reporting solution by integrating Snowflake with Tableau. The dashboard transforms renewable energy data into meaningful business insights, allowing users to explore monthly consumption trends, evaluate financial savings, and assess renewable energy performance through an intuitive visual interface.

---

# Business Problem

As organizations transition toward renewable energy sources, monitoring consumption and measuring financial benefits become essential for evaluating sustainability initiatives. Without centralized reporting, identifying changes in energy usage or understanding the impact of renewable energy adoption can be both time-consuming and inefficient.

The objective of this project was to develop an interactive analytical dashboard that consolidates renewable energy data into a single reporting solution capable of supporting operational monitoring and sustainability-focused decision-making.

---

# Project Objectives

- Develop an interactive Tableau dashboard for renewable energy analysis.
- Integrate Snowflake as the cloud data warehouse.
- Prepare analytical data using SQL within Snowflake.
- Monitor monthly renewable energy consumption.
- Measure cost savings generated through renewable energy usage.
- Publish the completed dashboard to Tableau Cloud for collaborative reporting.

---

# Tools & Technologies

| Tool | Purpose |
|------|----------|
| **Snowflake** | Cloud Data Warehouse |
| **Tableau Desktop** | Dashboard Development |
| **Tableau Cloud** | Dashboard Publishing |
| **Snowflake SQL** | Data Understanding & Transformation |
| **Amazon S3** | Initial Data Storage |

---

# Dataset Overview

The dashboard is built using renewable energy consumption data stored within Snowflake.

The dataset contains information related to:

- Energy consumption
- Renewable energy usage
- Monthly energy trends
- Cost savings
- Energy categories
- Time-based operational metrics

The dataset supports sustainability reporting by enabling users to evaluate renewable energy performance while monitoring monthly usage and associated financial benefits.

---

# Data Preparation (Snowflake SQL)

Before connecting Tableau to Snowflake, SQL was used within the cloud data warehouse to understand and prepare the dataset for reporting.

The preparation process included:

- Loading source data into Snowflake.
- Reviewing dataset structure and business attributes.
- Performing SQL-based data understanding.
- Preparing the dataset for analytical reporting.
- Validating the transformed data before visualization in Tableau.

Preparing the data within Snowflake centralizes transformation logic, improves scalability, and ensures Tableau connects to a reporting-ready dataset with minimal additional preparation.

---

# Data Model

The dashboard is built using a reporting-ready dataset managed within Snowflake.

Rather than relying on extensive calculations inside Tableau, the required business fields were prepared during the data engineering stage, allowing Tableau to focus primarily on interactive analysis and visualization.

This separation of responsibilities between the cloud data warehouse and the visualization layer improves maintainability, simplifies report development, and reflects modern cloud Business Intelligence architecture.

---

# Snowflake Implementation

The reporting dataset was prepared within **Snowflake**, enabling Tableau to connect directly to a centralized cloud data warehouse rather than relying on local files. Preparing the data inside Snowflake improves scalability, simplifies maintenance, and supports a modern cloud-based Business Intelligence workflow.

---

## Cloud Data Ingestion

The analytical workflow began by loading the source dataset into an **Amazon S3** bucket before importing it into Snowflake.

Using cloud object storage as the initial staging area reflects a common enterprise data ingestion pattern, where raw data is securely stored before being processed within a cloud data warehouse.

### Business Value

- Centralizes raw data storage.
- Supports scalable cloud-based data pipelines.
- Simplifies data ingestion into Snowflake.

---

## Snowflake SQL Data Preparation

After loading the dataset into Snowflake, SQL was used to understand the structure of the data and prepare it for reporting.

The preparation process focused on:

- Reviewing business attributes.
- Validating data quality.
- Preparing reporting-ready fields.
- Ensuring consistency before visualization.

Moving these activities into Snowflake keeps the visualization layer lightweight while improving maintainability of the reporting solution.

---

## Tableau–Snowflake Integration

Tableau connects directly to Snowflake, allowing the dashboard to retrieve data from a centralized cloud warehouse rather than importing standalone files.

This architecture enables organizations to separate data storage from visualization while supporting larger datasets and more scalable reporting environments.

### Business Value

- Enables centralized cloud reporting.
- Reduces dependency on local data files.
- Improves scalability for future data growth.
- Supports enterprise Business Intelligence workflows.

---

## Tableau Cloud Publishing

After dashboard development, the workbook was published to **Tableau Cloud**, making the report accessible through a centralized cloud platform.

Publishing to Tableau Cloud enables secure report sharing while ensuring users always interact with the latest published version of the dashboard.

---

# Dashboard Walkthrough

## Energy Consumption Analysis

> *<img width="1801" height="899" alt="Image" src="https://github.com/user-attachments/assets/633c8610-a04b-4a3c-860d-534994de7738" />*

The dashboard presents renewable energy performance through a combination of operational and financial metrics. Interactive visualizations allow users to monitor monthly energy consumption, evaluate cost savings, and compare performance across different renewable energy categories.

Rather than focusing on a single KPI, the dashboard combines multiple perspectives to provide a more complete understanding of sustainability performance.

### Business Value

- Tracks renewable energy consumption over time.
- Measures financial savings generated through renewable energy initiatives.
- Supports sustainability reporting.
- Helps identify consumption patterns that may support operational improvements.

---

# Key Business Insights

The dashboard enables users to evaluate renewable energy performance by combining consumption metrics with financial outcomes.

Key analytical capabilities include:

- Monitoring monthly renewable energy consumption.
- Measuring cost savings achieved through renewable energy adoption.
- Comparing energy performance across different reporting periods.
- Exploring consumption trends through interactive visualizations.
- Supporting sustainability initiatives through data-driven reporting.

By bringing operational and financial information together, the dashboard helps organizations better understand the impact of renewable energy programs.

---

# Business Recommendations

The analytical insights generated by this dashboard can support both operational and sustainability objectives.

- Monitor monthly energy consumption to identify changing usage patterns.
- Evaluate cost savings regularly to measure the effectiveness of renewable energy investments.
- Use historical consumption trends to support future resource planning.
- Continue maintaining Snowflake as the centralized analytical platform for renewable energy reporting.
- Publish dashboards through Tableau Cloud to improve collaboration and accessibility across business teams.

These recommendations help organizations maximize the value of sustainability reporting while supporting continuous operational improvement.

---

# Technical Highlights

This project demonstrates modern cloud Business Intelligence practices by combining cloud storage, cloud data warehousing, SQL, and Tableau.

- Loaded source data into **Amazon S3** before processing.
- Imported analytical data into **Snowflake** for centralized cloud storage.
- Used **Snowflake SQL** to understand and prepare the reporting dataset.
- Connected Tableau directly to Snowflake for cloud-based reporting.
- Designed an interactive dashboard focused on renewable energy consumption and cost savings.
- Published the completed workbook to **Tableau Cloud** for cloud-based report distribution.

---

# Skills Demonstrated

This project demonstrates practical cloud analytics, SQL, and Tableau development skills, including:

### Cloud Data Platforms

- Amazon S3
- Snowflake
- Cloud data warehousing
- Cloud data integration

### SQL

- Data understanding
- Data preparation
- Data validation
- Analytical dataset creation

### Tableau Development

- Interactive dashboard design
- Time-based trend analysis
- Sustainability reporting
- Tableau Cloud publishing

### Business Analysis

- Renewable energy analytics
- Sustainability reporting
- Energy consumption analysis
- Cost savings analysis
- Operational performance monitoring

---

# Conclusion

This project showcases a cloud-native analytics solution built around Snowflake and Tableau to support renewable energy reporting. By combining cloud-based data storage, SQL-driven data preparation, and interactive visualizations, the dashboard enables stakeholders to evaluate energy consumption patterns and quantify the financial impact of renewable energy initiatives.

Unlike traditional reporting workflows that depend on local data sources, this solution demonstrates a modern cloud architecture where data is managed within Snowflake and delivered through Tableau Cloud. The project highlights practical experience with cloud data warehousing, sustainability analytics, and interactive business reporting, making it a valuable addition to an enterprise Business Intelligence portfolio.
