# Sales Performance Analysis- Excel

### Project Overview

This project demonstrates an end-to-end sales analysis workflow in Microsoft Excel, covering data cleaning, data preparation, exploratory data analysis (EDA), and dashboard development.

The objective was to transform a raw sales dataset into a clean, structured dataset and generate actionable business insights using Excel functions, Pivot Tables, Pivot Charts, and interactive slicers.
### Project Objectives
## Project 1 – Data Cleaning & Preparation
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

## Project 2 – Exploratory Data Analysis (EDA)
**Goal**

Exploring the dataset to identify Outliers, trends, customer behaviour, product performance and operational patterns.

<img width="756" height="358" alt="image" src="https://github.com/user-attachments/assets/7bc1b9c3-af1f-461b-a0fc-e3f01bc72a6d" />

**Descriptive Statistics**

The following statistics were calculated:

Total Sales Value : 1264761.96
Total Orders: 1200
Average Order Value: 1053.9683
Total Customers: 1189
Total Quantity Sold:3535

<img width="163" height="158" alt="image" src="https://github.com/user-attachments/assets/1d1e3520-f963-4d94-88c9-038105657c4b" />


### Business Questions Answered
The analysis answered the following questions:

1. What is the total sales value?
2. What is the average order value?
3. Which month generated the highest sales value?
4. Which products generated the highest sales value?
5. Which product has the highest return rate?
6. Who are the top 10 customers by sales value?
7. Which customers contribute the highest sales?
8. Which referral source generated the highest sales value?
9. Do coupon users spend more than non-coupon users?
10. What is the return rate?
11. What is the cancellation rate?
12. How are orders distributed across different order statuses?

### Visuals
An interactive Excel dashboard was built using:

Pivot Tables, Pivot Charts, Slicers, KPI Cards, Excel Shapes, Conditional Formatting.

**Dashboard KPIs** : Total Sales Value, Average Order Value, Total Customers, Quantity Sold, Return Rate

**Dashboard Visuals**: Monthly Sales Trend, Product Return Rate, Order Status Distribution, Top 10 Customers, Sales Value by Product, Sales Value by Referral Source

<img width="478" height="293" alt="image" src="https://github.com/user-attachments/assets/9aa68a30-3d03-4c05-9d73-106a99cb51ad" />

### Business Insights
- The business recorded a Total Sales Value of ₦1,264,761.96 from 1,190 customer orders, with an Average Order Value of ₦1,053.97, indicating a healthy average customer spend.
- Sales peaked in June, suggesting a period of higher customer demand before declining in subsequent months.
- Chair emerged as the top-performing product by sales value, while Phone generated the lowest sales value, highlighting differences in product performance.
- Tablet recorded the highest return rate (24%), followed by Laptop (23%) and Monitor (22%), indicating these products may require further investigation to identify the causes of returns.
- Instagram generated the highest sales value among all referral channels, making it the most effective marketing source, while the Referral channel contributed the least.
- A relatively small group of customers accounted for the highest sales value, indicating opportunities to improve customer retention through loyalty and targeted marketing initiatives.
- The dataset recorded a 21% return rate, suggesting that a significant proportion of orders were returned. Although the dataset is synthetic, reducing returns would be a key area of focus in a real business environment.
- The distribution of order statuses was fairly balanced across Delivered, Shipped, Pending, Returned, and Cancelled orders, indicating that no single status overwhelmingly dominated the dataset.

### Business Recommendations
1. The reasons behind the high return rates for Tablet, Laptop, and Monitor should be investigated to improve product quality, product descriptions, or fulfilment processes.
2. Marketing investment in Instagram should be increased, as it generated the highest sales value among all referral sources.
3. Implementation of customer retention strategies targeting the top-spending customers through loyalty programmes and personalised promotions.
4. Increasing the visibility and promotion of high-performing products such as Chair while reviewing the pricing or marketing strategy for lower-performing products like Phone.
5. Continuously monitoring of order status trends and return rates to improve operational efficiency and customer satisfaction.

### Tools Used
- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- Excel Functions
- Conditional Formatting

### Skills Demonstrated
- Data Cleaning
- Data Validation
- Data Preparation
- Descriptive Statistics
- Exploratory Data Analysis
- Dashboard Design
- Data Visualization
- Business Insight Generation
- Analytical Thinking

**Project Workflow**

Microsoft ExcelRaw Dataset
        │
        ▼
  Data Cleaning
        │
        ▼
 Data Preparation
        │
        ▼
Exploratory Data Analysis
        │
        ▼
 Pivot Tables
        │
        ▼
 Dashboard Development
        │
        ▼
 Business Insights




