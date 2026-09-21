# 📊 End-to-End Oil & Gas Performance Analytics

## 💰 Financial Performance & Operational Efficiency Dashboard

An end-to-end **Power BI Business Intelligence project** that transforms operational and financial data into actionable insights for decision-making in the **Oil & Gas industry**.

---

## 📌 Project Overview

The Oil & Gas industry generates vast amounts of operational and financial data every day. However, data only becomes valuable when it is transformed into meaningful insights that support better business decisions.

This project demonstrates an **end-to-end analytics workflow using Power BI**, covering data preparation, data modeling, DAX development, dashboard design, and business insights.

The objective of this project is to analyze **financial performance, production, operational efficiency, maintenance, asset reliability, pipeline status, and operational incidents**.

---

## 🎯 Business Objectives

This project answers key business questions such as:

- 🌍 Which regions and countries contribute the most revenue?
- 💰 How does operating cost compare with revenue and profit?
- 🛢️ Which wells contribute the highest production volume?
- ⚠️ Which operational issues are affecting production?
- 🔧 How effectively is maintenance being carried out?
- 🏭 Are older assets associated with higher operating costs?
- 🚧 What insights can be gained from pipeline status and operational incidents?
- 📉 How does downtime impact revenue and production?

---

# 📊 Dashboard Pages

## 💰 1. Financial Performance Overview

Designed for executives and management to monitor overall business performance.

### Key KPIs

- Total Revenue
- Total Profit
- Operating Cost
- Production Volume
- Revenue Loss Due to Downtime

### Dashboard Analysis

- 📈 Monthly Financial Performance
- 🛢️ Top Producing Wells
- 🌍 Regional Cost Distribution
- 🌎 Country Performance
- 💵 Revenue vs Operating Cost
- 📊 Profitability Analysis

---

## ⚙️ 2. Operational Efficiency & Asset Reliability

Designed to monitor operational health, asset performance, and reliability.

### Key Analysis

- ⏱️ Downtime Analysis
- 🔧 Maintenance Coverage
- 🏭 Equipment Age Analysis
- 🚧 Pipeline Status
- ⚠️ Incident Analysis by Shift
- 🛢️ Well Performance Summary
- 📊 Asset Reliability

---

# 🧹 Data Preparation

## Data Cleaning

The raw dataset was prepared using **Power Query**.

The data preparation process included:

- Handling missing values
- Removing duplicate records
- Correcting data types
- Data transformation
- Data normalization
- Creating calculated columns
- Standardizing categorical values
- Preparing data for analysis

---

# 🏗️ Data Modeling

A **Star Schema** was implemented to create an efficient and scalable Power BI data model.

### Data Modeling Steps

1. Identified fact and dimension tables
2. Created relationships between tables
3. Defined primary and foreign keys
4. Established appropriate relationship cardinality
5. Created a centralized analytical model
6. Optimized the model for DAX calculations

### Simplified Data Flow

```text
                 ┌──────────────────┐
                 │  Dimension Tables│
                 │                  │
                 │ • Date           │
                 │ • Region         │
                 │ • Country        │
                 │ • Well           │
                 │ • Asset          │
                 │ • Equipment      │
                 └────────┬─────────┘
                          │
                          ▼
                 ┌──────────────────┐
                 │   Fact Tables    │
                 │                  │
                 │ • Production     │
                 │ • Financial      │
                 │ • Maintenance    │
                 │ • Incidents      │
                 │ • Operations     │
                 └──────────────────┘
