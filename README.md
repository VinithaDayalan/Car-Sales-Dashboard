# Car Sales Dashboard in Power BI

## Table of Contents
1. [Project Overview](#project-overview)
2. [Problem Statements](#problem-statements)
    - [KPI Requirements](#kpi-requirements)
    - [Charts Requirements](#charts-requirements)
3. [Tools and Technologies Used](#tools-and-technologies-used)
4. [Data Cleaning and Preparation](#data-cleaning-and-preparation)
5. [Dashboard Design and Development](#dashboard-design-and-development)
6. [Results and Insights](#results-and-insights)
7. [How to Use](#how-to-use)
8. [Contributing](#contributing)
9. [License](#license)

## Project Overview
This project involves designing and developing a dynamic and interactive Car Sales Dashboard using Power BI. The dashboard visualizes critical KPIs related to car sales, providing real-time insights into sales performance, and assisting in data-driven decision-making.

## Problem Statements

### KPI Requirements
The dashboard provides real-time insights into key performance indicators (KPIs) related to sales data. This enables informed decisions, monitoring progress, and identifying trends and opportunities for growth.

#### Sales Overview
- Year-to-Date (YTD) Total Sales
- Month-to-Date (MTD) Total Sales
- Year-over-Year (YOY) Growth in Total Sales
- Difference between YTD Sales and Previous Year-to-Date (PTYD) Sales

#### Average Price Analysis
- YTD Average Price
- MTD Average Price
- YOY Growth in Average Price
- Difference between YTD Average Price and PTYD Average Price

#### Cars Sold Metrics
- YTD Cars Sold
- MTD Cars Sold
- YOY Growth in Cars Sold
- Difference between YTD Cars Sold and PTYD Cars Sold

### Charts Requirements
1. **YTD Sales Weekly Trend**: A line chart illustrating the weekly trend of YTD sales with weeks on the X-axis and total sales amount on the Y-axis.
2. **YTD Total Sales by Body Style**: A pie chart showing the distribution of YTD total sales across different car body styles.
3. **YTD Total Sales by Color**: A pie chart representing the contribution of various car colors to the YTD total sales.
4. **YTD Cars Sold by Dealer Region**: A map chart displaying the YTD sales data based on different dealer regions.
5. **Company-Wise Sales Trend in Grid Form**: A tabular grid showing the sales trend for each company with company names and their YTD sales figures.
6. **Details Grid Showing All Car Sales Information**: A detailed grid presenting all relevant information for each car sale, including car model, body style, color, sales amount, dealer region, date, etc.

## Tools and Technologies Used
- **Power BI**: For data visualization and dashboard creation.
- **Microsoft Excel**: For initial data inspection and cleaning.
- **SQL**: For data extraction and transformation (if applicable).
- **DAX (Data Analysis Expressions)**: For creating calculated columns and measures in Power BI.

## Data Cleaning and Preparation
1. **Data Collection**: Gathered sales data from the company's database and exported it into Excel files.
2. **Data Inspection**: Examined the data for inconsistencies, missing values, and outliers using Excel.
3. **Data Cleaning**: Removed duplicates, filled missing values, and corrected any inaccuracies.
4. **Data Transformation**: Aggregated sales data by necessary dimensions such as date, body style, color, and region.
5. **Data Loading**: Imported the cleaned and transformed data into Power BI.

## Dashboard Design and Development
1. **Data Modeling**: Created relationships between different data tables to ensure accurate analysis.
2. **Measure Creation**: Developed DAX measures for calculating KPIs like YTD sales, MTD sales, YOY growth, etc.
3. **Visualization**: Designed interactive charts and grids to meet the specified requirements.
4. **Interactivity**: Added slicers and filters to enable dynamic data exploration.

## Results and Insights
- **Sales Performance**: The dashboard provides a comprehensive view of sales performance over time, highlighting trends and growth opportunities.
- **Average Price Trends**: Insights into how average prices have changed year-over-year and month-to-date.
- **Regional Analysis**: Identification of top-performing regions and potential areas for improvement.
- **Product Preferences**: Understanding customer preferences for different car body styles and colors.

## Dashboard Link : "Car Sales Dashboard" https://app.powerbi.com/links/-P1emZlsjf?ctid=a888c29a-2c29-470b-b399-ff992e459cdc&pbi_source=linkShare

![Overview](https://github.com/VinithaDayalan/Car-Sales-Dashboard/assets/167068287/b4a69fdc-f7f9-44a7-8c43-3988a217dac7)

![Details](https://github.com/VinithaDayalan/Car-Sales-Dashboard/assets/167068287/35973654-0caf-4a67-b781-9f68ae58ac2f)
