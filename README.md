# Supply Chain Performance & Risk Analysis

An interactive **Power BI Business Intelligence dashboard** designed to analyze sales performance, profitability, shipping efficiency, delivery risk, customer segments, regional performance, and operational risk across the supply chain.

---

## 📊 Project Overview

This project transforms supply chain transaction data into an interactive analytical dashboard using **Power BI, DAX, Power Query, and Star Schema data modeling**.

The dashboard provides an executive-level overview as well as detailed analysis across sales, delivery, customer, geography, shipping modes, and operational risk.

### Key Performance Indicators

* **Total Orders:** 66K
* **Total Sales:** 36.78M
* **Total Profit:** 3.97M
* **Profit Margin:** 10.78%
* **Late Delivery Risk:** 54.82%
* **Late Risk Orders:** 36,048

---

## 🎯 Business Objectives

The main objectives of this project are to:

* Analyze overall sales and profitability performance.
* Identify high-performing product categories and products.
* Track sales and profit trends over time.
* Evaluate shipping efficiency across shipping modes.
* Measure shipping delays and delivery risk.
* Analyze customer segment and regional performance.
* Identify regions and categories with higher delivery risk.
* Compare scheduled versus actual shipping time.
* Support data-driven supply chain decision-making.

---

## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **DAX**
* **Power Query**
* **Data Modeling**
* **Star Schema**
* **Data Visualization**
* **Business Intelligence**

---

## 🧩 Data Modeling

The project uses a **Star Schema** to organize the analytical model and improve filtering and reporting.

### Model Structure

**Fact Table**

* Fact Orders

**Dimension Tables**

* Dim Date
* Dim Product
* Dim Customer
* Dim Shipping
* Dim Location

The fact table is connected to the dimension tables through appropriate one-to-many relationships.

---

## 📐 DAX Measures

Key DAX calculations developed for the dashboard include:

* Total Sales
* Total Profit
* Total Orders
* Profit Margin %
* Actual Shipping Time
* Scheduled Shipping Time
* Shipping Delay
* Late Risk Orders
* Late Delivery %

The complete DAX documentation is available here:

[`documentation/dax-measures.md`](Dax measures)

---

## 📈 Dashboard Pages

### 1. Executive Overview

Provides a high-level view of overall business performance.

**Key analysis:**

* Total Orders
* Total Sales
* Total Profit
* Profit Margin
* Sales & Profit Trend
* Sales & Profit by Category
* Top Products by Sales
* Profit vs Discount by Category

**Dashboard Preview**

![Executive Overview](https://github.com/Ajmal-SR/Supply-Chain-Performance-Risk-Analysis/blob/58b2abdc9e686b933ee5966290bc53fc856b0930/Overview%20page%20%201.jpg)

---

### 2. Delivery & Shipping Performance

Focuses on shipping efficiency and delivery risk.

**Key analysis:**

* Scheduled vs Actual Shipping Time
* Shipping Delay by Mode
* Shipping Delay by Region
* Late Delivery Rate by Category
* Late Delivery %

**Dashboard Preview**

![Delivery & Shipping Performance](https://github.com/Ajmal-SR/Supply-Chain-Performance-Risk-Analysis/blob/6904012e787d7d9994335f2ea10a99c5769d4d1e/delivary%20Analysis%20page%202.jpg)
---

### 3. Customer & Market Performance

Analyzes customer segments, markets, regions, and shipping modes.

**Key analysis:**

* Sales by Customer Segment
* Market Performance Overview
* Sales & Profit by Region
* Sales by Shipping Mode

**Dashboard Preview**

![Customer & Market Performance](https://github.com/Ajmal-SR/Supply-Chain-Performance-Risk-Analysis/blob/6b813c3148b131ef375eb1d11ebd185e7cd357cb/Customer%20%26%20market%20performance%20page%203.jpg)

---

### 4. Operational Risk & Analysis

Provides detailed analysis of delivery risk and operational performance.

**Key analysis:**

* Late Risk Orders by Region
* Category Risk & Profitability
* Shipping Mode Performance & Risk
* Late Risk Orders
* Actual Shipping Time
* Profit by Shipping Mode

**Dashboard Preview**

![Operational Risk & Analysis](<img width="957" height="549" alt="image" src="https://github.com/user-attachments/assets/474b7d94-6661-47f4-a15a-3356117e8203" />
)

---

## 🎛️ Interactive Features

The dashboard includes:

* Interactive slicers
* Year filtering
* Quarter filtering
* Order Region filtering
* Shipping Mode filtering
* Synchronized slicers across report pages
* Page navigation
* Interactive visual filtering
* Multi-page analytical reporting

The dashboard uses a consistent navigation structure so users can move between the analysis pages directly.

---

## 🔍 Key Findings

Based on the dashboard:

* The overall dataset contains approximately **66K distinct orders**.
* Total sales are approximately **36.78M**, with total profit of approximately **3.97M**.
* Overall profit margin is approximately **10.78%**.
* Approximately **54.82% of orders are identified as having late delivery risk**.
* **36,048 orders** are classified as late-risk orders.
* Consumer customers generate the highest sales among the customer segments, followed by Corporate and Home Office segments.
* Shipping performance varies considerably across shipping modes, with Standard Class accounting for the largest late-risk order volume in the dashboard.
* Delivery risk differs across product categories and regions, highlighting areas that require operational attention.

---

## 💡 Business Recommendations

Based on the analysis, organizations can:

1. Investigate regions with consistently high delivery-risk orders.
2. Review shipping modes with higher delay or late-risk levels.
3. Analyze high-risk product categories for potential logistics issues.
4. Monitor the gap between scheduled and actual shipping time.
5. Optimize shipping strategies based on profitability and delivery performance.
6. Monitor customer and regional sales performance to identify growth opportunities.
7. Use delivery-risk metrics as part of ongoing supply chain performance monitoring.

---

## 📁 Repository Structure

```text
Supply-Chain-Performance-Risk-Analysis/
│
├── README.md
│
├── Supply_Chain_Performance_Risk_Analysis.pbix
│
├── dashboard/
│   ├── executive-overview.png
│   ├── delivery-shipping.png
│   ├── customer-market.png
│   └── operational-risk.png
│
└── documentation/
    ├── dax-measures.md
    └── data-model.png
```

---

---

## 🚀 Project Outcome

This project demonstrates the ability to:

* Build a professional Power BI dashboard from raw supply chain data.
* Design and implement a Star Schema data model.
* Create analytical DAX measures.
* Build interactive and synchronized dashboard filters.
* Analyze business performance from multiple dimensions.
* Translate data into actionable business insights.
* Present complex supply chain information through a clear executive dashboard.

---

## 👤 Author

**Ajmal**

---

## ⭐ Project Skills Demonstrated

`Power BI` `DAX` `Power Query` `Data Modeling` `Star Schema` `Data Visualization` `Business Intelligence` `Supply Chain Analytics` `Sales Analytics` `Risk Analysis`
