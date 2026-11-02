# 📊 MEGA SALES – Power BI Dashboard

An interactive Power BI report that analyzes sales performance, profitability, and customer behavior across regions, stores, and products. Built with DAX measures, slicers, and page navigation for easy exploration.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `MEGA_SALES.pbix` | Power BI report (data model, DAX measures, visuals) |
| `README.md` | Project documentation |

> To add screenshots, create a `/images` folder and reference them in the **Dashboard Preview** section below.

---

## 🎯 Project Objectives

- Monitor overall business performance (sales, profit, margin, orders).
- Identify top regions, store types, brands, and products.
- Understand customer demographics and membership segments.
- Track customer acquisition and churn, and estimate revenue loss.
- Compare sales year over year and view cumulative (running) sales.

---

## 🗂️ Report Pages

### 1. Overview
High-level KPIs and sales breakdowns.
- **KPI cards:** Sales, Profit, Profit Margin, Total Orders, Average Order Price, Total Customers, Total Products, Total Stores
- **Country-wise sales** (pie chart)
- **Region-wise sales** (donut chart) and **profit by region** (column chart)
- **Store-type-wise sales** (bar chart)
- **Sales by product brand** (area chart)
- **Top 5 best-selling items** (table)
- **Slicers:** Year, Sales Region, Store Type
- Navigation button to the Customer Insight page

### 2. Sales Trend (Page 2)
Time-based comparison tables.
- Sales vs. previous-year sales with **YoY** change
- **Running sales** by date
- Year slicer

### 3. Customer Insight
Customer composition and retention.
- Total customers and **customers by gender** (donut)
- **Customers by age category** (young / adult / aged)
- **Sales by membership card type** across customer revenue groups
- **Number of customers joined** vs. **customers lost** over time
- **Churned customers** count and **estimated loss**
- Navigation button back to the Overview

### 4. Page 4
Supporting data table.

---

## 🧮 Key Measures (DAX)

Stored in a dedicated `MEASURES TABLE`:

`SALES` · `profit` · `PROFIT_MARGIN` · `total orders` · `AVG_ORDER_PRICE` · `TOTAL_CUSTOMERS` · `TOTAL_PRODUCTS` · `TOTAL_STORES` · `previous_year_sales` · `yoy` · `running_sales` · `churned_customers` · `loss_estimated`

---

## 🧱 Data Model

Tables used in the report:

- `customers` – demographics, country, gender, member card, first/last transaction dates
- `product` – product name and brand
- `stores` – store type
- `regions` – sales region
- `calender` – date table (year, date) for time intelligence
- `TR_97_98` – transaction data with customer age category
- `churned_custumer2` – churned customer list
- `MEASURES TABLE` – all calculated measures

---

## 🛠️ Tools & Skills Demonstrated

- Power BI Desktop
- DAX (time intelligence, YoY, running totals, churn logic)
- Data modeling and relationships
- Interactive dashboard design (slicers, cards, page navigation, custom backgrounds)
- Customer segmentation and churn analysis

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open `MEGA_SALES.pbix` in **Power BI Desktop** (free, Windows).
3. Use the slicers (Year, Region, Store Type) to filter the Overview page.
4. Use the navigation buttons to switch between the Overview and Customer Insight pages.

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
```

---

## 🖼️ Dashboard Preview

<!-- Replace with your own screenshots -->
<!--
![Overview](images/overview.png)
![Customer Insight](images/customer-insight.png)
-->

---

## 📌 Key Insights

*Add your findings here after reviewing the dashboard, for example:*
- Which region generates the highest sales and profit?
- Which store type contributes most to revenue?
- Which membership tier drives the most sales?
- How many customers were lost, and what is the estimated revenue impact?

---

## 👤 Author

**Your Name**
- GitHub: [github](https://github.com/surajaseri0894-alt/MEGA-MALL-PROJECT.git)

---

⭐ If you found this project helpful, consider giving it a star!
