# 📊 Telecom Customer Churn Analysis

An interactive Excel dashboard that analyzes customer churn behavior for a telecom company, uncovering the key drivers behind customer attrition and surfacing actionable retention insights through dynamic KPIs, slicers, and visualizations.

---

## 🎯 Project Overview

Customer churn is one of the biggest revenue risks for subscription-based telecom businesses. This project analyzes a dataset of **7,044 customers** to identify **who is churning, why they're churning, and where the business should focus retention efforts.**

The end deliverable is a fully interactive, single-view Excel dashboard built with pivot tables, pivot charts, KPI cards, and slicers — allowing stakeholders to filter and explore churn patterns without needing to touch the underlying data.

---

## 🧰 Tools & Techniques

- **Microsoft Excel** – Pivot Tables, Pivot Charts, Slicers, KPI Cards, Conditional Formatting
- **Data Cleaning** – Handling nulls, standardizing categorical fields, formatting numeric fields
- **Dashboard Design** – Single-page executive dashboard layout for quick decision-making
- **Segmentation Analysis** – Churn broken down by contract type, gender, tenure, internet service, and payment method

---

## 📁 Workbook Structure

| Sheet | Purpose |
|---|---|
| `DASHBOARD` | Main interactive dashboard with KPIs, charts, and slicers |
| `charts` | Supporting chart objects |
| `01 Churn-Dataset` | Raw/cleaned source data |
| `customer demographic` | Demographic-level breakdown (gender, senior citizen, etc.) |
| `service analysis` | Analysis by internet service and add-on services |
| `financial analysis` | Monthly charges, total charges, revenue impact |
| `contract analysis` | Churn behavior across contract types |
| `customer lifetime` | Tenure-based churn and retention patterns |
| `payment analysis` | Churn by payment method |

---

## 📈 Key Metrics (KPIs)

| Metric | Value |
|---|---|
| Total Customers | 7,044 |
| Active Customers | 5,174 |
| Churned Customers | 1,869 |
| **Overall Churn Rate** | **26.5%** |
| Average Monthly Charge | $64.76 |
| Average Tenure | 34 months |

---

## 🔍 Key Business Insights

**1. Overall Churn**
26.5% of customers have churned, indicating a significant customer retention challenge for the business.

**2. Contract Type Drives Churn**
- Month-to-month contracts: **42.71% churn rate**
- One-year contracts: **11.27% churn rate**
- Two-year contracts: **2.83% churn rate**

Customers without long-term commitment are by far the most likely to leave — contract type is the single strongest churn predictor in this dataset.

**3. Internet Service**
Fiber optic customers show a noticeably higher churn tendency compared to DSL customers, suggesting possible pricing, reliability, or competitive pressure issues specific to that segment.

**4. Gender**
Churn is fairly evenly distributed between male and female customers, indicating gender is **not** a meaningful driver of churn.

**5. Payment Method**
Customers paying via **electronic check** show elevated churn compared to those on automatic payment methods (bank transfer, credit card), pointing to a possible link between payment friction/engagement and loyalty.

---

## 💡 Recommendations

- Prioritize converting month-to-month customers to one-year or two-year contracts through loyalty discounts or bundled offers.
- Investigate service quality and pricing for fiber optic customers to understand the root cause of higher churn.
- Encourage migration from electronic check to automatic payment methods to improve retention.
- Launch targeted retention campaigns for customers within their first 12 months of tenure, where churn risk is typically highest.

---

## 🖼️ Dashboard Preview

*(Add a screenshot of the DASHBOARD sheet here, e.g. `![Dashboard](dashboard_preview.png)`)*

---

## 🚀 How to Use

1. Download `Telecom_Customer_Churn_Analysis.xlsx` from this repository.
2. Open in Excel (2016 or later recommended for full slicer support).
3. Go to the `DASHBOARD` sheet.
4. Use the slicers (Contract, Gender, Senior Citizen, Internet Service, Churn, Tenure, Payment Method) to filter and explore the data interactively.

---

## 👤 Author

**Nithis**
Data Analyst | SQL • Python • Power BI • Excel
📫 Open to Data Analyst opportunities in Bangalore, Hyderabad, and Pune

---

## 📌 Dataset

Based on the widely used Telco Customer Churn dataset, adapted and analyzed for this project.
