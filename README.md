# 📊 Global Electronics: Sales, Profitability & Customer Insights Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Data-Analytics-0078D4?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-2EA44F?style=for-the-badge)

## 📌 Project Overview
An interactive, multi-page **Power BI Business Intelligence solution** designed for **Global Electronics** to monitor financial performance, evaluate product and brand profitability, and analyze global customer demographics across the **2016–2021** period. 

The report features a custom dark-themed UI with seamless page navigation, dynamic cross-filtering, reset filter buttons, and drill-down capabilities[cite: 1, 2, 3].

---
# 📊 Global Electronics: Sales, Profitability & Customer Insights Dashboard Overview
<img width="962" height="498" alt="Final Project" src="https://github.com/user-attachments/assets/b0929806-d98e-4dfe-af84-c8e877c36126" />
<img width="954" height="461" alt="Screenshot 2026-11-13 140754" src="https://github.com/user-attachments/assets/f1b315e2-b054-45db-a5bc-a352976d4cec" />
<img width="958" height="455" alt="Screenshot 2026-11-13 141008" src="https://github.com/user-attachments/assets/cb8d5f01-5d90-4320-b831-edad818e3be0" />

---

## 🎯 Key Business Metrics (KPIs)
* **Total Sales:** `$21.84M`[cite: 1, 2]
* **Total Profit:** `$12.81M` *(Target Benchmark: $15.00M)*[cite: 1, 2]
* **Total Cost:** `$9.04M`[cite: 2]
* **Total Orders:** `10,129`[cite: 1, 2]
* **Total Quantity Sold:** `76,908` units[cite: 1]
* **Total Customers:** `7K`[cite: 3]
* **Average Order Value (AOV LY):** `$2.16K`[cite: 3]

---

## 🗂️ Dashboard Architecture & Pages

### 1️⃣ Executive Overview
Provides high-level visibility into core financial health and seasonal sales trends[cite: 2]:
* **KPI Cards:** Total Sales (`21.84M`), Total Cost (`9.04M`), Total Profit (`12.81M`), and Total Orders (`10,129`)[cite: 2].
* **Total Sales by Year (Donut Chart):** Tracks annual revenue contribution from 2016 to 2021[cite: 2].
* **Total Profit Gauge:** Measures cumulative profit (`12.81M`) against the `15.00M` strategic target[cite: 2].
* **Total Cost & Total Profit by Month Name (Clustered Column Chart):** Compares monthly profitability against operational costs, highlighting peak performance in February, December, and April[cite: 2].
* **Total Sales by Product Name (Horizontal Bar Chart):** Ranks top-performing SKUs led by *WWI Wireless Transmitter and Bluetooth Headphones X250* models[cite: 2].

---

### 2️⃣ Product & Profitability
Deep-dives into category performance, brand contribution, and profit drivers[cite: 1]:
* **KPI Cards:** Total Sales (`21.84M`), Total Quantity (`76,908`), Total Profit (`12.81M`), and Total Orders (`10,129`)[cite: 1].
* **Total Sales by Brand (Waterfall Chart):** Visualizes incremental revenue contributions across brands (*Adventure Works, Contoso, Wide World Importers, Fabrikam, The Phone Company*, etc.)[cite: 1].
* **Total Sales by Category (Donut Chart):** Breaks down revenue share across product lines[cite: 1]:
  * **Computers:** `$7.51M` (`34%`)[cite: 1]
  * **Home Appliances:** `$4.38M` (`20%`)[cite: 1]
  * **Cameras & Camcorders:** `$2.64M` (`12%`)[cite: 1]
  * **Cell Phones:** `$2.48M` (`11%`)[cite: 1]
  * **TV & Video:** `$2.20M` (`10%`)[cite: 1]
  * **Music, Movies & Audio Books:** `$1.25M` (`6%`)[cite: 1]
* **Profit Decomposition Tree (AI Visual):** Interactive root-cause breakdown of `Total Profit ($12.81M)` by **Subcategory** (led by *Desktops* at `$2.14M`, *Projectors & Screens*, and *Televisions*) and **Country** (led by the *United States* at `$1.19M`, *United Kingdom*, and *Germany*)[cite: 1].

---

### 3️⃣ Customer Insights
Analyzes customer value, purchasing behavior, and geographic distribution[cite: 3]:
* **KPI Cards:** Average Order Value Last Year (`2.16K`) and Total Customers (`7K`)[cite: 3].
* **Total Sales by Customer Name (Horizontal Bar Chart):** Identifies top revenue-generating customers (led by *Karen Jones*, *Esin Holman*, and *Stephan Rothstein*)[cite: 3].
* **Total Customers by Country (Bubble Map):** Displays global customer concentration across North America, Europe, and Australia[cite: 3].

---

## 🛠️ Features & Technical Implementation
* **Interactive Navigation Sidebar:** Custom button-based navigation switching cleanly between *Executive Overview*, *Product & Profitability*, and *Customer Insights*[cite: 1, 2, 3].
* **Global Slicers & Filter Reset:** Synchronized slicers for **Year**, **Category**, and **Country** paired with a one-click clear-filters bookmark action[cite: 1, 2, 3].
* **Data Modeling & DAX:** Built using a star-schema data model with custom DAX measures for Revenue, Profit, Cost, Order Count, Quantity Sold, and Time-Intelligence (`AOV LY`)[cite: 1, 2, 3].

---

## 💡 Key Analytical Insights
1. **Core Revenue Drivers:** **Computers (`34%`)** and **Home Appliances (`20%`)** account for over half (`54%`) of Global Electronics' total revenue[cite: 1].
2. **High-Margin Subcategories:** Within the profit decomposition tree, **Desktops** generate the single largest profit share (`$2.14M`), with the **United States** serving as the primary geographic profit driver[cite: 1].
3. **Strong Profit Margins:** Maintaining `$12.81M` in profit against `$9.04M` in total cost reflects a healthy overall profit margin of **~58.65%** across `10,129` orders[cite: 2].

---

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/global-electronics-sales-profitability-powerbi.git
