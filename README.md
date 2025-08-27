# 📊 Power BI Loan Default Analysis Project

## 🚀 Overview

This project demonstrates a complete end-to-end data analytics pipeline using Microsoft SQL Server and Power BI. It focuses on analyzing loan default patterns to assist financial institutions in making informed lending decisions. The solution includes data ingestion, transformation, modeling, visualization, and automated refresh strategies—ideal for interview preparation and real-world deployment.

---

## 🧰 Tools & Technologies

| Tool               | Purpose                                      |
|--------------------|----------------------------------------------|
| Power BI Desktop   | Data modeling, visualization, and reporting  |
| Power BI Service   | Cloud-based publishing and dataflows         |
| SQL Server         | Data storage and query execution             |
| SSMS               | SQL Server Management Studio for scripting   |
| Power Query Editor | Data cleaning and transformation             |
| Data Gateway       | Secure connection between on-prem SQL Server and Power BI Service |

---

## 📂 Project Structure

```plaintext
├── SQL Server Setup
│   └── Loan Default Dataset Import
├── Power BI Desktop
│   └── Data Modeling & Report Design
├── Power BI Service
│   └── Dataflow Creation & Scheduled Refresh
├── DAX Measures
│   └── KPI Calculations (YOY, Median, Averages)
├── Visualizations
│   └── Line Charts, Donut Charts, Ribbon Charts, Decomposition Trees
```

---

## 📈 Key Features

- ✅ **Dataflow Integration**: Centralized data cleaning for scalable reporting
- ✅ **DAX Mastery**: Advanced measures using CALCULATE, FILTER, SWITCH, MEDIANX, SUMX, etc.
- ✅ **Dynamic Visuals**: Interactive charts for loan trends, default rates, and demographic insights
- ✅ **Validation**: Cross-checked results with Excel pivot tables for accuracy
- ✅ **Scheduled & Incremental Refresh**: Ensures up-to-date reporting with optimized performance
- ✅ **Report Sharing**: Secure collaboration within organizational boundaries

---

## 📊 KPIs & Insights

- 📌 Loan Amount by Purpose
- 📌 Average Income by Employment Type
- 📌 Default Rate by Year & Employment Type
- 📌 Median Loan by Credit Score Category
- 📌 YOY Loan Amount & Default Change
- 📌 YTD Loan Amount by Credit Score & Marital Status

---

## 🧠 Learning Outcomes

- Understand the role of dataflows in enterprise BI architecture
- Master DAX for analytical depth and performance
- Design visually compelling and validated dashboards
- Automate refresh cycles for real-time insights
- Prepare for data science interviews with hands-on experience

---

## 📅 Refresh Strategy

| Type             | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| Manual Refresh   | Triggered on-demand via Power BI Service                                    |
| Scheduled Refresh| Daily updates configured via Power BI workspace settings                    |
| Incremental Refresh | Refreshes only recent data using date-time filters (requires Premium)     |

---

## 📤 Deployment

1. Import dataset into SQL Server
2. Create dataflow in Power BI Service
3. Connect Power BI Desktop to dataflow
4. Build and publish report
5. Configure scheduled refresh
6. Share securely within organization

s

