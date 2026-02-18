# Business Sales Performance Analytics - Superstore Dataset

## 📌 Project Overview

This project was completed as part of the **FutureIntern** Data Analytics Internship. The primary objective was to analyze a multi-year sales dataset to identify key revenue drivers, seasonal trends, and profitability gaps across various product categories and geographic regions.

## 🎯 Business Questions Addressed

* **Revenue:** Which specific products and categories generate the most income?
* **Trends:** How do sales patterns fluctuate over time, and is there evidence of seasonality?
* **Profitability:** Which regions and categories are the most and least profitable?
* **Strategy:** Where should the business focus its resources to improve the bottom line?

## 🛠️ Tools Used

* **Power BI:** Data modeling, DAX (Data Analysis Expressions), and interactive dashboard creation.
* **Power Query:** ETL processes (Data cleaning and transformation).
* **Python (Optional):** Exploratory Data Analysis (EDA) and handling encoding issues.
* **Excel:** Initial data inspection.

## 🧹 Data Cleaning & Preparation

Before analysis, the following steps were taken to ensure data integrity:

1. **Date Standardization:** Converted `Order Date` and `Ship Date` into proper datetime formats to enable time-series analysis.
2. **Data Typing:** Changed `Postal Code` to Text format to prevent unnecessary mathematical operations.
3. **Missing Values:** Audited the dataset for null values and ensured consistency in categorical naming (Categories, Regions).
4. **DAX Measures:** Created custom measures for `Total Sales`, `Total Profit`, and `Profit Margin %`.

## 📊 Key Insights & Findings

* **Technology is the Profit Leader:** While Furniture has high sales volume, the **Technology** category drives the highest profit margin ().
* **The "Profit Leak":** Analysis revealed that **Tables** and **Bookcases** are consistently loss-making sub-categories due to high discounts or shipping overheads.
* **Geographic Performance:** The **West Region** outperforms all others in profitability, while the **Central Region** requires strategic intervention to improve margins.
* **Seasonality:** A significant sales spike is observed annually in **Q4 (November-December)**, suggesting the business should optimize inventory levels ahead of this period.

## 📈 Dashboard Preview

## 🚀 Skills Gained

* **Business Intelligence:** Creating executive-level reports that answer specific stakeholder questions.
* **Conditional Formatting:** Using visual cues (Red/Green logic) to highlight business "Red Flags."
* **Storytelling with Data:** Translating complex data tables into actionable business recommendations.

## 📂 Repository Structure

* `Data/`: Contains the raw Sample - Superstore.csv file.
* `Dashboard/`: The `.pbix` Power BI file.
* `Images/`: Screenshots of the final report.
* `README.md`: Project documentation.

---
