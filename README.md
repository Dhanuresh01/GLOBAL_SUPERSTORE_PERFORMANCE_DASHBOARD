# 📊 Global Superstore Performance Dashboard (Power BI)

## 📌 Project Overview
This project is a comprehensive business intelligence dashboard created using **Power BI**.  
The goal was to transform raw sales data from a global superstore into a set of interactive, insightful reports.  
The dashboard provides a **360-degree view** of the business, covering **financial performance, product profitability, and customer/operational insights**.

---

## ✨ Key Features & Goals
The dashboard is structured into **three distinct pages**, each designed to answer a set of critical business questions:

### Page 1: Executive Summary
**Goal:** Provide a high-level overview of key financial performance indicators (KPIs) and identify overall sales trends and geographical strengths.

### Page 2: Product & Category Analysis
**Goal:** Analyze the product portfolio to understand profitability, sales drivers, and identify top-performing products.

### Page 3: Customer & Operational Insights
**Goal:** Segment customers based on their value and analyze operational efficiency, particularly related to shipping and logistics.

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** – Data modeling, DAX calculations, and visualization  
- **Power Query** – Data cleaning, transformation, and preparation  
- **DAX (Data Analysis Expressions)** – Custom measures for KPIs (e.g., Total Sales, Profit Margin, etc.)

---

## 📈 Key Skills Demonstrated
- **Data Cleaning & Transformation:** Corrected data types, handled missing values, and prepared dataset.  
- **Data Modeling:** Established relationships between tables for cross-visual filtering.  
- **Advanced DAX:** Created measures like `Profit Margin = DIVIDE([Total Profit], [Total Sales])`.  
- **Data Visualization:** Designed visuals – Cards, Line Charts, Maps, Treemaps, Donut Charts, Scatter Charts.  
- **Dashboard Design:** Interactive, multi-page layout with clean UI and cohesive color palette.  
- **Storytelling & Insights:** Converted complex data into actionable business insights.

---

## 🚀 Challenges & Solutions

| **Challenge** | **Solution** |
|---------------|--------------|
| **Data Aggregation:** Multiple rows per order made it hard to count total orders. | Created a DAX measure with `DISTINCTCOUNT(Orders[Order ID])`. |
| **KPI Calculation:** Profit Margin not available in raw data. | Built a custom DAX measure: `Profit Margin = DIVIDE([Total Profit], [Total Sales])`. |
| **Information Overload:** A single page would be too cluttered. | Split into 3 pages: Executive Summary, Product Analysis, Operational Insights. |
| **Geographical Visualization:** Hard to show sales across countries/states. | Used Power BI Filled Map visual linked to Country & State columns. |

---

## 💡 Key Insights from the Analysis
- **Profitability vs. Volume :** The Technology category, while not our highest-volume seller, is by far the most profitable, justifying a focus on this high-margin product line.

- **Strategic Geography :** The United States is our top-performing market, with sales concentrated in the West region. This data can be used to replicate successful strategies in other regions.

- **Seasonal Trends :** Sales show a strong seasonal pattern, with significant peaks in the final quarter of each year, which is crucial for forecasting and inventory planning.

- **Customer Value :** A small group of high-value customers contributes a significant portion of total sales and profit, highlighting the importance of customer retention strategies.

- **Operational Efficiency :** The company is heavily reliant on "Standard Class" shipping, which presents an opportunity for the logistics team to optimize this process for greater efficiency and cost savings.

---

## 🖼️ Dashboard Screenshots
- **Page 1: Executive Summary**  
  ![Executive Summary Screenshot](./images/Executive%20summary.PNG)  

- **Page 2: Product & Category Analysis**  
  ![Product Analysis Screenshot](./images/product%20analysis.PNG)  

- **Page 3: Customer & Operational Insights**  
  ![Customer Insights Screenshot](./images/Customer%20analysis.PNG)  

---


## 🤝 Feedback & Collaboration
Thank you for viewing this project!  
I am open to **feedback, suggestions**. 🚀

