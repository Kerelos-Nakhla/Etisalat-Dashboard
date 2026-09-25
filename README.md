# 📡 Telecom Customer Churn & Revenue Risk Analysis

<p align="center">
  <b>Executive Retention Modeling, Contract Vulnerability & Revenue Exposure Intelligence in Power BI</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/DAX-Retention_Analytics-blue?style=for-the-badge" alt="DAX" />
  <img src="https://img.shields.io/badge/Telecom-Churn_Prediction-critical?style=for-the-badge" alt="Telecom Churn" />
  <img src="https://img.shields.io/badge/Revenue_Risk-MRR_Protection-success?style=for-the-badge" alt="MRR Protection" />
</p>

---

## 📌 Executive Overview
The **Etisalat Customer Churn & Revenue Risk Analysis** is an enterprise telecommunications analytics dashboard built in Power BI. By evaluating subscriber contract structures, support ticket frequency, and service adoption, the platform isolates customer segments at imminent risk of departure and quantifies the direct financial impact on monthly and annual recurring revenue.

### 📊 Core Key Performance Indicators (KPIs)
- 👥 **Total Customer Accounts:** **7,043 subscriber profiles**
- 🚪 **Total Churned Customers:** **1,869 subscribers**
- ⚠️ **Overall Churn Rate:** **26.54%**
- 🛡️ **Retained Customer Base:** **5,174 subscribers** (73.46%)
- 💳 **Total Monthly Charges:** **$456,116.60 / month**
- 🚨 **Monthly Revenue at Risk (Churned):** **$139,130.85 / month** (**30.50%** of monthly billings)
- 💰 **Cumulative Lifetime Revenue Analyzed:** **$16,056,168.70** ($16.06M total revenue)
- 📉 **Cumulative Revenue Lost to Churn:** **$2,862,926.90** ($2.86M total lost)

---

## 🎯 Business Problem & Objectives
1. 📄 **Contract Structure Vulnerability:** Quantify the churn differential between Month-to-Month contracts and 1-Year/2-Year commitments.
2. 💸 **Disproportionate Revenue Exposure:** Explain why churned customers represent only 26.54% of accounts but account for 30.50% of monthly billings.
3. 🌐 **High-Risk Product Bundles:** Evaluate churn rates across Fiber Optic vs. DSL subscribers lacking value-added security or technical support services.
4. 💳 **Payment Method Friction:** Identify payment channel failure rates and churn correlations (Electronic Check vs. Auto-Pay Credit Card/Bank Transfer).

---

## 💡 In-Depth Data Analysis & Business Insights
- 🚨 **Revenue Exposure Exceeds Account Churn:** Churned accounts represent **26.54% of customers but 30.50% of monthly revenue**, proving that higher-paying accounts churn at significantly higher rates.
- 📄 **Contract Stability Multiplier:** Month-to-Month subscribers exhibit an alarming **42.7% churn rate**, whereas 1-Year (11.3%) and 2-Year (2.8%) agreements deliver over **4x to 15x greater retention**.
- 🌐 **The Fiber Optic Paradox:** Fiber optic customers generate the highest average monthly spend ($75–$110) yet experience a **41.9% churn rate**, driven by service delivery friction when bundled without tech support.
- 💳 **Payment Channel Vulnerability:** Customers paying via **Electronic Check** represent the highest churn cohort (over 45%), while automatic bank and credit card billing cohorts experience churn below 16%.

---

## 🖼️ Dashboard Visual Tour & Storytelling

### 1. Landing Page
<p align="center">
  <img src="./Dashboard%20Previews/Landing%20Page.png" alt="Etisalat Churn Analysis — Landing" width="95%">
</p>

### 2. Executive Overview
<p align="center">
  <img src="./Dashboard%20Previews/Overview%20Page.png" alt="Etisalat Churn Analysis — Overview" width="95%">
</p>

### 3. Customer Profile & Cohort Analysis
<p align="center">
  <img src="./Dashboard%20Previews/Customers.png" alt="Etisalat Churn Analysis — Customers" width="95%">
</p>

### 4. Telecommunication Services Breakdown
<p align="center">
  <img src="./Dashboard%20Previews/Services%20Page.png" alt="Etisalat Churn Analysis — Services" width="95%">
</p>

### 5. Billing & Payment Methods
<p align="center">
  <img src="./Dashboard%20Previews/Payment%20Page.png" alt="Etisalat Churn Analysis — Payment" width="95%">
</p>

---

## 🏗️ Data Architecture & Star Schema
The telecommunications data model connects customer contracts, service subscriptions, and billing transactions:

- **Fact Table:**
  - `fact_churn` — Account ID, customer status (Active/Churned), monthly charges, total charges, tenure months, and tenure cohort
- **Dimension Tables:**
  - `dim_customer` — Demographics, partner status, dependents, senior citizen status
  - `dim_contract` — Contract type (Month-to-Month, One Year, Two Year), paperless billing flag
  - `dim_services` — Internet service type (DSL, Fiber Optic, No), Online Security, Tech Support, Streaming TV/Movies
  - `dim_payment` — Payment method (Electronic Check, Mailed Check, Bank Transfer, Credit Card)

### 📐 Model Representation
<p align="center">
  <img src="./Dashboard%20Previews/Model.png" alt="Etisalat Churn Analysis — Power BI Data Model" width="95%">
</p>

---

## 🛠️ Tools & Technologies
- 📊 **Power BI Desktop:** Multi-page executive dashboards, slicers, risk matrices
- 📐 **DAX Calculations:** Churn Rate %, Monthly Revenue at Risk ($), Customer Lifetime Value (CLV), Tenure Cohort Distributions
- 🧹 **Power Query (M):** ETL pipelines, automated data type casting, null handling
- 📡 **Domain Knowledge:** Telecom subscription economics, churn prevention, contract lifecycle management

---

## 📜 License & Author
- **Author:** Kerelos Nakhla ([GitHub](https://github.com/Kerelos-Nakhla))
- **License:** MIT License
