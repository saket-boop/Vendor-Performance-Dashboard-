# Vendor Performance Dashboard 

## 1. Project Overview
The Vendor Performance Dashboard project focuses on analyzing vendor and brand-level performance to support data-driven business decisions. The primary objective of this project is to evaluate sales, purchase behavior, profitability, and inventory efficiency using interactive visualizations. The dashboard enables stakeholders to identify high-performing vendors and brands, monitor profit margins, and detect underperforming entities that may require corrective action.
This project demonstrates the practical application of data analysis, business intelligence, and visualization techniques to convert raw transactional data into actionable insights.---
## 2. Business Problem Statement
Organizations dealing with multiple vendors and brands often face challenges such as:
* Lack of visibility into vendor-wise and brand-wise performance
* Difficulty identifying low-performing vendors and brands
* Inefficient capital utilization due to unsold inventory
* Limited understanding of profit margin distribution across vendors
The goal of this project is to address these challenges by building a centralized dashboard that provides a clear and comprehensive view of vendor and brand performance.
---
## 3. Objectives
* Analyze overall sales, purchases, and profitability
* Identify top-performing vendors and brands based on sales
* Detect low-performing vendors and brands using contribution and margin metrics
* Evaluate purchase contribution concentration
* Monitor unsold capital to assess inventory efficiency
* Present insights through clear and interactive Power BI visualizations
---
## 4. Data Description
The dataset contains transactional-level data related to vendors, brands, sales, purchases, and inventory. Key attributes used in the analysis include:
* Vendor Name
* Brand Name
* Total Sales ($)
* Total Purchase ($)
* Gross Profit ($)
* Profit Margin (%)
* Purchase Contribution (%)
* Unsold Capital ($)
The data was cleaned, transformed, and aggregated to ensure accuracy and consistency before visualization.
---
## 5. Key Performance Indicators (KPIs)
The dashboard highlights the following KPIs to provide a high-level business overview:
* **Total Sales:** $441.41M
* **Total Purchase:** $307.34M
* **Gross Profit:** $134.07M
* **Profit Margin:** 38.72%
* **Unsold Capital:** $2.71M
These KPIs help stakeholders quickly assess financial performance and operational efficiency.
---
## 6. Dashboard Design & Visualizations
### 6.1 KPI Cards
KPI cards are placed at the top of the dashboard to present a quick snapshot of overall business performance. This allows decision-makers to instantly understand revenue, cost structure, profitability, and capital blockage.
### 6.2 Low Performing Vendors Analysis
A horizontal bar chart is used to identify low-performing vendors based on contribution ratios. Vendors such as Dunn Wine Brokers, Circa Wines, and others show lower performance scores, indicating the need for:
* Contract review
* Vendor renegotiation
* Performance improvement plans
### 6.3 Low Performing Brands Analysis
A scatter plot visualizes Total Sales against Average Profit Margin. This analysis helps identify:
* Brands with high sales but low margins
* Brands with low sales and low profitability
Such brands may require pricing optimization, cost control, or discontinuation strategies.
### 6.4 Purchase Contribution Analysis
The donut chart illustrates the percentage contribution of each vendor to total purchases. The visualization highlights vendor concentration, where a small number of vendors contribute a significant share of purchases, posing potential dependency risks.
### 6.5 Top Vendors by Sales
A ranked bar chart identifies top vendors driving revenue. Vendors contributing up to $68M in sales indicate strong partnerships and reliable revenue streams.
### 6.6 Top Brands by Sales
This chart highlights high-performing brands such as premium liquor brands that consistently generate strong sales. These insights support focused brand investment and marketing strategies

---
## 7. Key Insights & Findings
* A limited number of vendors and brands contribute a major portion of total sales, indicating revenue concentration.
* Several vendors show low contribution ratios, signaling underperformance.
* Some brands generate high sales but operate on thin profit margins, affecting overall profitability.
* Unsold capital of $2.71M highlights opportunities to improve inventory turnover and reduce working capital blockage.
---
## 8. Business Impact
The Vendor Performance Dashboard enables organizations to:
* Optimize vendor selection and negotiation strategies
* Improve profit margins through better brand performance analysis
* Reduce inventory-related losses and unsold capital
* Support strategic planning with data-backed insights
The dashboard serves as a decision-support system for procurement, finance, and operations teams.
---
## 9. Tools & Technologies Used
* **Power BI:** Data modeling and interactive dashboard creation
* **SQL:** Data extraction and transformation
* **Python (Pandas, Matplotlib/Seaborn):** Exploratory Data Analysis (EDA)
* **Excel/CSV:** Data storage and preprocessing
---
## 10. Conclusion
This project successfully demonstrates how business intelligence tools and analytical techniques can be used to evaluate vendor and brand performance effectively. By integrating KPIs, comparative analysis, and visual storytelling, the Vendor Performance Dashboard provides actionable insights that help improve profitability, operational efficiency, and strategic decision-making.

---
## 11. Future Enhancements
* Add time-based trend analysis (monthly/quarterly)
* Include vendor risk and reliability metrics
* Implement automated data refresh pipelines
* Add drill-through pages for detailed vendor and brand analysis
