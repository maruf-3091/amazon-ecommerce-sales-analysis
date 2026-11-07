# 📊 Amazon E-Commerce Sales Data Analysis & Interactive Dashboard

An end-to-end data analysis project exploring Amazon e-commerce sales performance, featuring rigorous data cleaning, feature engineering, exploratory data analysis (EDA), and an interactive web dashboard.

---

## 🚀 Project Overview
This project dives deep into an Amazon sales dataset to uncover actionable business insights. It covers everything from raw data preprocessing and missing value imputation to advanced feature engineering, statistical grouping, and multi-dimensional pivot tables, culminating in a modern, responsive web dashboard built with Tailwind CSS and Chart.js.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib
* **Dashboard Interface:** HTML5, Tailwind CSS, JavaScript, Chart.js
* **Development Environments:** Google Colab, Visual Studio Code

---

## 📝 Project Workflow & Steps

### 1. Data Cleaning & Preprocessing
* Handled missing values by imputing defaults or dropping columns with excessive null values (e.g., `Unnamed: 22`, `index`, `fulfilled-by`).
* Standardized column names and fixed data types (converting order dates to proper datetime objects).

### 2. Feature Engineering
Created rich analytical features to enhance business intelligence:
* **Time-based Features:** `Month_Name`, `Month_Num`, `Day_Name`, `Year`, and `Quarter`.
* **Financial Metric:** `Total_Revenue` (calculated from Quantity and Amount).
* **Categorical Segmentation:** `Price_Tier` (Budget, Mid-Range, Premium) and `Delivery_Status_Group` (Successfully Delivered, Cancelled, Returned).

### 3. Exploratory Data Analysis (EDA)
* **Groupby Analysis:** Evaluated top-performing product categories, monthly revenue trends, and regional order distributions across shipping states (`ship-state`).
* **Pivot Tables:** Analyzed multi-dimensional relationships such as Category vs. Price Tier, Fulfillment Channels vs. Delivery Outcomes, and B2B vs. B2C customer order patterns.

### 4. Interactive Dashboard
* Designed a responsive, glassmorphic dashboard (`amazon_sales_analytics_dashboard.html`) featuring real-time KPI metrics, dynamic filters, trend lines, donut charts, and a matrix data table.

---

## 📈 Key Insights
* **Top Revenue Categories:** `Set` and `Kurta` dominate total sales revenue and order quantities.
* **Geographic Concentration:** High order volumes originate from metropolitan and major shipping states like Maharashtra, Karnataka, and Tamil Nadu.
* **Delivery Performance:** The majority of orders achieve successful delivery, with minimal cancellation rates.

---

## 📁 Repository Structure
```text
├── clean_amazon_sales_data.csv          # Cleaned and processed dataset
├── amazon_sales_analytics_dashboard.html # Interactive HTML dashboard
├── amazon_sales_analysis.ipynb          # Jupyter Notebook containing full EDA & code
└── README.md                            # Project documentation
