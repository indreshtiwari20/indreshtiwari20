# Credit Risk Analytics | Power BI & Snowflake




> **Strategic Credit Risk Portfolio Management System for Tier-1 North American Bank**  
> *Architected an end-to-end analytics ecosystem managing a **Multi-Billion Dollar ($5B+)** synthetic portfolio (Credit Cards & Personal Loans), reducing risk exposure and optimizing capital allocation.*




---




## 📌 Project Overview
**Client:** Major North American Bank (Confidential)  
**Partner:** Global IT Consulting Firm  
**Role:** Senior Data Analyst  
**Duration:** Ongoing  
**Tools:** Power BI, Snowflake, SQL, Alteryx, Excel, DAX  
**Portfolio Scope:** **Multi-Billion Dollar ($5B+)** | **30,000+ Accounts** | Credit Cards (60%) & Personal Loans (40%)




## 💼 Business Problem
The bank required a unified view of its credit risk portfolio to address:
*   **Fragmented Data:** Data silos across **Multiple disparate sources** (Origination, Collections, Recovery) prevented holistic risk assessment.
*   **Manual Reporting:** 12-hour batch processing delays hindered real-time decision-making on delinquencies.
*   **Risk Visibility:** Lack of granular visibility into "Time-to-Cure" and "Roll Rates" (delinquency progression) increased charge-off risks.




## 🛠️ Solution Architecture
Designed and implemented a **Star Schema** data model in **Power BI** fed by a **Snowflake** data warehouse.




1.  **Data Engineering (ETL):**
    *   Automated daily workflows using **Alteryx** to blend 12+ Excel data marts into **Snowflake (Bronze/Silver/Gold layers)**.
    *   Performed data quality enforcement (Null checks, duplicate removal, format validation) achieving **<2% error rate** (down from 28%).
2.  **Data Modeling:**
    *   Built a robust Star Schema with **5 Fact Tables** (Delinquency, Payment, Charge-off...) and **6 Dimension Tables**.
    *   Managed relationships (1-to-many) for a dataset of **30,000+ accounts**.
3.  **Advanced Analytics (DAX & SQL):**
    *   Developed **50+ DAX measures** including complex logic for **BCR (Balance Control Ratio)**, **GLPA (Good Loan Per Account)**, and **Roll Rates**.
    *   Implemented **Delinquency Bucket Logic** (Current → X+1 → Charge-Off) using SQL window functions.




## 🚀 Key Features & Dashboards
Delivered **20+ Production Dashboards** with 99.5% uptime:




*   **Executive Risk View:** Top 10 KPIs, Portfolio Health Score, and Monthly Revenue Impact.
*   **Origination Audit:** Analysis of Approval Rates, Processing Days, and Underwriter Performance.
*   **Collection Scorecard:** Risk-adjusted collector performance tracking and "Priority Score" algorithms (Balance × Risk Weight × FICO).
