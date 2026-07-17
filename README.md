# Customer Sales Dashboard

## Project Overview

**Customer Sales Dashboard** is an interactive Power BI report designed
to analyze sales performance, profitability, discounts, customer types,
product categories, payment methods, and regional sales activity.

The dashboard provides a high-level view of important sales KPIs and
allows users to filter the analysis by sales representative, product
category, and region.

## File Information

-   **Power BI File:** `Customer Sales Dashboard (16-07-2026).pbix`
-   **Dashboard Page:** Customer Sales Dashboard
-   **Data Table:** Sales
-   **Created with:** Microsoft Power BI
-   **Purpose:** Customer and sales performance analysis

## Dashboard Components

The report contains the following visual elements:

### KPI Cards

The dashboard includes KPI cards for:

-   Average Sales Amount
-   Maximum Sold
-   Total Discount
-   Total Profit
-   Minimum Sold

These cards provide a quick summary of the overall sales performance.

### Charts

1.  **Regional Sales Comparison**
    -   Clustered column chart
    -   Compares the sum of Unit Cost and Unit Price by Region.
2.  **Discount by Payment Method**
    -   Pie chart
    -   Shows the distribution of total discount by Payment Method.
3.  **Discount by Product Category**
    -   Donut chart
    -   Compares total discount across Product Categories.
4.  **Monthly Profit Trend by Customer Type**
    -   Line chart
    -   Displays Total Profit by month and compares performance across
        Customer Types.
5.  **Profit by Product Category**
    -   Table
    -   Summarizes Total Profit for each Product Category.

## Interactive Filters

The following slicers are available:

-   Sales Rep
-   Product Category
-   Region

These filters allow users to interactively analyze the dashboard from
different business perspectives.

## Key Measures Used

The report uses measures including:

-   **Average the Sales Amount**
-   **Maximum Sold**
-   **Minimum Sold**
-   **Total Profit**

The dashboard also uses aggregated sales fields such as:

-   Sum of Unit Cost
-   Sum of Unit Price
-   Sum of Discount

## Business Questions Answered

This dashboard helps answer questions such as:

-   Which regions have higher unit cost and unit price values?
-   Which payment methods are associated with greater discounts?
-   Which product categories receive the highest discounts?
-   How does profit change over time?
-   Which customer types generate stronger monthly profit?
-   Which product categories generate the greatest total profit?
-   What are the minimum, maximum, average, and total profit performance
    indicators?

## How to Use the Dashboard

1.  Open the `.pbix` file in Microsoft Power BI Desktop.
2.  Use the **Sales Rep** slicer to analyze individual sales
    representatives.
3.  Use the **Product Category** slicer to focus on specific product
    categories.
4.  Use the **Region** slicer to compare regional performance.
5.  Review the KPI cards for an overall summary.
6.  Analyze the charts and table to identify trends, differences, and
    high-performing categories.

## Recommended Analysis Workflow

For an effective analysis:

1.  Start with the KPI cards to understand the overall performance.
2.  Review the regional sales comparison.
3.  Analyze discounts by payment method and product category.
4.  Review the monthly profit trend by customer type.
5.  Use the slicers to drill down into specific sales representatives,
    categories, or regions.
6.  Compare product categories using the Total Profit table.

## Project Structure

``` text
Customer Sales Dashboard/
│
├── Customer Sales Dashboard (16-07-2026).pbix
├── Customer Sales Dashboard -- Articles.docx
├── sales_data.csv
└── README.md
```

## Notes

This README documents the dashboard structure and analytical purpose of
the Power BI report. The report should be opened with Microsoft Power BI
Desktop for full interaction with the visuals, slicers, measures, and
data model.

## Author

**Rudrashis Chowdhury**
