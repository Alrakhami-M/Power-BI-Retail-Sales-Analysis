# Retail Sales & Business Analysis Dashboard

## Project Overview

This project presents an interactive **Retail & E-commerce Sales
Analysis** solution built with Microsoft Power BI. It explores sales
performance across products, stores, regions, and sales channels,
helping users understand business results and identify areas that may
require attention.

The report is organized into three pages:

-   **Executive Dashboard** --- a high-level view of sales, profit, key
    performance indicators, and monthly and channel-level performance.
-   **Product Analysis** --- product-level performance, top products,
    profitability, returns, and target comparisons.
-   **Stories & Channels** --- store, city/region, and sales-channel
    analysis.

## Project Objectives

-   Monitor overall sales and profitability.
-   Compare performance across products, stores, regions, and channels.
-   Identify top-performing products and business areas.
-   Review returns and their relationship to sales performance.
-   Present key metrics in an interactive report to support
    data-informed decisions.

## Dataset

The project uses a set of CSV files representing the main business
entities and transactions:

  Dataset          Records
  -------------- ---------
  Sales             50,010
  SalesDetails     149,962
  Customers          5,000
  Products             500
  Returns            5,000
  Employees            200
  Stores                30
  Calendar           2,192

The files cover sales transactions, transaction details, customers,
products, returns, employees, stores, and calendar dates. Record counts
are based on the supplied project files.

## Tools & Technologies

-   **Microsoft Power BI Desktop** --- report development and data
    visualization.
-   **Power Query** --- data import, preparation, and transformation.
-   **DAX** --- measures and business calculations.
-   **CSV** --- source data format.

## Analysis Workflow

1.  Import the source CSV files into Power BI.
2.  Explore and prepare the data for analysis.
3.  Build relationships between the relevant data tables.
4.  Create measures and calculations for business performance analysis.
5.  Design report pages with charts, KPI cards, and interactive filters.
6.  Review performance across time, products, stores, regions, and
    channels.

## Key Analysis Areas

-   Sales and profit performance.
-   Monthly sales trends.
-   Product performance and top-selling products.
-   Profitability and profit margin.
-   Sales by store, city/region, and channel.
-   Returns analysis and target comparisons.

## Repository Structure

``` text
Power-BI-Retail-Sales-Analysis/
├── Dashboard/
│   └── Retail-Sales-Analysis.pbix
├── Dataset/
│   ├── Sales.csv
│   ├── SalesDetails.csv
│   ├── Customers.csv
│   ├── Products.csv
│   ├── Returns.csv
│   ├── Employees.csv
│   ├── Stores.csv
│   └── Calendar.csv
├── Screenshots/
│   ├── Executive-Dashboard.jpg
│   ├── Product-Analysis.jpg
│   └── Stories-and-Channels.jpg
└── README.md
```

*The folder and file names above are a suggested repository structure.
Adjust them to match the names you upload.*

## How to Use

1.  Download or clone this repository.
2.  Open the `.pbix` file using Microsoft Power BI Desktop.
3.  If Power BI requests the source files, update the data source paths
    to the location of the `Dataset` folder.
4.  Refresh the data to load the report.

## Notes

-   The source data is included for learning and portfolio demonstration
    only, subject to the original dataset's usage and redistribution
    terms.
-   Validate the date coverage and data quality when refreshing or
    extending the analysis.
-   Dashboard screenshots can be added to the `Screenshots` folder and
    embedded here for a quick preview.

## Author

**\[Moahmmed Al-Rakhmai]**

Data Analytics \| Power BI

------------------------------------------------------------------------

*This project is part of a data analytics portfolio and demonstrates a
practical business reporting workflow using Power BI.*
