# Worldwide-Importers-Power-BI-Report
This repository contains a Power BI report designed to analyze and visualize key business metrics for the Worldwide Importers dataset. The report offers insights into sales performance, profitability, and detailed geographic breakdowns, supporting data-driven decision-making.
## Table of Contents
1. [Introduction](#introduction)
2. [Report Pages](#report-pages)
   - [Page 1: Sales Summary](#page-1-sales-summary)
   - [Page 2: Profits Analysis](#page-2-profits-analysis)
   - [Page 3: State/City Details](#page-3-statecity-details)
3. [How to Use](#how-to-use)
4. [Technical Details](#technical-details)

## Introduction

The **Worldwide Importers Power BI Report** is designed to help business analysts and decision-makers analyze sales and profitability trends across regions and products. The report includes multiple filters, interactive charts, and drill-through capabilities for detailed insights at the state and city level.

---

## Report Pages

### Page 1: Sales Summary

The **Sales Summary** page offers an overview of total sales, profit, and quantities sold. Users can filter the data by employee, customer, city, and buying group to get tailored insights. 

Key metrics displayed:
- **Total Sales Without Tax**
- **Profit**
- **Chiller Quantity** & **Dry Quantity**
- **Sales by Year** (line chart)
- **Sales by State** (table)

Note: When using filters, the sales performance in the Sales by State chart will always show as poor or good based on hardcoded state numbers. This is a pre-set logic that categorizes states' performance according to fixed benchmarks, which may affect how the filtered results are displayed.

![image](https://github.com/user-attachments/assets/768738f4-89f6-472f-8aec-8d6decc62c2f)


---

### Page 2: Profits Analysis

The **Profits Analysis** page focuses on profit breakdowns by state and item, allowing users to analyze which regions and products are most profitable. It includes filters similar to the sales summary and provides insights into profit margins over time.

Key metrics displayed:
- **Profits by Year** 
- **Total Profit by State**
- **Top Profit Generating Products**

![image](https://github.com/user-attachments/assets/c6647be8-0637-4a21-a187-c28c9b19d968)


---


### Page 3: Sales by State

The **Sales by State** page provides a detailed breakdown of sales, profit, and quantities for each state across multiple fiscal years. It offers insight into how sales have evolved by state and can be filtered by employee, customer, city, and buying group.

Key features:
- **Sales by Fiscal Year**: Displays profit, total sales excluding tax, and quantity sold for each state from 2013 to 2015.
- **Detailed Breakdown**: Shows individual state profits and sales, with drill-down capabilities to view cities and regions within each state.
- **Filters**: Customizable view based on Employee, Customer, City, and Buying Group.


![image](https://github.com/user-attachments/assets/461423b4-b7a6-42b6-9bb8-2abf59d74b83)

---

## How to Use

1. **Filters**: You can filter the report by Employee, Customer, City, and Buying Group to refine the results.
2. **Interactive Visuals**: Click on charts and visuals to drill down into specific data points.
3. **Drill Through**: The report allows drill-through functionality from state-level data to city-level data for detailed regional analysis.

---

## Technical Details

- **Power BI Version**: 2.137.952.0 64-bit (October 2024)
- **Data Source**: Worldwide Importers Dataset (Microsoft Demo Data)
- **Visualization Tools**: Power BI Desktop
- **File Format**: .pbix

---
