# 🛒 Walmart Sales Analysis & Forecasting

This project focuses on analyzing and forecasting Walmart's weekly sales across multiple stores using Python. Leveraging real-world data, I explored sales trends, identified performance patterns, and applied predictive modeling to forecast future sales.

## 📌 Project Objectives

✅ Analyze weekly sales data across multiple stores  
✅ Explore correlations with factors like **unemployment**, **temperature**, and **Consumer Price Index (CPI)**  
✅ Identify **top-performing and lowest-performing stores** based on historical data  
✅ Detect **seasonal sales trends** (Black Friday, Christmas, etc.)  
✅ Forecast **next 12 weeks' sales for each store** using **Prophet time series forecasting**

---

## 🏗️ Project Workflow

1. **Data Cleaning & Preparation**
   - Loaded dataset with columns: `Store`, `Date`, `Weekly_Sales`, `Unemployment`, `Temperature`, `CPI`, `IsHoliday`
   - Converted date formats
   - Checked for missing values

2. **Exploratory Data Analysis (EDA)**
   - Correlation analysis between Weekly_Sales and:
     - Unemployment
     - Temperature
     - CPI
   - Plotted sales trends over time
   - Identified seasonal peaks (Black Friday, Christmas)

3. **Store Performance Analysis**
   - Ranked stores by total historical sales
   - Identified top 5 and bottom 5 performing stores
   - Compared difference between best and worst store

4. **Predictive Modeling**
   - Built time series forecast for **each store** using **Facebook Prophet**
   - Predicted sales for next 12 weeks
   - Visualized forecast per store

---

## 📊 Key Insights

- 📈 Sales peak consistently in late November to December (Black Friday, Thanksgiving, Christmas)
- 🧊 Temperature & CPI show **weak correlation** with weekly sales
- 🏆 Significant difference between top-performing and lowest-performing stores
- 🤖 Forecasts help visualize expected sales trends per store for planning

---

## 🖥️ Tools & Technologies

- **Python 3.x**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Prophet (Facebook)**
- **Jupyter Notebook**

---

## 📁 Repository Structure
