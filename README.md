# Sales Performance Analysis- Excel

### Project Overview

This project demonstrates an end-to-end sales analysis workflow in Microsoft Excel, covering data cleaning, data preparation, exploratory data analysis (EDA), and dashboard development.

The objective was to transform a raw sales dataset into a clean, structured dataset and generate actionable business insights using Excel functions, Pivot Tables, Pivot Charts, and interactive slicers.
### Project Objectives
### Project 1 – Data Cleaning & Preparation
**Goal**

Prepare the raw dataset for analysis by improving data quality and ensuring consistency.

**Tasks Performed**
1. Missing Values
- Inspected all columns for missing values.
- Identified blank records using Excel filters.
- Replaced missing categorical values where appropriate.
- Confirmed no critical missing values remained before analysis.
2. Duplicate Records
- Used Remove Duplicates on OrderID.
- Verified that every OrderID was unique.
- Removed duplicate entries where necessary.
3. Data Type Validation
Validated all fields to ensure correct formatting.

| Column        | Data Type |
| ------------- | --------- |
| OrderID       | Text      |
| Date          | Date      |
| CustomerID    | Text      |
| Product       | Text      |
| Quantity      | Number    |
| UnitPrice     | Currency  |
| TotalPrice    | Currency  |
| OrderStatus   | Text      |
| CouponCode    | Text      |
| PaymentMethod | Text      |


4. Data Consistency was checked in other to ensure consistent text values.

5. Helper Columns Created

Additional columns were created to simplify analysis.
 
| Helper Column | Purpose                             |
| ------------- | ----------------------------------- |
| Month         | Monthly trend analysis              |
| Year          | Year filtering                      |
| Coupon User   | Compare coupon vs non-coupon orders |




