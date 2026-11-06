[README (3).md](https://github.com/user-attachments/files/34467863/README.3.md)
# 📊 PR. Final Project: Data Intelligence Dashboard & Advanced Business Analytics

### 👤 Author
**Pankti Patel**

### 🔗 Project Link
👉 [**View Project Spreadsheet**](https://docs.google.com/spreadsheets/d/1vzX4qI6-tt5dI25Cvh--dUi7zprde9rH/edit?usp=drive_link&ouid=106178778574788685790&rtpof=true&sd=true)

⭐ *"Thank you for exploring this project! May your spreadsheets always balance, your data stories inspire, and your analytics journey be filled with continuous discovery."*

---

## 📑 Table of Contents

- [🌟 Project Overview](#-project-overview)
- [🛠️ Key Topics & Technical Skills Covered](#️-key-topics--technical-skills-covered)
- [🧮 Functions Reference](#-functions-reference)
- [📁 Workbook Architecture & Sheets](#-workbook-architecture--sheets)
- [🗂️ Dataset Dictionary](#️-dataset-dictionary)
- [📈 Key Analytical Highlights & Findings](#-key-analytical-highlights--findings)
- [🚀 How to Explore & Use This Model](#-how-to-explore--use-this-model)
- [✅ Skills Demonstrated](#-skills-demonstrated)

---

## 🌟 Project Overview

The **PR. Final Project - Data Intelligence Dashboard** is an end-to-end business intelligence and transaction modeling solution built to analyze customer transactions, regional sales distribution, product demand, and financial forecasting.

Designed using advanced spreadsheet techniques in **Microsoft Excel** and **Google Sheets**, this project transforms over **200 customer sales records** into actionable executive insights through interactive dashboard design, dynamic lookup logic, automated date tracking, and What-If scenario planning.

| 📌 Item | Details |
|---|---|
| **Project Title** | PR. Final Project - Data Intelligence Dashboard |
| **Author** | Pankti Patel |
| **Tools** | Microsoft Excel, Google Sheets |
| **Records Analyzed** | 200+ customer transactions |
| **Focus Areas** | Sales analysis, regional performance, product demand, forecasting |
| **Spreadsheet** | [View Project Spreadsheet](https://docs.google.com/spreadsheets/d/1vzX4qI6-tt5dI25Cvh--dUi7zprde9rH/edit?usp=drive_link&ouid=106178778574788685790&rtpof=true&sd=true) |

---

## 🛠️ Key Topics & Technical Skills Covered

- **⏱️ Dynamic Date & Time Automation:** Real-time timestamping using `TODAY()` and `NOW()`, customer tenure calculation using `DATEDIF()`, and end-of-month billing cycle tracking with `EOMONTH()`.
- **🧹 Data Cleaning & Text Manipulation:** String extraction and code generation using `UPPER()`, `LEFT()`, and `TEXT()` functions to generate uniform product abbreviations.
- **📊 Group-By & Dynamic Aggregations:** Multi-criteria summary reporting using `SUMIF()`, `COUNTIF()`, and array index matching (`INDEX()` + `MODE()` + `MATCH()`) to identify most frequently purchased products.
- **🔍 Multi-Value Dynamic Filtering:** Automated subset extraction using the `FILTER()` function for multi-condition queries (e.g., region-specific high-quantity sales).
- **🎯 Quantitative & Predictive Modeling:**
  - **What-If Analysis & Goal Seek:** Revenue target modeling ($100,000 target scenario).
  - **Linear Regression Analysis:** Quantifying relationship trends (Quantity vs. Total Sales) using `SLOPE()` and `INTERCEPT()`.
- **📉 Interactive Visualizations & Dashboarding:**
  - Dynamic Pivot Tables and Pivot Charts (Regional Bar Chart, Monthly Sales Trend Line Chart, Category Share Pie Chart).
  - Cross-connected **Slicers** and Timelines (`Payment_Method` and `Region`) linked across multiple pivot tables using **Report Connections**.
- **🎨 Automated Formatting:** Custom 3-Icon Set conditional formatting (arrows/indicators) for immediate KPI performance tracking.

---

## 🧮 Functions Reference

| Category | Functions Used | Purpose |
|---|---|---|
| **Date & Time** | `TODAY()`, `NOW()`, `DATEDIF()`, `EOMONTH()` | Live timestamps, customer tenure, billing cycle end dates |
| **Text** | `UPPER()`, `LEFT()`, `TEXT()` | Standardized product abbreviation codes |
| **Aggregation** | `SUMIF()`, `COUNTIF()` | Group-by totals and counts per region/category |
| **Lookup & Stats** | `INDEX()`, `MATCH()`, `MODE()` | Most frequently purchased product |
| **Dynamic Arrays** | `FILTER()` | Multi-condition subset extraction |
| **Regression** | `SLOPE()`, `INTERCEPT()` | Linear relationship between Quantity and Total Sales |
| **What-If** | Goal Seek | Revenue target modeling ($100,000) |

---

## 📁 Workbook Architecture & Sheets

| # | Sheet | Description |
|---|---|---|
| 1 | 📝 **Project Instructions** | Detailed project objectives, guidelines, and core topics to implement. |
| 2 | 📊 **Dashboard** | Consolidated executive summary displaying KPI indicators, embedded interactive slicers, and visual chart distributions. |
| 3 | 🔄 **Visualizations / Pivot Tables** | Dedicated structured pivot tables aggregating revenue across geographic territories (`Region`) and product lines (`Category`). |
| 4 | 🗃️ **Final Project Dataset (Raw Data & Analysis)** | The core database containing 200+ transactional records alongside newly created calculated helper columns. |

---

## 🗂️ Dataset Dictionary

| Column | Description |
|---|---|
| `Transaction_ID` | Unique identifier for each transaction |
| `Customer_ID` | Unique identifier for each customer |
| `Product_ID` | Product identifier / code |
| `Category` | Product category (Electronics, Appliances, Furniture) |
| `Unit_Price` | Price per unit |
| `Quantity` | Number of units purchased |
| `Payment_Method` | Payment type used for the transaction |
| `Region` | Sales territory (Central, East, North, South, West) |
| `Customer_Since` | Date the customer relationship began |
| `Total_Amount` | Transaction total (`Unit_Price × Quantity`) |

> Additional **calculated helper columns** (tenure, billing date, product code, etc.) are added alongside the raw fields in the dataset sheet.

---

## 📈 Key Analytical Highlights & Findings

- 💰 **Total Transaction Revenue:** Comprehensive aggregation across 200+ customer records generating total revenue.
- 🌍 **Top Regional Drivers:** Performance analysis identifying lead sales volume across regional territories (Central, East, North, South, West).
- 🛒 **Product & Category Breakdown:** Sales distribution highlighting dominant revenue categories across Electronics, Appliances, and Furniture.
- 🔮 **Predictive Pricing Model:** Linear regression metrics evaluating sales volume sensitivity against price variations.

---

## 🚀 How to Explore & Use This Model

1. 🔗 Open the [**Project Spreadsheet**](https://docs.google.com/spreadsheets/d/1vzX4qI6-tt5dI25Cvh--dUi7zprde9rH/edit?usp=drive_link&ouid=106178778574788685790&rtpof=true&sd=true), or open `PR_Final_Project.xlsx` in Excel.
2. 📊 Navigate to the **Dashboard** sheet to view interactive charts and KPI metrics.
3. 🎛️ Use the **Payment Method** and **Region** slicers to dynamically filter all visualizations in real time.
4. 🔎 Review the **Analysis** and **Dataset** tabs to inspect the underlying Excel formulas, helper columns, Goal Seek calculations, and dynamic filter ranges.

---

## ✅ Skills Demonstrated

`Data Cleaning` · `Pivot Tables` · `Dashboard Design` · `Slicers & Timelines` · `Conditional Formatting` · `Dynamic Arrays` · `Linear Regression` · `Goal Seek` · `Business Intelligence`

---

<p align="center">
  Made with ❤️ by <b>Pankti Patel</b><br>
  <a href="https://docs.google.com/spreadsheets/d/1vzX4qI6-tt5dI25Cvh--dUi7zprde9rH/edit?usp=drive_link&ouid=106178778574788685790&rtpof=true&sd=true">View Project Spreadsheet</a>
</p>
