# 📚 Book Sales Analysis Dashboard (Power BI)

A professional **Power BI Dashboard** built to analyze **Book Sales Performance**, **Revenue**, **Payment Status**, **Daily Sales Trends**, and **State-wise Sales Distribution**. The dashboard helps business owners monitor sales performance, identify top-selling books, and make data-driven decisions.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Business Problem](#-business-problem)
- [Objectives](#-objectives)
- [Dataset Overview](#-dataset-overview)
- [Dashboard Features](#-dashboard-features)
- [KPIs](#-kpis)
- [Visualizations Used](#-visualizations-used)
- [Key Insights](#-key-insights)
- [Business Recommendations](#-business-recommendations)
- [Tools & Technologies](#-tools--technologies)
- [Project Structure](#-project-structure)
- [Dashboard Screenshot](#-dashboard-screenshot)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

# 📖 Overview

The **Book Sales Analysis Dashboard** provides a complete overview of sales transactions, payment status, revenue, and customer purchasing trends. It enables businesses to analyze top-performing books, monitor daily sales performance, compare state-wise revenue, and evaluate gross and net sales using interactive Power BI visualizations.

---

# 🎯 Business Problem

The bookstore wanted answers to the following questions:

- Which books generate the highest sales?
- How many orders are completed successfully?
- Which payment status has the highest transactions?
- Which states contribute the highest revenue?
- How do daily sales fluctuate?
- What is the Gross Sales vs Net Sales?
- Which books are top-selling by quantity?
- Which books generate the highest revenue?

Without an interactive dashboard, answering these questions required manual reporting and significant time.

---

# 🎯 Objectives

- Monitor overall sales performance.
- Track completed, pending, and failed payments.
- Analyze top-selling books.
- Compare gross and net sales.
- Identify high-performing states.
- Monitor daily sales trends.
- Support business decision-making.

---

# 📂 Dataset Overview

The dataset contains transactional information of a bookstore.

| Column | Description |
|---------|-------------|
| Order ID | Unique order number |
| Book Name | Name of the purchased book |
| Order Date | Transaction date |
| Customer Name | Customer details |
| State | Customer location |
| City | Customer city |
| Gross Amount | Total sales amount |
| Net Amount | Final received amount |
| GST | Tax amount |
| Discount | Discount applied |
| Payment Status | Success / Pending / Failed |
| Payment Method | Mode of payment |

---

# 📊 Dashboard Features

### Payment Status Filter
- Select All
- Failed
- Pending
- Success

### KPI Cards

- Number of Orders
- Net Sales
- Gross Sales

### Product Analysis

- Top 5 Books Sold
- Top 5 Revenue Generating Books

### Sales Analysis

- Daily Net Sales
- Daily Gross Sales
- State-wise Net Sales

---

# 📈 KPIs

| KPI | Value |
|------|-------|
| Total Orders | 52 |
| Net Sales | ₹45.50K |
| Gross Sales | ₹53.69K |

---

# 📊 Visualizations Used

| Visualization | Purpose |
|--------------|---------|
| Slicer | Filter data by payment status |
| KPI Cards | Display Orders, Net Sales, Gross Sales |
| Clustered Column Chart | Top 5 Books Sold |
| Clustered Column Chart | Top 5 Revenue Books |
| Column Chart | Daily Net Sales |
| Pie Chart | Net Sales by State |
| Bar Chart | Gross Sales by Day |

---

# 🔍 Key Insights

- Total transactions recorded: **52**
- Gross Sales reached **₹53.69K**
- Net Sales generated **₹45.50K**
- Excel Book recorded the highest sales quantity.
- Power BI Book generated the highest revenue.
- Maharashtra contributed the highest Net Sales.
- Sales peaked on Day 21.
- Successful payments represented the majority of transactions.

---

# 💡 Business Recommendations

- Increase inventory for top-selling books.
- Focus marketing campaigns on high-revenue books.
- Improve payment processing to reduce failed transactions.
- Expand sales efforts in high-performing states.
- Investigate low-sales days and optimize promotional activities.
- Introduce targeted discounts during slow sales periods.

---

# 🛠 Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard Development |
| Power Query | Data Cleaning |
| DAX | KPI Calculations |
| Excel | Dataset Source |
| Data Modeling | Relationships |

---

# 📁 Project Structure

```
Book-Sales-Analysis/
│
├── Dashboard/
│   └── Book Sales Dashboard.pbix
│
├── Dataset/
│   └── Book Sales Dataset.csv
│  
│
├── Images/
│   └── Dashboard.png
│
└── README.md
```

---

# 📷 Dashboard Screenshot

<img src="image/Book sales Dashboard.png" alt="Project Architecture" width="1000">

# 🚀 Future Improvements

- Monthly & Yearly Sales Analysis
- Customer Segmentation
- Profit Analysis
- Category-wise Sales
- Interactive Drill-through Reports
- Forecasting using Power BI
- Dynamic Date Filters

---

# 👨‍💻 Author

**Swastik Kumar**

Computer Engineering Student

Skills:
- Power BI
- SQL
- Python
- Excel
- Power Query
- DAX
- Data Analytics

---

## ⭐ If you found this project useful, don't forget to Star this repository.
