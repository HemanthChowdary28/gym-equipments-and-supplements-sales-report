

Overview

This repository contains a dataset and related artifacts for analyzing sales data from a fitness retail business. The dataset, provided in Excel format (HEMANTH 2 (4).xlsx), includes detailed transaction records for fitness products sold across various cities and states in India. The data encompasses transaction IDs, dates, customer names, product types, quantities sold, unit prices, total sale amounts, payment modes, discounts, final prices, and seller names.

Dataset Description

The dataset includes the following columns:





Transaction ID: Unique identifier for each transaction.



Date: Date of the transaction (in Excel serial date format).



Customer Name: Name of the customer.



City: City where the sale occurred.



State: State where the sale occurred.



Product Type: Category of the product (e.g., Supplement, Equipment).



Product Name: Specific product sold (e.g., Creatine, Treadmill).



Quantity Sold: Number of units sold.



Unit Price (INR): Price per unit in Indian Rupees.



Total Sale Amount (INR): Total revenue from the transaction before discounts.



Payment Mode: Method of payment (e.g., Credit Card, UPI, Cash).



Discount (%): Percentage discount applied.



Final Price (INR): Final amount paid after discount.



Seller Name: Name of the seller.

Summary Statistics





Total Sales: ₹325,541,782 across all transactions.



Total Quantity Sold: 50,008 units.



Product Types: Includes Supplements (e.g., Whey Protein, Creatine) and Equipment (e.g., Treadmills, Dumbbells).



States Covered: Delhi, Gujarat, Karnataka, Maharashtra, Tamil Nadu, Telangana, West Bengal.



Average Unit Prices:





BCAA: ₹2,794.14



Bench Press: ₹10,273.98



Creatine: ₹2,750.04



Dumbbells: ₹9,988.48



Exercise Bike: ₹10,354.02



Fat Burner: ₹2,720.68



Fish Oil: ₹2,770.44



Kettlebell: ₹10,118.23



Multivitamins: ₹2,787.91



Pre-Workout: ₹2,722.89



Resistance Bands: ₹10,361.15



Rowing Machine: ₹10,151.20



Treadmill: ₹10,231.68



Whey Protein: ₹2,750.60

Sales by State





Maharashtra: ₹84,639,010



Gujarat: ₹41,495,688



Tamil Nadu: ₹40,902,040



West Bengal: ₹40,732,624



Karnataka: ₹39,768,394



Telangana: ₹39,238,154



Delhi: ₹38,765,872

Repository Contents





HEMANTH 2 (4).xlsx: The primary dataset containing sales transaction data.



README.md: This file, providing an overview and instructions for using the dataset.

Usage

This dataset can be used for various analytical purposes, such as:





Sales Performance Analysis: Evaluate top-selling products, regions, and sellers.



Customer Behavior: Analyze purchasing patterns based on product types and payment modes.



Pricing and Discounts: Study the impact of discounts on final prices and sales volumes.



Geographic Insights: Compare sales performance across different states and cities.

Prerequisites

To work with the dataset, you will need:





A spreadsheet application (e.g., Microsoft Excel, Google Sheets) or a data analysis tool (e.g., Python with pandas, R).



Basic knowledge of data cleaning and analysis for handling Excel serial dates and potential data inconsistencies.

Getting Started





Clone the Repository:

git clone https://github.com/your-username/fitness-retail-sales.git



Open the Dataset:





Use Excel or Google Sheets to view HEMANTH 2 (4).xlsx.



Alternatively, use Python with pandas:

import pandas as pd
df = pd.read_excel('HEMANTH 2 (4).xlsx')
print(df.head())



Data Cleaning:





Convert Excel serial dates to standard date formats (e.g., using pd.to_datetime in Python).



Check for missing or inconsistent values (e.g., incorrect state names or negative quantities).



Analysis:





Aggregate sales by product, state, or seller.



Visualize trends using libraries like matplotlib, seaborn, or Recharts (for web-based visualizations).

Example Analysis Ideas





Top Products by Revenue: Identify which products (e.g., Bench Press, Whey Protein) contribute most to total sales.



Regional Sales Trends: Compare sales performance across states, focusing on high-performing regions like Maharashtra.



Discount Impact: Analyze how discounts affect final prices and whether higher discounts correlate with increased sales volumes.



Seller Performance: Rank sellers by total sales or average discount offered.
