# 📊 TrendMart Sales & Profit Intelligence Dashboard  

## 📌 Project Overview  
This project analyzes **retail sales and profitability** using Power BI. The goal was to design an **interactive dashboard** that helps business stakeholders track KPIs, identify high-performing products/customers, and uncover insights for growth.  

The project follows best practices in **data modeling, DAX, and visualization design**, making it portfolio-ready for data analytics roles.  

---

## 🗂 Dataset  
The dataset was adapted from an e-commerce retail scenario and includes:  
- **Orders** → Transaction-level sales data  
- **Customers** → Customer demographic & segment details  
- **Products** → Product category & sub-category info  
- **Returns** → Records of returned orders  
- **Calendar** → Date dimension for time-based analysis  

---

## 🏗 Data Modeling  
A **star schema** was implemented in Power BI:  
- **Fact Table**: Orders  
- **Dimension Tables**: Customers, Products, Returns, Calendar  

Relationships:  
- Customers → Orders  
- Products → Orders  
- Calendar → Orders  
- Returns → Orders  

This structure improves performance, simplifies DAX, and follows BI best practices.  

---

## 📐 Key Measures (DAX)  
Some important measures created:  
- `Total Sales = SUM(Orders[Sales])`  
- `Total Profit = SUM(Orders[Profit])`  
- `Profit Margin = DIVIDE([Total Profit], [Total Sales])`  
- `Avg Order Value = DIVIDE([Total Sales], DISTINCTCOUNT(Orders[Order ID]))`  
- `Customer Retention %` (calculated via returning customers year-over-year)  

---

## 📊 Dashboards  

### 1️⃣ Sales Intelligence Dashboard  
- **KPIs**: Total Sales, Total Orders, Avg Order Value  
- **Visuals**:  
  - Sales by Category & Sub-Category  
  - Top 10 Customers & Products  
  - Sales Trend by Month  
  - Regional Performance Map  

### 2️⃣ Profit Intelligence Dashboard  
- **KPIs**: Total Profit, Profit Margin %  
- **Visuals**:  
  - Profit by Category & Region  
  - Top 10 Most/Least Profitable Products  
  - Returns Analysis  
  - Profitability Trends over Time  

---

## 🔑 Insights  
- Technology products drive the highest profit margins.  
- The West region underperforms in profitability compared to others.  
- A small % of customers contribute a large share of total revenue.  
- High return rates in Office Supplies impact overall profitability.  

---

## 🛠 Tools & Techniques  
- **Power BI** → Data modeling, DAX, dashboard design  
- **Data Modeling** → Star schema with fact & dimension tables  
- **ETL** → Power Query for cleaning & shaping data  
- **Visualization** → Interactive reports, slicers, drill-throughs  

---

## 📂 Repository Structure  
```
📁 TrendMart-Dashboard
│── 📄 README.md  (this file)
│── 📄 TrendMart_Dashboard.pbix  (Power BI file)
│── 📄 Dashboard_Screenshots/  (PNG/JPEG of dashboards)
│── 📄 CaseStudy.pdf  (2-page portfolio summary)
│── 📂 Data/ (CSV files if included or link to source)
```

---

## 🚀 Business Value  
This dashboard empowers decision-makers to:  
- Monitor **sales & profit KPIs** in real-time  
- Identify **profitable regions & product categories**  
- Improve **customer segmentation & targeting**  
- Reduce **losses from product returns**  

---

## 📸 Sample Dashboard Screenshots  

*(Insert screenshots of your Page 1 & Page 2 dashboards here)*  

---

✨ **Created with Power BI as part of Data Analytics Portfolio Projects.**  
