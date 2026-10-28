 # Coffee Sales Analytics Dashboard ☕📊

A high-end, executive-level coffee sales and business analytics dashboard built in Power BI with custom dark-brown and coffee-themed aesthetics. 

---

## 🖼️ Dashboard Preview

<p align="center">
 ![Coffee Dashboard](Coffee%20Sales%20Dashboard%20Analytics.png)
 </p>
  
 ---

## 🚀 Project Overview & Features

* **Dark-Theme UI/UX:** Designed with a professional dark background (`#090D16`) and executive styling.
* **Top KPI Metrics (Top Row):**
  * **Total Sales**
  * **Total Orders** (`1,000`)
  * **Total Quantity Sold** (`3,551`)
  * **Average Order Value (AOV)**
* **Comprehensive Charts & Breakdowns:**
  * **Sales by Year:** Yearly performance tracking.
  * **Sales by Country:** Country-wise sales distribution (USA, UK, Canada, Australia, etc.).
  * **Sales by Customer Type:** Donut chart breakdown for VIP, Regular, New, and Returning customers.
  * **Sales by Order Status:** Delivered, Shipped, Processing, and Cancelled orders.
  * **Sales by Coffee Type:** Arabica, Robusta, Liberica, and Excelsa sales analysis.

---

## 🛠️ Built With

* **Power BI Desktop** - Dashboard design, data modeling, and visualization
* **DAX** - Custom measures and metrics calculation
* **Python (Pandas & NumPy)** - Dataset generation and processing
* **GitHub** - Version control and repository hosting

---

## 📊 DAX Measures Used

1. **Total Sales:**
   ```dax
   Total Sales = SUM('coffee_sales_data'[Sales Amount])
