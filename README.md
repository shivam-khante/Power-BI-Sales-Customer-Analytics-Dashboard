# 📊 Power BI Sales & Customer Analytics Dashboard

## 📸 Dashboard Preview

![Dashboard Preview](dashboard.png)

---

## 🚀 Project Overview

This project is an end-to-end **Power BI Dashboard** designed to analyze business performance across **Sales, Customers, Products, and Geography**.

The dashboard provides actionable insights into:

* Revenue & Profit performance
* Customer behavior and retention
* Product performance
* Regional trends and delivery insights

> ⚠️ Note: The dataset used in this project is **synthetically generated using ChatGPT** for learning and portfolio purposes.

---

## 🎯 Business Objective

The goal of this dashboard is to enable business stakeholders to:

* Monitor overall sales and profitability
* Identify top-performing products and regions
* Analyze customer retention and acquisition trends
* Support data-driven decision making

---

## ❓ Key Business Questions Answered

* Which products generate the highest revenue and profit?
* Which regions contribute the most to total sales?
* What is the customer retention vs acquisition trend?
* How do discounts impact revenue?
* Which customer segments are most valuable?

---

## 🧠 Data Model

The dashboard is built using a **Star Schema** approach:

### Fact Table:

* **Orders**

  * Revenue
  * Quantity
  * Discount
  * Payment Method
  * Delivery Status

### Dimension Tables:

* **Customers**

  * CustomerID, Name, Gender, Age, City, Loyalty Tier
* **Products**

  * Product Name, Category, Subcategory, Brand, Cost, Margin
* **Date Table**

  * Date, Month, Quarter, Year
* **Region**

  * Region, State, Country

---

## 📊 Dashboard Pages

### 🟣 Executive Overview

* Total Revenue, Profit, Orders, Customers, AOV
* Revenue trends over time
* Category & region contribution
* Top customers

### 🔵 Sales Analysis

* Revenue by product
* Orders trend
* Brand performance
* Payment method distribution
* Discount vs Revenue analysis

### 🟢 Customer Analytics

* Customer segmentation (Age, Gender, Loyalty Tier)
* Repeat vs New customers
* Customer growth trend
* AOV analysis

### 🟡 Product Insights

* Top & bottom performing products
* Category-level contribution
* Profit analysis by category
* Product performance matrix

### 🟠 Geographic Insights

* Map-based sales distribution
* Region comparison
* State-level sales performance
* Delivery status breakdown

---

## ✨ Key Features

* 📌 Interactive slicers synced across pages
* 🔄 Reset filters using bookmarks
* 🧩 Custom tooltip pages for product-level insights
* 📈 Dynamic KPIs and trend analysis
* 🌍 Multi-page navigation
* 🎯 Drill-down and cross-filtering

---

## ⚙️ DAX Highlights

```DAX
Total Revenue = SUM(FactSales[Revenue])

Total Profit = SUM(FactSales[Profit])

Profit Margin % =
DIVIDE([Total Profit], [Total Revenue])

AOV =
DIVIDE([Total Revenue], [Total Orders])
```

---

## 📌 Key Insights (Sample)

* Revenue is concentrated in a few high-performing categories
* Repeat customers significantly outnumber new customers
* Certain regions contribute disproportionately to total revenue
* Product performance varies significantly across categories

---

## 📂 Project Structure

```
📁 PowerBI-Sales-Dashboard
 ┣ 📊 Dashboard.pbix
 ┣ 📄 README.md
 ┗ 📁 Dataset (Generated)
```

---

## 🚧 Limitations

* Dataset is synthetically generated using ChatGPT
* Does not reflect real-world business complexity
* Some fields are simplified for demonstration

---

## 🔮 Future Improvements

* Add revenue forecasting
* Implement RFM customer segmentation
* Enable real-time data integration
* Improve mobile dashboard experience

---

## 🛠️ Tools & Technologies

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Data Modeling (Star Schema)
* Bookmarks & Tooltips
* Data Visualization Best Practices

---

## 🙌 Author

**Shivam Khante**

---

## ⭐ If you like this project

* Star ⭐ the repository
* Fork 🍴 the project
* Share feedback 💬

---
