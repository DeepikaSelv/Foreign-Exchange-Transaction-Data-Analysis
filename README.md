# Foreign-Exchange-Transaction-Data-Analysis
📌 Project Overview

This project focuses on analyzing foreign exchange (Forex) transaction data using automation, OLAP techniques, and visualization tools. It integrates live currency exchange rate data, preprocesses it with Python, and delivers real-time insights through interactive Power BI dashboards. An alerting system was also implemented to monitor anomalies in exchange rate movements.

🛠 Tools & Technologies

Python – API integration, ETL automation, and preprocessing

Power BI – Dashboards, alerts, and OLAP operations

Power Query (M Language) – Data cleaning and transformations

SQL – OLAP cube operations and schema design (Star, Snowflake, Fact Constellation)

Fixer.io API – Source of live exchange rate data

Excel – Data exploration and validation

🎯 Features

Automated daily data extraction from Fixer.io API

Data preprocessing and normalization using Python & Power Query

OLAP operations (Slice, Dice, Drill-Down, Pivot) for deep analysis

Dynamic Power BI dashboards for real-time visualization

Threshold-based alert system with notifications via dashboard and external tools

Data warehouse schemas: Star, Snowflake, and Fact Constellation

📂 Project Workflow

Data Retrieval – API integration with Fixer.io to fetch exchange rate data.

Data Preparation – Flatten JSON data into structured tables.

Data Modeling – Build Fact & Dimension tables for OLAP analysis.

OLAP Processing – Slice, Dice, Drill-Down, Pivot for flexible exploration.

Visualization – Power BI dashboards with charts, KPIs, and filters.

Alerts – Trigger visual/email alerts when thresholds are exceeded.

🚀 Future Enhancements

Predictive analytics using machine learning models

Cloud-based data warehousing for scalability

Enhanced alerting with SMS/Push notifications
