# Blinkit Grocery Data Analysis: Supply Chain & Sales Dashboard

## 📌 Project Overview
This project focuses on analyzing the operational and financial performance of Blinkit, a quick-commerce grocery delivery platform. 

Using a dataset of over **13,000 orders**, I designed a Power BI dashboard to solve critical inventory and logistics challenges. The goal was to translate raw data into actionable insights for three distinct stakeholders: Top Management (Executive), Inventory Managers, and Operations Teams.

**Domain:** E-Commerce & Supply Chain Analytics  
**Tools Used:** Power BI, Microsoft Excel, Data Modelling

---

## 💼 Business Problem Statement
The business required a centralized reporting system to address specific questions across different levels of management:

1.  **Executive View (CEO):** Needed a "one-glance" view of total revenue, sales volume, and customer satisfaction ratings.
2.  **Inventory View (Store Manager):** Required visibility on "Dead Stock" (items not selling) and "Low Stock" (items running out) to prevent revenue loss.
3.  **Operations View (Logistics):** Needed to identify delivery delays and evaluate seller performance based on delivery speed.

---

## 📊 Dashboard Solution & Features

### 1. Executive Dashboard (High-Level KPIs)
* **Performance Cards:** Tracked Total Revenue (**₹509M**), Total Orders (**13K**), and Average Rating (**4.2**).
* **Sales Trend Analysis:** A line chart visualizing revenue fluctuations over time to identify growth patterns.
* **Category Performance:** Breakdown of revenue sources, highlighting **Household** and **Personal Care** as top-performing categories.
* **Geographic Insights:** A map/bar chart identifying top revenue-generating cities like **Pune** and **Lucknow**.

### 2. Inventory Management (Supply Chain Optimization)
* **Dead Stock Analysis:** Identified items with high inventory but zero sales to reduce warehousing costs.
* **Low Stock Alerts:** Created a conditional formatting system to flag items falling below the reorder level.
* **Product Preferences:** Analyzed customer preference for **Packet Size** vs. Box/Bottle to optimize stocking decisions.

### 3. Operations & Logistics Analysis
* **Delivery Efficiency:** Calculated an **Average Delivery Time of 28 minutes**.
* **Seller Performance:** Compared delivery times between distinct sellers (e.g., 'UrbanSeller' vs 'QuickStores') to optimize partner selection.
* **Delay Heatmaps:** Identified which cities face the highest frequency of delayed deliveries to target logistical improvements.

---

## 📈 Key Insights & Findings
* **Revenue Drivers:** The "Household" category is the largest revenue contributor at **₹120.6M**, followed by "Personal Care" at **₹99.8M**.
* **Customer Satisfaction:** There is a correlation between delivery speed and customer ratings; the average rating stands at a strong **4.2/5**.
* **Organic vs. Non-Organic:** Non-organic products currently dominate sales, accounting for **87%** of the market share (₹443M), while organic products capture **13%**.
* **Top Markets:** Tier 1 and Tier 2 cities like **Pune (₹54M)** and **Lucknow (₹53M)** are the "Cash Cows" for the business.

---

## 🧠 Analytical Approach (Engineering Mindset)
As an **Electrical & Electronics Engineer (EEE)**, I approach data analysis as a system optimization task. I view this dashboard not just as charts, but as a feedback loop for business efficiency:

1.  **Input Analysis:** Processing raw transaction logs and inventory status.
2.  **Signal Filtering:** Identifying valid KPIs (Revenue per Unit, Delivery Time) and removing noise.
3.  **System Optimization:** Highlighting bottlenecks (Dead Stock, Delays) to improve the overall "throughput" (Sales & Delivery).

---

## 📂 Repository Structure
* `Data` - Contains the raw Excel/CSV files used for analysis.
* `Dashboard` - The final Power BI (.pbix) file.
* `Screenshots` - Images of the dashboard pages (Executive, Inventory, Operations).
* `README.md` - Project documentation.
