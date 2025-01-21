# Online Retail Data Analysis

## Project Overview
This project involves analyzing the Online Retail Dataset, which contains transactional data from an online retail store spanning 2010–2011. The goal is to explore the dataset, clean missing data, and generate insights about sales, customers, and products.

## Dataset Description
The dataset, Online Retail.xlsx, includes the following columns:
- **InvoiceNo**: Invoice number of the transaction.
- **StockCode**: Unique product code.
- **Description**: Description of the product.
- **Quantity**: Quantity of the product in the transaction.
- **InvoiceDate**: Date and time of the transaction.
- **UnitPrice**: Price per unit of the product.
- **CustomerID**: Unique identifier for each customer.
- **Country**: Country where the transaction occurred.

Download the dataset from here if working locally.

## Project Features

### Data Cleaning:
- Handling missing values for Description and CustomerID.
- Exploring patterns in missing data.

### Exploratory Data Analysis (EDA):
- Identify top-selling products.
- Analyze sales by country.
- Understand customer behavior.

### Visualization:
- Bar charts for top-performing products and countries.
- Distribution of transactions with missing CustomerID.

### Flexible Analysis:
- Support for analyzing data with and without missing CustomerID.

## Requirements
Make sure you have the following Python libraries installed:
- pandas
- numpy
- matplotlib
- openpyxl (for reading .xlsx files)

You can install these dependencies with:
!pip install pandas numpy matplotlib openpyxl
