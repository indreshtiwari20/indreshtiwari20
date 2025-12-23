# 🏥 Hospital Healthcare Management System – Power BI Project

> **Role:** Power BI Developer / Lead  
> **Domain:** Healthcare Analytics  
> **Tools:** Power BI, Azure SQL SDK, DAX, Power Query (M), JIRA  
> **Duration:** Sept 2021 – June 2023

## 📌 Executive Summary
Led the end-to-end development of a comprehensive **Hospital Healthcare Management System** analytics suite for a major healthcare provider. This initiative transformed fragmented data from EHR systems (Epic/Cerner), billing databases, and HR records into **6 interactive Power BI dashboards**.

The solution provided a "single source of truth" for hospital executives, clinical managers, and finance teams, directly resulting in a **15% reduction in billing bottlenecks** and significantly improved resource allocation during peak ER hours.

## 🛠️ Technical Implementation

### Data Architecture & Modeling
*   **Star Schema Design:** Built a robust dimensional model with Fact tables (Admissions, Transactions) and Conformed Dimensions (Patient, Doctor, Date, Department).
*   **ETL with Power Query (M):**
    *   Standardized inconsistent department codes across 3+ source systems using lookup tables.
    *   Implemented **Incremental Refresh** for large transaction tables to reduce load times.
    *   Utilized **Query Folding** to push transformations back to the Azure SQL source for performance.
*   **Complex DAX Measures:**
    *   Developed specialized healthcare KPIs: `Average Length of Stay`, `Readmission Rate`, `Patient-to-Staff Ratio`.
    *   Implemented Time Intelligence (`DATESYTD`, `PARALLELPERIOD`) for financial trend analysis.
    *   Advanced variables (`VAR`) used to optimize performance and readability.

### Key Features
*   **Row-Level Security (RLS):** Implemented dynamic security roles ensuring doctors view only their patient data while C-suite executives see aggregated hospital-wide views.
*   **Drill-Through Capabilities:** Enabled deep dives from high-level "Overview" KPIs down to individual patient transaction records.
*   **Custom Tooltips & Bookmarks:** Enhanced user experience (UX) by providing context-sensitive data without cluttering the main canvas.

## 🚀 Impact & Outcomes
*   **Efficiency:** Automated reporting saved **20+ hours per month** for the analytics team, replacing manual Excel-based workflows.
*   **Operational Agility:** Real-time visibility into ER wait times allowed operations teams to dynamically reallocate staff, reducing average wait times.
*   **Financial Accuracy:** Identified and resolved revenue leakage points in the claims process through improved tracking of claim denials.
*   **Adoption:** Achieved high adoption rates across 5 specialized departments (Operations, Finance, Clinical, HR, Exec).

---
*This project demonstrates expertise in translating complex business requirements into scalable, secure, and actionable BI solutions.*
