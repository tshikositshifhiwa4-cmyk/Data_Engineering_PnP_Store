# 🛒 PnP Stores 12-Month Sales Analysis

This project analyzes 12 months of PnP Stores transactional data (January–December) to generate business insights and build a consolidated master dataset for reporting and analytics.

## Project Overview

The objective of this project was to:

Import and clean 12 separate monthly datasets (Jan–Dec)

Standardize column names and data types

Handle missing values and data inconsistencies

Perform exploratory data analysis (EDA)

Create a unified Master Table combining all 12 months

Generate business insights to support data-driven decision-making

🗂️ Dataset Structure

Each month’s dataset contains transactional-level data including:

Store information

Product details

Sales amounts

Quantity sold

Transaction dates

Payment methods

After cleaning and validation, all datasets were merged into a single Master Table using SQL UNION operations.

🛠️ Tools & Technologies

SQL Server (SSMS) – Data cleaning, transformation, and merging

Excel / Power BI – Data visualization and reporting

GitHub – Version control and documentation

📊 Key Analysis Performed

Monthly sales trends (Jan–Dec)

Revenue distribution by store

Top-performing products

Sales by payment method

Total annual revenue calculation

Data validation and quality checks

🧱 Master Table Creation

A final consolidated master table was created by:

Ensuring consistent data types across all 12 tables

Cleaning barcode and numeric fields

Standardizing date formats

Using SQL UNION ALL to combine all monthly tables

Creating indexes for performance optimization

This master dataset serves as the foundation for advanced reporting and future analytics projects.

🎯 Project Goal

To demonstrate practical data engineering skills including:

Data cleaning

Schema consistency

Data consolidation

SQL querying

Analytical thinking
