# Retail Business Analytics Dashboard

An interactive Power BI dashboard created as a class project to explore retail sales, profitability, customer behaviour, product performance, and geographic trends.

## Project Overview

This report is organised into three pages—**Sales**, **Profit**, and **Demographics**—with date and country slicers to support interactive exploration.

### Dashboard Pages

#### 1\. Sales

* Total sales and previous-year sales KPIs
* Year-over-year sales growth and average sales per order
* Sales by product category and customer segment
* Top-selling products
* Sales distribution across countries
* Monthly sales comparison with the previous year

#### 2\. Profit

* Total profit and previous-year profit KPIs
* Year-over-year profit growth and average profit per order
* Profit by category and customer segment
* Top profitable products and countries
* Monthly profit comparison with the previous year

#### 3\. Demographics

* Total customer, order, and product KPIs
* Average sales per state
* Top active buyers and valuable customers
* Profitable states
* Profit by order priority
* Sales and profit by region

## Selected Dashboard Figures

The figures below are the values displayed in the supplied report screenshots with the Date and Country slicers set to **All**:

|Metric|Displayed value|
|-|-:|
|Total Sales|$12.64M|
|Total Profit|$1.47M|
|Previous-Year Sales|$8.34M|
|Previous-Year Profit|$963.29K|
|Year-over-Year Sales Growth|51.54%|
|Year-over-Year Profit Growth|52.34%|
|Average Sales per Order|$504.99|
|Average Profit per Order|$58.62|
|Total Customers|1,590|
|Total Orders|25K|
|Total Products|3,797|
|Average Sales per State|$11.56K|

These are screenshot values and may change when slicers or report filters are applied.

## Data and Model

The repository includes the Excel workbook used for the project. The workbook contains these sheets:

* `product\_data`
* `location\_data`
* `customer\_data`
* `sales\_data`

The Power BI model screenshot shows the sales table connected to product, location, customer, and date tables, alongside supporting calculation and parameter tables. Refer to the model screenshot for the relationships represented in the report.

## Tools and Features

* **Microsoft Power BI Desktop** — report design, data modelling, interactive visuals, slicers, and measures
* **Microsoft Excel** — source workbook
* **DAX** — KPI and comparison calculations, including year-over-year metrics and averages
* **Power Query** — data preparation where applied in the project

## Repository Structure

```text
retail-business-analytics/
├── dashboard/
│   └── Retail Business Analytics Report.pbix
├── data/
│   └── global\_retail\_sales\_data.xlsx
├── screenshots/
│   ├── Sales.png
│   ├── Profit.png
│   ├── Demographics.png
│   └── Data Modeling.png
└── README.md
``` 

## How to View the Project

1. Open the screenshots in `screenshots/` to preview the report pages and data model.
2. Download the `Retail Business Analytics Report.pbix` file from `dashboard/`.
3. Open it using Microsoft Power BI Desktop.
4. If Power BI prompts for a data source, point it to the Excel workbook in `data/` and confirm the relevant queries load.
5. Use the Date and Country slicers to explore the report.

## Notes and Limitations

* This is a class project and is presented for learning and portfolio purposes.
* The values in the KPI section reflect the supplied screenshots with all slicers selected; they are not guaranteed to remain the same under other filters.

## Screenshots

The `screenshots/` folder contains the Sales, Profit, and Demographics report pages, along with the Power BI data model.

