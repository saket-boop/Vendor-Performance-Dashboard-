# Vendor Performance Analysis 

## 1. Introduction

The **Vendor Performance Analysis Project** is a business intelligence initiative aimed at evaluating vendor and brand performance using transactional sales and purchase data. The project leverages data analysis, time-based trend evaluation, and interactive visualizations to support strategic decision-making in procurement, inventory management, and profitability optimization.

The analysis is presented through a Power BI dashboard that transforms raw data into meaningful insights for business stakeholders.

---

## 2. Business Problem

Organizations working with multiple vendors and brands often face the following challenges:

* Limited visibility into vendor-wise and brand-wise contribution
* Difficulty identifying underperforming vendors and brands
* High dependency on a small group of vendors
* Inefficient inventory utilization leading to unsold capital
* Lack of time-based insights for forecasting and planning

This project addresses these challenges by creating a centralized, interactive dashboard that enables performance monitoring across multiple dimensions.

---

## 3. Project Objectives

* Analyze overall sales, purchase, and profitability metrics
* Identify top-performing and low-performing vendors
* Evaluate brand-level sales and profit margin performance
* Analyze purchase contribution concentration
* Assess unsold capital and inventory efficiency
* Perform monthly and vendor-wise trend analysis
* Support data-driven procurement and business strategies

---

## 4. Data Description

The dataset consists of vendor sales and purchase transactions containing the following key attributes:

* Vendor Name
* Brand Name
* Invoice Date
* Total Sales Dollars
* Total Purchase Dollars
* Gross Profit
* Average Profit Margin
* Order Size Category (Small, Medium, Large)

The data was cleaned, validated, and transformed using Python and SQL before being modeled in Power BI.

---

## 5. Key Performance Indicators (KPIs)

The dashboard highlights critical KPIs to provide a quick financial overview:

* **Total Sales:** $441.41M
* **Total Purchase:** $307.34M
* **Gross Profit:** $134.07M
* **Profit Margin:** 38.72%
* **Unsold Capital:** $2.71M

These KPIs help stakeholders evaluate business performance, cost structure, and working capital efficiency at a glance.

---

## 6. Data Modeling & Preparation

* Created a **Date Table** to support monthly and yearly analysis
* Established relationships between transaction data and date dimensions
* Developed calculated measures using DAX for sales, purchase, profit, and margin analysis
* Applied aggregation logic to support vendor, brand, and time-based analysis

---

## 7. Dashboard Design & Analysis

### 7.1 Vendor Performance Overview

The dashboard identifies top vendors by sales contribution, with vendors such as **Diageo North America**, **Martignetti Companies**, and **Pernod Ricard USA** generating the highest revenue. This highlights strong vendor partnerships but also indicates revenue concentration risk.

### 7.2 Brand Performance Analysis

Brand-level analysis shows premium brands such as **Jack Daniels**, **Tito’s Handmade Vodka**, and **Grey Goose** as leading revenue drivers. These insights help prioritize marketing and inventory investment toward high-performing brands.

### 7.3 Purchase Contribution Analysis

The purchase contribution donut chart reveals that a small number of vendors contribute nearly **25% of total purchases**, while several vendors contribute marginally. This uneven distribution signals dependency risks and opportunities for vendor diversification.

### 7.4 Low-Performing Vendors & Brands

Low-performing vendors are identified using contribution ratios, highlighting vendors with weaker performance that may require renegotiation or strategic review. A scatter plot comparing total sales against average profit margin identifies brands with high sales but low margins, as well as brands with low sales and low profitability.

### 7.5 Time-Based Trend Analysis

Monthly purchase trend analysis reveals seasonality and fluctuations in purchasing behavior across the year. Vendor-wise monthly trends for top vendors highlight dependency patterns and consistency in procurement. Additionally, order-size-based trend analysis (small, medium, large orders) provides insights into demand structure and purchasing strategy.

---

## 8. Key Insights

* Revenue and purchases are highly concentrated among a few key vendors
* Several vendors and brands underperform based on contribution and margin metrics
* Monthly trend analysis reveals seasonal purchasing patterns
* Large order sizes contribute significantly to total purchase value
* Unsold capital of $2.71M indicates scope for inventory optimization

---

## 9. Business Impact

This dashboard enables organizations to:

* Optimize vendor selection and negotiation strategies
* Improve profitability through brand-level margin analysis
* Reduce inventory inefficiencies and unsold capital
* Enhance forecasting and planning using time-based trends
* Support data-driven decision-making across procurement and finance teams

---

## 10. Tools & Technologies Used

* **Power BI:** Dashboard development and data modeling
* **SQL:** Data extraction and aggregation
* **Python (Pandas, Matplotlib):** Data cleaning and exploratory analysis
* **Excel / CSV:** Data storage and preprocessing

---

## 11. Conclusion

The Vendor Performance Analysis Project demonstrates the effective use of data analytics and business intelligence tools to convert transactional data into actionable insights. By combining KPIs, vendor and brand analysis, and time-based trends, the dashboard provides a comprehensive decision-support system that improves operational efficiency, profitability, and strategic planning.

---

## 12. Future Enhancements

* Implement year-over-year growth analysis
* Add predictive forecasting models
* Integrate automated data refresh pipelines
* Include vendor risk and reliability metrics
* Enable drill-through views for detailed vendor and brand analysis
