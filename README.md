# Amazon Sales Performance Analysis

## Project Overview

This project analyzes one month of Amazon order-level sales data using Microsoft Excel.

The objective is to transform raw transactional data into meaningful business insights related to product performance, category performance, customer locations, payment methods, customer spending, and order status.

An interactive Excel dashboard was developed using PivotTables, PivotCharts, Excel formulas, and slicers to support data-driven decision-making.

## Project Objectives

- Analyze overall Amazon sales performance
- Identify high-performing products and categories
- Analyze sales performance across customer locations
- Understand customer payment method preferences
- Analyze completed, cancelled, and pending orders
- Identify top customers based on total spending
- Create PivotTables for business analysis
- Develop an interactive Excel dashboard
- Generate actionable business insights and recommendations

## Tools and Skills

### Tools

- Microsoft Excel
- PivotTables
- PivotCharts
- Slicers
- Excel Formulas

### Skills

- Data Analysis
- Data Cleaning and Validation
- Data Preprocessing
- Exploratory Data Analysis
- Data Aggregation
- KPI Analysis
- Dashboard Development
- Data Visualization
- Business Insights
- Business Recommendations

## Dataset

The dataset contains Amazon order-level sales information.

### Dataset Information

| Metric | Value |
|---|---:|
| Total Orders | 250 |
| Total Columns | 11 |
| Missing Values | 0 |
| Duplicate Order IDs | 0 |
| Total Sales | 243,845 |

### Dataset Columns

| Column | Description |
|---|---|
| Order ID | Unique identifier for each order |
| Date | Order date |
| Product | Product name |
| Category | Product category |
| Price | Price per unit |
| Quantity | Quantity ordered |
| Total Sales | Total sales amount |
| Customer Name | Customer name |
| Customer Location | Customer city or location |
| Payment Method | Payment method used |
| Status | Order status |

## Project Methodology

### 1. Data Loading

- Imported the Amazon sales dataset into Excel.
- Reviewed the dataset structure and data types.

### 2. Data Validation

- Checked for missing values.
- Checked for duplicate records and Order IDs.
- Validated Total Sales using Price multiplied by Quantity.
- Verified the dataset contains 250 orders.

### 3. Data Preprocessing

Created calculated fields including:

- Month
- Day of Week
- Order Status Flag

### 4. Data Analysis

Created PivotTables to analyze:

- Category-wise Total Sales
- Product-wise Total Sales
- City-wise Total Sales
- Payment Method Usage
- Order Status Distribution
- Top Customers by Spending

### 5. Dashboard Development

Developed an interactive Excel dashboard containing:

- KPI cards
- Sales analysis charts
- Order status analysis
- Payment method analysis
- Interactive slicers

## Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Sales | 243,845 |
| Total Orders | 250 |
| Completed Orders | 88 |
| Cancelled Orders | 77 |
| Pending Orders | 85 |

### Order Status Analysis

| Status | Orders | Percentage |
|---|---:|---:|
| Completed | 88 | 35.2% |
| Cancelled | 77 | 30.8% |
| Pending | 85 | 34.0% |
| Total | 250 | 100% |

## Category Performance

| Category | Total Sales |
|---|---:|
| Electronics | 129,950 |
| Home Appliances | 105,000 |
| Footwear | 4,320 |
| Clothing | 3,540 |
| Books | 1,035 |
| Total | 243,845 |

Electronics generated the highest category sales at 129,950, followed by Home Appliances at 105,000.

Together, these two categories generated 234,950, representing approximately 96.4% of total sales.

## Product Performance

| Product | Total Sales |
|---|---:|
| Refrigerator | 78,000 |
| Laptop | 58,400 |
| Smartphone | 48,500 |
| Washing Machine | 27,000 |
| Smartwatch | 15,750 |
| Headphones | 7,300 |
| Running Shoes | 4,320 |
| Jeans | 2,480 |
| T-Shirt | 1,060 |
| Book | 1,035 |

Refrigerator was the highest-performing product with total sales of 78,000, followed by Laptop and Smartphone.

## Customer Location Analysis

| Customer Location | Total Sales |
|---|---:|
| Miami | 31,700 |
| Denver | 29,785 |
| Houston | 28,390 |
| Dallas | 27,145 |
| Seattle | 26,890 |
| Boston | 26,170 |
| Chicago | 20,810 |
| New York | 18,940 |
| Los Angeles | 17,820 |
| San Francisco | 16,195 |

Miami recorded the highest sales among customer locations at 31,700, while San Francisco recorded the lowest at 16,195.

## Payment Method Analysis

| Payment Method | Orders |
|---|---:|
| PayPal | 60 |
| Credit Card | 54 |
| Debit Card | 53 |
| Gift Card | 42 |
| Amazon Pay | 41 |
| Total | 250 |

PayPal was the most frequently used payment method with 60 orders.

## Top Customers by Spending

| Customer | Total Spending |
|---|---:|
| Olivia Wilson | 36,170 |
| Jane Smith | 31,185 |
| Emma Clark | 29,700 |
| John Doe | 26,870 |
| Emily Johnson | 23,475 |
| David Lee | 22,665 |
| Michael Brown | 22,655 |
| Daniel Harris | 18,945 |
| Chris White | 18,885 |
| Sophia Miller | 13,295 |

Olivia Wilson was the highest-spending customer with total spending of 36,170.

## Dashboard

The interactive Excel dashboard provides a consolidated view of Amazon sales performance.

### Dashboard Visualizations

- Sales by Category
- Sales by Product
- Sales by Customer Location
- Order Status Distribution
- Payment Method Distribution

### Dashboard Filters

- Category
- Customer Location
- Order Status
- Month

The slicers allow users to dynamically filter the dashboard and analyze different segments of the dataset.

## Key Business Insights

### Category Performance

Electronics and Home Appliances are the primary revenue-generating categories, contributing approximately 96.4% of total sales.

### Product Performance

Refrigerator generated the highest product sales, followed by Laptop and Smartphone.

### Customer Location

Miami recorded the highest sales among the analyzed locations, while San Francisco recorded the lowest.

### Payment Preferences

PayPal was the most frequently used payment method, followed by Credit Card and Debit Card.

### Order Status

Only 35.2% of orders were completed, while 64.8% were either cancelled or pending. This indicates an opportunity to improve order fulfillment and order completion.

### Customer Performance

Olivia Wilson was the highest-spending customer, with total spending of 36,170.

## Business Recommendations

### 1. Focus on High-Performing Categories

Prioritize inventory planning, promotions, and marketing activities for Electronics and Home Appliances.

### 2. Maintain Inventory for High-Performing Products

Ensure adequate inventory for high-performing products such as Refrigerator, Laptop, and Smartphone.

### 3. Reduce Cancelled Orders

Investigate cancellation drivers such as product availability, pricing, delivery expectations, and order confirmation.

### 4. Improve Pending Order Fulfillment

Monitor pending orders and improve fulfillment processes to increase the percentage of completed orders.

### 5. Target High-Performing Locations

Focus marketing and promotional activities on locations with strong sales performance while investigating opportunities in weaker locations.

### 6. Monitor Payment Preferences

Continue monitoring payment method usage to provide customers with convenient and reliable payment options.

## Repository Structure

amazon-sales-performance-analysis/
│
├── Amazon_Sales_Performance_Analysis.xlsx
├── dashboard.png
└── README.md

## Author

Varsha Maturi
