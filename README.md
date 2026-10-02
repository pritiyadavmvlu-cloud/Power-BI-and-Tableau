# Mobile Phone Sales Performance Dashboard

## Project Overview

This project presents an interactive **Mobile Phone Sales Performance Dashboard** created using Tableau. The dashboard analyzes mobile phone sales data and provides useful insights into sales, profit, quantity, brands, categories, regions, mobile models and customer segments.

The dashboard helps users understand sales performance through interactive charts, KPI cards, filters and map visualizations.

## Objective

The main objective of this project is to create an interactive Tableau dashboard for analyzing mobile phone sales performance.

The dashboard helps to:

- Analyze total sales and profit
- Track sales trends over time
- Compare sales by brand and category
- Analyze sales by region and city
- Identify the top 10 mobile models
- Analyze customers based on age groups
- Compare sales by payment method
- Filter the analysis using Year, Brand, Category and Region

## Dataset

**Dataset Name:** Mobile Phone Sales Dataset

**File Format:** CSV

**Number of Records:** 1,000

### Important Fields

- Order ID
- Order Date
- Brand
- Model
- Category
- Storage
- RAM
- Customer Gender
- Customer Age
- City
- Region
- Quantity
- Unit Price
- Discount (%)
- Sales
- Cost
- Profit
- Payment Method
- Rating

## Tools Used

- Tableau Public
- CSV Dataset
- Tableau Calculated Fields
- Tableau Dashboard
- Data Visualization

## Dashboard Visualizations

The dashboard contains the following visualizations:

| Visualization | Purpose |
|---|---|
| KPI Cards | Display Total Sales, Total Profit and Total Quantity |
| Sales Trend | Shows sales trend over time |
| Sales by Category | Compares sales across mobile categories |
| Sales by Brand | Compares sales performance of different brands |
| Sales Map | Shows sales distribution by city/location |
| Top 10 Mobile Models | Displays the top mobile models based on sales |
| Customer Segmentation | Shows sales across different customer age groups |
| Sales by Payment | Compares sales by payment method |
| Interactive Filters | Allows filtering by Year, Brand, Category and Region |

## Calculated Fields

The following calculated fields were used in Tableau:

### Total Sales

```text
SUM([Sales])
