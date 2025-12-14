# Customer Churn & Retention Analysis Dashboard 📊

## 📌 Project Overview
This Business Intelligence project analyzes customer attrition patterns for a retail business to identify high-risk segments and improve retention strategies. The dashboard processes transaction data to visualize churn rates across loyalty tiers, geographic regions, and product categories.

* **Key Metric:** Analyzed a total churn rate of **51.7%** across the customer base.
* **Tools Used:** Power BI, DAX, Power Query, Data Modeling.

## 🔍 Key Business Insights
* **Critical Loyalty Risk:** Identified a major retention gap in the **Platinum Loyalty Tier**, which exhibited the highest churn rate at **55.95%** compared to other groups.
* **Regional Performance:** **Leeds** emerged as the most engaged region with an Average Purchase Frequency of **4.3**, outperforming London (3.7).
* **At-Risk Forecasting:** Correlated "Days Since Last Purchase" with Customer Lifetime Value (CLV) to flag high-value customers likely to churn.
* **Product Trends:** **Clothing** was identified as the highest transaction volume category.

## 🛠️ Technical Implementation
* **Data Modeling:** Designed a star schema connecting Customer, Transaction, and Region tables.
* **Complex DAX:** Engineered measures for **Customer Lifetime Value (CLV)**, **Repeat Purchase Rate**, and **Churn Rate**.
* **Visualizations:** Utilized Decomposition Trees for root cause analysis and Funnel Charts to track customer retention flow.

## 📂 Files Included
* `Customer_Churn_Analysis.pbix`: The source Power BI file.
* `Dashboard_Report.pdf`: A high-quality PDF export of the final report.
