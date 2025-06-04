# Retail-Performance-Optimization

This project involves analyzing sales and profit data for a retail company to identify opportunities for optimization and growth.

# Table of Contents
- [Project Overview](#Project-Overview)
- [Objective](#objective)
- [Impact & Outcome](#Expected-outcome)
- [Data Source](#data-source)
- [Design](#design)
  - [Tools](#tools)
- [Data Exploration Notes](#data-exploration)
- [Data Cleaning](#data-cleaning)
- [Transform the Data](#transform-the-data)
- [Visualization](#visualization)
  - [Results](#results)
  - [DAX Measures](#dax-measures)
- [Analysis](#analysis)
  - [Findings](#findings)
  - [Interpretation](#interpretation)
- [Recommendations](#recommendations)





# Project Overview
## Objective
Sales, Orders & Profitability Analysis – Retail Company
In this project, I led the development of a comprehensive Power BI dashboard for a retail company facing declining profit margins despite growing sales. The goal was to uncover key business insights and support data-driven decision-making by analyzing historical performance across orders, products, customer segments, and regions.

## Key Focus Areas:
- Sales & Profit Trends: Monthly analysis of over $1.58M in total sales, $173K in total profit, and 8,399 customer orders, helping identify peak and low-performing months.

- Customer Segmentation: Evaluated profitability across segments (e.g., Corporate, Consumer, Small Business), revealing Corporate as the most profitable.

- Product Performance: Highlighted top-performing products and identified loss-generating sub-categories like Tables and Storage & Organization for strategic review.

- Geographic Performance: Pinpointed states with the highest revenue (e.g., New York, Texas) and profit margins, aiding regional marketing strategy.

- Discount & Shipping Impact: Assessed correlation between high discounting and low profit, and reviewed shipping costs by mode and region, identifying cost inefficiencies with Delivery  Truck mode.

- Case Metrics: Included key KPIs such as Average Order Value ($189), Average Discount (5%), and Average Shipping Cost ($13).

## Impact & Outcome:
- Enabled the business to identify low-margin high-volume products, optimize discounts, and streamline shipping.

- Provided granular visibility into performance drivers, supporting targeted marketing, pricing, and inventory decisions.

- Served as a central tool for C-suite reporting and operational planning.

# Data Source
- What data is needed to achieve this?

We require the sales and order data from the retail company to gain a clear understanding of the business performance and operational trends.
Details such as
- Order ID
- Order Date / Ship Date
- Customer ID / Name
- Product ID / Name
- Sales Amount
- Quantity Ordered
- Unit Price
- Discount Applied
- Shipping Cost
- Profit / Margin
and other details to aid in-depth analysis.

- Where is the data coming from?
The data is gotten from a retail company whose business is situated in the United States of America.

# Design
## Dashboard components required
- What should the dashboard contain?

To understand this, we need to know the business problems we are trying to solve using our dashboard:

1. Which states generate the highest sales and profit?
2. Which product categories or sub-categories drive the most profit vs. the most losses?
3. Are high discounts correlated with negative or low profit margins?
4. Is there a trend where high sales volumes don't translate into high profits? If so, which segments or products are affected?
5. What are the average shipping costs by state, segment, or product category?
6. Does the shipping method impact profitability significantly?
7. Which customer segments contribute the most to profit and which to losses?
8. Do high-priority orders correlate with higher shipping costs or lower profits?
9. What's the return rate or cancellation trend by product or state?
10. Which products are frequently sold at a high discount and still underperform?
11. How does the 'Product Base Margin' vary across categories?

## Tools
The following tools were used during this analysis
| Tool | Purpose |
| --- | --- |
| Excel | -Exploring data |
|       | - Cleaning, testing, and analyzing data |
| Power BI | Visualizing the data by creating interactive dashboards |
| PowerPoint | Designing of dashboard canvas |
| GitHub | Hosting, and documentation of the projects |
