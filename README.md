# 📊 Adventure Works Sales Analytics Dashboard (Tableau)

An **end-to-end Business Intelligence project** built using the **Adventure Works dataset** to analyze sales performance, customer behavior, regional revenue, and product category profitability using **Tableau dashboards and dimensional data modeling**.

This project demonstrates a **complete data analytics workflow**:

Raw Data → Data Modeling → Data Relationships → Tableau Dashboards → Business Insights

---

# 🚀 Project Objective

The goal of this project is to build an **interactive sales analytics dashboard** that helps businesses understand:

• Sales performance across time
• Product category profitability
• Customer purchasing behavior
• Regional sales trends
• Revenue drivers


# 🗂 Dataset Overview

The project uses the **Adventure Works Sales Dataset** organized in a **Star Schema** structure.

## Fact Table

### Fact_sales

Contains transactional sales records.

Key columns include:

* ProductKey
* CustomerKey
* SalesTerritoryKey
* OrderDateKey
* ShipDateKey
* DueDateKey
* OrderQuantity
* UnitPrice
* ExtendedAmount
* DiscountAmount
* TaxAmt
* Freight
* ProductStandardCost

This table stores **sales transactions and revenue metrics**.

---

## Dimension Tables

### DimProduct

Contains product level information.

Fields include:

* ProductKey
* Product Name
* Product Subcategory

---

### DimProductSubCategory

Defines product subcategories.

Fields include:

* ProductSubcategoryKey
* ProductSubcategoryName
* ProductCategoryKey

---

### DimProductCategory

Defines high level product categories.

Examples:

* Bikes
* Components
* Accessories
* Clothing

---

### DimCustomer

Customer demographic information.

Fields include:

* CustomerKey
* First Name
* Last Name
* Customer Location
* Customer Segments

---

### DimSalesTerritory

Contains geographic sales information.

Fields include:

* SalesTerritoryKey
* Country
* Region
* Territory

---

### DimDate

Calendar table used for time intelligence.

Fields include:

* Date
* Year
* Quarter
* Month
* Day


# 🧠 Data Modeling

The dataset follows a **Star Schema Architecture**.

Fact Table

Fact_sales

Connected Dimension Tables

* DimProduct
* DimProductSubCategory
* DimProductCategory
* DimCustomer
* DimSalesTerritory
* DimDate

Benefits of this model:

✔ Faster queries
✔ Clean relationships
✔ Scalable BI architecture

---

# 📊 Key Metrics & KPIs

The following KPIs were created in Tableau:

• Total Sales
• Total Orders
• Total Profit
• Profit Margin
• Average Order Value
• Sales by Category
• Sales by Region
• Sales by Customer
• Monthly Sales Growth

---

# 📈 Dashboards Created

## 1️⃣ Sales Overview Dashboard

Provides a high-level summary of business performance.

Includes:

• Total sales and profit KPIs
• Sales trend over time
• Sales distribution by category
• Regional sales comparison

---

## 2️⃣ Product Performance Dashboard

Analyzes product level performance.

Includes:

• Category-wise sales
• Subcategory comparison
• Top performing products
• Profit contribution by category

---

## 3️⃣ Customer Insights Dashboard

Focuses on customer purchasing behavior.

Includes:

• Top customers by revenue
• Customer purchase patterns
• Revenue contribution by customers

---

## 4️⃣ Regional Sales Dashboard

Analyzes geographical sales distribution.

Includes:

• Sales by territory
• Country-level performance
• Regional revenue comparison

---

# 📊 Visualizations Used

The dashboards include multiple visualization types:

• Line charts for time trends
• KPI cards for performance metrics
• Tables for detailed breakdowns

---

# 📸 Dashboard Preview

https://github.com/user-attachments/assets/5a19e27f-1247-4386-94c7-514e7036a7c4


Some insights derived from the analysis:

• Certain product categories generate **higher revenue but lower profit margins**

• A **small percentage of customers contribute a large portion of revenue**

• Some regions outperform others in both **sales and profitability**

• Sales trends show **seasonal patterns across months**

These insights help organizations make **data-driven strategic decisions**.

---

# 🛠 Tools & Technologies Used

Tableau
Excel
Data Modeling
Business Intelligence
Data Visualization
Star Schema Design



# 🎯 Skills Demonstrated

Data Modeling
Business Intelligence
Dashboard Development
Data Visualization
KPI Development
Analytical Thinking
Dimensional Modeling (Star Schema)
