# 📊 Amazon Product Sales & Offers Analysis -- Power BI Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![DAX](https://img.shields.io/badge/Language-DAX-blue) ![Power
Query](https://img.shields.io/badge/ETL-Power%20Query-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

------------------------------------------------------------------------

## 📌 Project Overview

This Power BI project analyzes Amazon product data to uncover insights
about sales performance, pricing strategies, offers distribution, and
sustainability indicators.

The project demonstrates strong capabilities in: - Data Cleaning &
Transformation - DAX Calculations - KPI Design - Interactive Dashboard
Development - Business Insight Extraction

------------------------------------------------------------------------

## 🎯 Business Questions Answered

-   What is the total sales volume?
-   What is the average product price?
-   Which products generate the highest sales?
-   How many offers exist across products?
-   What is the difference between original and offer prices?
-   What percentage of products are climate-friendly?
-   How do Best Sellers compare with Amazon Choice products?

------------------------------------------------------------------------

## 🧹 Data Cleaning Process (Power Query)

-   Removed columns with high missing value percentages.
-   Cleaned `sales_volume` column:
    -   Replaced special characters.
    -   Converted "K" to numeric format.
    -   Used `IF(ISNUMBER())` logic in DAX to handle remaining text
        values.
-   Created Conditional Column to replace missing `original_price` with
    `product_price`.
-   Ensured numeric fields were properly formatted for aggregation.
-   Validated data types before modeling.

------------------------------------------------------------------------

## 📐 DAX Measures Created

-   Total Sales Volume
-   Sales per Product
-   Average Product Price
-   Average Rating
-   Number of Offers (SUM)
-   Climate-Friendly Percentage
-   Average Price Difference (Original vs Offer)
-   Discount Percentage

------------------------------------------------------------------------

## 📊 Dashboard Features

### KPI Cards

-   Total Sales Volume
-   Average Price
-   Average Rating
-   Number of Offers
-   Climate-Friendly %
-   Average Price Difference

### Visualizations

-   Sales per Product (Bar Chart)
-   Average Price per Product
-   Number of Offers per Product
-   Climate-Friendly Distribution (Donut Chart)
-   Best Sellers vs Amazon Choice Comparison

------------------------------------------------------------------------

## 💡 Key Insights

-   Data cleaning significantly impacted the accuracy of calculations.
-   Products with higher offer counts do not always correlate with
    higher sales.
-   Climate-friendly products represent a measurable portion of the
    catalog.
-   Price difference analysis highlights real discount value across
    products.

------------------------------------------------------------------------

## 🛠 Tools & Technologies

-   Power BI
-   Power Query
-   DAX
-   Data Modeling
-   KPI Design

------------------------------------------------------------------------

## 📂 Project Structure

    amazon-powerbi-dashboard/
    │
    ├── Amazon_Product_Sales.pbix
    ├── dashboard_preview.png
    └── README.md

------------------------------------------------------------------------

## 📷 Dashboard Preview

(Add your dashboard screenshot here)

------------------------------------------------------------------------

## 🚀 Author

Mohamed Heta\
Data Analyst \| Power BI Developer
