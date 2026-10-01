# 📡 Telecom Customer Churn & Revenue Risk Intelligence System

<p align="center">
  <b>Enterprise Subscriber Retention, Contract Exposure Modeling & MRR Protection Analytics in Power BI</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/DAX-Retention_Analytics-blue?style=for-the-badge" alt="DAX" />
  <img src="https://img.shields.io/badge/Telecom-Churn_Prediction-critical?style=for-the-badge" alt="Telecom Churn" />
  <img src="https://img.shields.io/badge/Revenue_Risk-$2.86M_Identified-success?style=for-the-badge" alt="Revenue at Risk" />
  <img src="https://img.shields.io/badge/Data_Model-Star_Schema-orange?style=for-the-badge" alt="Star Schema" />
</p>

---

## 📌 Executive Overview

The **Etisalat Customer Churn & Revenue Risk Intelligence System** is an end-to-end telecommunications decision-support platform engineered in **Power BI**. It uncovers the structural, behavioral, and operational drivers behind customer attrition across **7,043 subscribers**, pinpointing **$2,862,926.90** in cumulative revenue exposure and **$139,130.85** in monthly recurring revenue (MRR) at risk.

By combining granular contract structures, payment method friction, service bundle adoption, and customer support ticket telemetry (technical vs. administrative), this solution enables C-suite leadership, retention teams, and customer care executives to shift from **reactive firefighting** to **proactive, high-precision subscriber intervention**.

```
+----------------------------------------------------------------------------------------------------+
|                                    EXECUTIVE PORTFOLIO AT A GLANCE                                 |
+--------------------------+--------------------------+-----------------------+----------------------+
|     7,043 Subscribers    |    1,869 Churned Users   |     26.54% Churn      |  $16.06M Total Value |
|  5,174 Active Accounts   |   $2.86M Revenue at Risk |  $64.76 Avg Mo Charge |  $139.13K Churned MRR|
+--------------------------+--------------------------+-----------------------+----------------------+
```

---

## 📊 Executive Scorecard & Core Portfolio Metrics

The enterprise scorecard aggregates core subscriber metrics and financial velocity:

| Key Performance Indicator | Total Portfolio | Active / Retained | Churned / Lost | Portfolio Variance / Impact |
| :--- | :---: | :---: | :---: | :--- |
| **Total Subscribers** | **7,043** | 5,174 (73.46%) | 1,869 (26.54%) | Baseline customer universe |
| **Gross Cumulative Charges** | **$16,056,168.70** | $13,193,241.80 | **$2,862,926.90** | **17.83%** lifetime revenue loss |
| **Monthly Billed Revenue (MRR)** | **$456,116.60** | $316,985.75 | **$139,130.85** | **30.50%** monthly run-rate exposure |
| **Average Monthly Charge (ARPU)** | **$64.76** | $61.26 | **$74.44** | Churners pay **+$13.18/mo** (+21.5%) |
| **Average Customer Tenure** | **32.37 Months** | 37.57 Months | **17.98 Months** | Churners exit at **< half** normal lifetime |
| **Senior Citizen Subscribers** | **1,142 (16.21%)** | 666 (58.32%) | **476 (41.68%)** | 1.7x higher churn than non-seniors (23.61%) |
| **Dependents & Family Accounts** | **2,110 (29.96%)** | 1,784 (84.55%) | **326 (15.45%)** | Strong retention anchor (vs 31.28% single) |

---

## 📜 Contract Structure & Commitment Horizon

Contractual commitment is the single strongest structural defense against churn. The portfolio reflects an acute vulnerability due to heavy reliance on month-to-month arrangements:

| Contract Type | Total Subscribers | Share of Base | Churned Count | Churn Rate (%) | Cumulative Charges | Revenue at Risk ($) | Risk Share (%) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Month-to-Month** | **3,875** | 55.02% | **1,655** | **42.71%** | $5,305,820.00 | **$1,927,182.25** | **67.31%** |
| **One Year** | **1,473** | 20.91% | 166 | 11.27% | $4,467,051.40 | $674,991.20 | 23.58% |
| **Two Year** | **1,695** | 24.07% | 48 | **2.83%** | $6,283,297.30 | $260,753.45 | 9.11% |
| **Total / Weighted** | **7,043** | 100.0% | **1,869** | **26.54%** | **$16,056,168.70** | **$2,862,926.90** | **100.0%** |

### 💡 Strategic Takeaway:
* **The Month-to-Month Hazard:** Over 88.5% of all churned subscribers (1,655 out of 1,869) and 67.3% of lost revenue originate from Month-to-Month contracts.
* **The Long-Term Lock-In:** Moving a customer from Month-to-Month to a Two-Year agreement reduces attrition probability by **93.4%** (from 42.71% down to 2.83%).

---

## 💳 Payment Friction & Billing Method Analysis

Analysis of payment channels reveals that payment automation and frictionless billing form a crucial retention safeguard:

| Payment Method | Channel Type | Subscribers | Churned Count | Churn Rate (%) | Revenue at Risk ($) | Avg Monthly Charge |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Electronic Check** | Manual | **2,365** | **1,071** | **45.29%** | **$1,567,576.40** | $79.09 |
| **Mailed Check** | Manual | **1,612** | 308 | 19.11% | $164,478.95 | $44.91 |
| **Bank Transfer (Automatic)** | Automated | **1,544** | 258 | 16.71% | $585,611.75 | $67.19 |
| **Credit Card (Automatic)** | Automated | **1,522** | 232 | **15.24%** | $545,259.80 | $67.42 |
| **Automated vs. Manual Comparison** |
| *All Automated Channels* | Automated | 3,066 | 490 | **15.98%** | $1,130,871.55 | $67.31 |
| *All Manual Channels* | Manual | 3,977 | 1,379 | **34.67%** | **$1,732,055.35** | $62.80 |

### 💡 Strategic Takeaway:
* **Electronic Check Failure:** Subscribers using Electronic Checks experience an alarming **45.29% churn rate**, generating **$1.57M in lost revenue** (54.8% of total portfolio losses).
* **The Auto-Pay Moat:** Enrolling subscribers in Auto-Pay (Bank Transfer or Credit Card) cuts churn in half (from 34.67% to 15.98%).

---

## 🌐 Product Ecosystem & Service Adoption Dynamics

Evaluation of internet infrastructure, bundled add-ons, and product depth reveals clear churn drivers and retention anchors:

### 1. Internet Service Technology Breakdown
| Internet Technology | Total Users | Share (%) | Churned | Churn Rate (%) | Avg Monthly Charge | Revenue at Risk ($) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Fiber Optic** | **3,096** | 43.96% | **1,297** | **41.89%** | **$91.50** | **$2,483,257.45** (86.7%) |
| **DSL** | **2,421** | 34.38% | 459 | 18.96% | $58.10 | $360,016.50 (12.6%) |
| **No Internet (Phone Only)**| **1,526** | 21.67% | 113 | 7.40% | $21.08 | $19,652.95 (0.7%) |

> **Critical Observation:** Fiber optic accounts for **86.74% of all lost revenue** ($2.48M). Fiber subscribers pay high monthly bills ($91.50 average) but suffer the highest attrition rate (41.89%), pointing toward pricing friction, onboarding gaps, or technical service dissatisfaction.

### 2. Service Bundling & "Stickiness" Curve
The number of active services adopted acts as a powerful retention engine:

| Active Services Count | Total Customers | Churned Count | Churn Rate (%) | Cumulative Value | Lost Revenue ($) |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **1 Service** | 80 | 35 | **43.75%** | $17,759.30 | $3,216.65 |
| **2 Services** | 1,701 | 359 | 21.11% | $863,383.75 | $94,172.80 |
| **3 Services** | 1,188 | 390 | 32.83% | $1,140,099.45 | $227,385.55 |
| **4 Services** | 965 | 352 | 36.48% | $1,561,125.40 | $416,915.20 |
| **5 Services** | 922 | 289 | 31.34% | $2,246,321.90 | $515,641.50 |
| **6 Services** | 908 | 232 | 25.55% | $3,218,166.30 | $621,336.45 |
| **7 Services** | 676 | 152 | 22.49% | $3,222,561.80 | $639,972.20 |
| **8 Services** | 395 | 49 | 12.41% | $2,340,853.05 | $267,367.40 |
| **9 Services (Full Ecosystem)** | **208** | **11** | **5.29%** | $1,445,897.75 | $76,919.15 |

### 3. Add-On Services Retention Impact
| Add-On Feature | Users With Feature | Churn Rate (With) | Churn Rate (Without) | Retention Delta |
| :--- | :---: | :---: | :---: | :---: |
| **Online Security** | 2,019 | **14.61%** | 41.77% | **-27.16% Churn Reduction** |
| **Tech Support** | 2,044 | **15.17%** | 41.65% | **-26.48% Churn Reduction** |
| **Online Backup** | 2,429 | **21.53%** | 39.93% | **-18.40% Churn Reduction** |
| **Device Protection** | 2,422 | **22.50%** | 39.13% | **-16.63% Churn Reduction** |

---

## 🎧 Support Ticket Escalation & Operational Trigger Points

The dataset tracks operational ticket frequency partitioned by **Technical Tickets** versus **Administrative Tickets**:

```
+----------------------------------------------------------------------------------------------------+
|                               TECHNICAL TICKETS: THE CHURN CLIFF                                    |
|                                                                                                    |
|   0 Tech Tickets   [======================] 19.69% Churn Rate   (6,073 customers)                  |
|   1 Tech Ticket    [=============================================] 65.63% Churn  (256 customers)   |
|   2 Tech Tickets   [============================================] 62.69% Churn   (201 customers)   |
|   3 Tech Tickets   [==============================================] 66.89% Churn  (151 customers)   |
|   4 Tech Tickets   [===============================================] 69.17% Churn (133 customers)  |
|   5+ Tech Tickets  [====================================================] 81.5% Churn (229 cust.) |
+----------------------------------------------------------------------------------------------------+
```

* **The Operational Red Line:** As soon as a subscriber submits **even 1 technical ticket**, their churn probability surges from **19.69% to 65.63%** (+233% increase).
* **Technical vs. Administrative:** Administrative tickets show a flat churn profile (**20% – 27%** across all ticket volumes). Unresolved technical friction (speed, disconnections, latency) is the direct operational trigger for account cancellation.

---

## ⏳ Customer Lifecycle & Tenure Horizons

Customer flight is heavily front-loaded in the initial 12 months:

| Tenure Cohort | Total Customers | Churned Count | Churn Rate (%) | Cumulative Value | Lost Value ($) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **0 – 12 Months** | **2,186** | **1,037** | **47.44%** | $1,154,395.70 | **$624,379.75** |
| **13 – 24 Months** | 1,024 | 294 | 28.71% | $1,556,585.35 | $481,217.15 |
| **25 – 36 Months** | 832 | 180 | 21.63% | $1,885,039.05 | $440,551.40 |
| **37 – 48 Months** | 762 | 145 | 19.03% | $2,341,894.10 | $471,061.20 |
| **49 – 60 Months** | 832 | 120 | 14.42% | $3,371,481.55 | $491,959.00 |
| **61+ Months** | **1,407** | **93** | **6.61%** | $5,746,772.95 | **$353,758.40** |

> **Key Discovery:** **55.5% of all churn events** occur within the first year of onboarding. After 5 years of tenure, the subscriber churn rate falls to just **6.61%**.

---

## 📐 Core DAX Measures & Formulas Reference

All business logic is centralized in the model under the `DAX Measures` dedicated calculation table:

### 1. Portfolio & Churn Performance Measures

#### Churn Rate %
```dax
Churn Rate = 
DIVIDE(
    CALCULATE(COUNTROWS(fact_churn), fact_churn[Churn] = "Yes"),
    COUNTROWS(fact_churn)
)
```

#### Revenue at Risk ($)
```dax
Revenue at Risk = 
CALCULATE([Total Charge], fact_churn[Churn] = "Yes")
```

#### Revenue at Risk %
```dax
Revenue at Risk % = 
DIVIDE([Revenue at Risk], [Total Charge])
```

#### Average Monthly Charge
```dax
AVG Monthly Charge = 
AVERAGE(fact_churn[Monthly Charges])
```

### 2. Contract & Service Intelligence

#### Month-to-Month Contract Churn Rate
```dax
Month To Month % = 
CALCULATE([Churn Rate], dim_contract[Contract] = "Month-To-Month")
```

#### Fiber Optic Churn %
```dax
Fiber Optic Churn % = 
DIVIDE(
    CALCULATE(
        [Count Churn Customers],
        dim_services[Internet Service] = "Fiber optic"
    ),
    [Count Churn Customers]
)
```

#### Allocated Revenue at Risk by Service Density
```dax
Allocated Revenue at Risk = 
CALCULATE(
    [Allocated Total Charges],
    fact_churn[Churn] = "Yes"
)

Allocated Total Charges = 
SUMX(
    fact_churn,
    DIVIDE(
        fact_churn[Total Charges],
        fact_churn[Service Count],
        0
    )
)
```

### 3. Support & Service Density Measures
```dax
Churn Rate 5 Plus Services = 
DIVIDE(
    [Churn Customers 5 Plus Services],
    [Customers 5 Plus Services],
    0
)

AVG Num Tech Tickets = 
AVERAGE(fact_churn[Num Tech Tickets])

AVG Num Admin Tickets = 
AVERAGE(fact_churn[Num Admin Tickets])
```

---

## 🖼️ Dashboard Visual Tour & Architecture

The report is structured into **5 interactive pages** with bespoke HTML visuals, modern KPI cards, and dynamic cross-filtering:

### 1. Executive Landing Portal (`Landing Page.png`)
* Enterprise navigation hub connecting C-suite leaders to deep-dive analytics workspaces.
* High-level mission statement, executive summary metrics, and direct routing.

<p align="center">
  <img src="./Dashboard%20Previews/Landing%20Page.png" width="92%" alt="Landing Page Preview" />
</p>

---

### 2. High-Level Churn & Revenue Overview (`Overview Page.png`)
* Executive KPI cards: Total Customers (`7,043`), Retained (`5,174`), Churned (`1,869`), Revenue at Risk (`$2.86M`), and Churn Rate (`26.54%`).
* Contract breakdown bar charts comparing Month-to-Month (`42.71%`), One Year (`11.27%`), and Two Year (`2.83%`).
* Multi-dimensional tenure cohorts and internet service contribution matrix.

<p align="center">
  <img src="./Dashboard%20Previews/Overview%20Page.png" width="92%" alt="Overview Page Preview" />
</p>

---

### 3. Subscriber Profile & Demographics (`Customers.png`)
* Deep demographic segmentation: Senior Citizen risk index (`41.68%` churn), Gender balance, Partner and Dependent influence.
* Tenure journey tracking highlighting early-tenure flight risk (`0-12 months`).
* High-risk customer persona matrix combining contract type with demographic variables.

<p align="center">
  <img src="./Dashboard%20Previews/Customers.png" width="92%" alt="Customers Page Preview" />
</p>

---

### 4. Service Adoption & Network Infrastructure (`Services Page.png`)
* Internet technology analysis contrasting Fiber Optic (`41.89%` churn / `$2.48M` risk) against DSL (`18.96%`).
* Protective add-on ecosystem analysis: Online Security, Tech Support, Cloud Backup, and Device Protection.
* Service count graduation curve (from 1 service down to 9 full-bundle services).

<p align="center">
  <img src="./Dashboard%20Previews/Services%20Page.png" width="92%" alt="Services Page Preview" />
</p>

---

### 5. Payment Methods & Billing Dynamics (`Payment Page.png`)
* Financial channel distribution evaluating Electronic Check (`45.29%` churn) vs. Credit Card / Bank Transfer Auto-Pay (`~15-16%`).
* Paperless billing correlation (`33.56%` churn) and monthly charge distribution brackets.
* Revenue recovery simulation model based on automated payment migrations.

<p align="center">
  <img src="./Dashboard%20Previews/Payment%20Page.png" width="92%" alt="Payment Page Preview" />
</p>

---

### 6. Star Schema Model Architecture (`Model.png`)
* Verified star schema architecture connecting normalized dimensional tables to central subscriber fact table.

<p align="center">
  <img src="./Dashboard%20Previews/Model.png" width="92%" alt="Model Architecture Preview" />
</p>

---

## 🏗️ Data Architecture & Star Schema Design

The model follows a rigorous **Kimball Star Schema** pattern optimized for fast DAX evaluation and clear analytical filtering paths.

```
                         +--------------------------+
                         |       dim_customer       |
                         +--------------------------+
                         | Customer Key (PK)        |
                         | Gender                   |
                         | Senior Citizen           |
                         | Partner / Dependents     |
                         | Demographic Groups       |
                         +------------+-------------+
                                      | 1
                                      |
                                      | *
+-----------------------+ 1           |           1 +-----------------------+
|     dim_contract      |-------------+-------------|      dim_payment      |
+-----------------------+             |             +-----------------------+
| Contract Key (PK)     |             |             | Payment Key (PK)      |
| Contract              |             |             | Payment Method        |
+-----------------------+             |             | Automatic Payment     |
                                      |             | Paperless Billing     |
                                      |             +-----------------------+
                                      |
                         +------------+-------------+
                         |        fact_churn        |
                         +--------------------------+
                         | Customer Key (FK)        |
                         | Contract Key (FK)        |
                         | Payment Key (FK)         |
                         | Services Key (FK)        |
                         | Tenure (Months)          |
                         | Monthly Charges          |
                         | Total Charges            |
                         | Num Admin Tickets        |
                         | Num Tech Tickets         |
                         | Churn (Yes / No)         |
                         | Group Tenure             |
                         | Service Count            |
                         +------------+-------------+
                                      | *
                                      |
                                      | 1
                         +------------+-------------+
                         |       dim_services       |
                         +--------------------------+
                         | Services Key (PK)        |
                         | Phone / Multiple Lines   |
                         | Internet Service         |
                         | Online Security / Backup |
                         | Device Protection        |
                         | Tech Support             |
                         | Streaming TV / Movies    |
                         +--------------------------+
```

### 📐 Relationship Specifications:
| Fact Table Column (Many / `*`) | Dimension Table Column (One / `1`) | Cardinality | Cross Filter | Enforcement |
| :--- | :--- | :---: | :---: | :---: |
| `fact_churn[Customer Key]` | `dim_customer[Customer Key]` | `* : 1` | Single | Active Primary Key |
| `fact_churn[Contract Key]` | `dim_contract[Contract Key]` | `* : 1` | Single | Active Foreign Key |
| `fact_churn[Payment Key]` | `dim_payment[Payment Key]` | `* : 1` | Single | Active Foreign Key |
| `fact_churn[Services Key]` | `dim_services[Services Key]` | `* : 1` | Single | Active Foreign Key |

---

## ⚙️ ETL & Power Query Pipeline

The data ingestion process utilizes **Power Query (M)** to cleanse, normalize, and transform raw subscriber operational files:
1. **Source Ingestion & Cleansing:** Cleaned raw Excel sheets, standardized numeric headers, and imputed missing or blank Total Charges for zero-tenure accounts.
2. **Dimension Modeling:** Normalized flattened customer tables into dedicated `dim_contract`, `dim_customer`, `dim_payment`, and `dim_services` dimension entities.
3. **Surrogate Key Generation:** Engineered clean integer surrogate keys (`Contract Key`, `Payment Key`, `Services Key`, `Customer Key`) to replace verbose text keys.
4. **Calculated Feature Engineering:**
   * `Group Tenure`: Binned continuous tenure into operational cohorts (`0-12 Months`, `13-24 Months`, ..., `+61 Months`).
   * `Service Count`: Dynamically summed the active boolean adoption flags across Phone, Multiple Lines, Internet, Security, Backup, Device Protection, Tech Support, and Streaming services.
   * `Ticket Segmentation`: Partitioned ticket metrics into administrative vs. technical issues.

---

## 📁 Repository Structure

```
Kerelos-Nakhla/Etisalat-Dashboard/
│
├── Dashboard Previews/             # High-resolution report page screenshots
│   ├── Customers.png              # Customer Demographics & Persona Analysis
│   ├── Landing Page.png           # Executive Portal Navigation Page
│   ├── Model.png                  # Power BI Star Schema Data Model View
│   ├── Overview Page.png          # Executive Churn & Revenue Exposure Dashboard
│   ├── Payment Page.png           # Billing Channels & Auto-Pay Analysis
│   └── Services Page.png          # Fiber/DSL Infrastructure & Service Bundling
│
├── Data/                          # Cleaned, dimensional Excel source workbooks
│   ├── dim_contract.xlsx          # Contract dimension table
│   ├── dim_customer.xlsx          # Customer demographic dimension table
│   ├── dim_payment.xlsx           # Payment & billing method dimension table
│   ├── dim_services.xlsx          # Telecom services & add-ons dimension table
│   └── fact_churn.xlsx            # Central subscriber churn fact table
│
├── Etisalat.pbix                  # Production Power BI desktop file
├── LICENSE                        # Repository license
└── README.md                      # Comprehensive project documentation
```

---

## 🛠️ Tools & Technologies

* **Business Intelligence:** Microsoft Power BI Desktop (May 2024+ PBIP & TMDL Format)
* **Data Modeling:** Star Schema (Kimball methodology), 1:Many unidirectional relationships
* **Calculations:** DAX (Data Analysis Expressions) for retention rate, exposure attribution, and dynamic segmentation
* **ETL Engine:** Power Query / M language for tabular normalization, key indexing, and feature engineering
* **Visualization:** Custom SVG/HTML visual rendering, native Power BI multi-row cards, clustered bar charts, donut charts

---

## 📜 License & Author

Developed by **[Kerelos Nakhla](https://github.com/Kerelos-Nakhla)**  
Data Analyst & BI Developer | Power BI & Data Modeling Specialist

* **GitHub:** [@Kerelos-Nakhla](https://github.com/Kerelos-Nakhla)
* **Email:** kerelosnakhlasaad@gmail.com

*This project is distributed under the MIT License.*
