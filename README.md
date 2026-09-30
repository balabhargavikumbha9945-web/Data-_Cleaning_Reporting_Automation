# Data Cleaning & Reporting Automation

## Project Overview

This project focuses on automating data cleaning and reporting workflows using Python. The project uses a sales dataset containing information about orders, customers, cities, products, quantities, prices, and sales.

The raw sales data is processed to identify and handle data-quality issues such as missing values, duplicate records, and inconsistent product names. After cleaning, automated reports and visualizations are generated to summarize the sales data.

## Objective

The main objective of this project is to demonstrate a complete data cleaning and reporting workflow that:

* Handles missing values
* Removes duplicate records
* Standardizes inconsistent data
* Calculates sales values
* Generates automated reports
* Creates data visualizations
* Exports cleaned data and reports for further analysis

## Tools Used

* **Python**
* **Pandas**
* **Matplotlib**
* **Google Colab**
* **GitHub**
* **CSV**

## Dataset

The sales dataset contains the following columns:

| Column   | Description                        |
| -------- | ---------------------------------- |
| Order_ID | Unique order identification number |
| Date     | Date of the order                  |
| Customer | Customer name                      |
| City     | Customer city                      |
| Product  | Product purchased                  |
| Quantity | Quantity of products purchased     |
| Price    | Price per product                  |
| Sales    | Total sales amount                 |

The original dataset contains intentional data-quality issues such as missing values, duplicate records, and inconsistent product names. These issues are used to demonstrate the data-cleaning process.

## Data Cleaning Process

The following steps were performed using Python and Pandas:

1. Created and loaded the original sales dataset.
2. Inspected the dataset structure and columns.
3. Checked for missing values.
4. Identified duplicate records.
5. Removed duplicate records.
6. Handled missing quantity values.
7. Calculated sales values using:

```text
Sales = Quantity × Price
```

8. Standardized inconsistent product names.
9. Handled missing date values.
10. Saved the cleaned dataset as a separate CSV file.

## Automated Reporting

After cleaning the dataset, the following reports were generated:

* Sales summary report
* Product-wise sales report
* City-wise sales report
* Total number of orders
* Total quantity sold
* Total sales

## Data Visualization

Matplotlib was used to create visual summaries of the cleaned data.

The project includes:

* Product-wise Sales Chart
* City-wise Sales Chart

These visualizations make it easier to understand sales performance across different products and cities.

## Project Workflow

```text
Original Sales Dataset
        ↓
Data Inspection
        ↓
Missing Value Detection
        ↓
Duplicate Detection
        ↓
Data Cleaning
        ↓
Data Standardization
        ↓
Sales Calculation
        ↓
Cleaned Dataset
        ↓
Automated Reports
        ↓
Data Visualizations
```

## Repository Structure

```text
Data-Cleaning-Reporting-Automation/
│
├── README.md
│
├── Data_Cleaning_Reporting_Automation.ipynb
│
├── sales_data.csv
│
├── cleaned_sales_data.csv
│
├── sales_summary_report.csv
│
├── product_sales_report.csv
│
├── city_sales_report.csv
│
├── product_wise_sales.png
│
└── city_wise_sales.png
```

## Expected Outcome

The project demonstrates how Python can be used to automate data preprocessing, cleaning, reporting, and visualization.

The workflow improves data quality by handling missing values, duplicate records, and inconsistent data. It also reduces manual effort by automatically generating reports and visual summaries from the cleaned dataset.

## Conclusion

This project provides a complete example of Data Cleaning & Reporting Automation using Python. Starting with the original sales dataset, the project performs data preprocessing and cleaning and produces a cleaned dataset, automated reports, and visualizations.

The project demonstrates practical skills in:

* Data Cleaning
* Data Preprocessing
* Data Analysis
* Automation
* Report Generation
* Data Visualization
