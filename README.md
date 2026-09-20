# Telecom Customer Churn & Revenue Risk Analysis in Power BI

<p align="center">
  <b>Executive Retention Modeling, Contract Vulnerability & Revenue Exposure Intelligence</b>
</p>

---

## Executive Overview
The **Etisalat Customer Churn & Revenue Risk Analysis** is an enterprise telecommunications analytics dashboard built in Power BI. By evaluating subscriber contract structures, support ticket frequency, and service adoption, the platform isolates customer segments at imminent risk of departure and quantifies the direct financial impact on monthly and annual recurring revenue.

### Core Telecom Metrics (Calculated from Actual Production Dataset)
- **Total Customer Accounts:** 7,043 subscriber profiles
- **Total Churned Customers:** 1,869 subscribers
- **Overall Churn Rate:** **26.54%**
- **Retained Customer Base:** 5,174 subscribers (73.46%)
- **Total Monthly Charges:** **$456,116.60 / month**
- **Monthly Revenue at Risk (Churned):** **$139,130.85 / month** (30.50% of monthly billings)
- **Cumulative Lifetime Revenue Analyzed:** **$16,056,168.70** ($16.06M total revenue)
- **Cumulative Revenue Lost to Churn:** **$2,862,926.90** ($2.86M total lost)

---

## Business Problem & Key Analytical Findings
1. **Contract Type as Primary Churn Driver:** Month-to-month contract holders account for the vast majority of departures. Subscribers committed to 1-year or 2-year agreements exhibit over 4x higher retention rates.
2. **Tech Support Ticket Velocity:** Customers logging more than 2 technical support tickets within their first 6 months have an attrition probability exceeding 60%.
3. **Fiber Optic & Value-Added Services:** Customers utilizing Fiber Optic connections with high monthly charges but lacking online security or tech support add-ons represent the highest financial exposure cohort.

---

## Dashboard Visual Tour & Storytelling

### 1. Landing
<p align="center">
  <img src="./Dashboard%20Previews/Landing%20Page.png" alt="Etisalat Churn Analysis — Landing" width="95%">
</p>

### 2. Overview
<p align="center">
  <img src="./Dashboard%20Previews/Overview%20Page.png" alt="Etisalat Churn Analysis — Overview" width="95%">
</p>

### 3. Customer
<p align="center">
  <img src="./Dashboard%20Previews/Customers.png" alt="Etisalat Churn Analysis — Customers" width="95%">
</p>

### 4. Services
<p align="center">
  <img src="./Dashboard%20Previews/Services%20Page.png" alt="Etisalat Churn Analysis — Services" width="95%">
</p>

### 5. Payment
<p align="center">
  <img src="./Dashboard%20Previews/Payment%20Page.png" alt="Etisalat Churn Analysis — Payment" width="95%">
</p>

---

## Data Architecture & Model
The data model is engineered as a normalized Star Schema linking subscriber profiles, subscription plans, payment channels, and service combinations to churn outcomes.

### Model Representation
<p align="center">
  <img src="./Dashboard%20Previews/Model.png" alt="Etisalat Churn Analysis — Power BI Data Model" width="95%">
</p>

- **Fact Table (`fact_churn`):** 7,043 subscriber records detailing tenure duration, monthly charges, total charges, admin tickets, tech tickets, and churn flags.
- **Dimension Tables:**
  - `dim_customer`: Subscriber demographics, partner status, dependents, and senior citizen classification.
  - `dim_contract`: Month-to-month, one-year, and two-year contract agreements.
  - `dim_payment`: Electronic check, mailed check, bank transfer, and credit card auto-pay mechanisms.
  - `dim_services`: Phone service, multiple lines, Internet (DSL/Fiber Optic), online security, backup, protection, and streaming services.

---

## Tools & Technologies
- **Business Intelligence:** Microsoft Power BI Desktop
- **Analytics & Calculations:** Advanced DAX (Churn Rate %, Revenue at Risk, Tenure Cohorts, Customer Lifetime Value)
- **Data Engineering:** Power Query (M) for categorical encoding, ticket aggregation, and data profiling

---

## License & Usage
This repository is released under the [MIT License](LICENSE). Developed by **Kerelos Nakhla** — Data Analyst & BI Developer.
