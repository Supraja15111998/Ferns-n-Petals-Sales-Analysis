# FNP Sales Analysis Dashboard

An end-to-end Excel data analytics project analyzing sales performance for **Ferns and Petals (FNP)** — a gifting company serving occasions like Diwali, Raksha Bandhan, Holi, Valentine's Day, Birthdays, and Anniversaries.

## Dashboard Preview
![FNP Sales Analysis Dashboard](dashboard.png)

## Objective
Analyze FNP's order dataset to uncover actionable insights on sales trends, customer behavior, and product performance — helping the business optimize its sales strategy and improve customer satisfaction.

## Dataset
3 datasets used in this project:

| File | Records | Description |
|---|---|---|
| customers.csv | 204 | Customer_ID, Name, City, Gender, Contact, Email, Address |
| orders.csv | 1,000 | Order_ID, Customer_ID, Product_ID, Quantity, Order_Date, Delivery_Date, Location, Occasion |
| products.csv | 70 | Product_ID, Product_Name, Category, Price (INR), Occasion, Description |

## Key Metrics
| Metric | Value |
|---|---|
| Total Orders | 1,000 |
| Total Revenue | ₹35,20,984 |
| Avg. Order–Delivery Time | 5.53 days |
| Avg. Customer Spending | ₹3,521 |

## Tools Used
- **Power Query Editor** — Data cleaning and transformation
- **Power Pivot** — Data modeling (linked via Customer_ID & Product_ID) and DAX measures
- **Pivot Tables** — Data aggregation and summarization
- **Pivot Charts** — Visual representation of insights
- **Slicers & Timelines** — Interactive dashboard filtering by Occasion, Order Date, Delivery Date

## Project Structure
fnp-sales-analysis/
├── datasets/
│   ├── customers.csv
│   ├── orders.csv
│   └── products.csv
├── FNP_Sales_Analysis.xlsx
├── FNP_Analysis_Report.txt
├── dashboard.png
└── README.md

## Key Insights
- Anniversary and Holi are the top revenue-generating occasions
- Cakes dominate product category revenue (~₹10,00,000)
- Revenue peaks in February (Valentine's Day) and August (Raksha Bandhan)
- Magnum Set and Quia Gift are the top revenue-generating products
- Average delivery time is a consistent 5.53 days across all order volumes
- Top cities by orders — Kavali, Imphal, and Dhanbad lead demand

## Business Questions Answered
1. Total Revenue
2. Average Order & Delivery Time
3. Monthly Sales Performance
4. Top Products by Revenue
5. Customer Spending Analysis
6. Top 5 Products Sales Performance
7. Top 10 Cities by Orders
8. Order Quantity vs. Delivery Time
9. Revenue by Occasion
10. Product Popularity by Occasion

