# Sales & Inventory Intelligence Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-00758F?style=for-the-badge&logo=databricks&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

An end-to-end business intelligence solution designed to track financial trends, optimize supply chain operations, and evaluate branch-level performance. This dashboard provides executive stakeholders with real-time visibility into key performance indicators (KPIs), enabling data-driven strategic decisions.

---

## 📌 Executive Summary
* **Business Problem:** Leadership lacked a unified view of cross-channel sales performance and inventory bottlenecks, leading to delayed decision-making and delayed operational responses.
* **Solution:** Developed a multi-page interactive Power BI dashboard integrating financial scorecards, product margin analyses, and regional logistics metrics.
* **Impact:** Streamlined monthly reporting workflows and uncovered key cost-saving opportunities through optimized stock distribution.

---

## 🖼️ Dashboard Preview

| Executive Overview | Product Margin Analysis |
| :---: | :---: |
| <img width="700" alt="Dashboard Overview" src="https://github.com/user-attachments/assets/ee70bc4e-3e24-4b3b-af37-aecdbef7c384" /> | <img width="700" alt="Dashboard Product Margin" src="https://github.com/user-attachments/assets/67be0a0b-d6b2-4223-a815-dbb7449b8897" /> |

| Branch Operations & Customers | Supply Chain & Logistics |
| :---: | :---: |
| <img width="700" alt="Dashboard Branch Customers" src="https://github.com/user-attachments/assets/e0365491-4b94-42e0-baa9-0594498fcfaf" /> | <img width="700" alt="Dashboard SupplyChain Ops" src="https://github.com/user-attachments/assets/f5adf27c-0fe2-4387-82a1-d97d84d3d0f2" /> |

---

## 🏗️ Architecture & Data Workflow

1. **Data Ingestion & Modeling:** Connected raw transactional data and built a clean Star Schema with designated fact and dimension tables to optimize query performance.
2. **Data Transformation & DAX:** Authored custom DAX measures (time intelligence, running totals, profit margins, and dynamic conditional formatting).
3. **UI/UX Design:** Implemented a structured 4-page canvas layout featuring clean navigation, consistent color themes, and cross-filtering behaviors.

---

## 📊 Key Features & Page Breakdown

* **Page 1: Executive Scorecard**
  * High-level financial KPIs (Revenue, Net Profit, YTD Growth vs. Target).
  * Trend analysis lines with dynamic slicers for date ranges and regions.
* **Page 2: Product Margin & Profitability**
  * Deep dive into product-level contributions, identifying high-margin vs. loss-leading inventory.
  * ABC analysis categorization via custom measures.
* **Page 3: Branch Operations**
  * Store-level performance scorecards and operational efficiency metrics.
  * Comparative rankings using dynamic measures.
* **Page 4: Supply Chain & Logistics**
  * Delivery lead times, fulfillment rates, and inventory turnover ratios.
  * Visual bottlenecks highlighting regional shipping delays.

---

## 🛠️ Technical Stack & Skills Demonstrated

* **BI & Visualization:** Power BI Desktop, Power Query, DAX Studio.
* **Data Modeling:** Star Schema design, surrogate keys, relationship management (1-to-many, bidirectional handling).
* **Calculations:** Advanced DAX (`CALCULATE`, `FILTER`, `SELECTEDVALUE`, time intelligence functions like `TOTALYTD` and `SAMEPERIODLASTYEAR`).
* **Design Principles:** User-centered layout, minimalist UI, fast-loading visuals, and cross-page navigation bookmarks.

---

## 🚀 How to Explore This Project

* **View the Interactive File:** Download the `.pbix` file from this repository and open it in Power BI Desktop.
* **Review the Data Model:** Inspect the relationships tab to review the Star Schema architecture.
* **Explore the DAX:** Check out the `_Measures` table to review the custom calculation logic used throughout the report.

---

## 📬 Contact & Connect

**Adrian Alaba**
* **LinkedIn:** [linkedin.com/in/adrianalaba](https://www.linkedin.com/in/adrianalaba)
* **Email:** adrian.alaba@gmail.com
