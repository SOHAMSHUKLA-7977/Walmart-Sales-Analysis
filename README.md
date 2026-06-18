# Walmart Sales Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on Walmart sales data to identify sales trends, seasonal patterns, store performance, and the impact of holidays on weekly sales. The analysis was carried out using Python and various data visualization techniques to generate meaningful business insights.

---

## Objectives

* Analyze weekly sales trends across Walmart stores.
* Identify top-performing stores based on total sales.
* Study monthly sales patterns.
* Compare holiday and non-holiday sales performance.
* Examine relationships between sales and economic indicators.
* Generate actionable business insights through data analysis.

---

## Dataset Information

The dataset contains **6,435 records** and **8 features**.

### Features

| Column       | Description            |
| ------------ | ---------------------- |
| Store        | Store Number           |
| Date         | Week Date              |
| Weekly_Sales | Weekly Revenue         |
| Holiday_Flag | Holiday Week Indicator |
| Temperature  | Average Temperature    |
| Fuel_Price   | Fuel Cost              |
| CPI          | Consumer Price Index   |
| Unemployment | Unemployment Rate      |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## Data Preprocessing

The following preprocessing steps were performed:

* Checked for missing values.
* Checked for duplicate records.
* Converted Date column to datetime format.
* Created Month and Year features from the Date column.
* Prepared data for visualization and analysis.

---

## Exploratory Data Analysis

The following analyses were performed:

### 1. Weekly Sales Trend

Analyzed sales fluctuations over time to identify trends and seasonality.

### 2. Average Monthly Sales

Compared monthly average sales to identify peak-performing months.

### 3. Store-wise Sales Analysis

Evaluated sales performance across all Walmart stores.

### 4. Holiday vs Non-Holiday Sales

Compared average sales during holiday and non-holiday weeks.

### 5. Correlation Heatmap

Studied relationships between sales and economic factors.

### 6. Top 10 Stores by Sales

Identified the highest revenue-generating stores.

---

## Key Findings

### Top Performing Stores

| Store | Total Sales (Million) |
| ----- | --------------------- |
| 20    | 301.40                |
| 4     | 299.54                |
| 14    | 289.00                |
| 13    | 286.52                |
| 2     | 275.38                |

### Monthly Sales Insights

* December recorded the highest average sales (~1.28 Million).
* November recorded the second-highest average sales.
* January showed comparatively lower sales.

### Holiday Impact

* Non-Holiday Weeks: ~1.04 Million average sales.
* Holiday Weeks: ~1.12 Million average sales.

Holiday periods positively influenced Walmart sales performance.

---

## Project Structure

```text
Walmart-Sales-Analysis/
│
├── Walmart.csv
├── Walmart_Sales_Analysis.ipynb
├── Walmart_Sales_Report.pdf
├── README.md
└── Images/
```

---

## Conclusion

The analysis revealed important sales trends, seasonal demand patterns, and store-level performance insights. Holiday periods significantly increased sales, while December emerged as the strongest sales month. The findings can help improve inventory planning, marketing strategies, and business decision-making.

---

## Future Scope

* Sales Forecasting using Machine Learning.
* Demand Prediction Models.
* Interactive Dashboards using Power BI or Tableau.
* Store Performance Prediction.
* Advanced Retail Analytics.

---

## Author

**Soham Shukla**

Data Analytics Project using Python and Google Colab.
