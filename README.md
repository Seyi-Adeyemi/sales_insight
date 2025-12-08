# Sales & Customer Insights Project

## Executive Summary
This project analysed sales, customer behavior, product returns, shipping fees, and product performance. Using data-driven insights, the analysis identified key drivers of revenue, returns, and customer engagement, enabling actionable recommendations to improve business performance and operational efficiency.

## Project Overview
This project analyses sales, returns, shipping, and customer behavior to provide actionable business recommendations.

## Key Questions
- Total Revenue: How much revenue did we generate in total, and how has revenue changed month-to-month?
- Top products by revenue and by units sold: Which products generate the most revenue, and which sell the most units?
- Returns by region: Which regions have the highest return rates and what is the financial impact of those returns?
- Average spending / Average Order Value (AOV): What is the average order value and how does it vary by region and gender?
- Age group trends — revenue, orders, AOV, and return behavior: How do different age groups behave (orders, revenue, AOV, returns)?
- Top customers (lifetime value / repeat purchase): Who are the top customers by lifetime revenue and how many repeat purchases do they make?
- Product return hotspots (products with high return rates): Which products have unusually high return rates and deserve investigation?
- Shipping fee impact on returns (correlation check): Do orders with higher/lower shipping fees have different return rates?

### Data Exploration:

![DataExploration](docs/Screenshot 2025-12-08 151658.png)

#### Exploratory Data Analysis
![DataExploration](docs/Screenshot 2025-12-08 153505.png)

#### Checking for null values
![Nullvalues](docs/Screenshot 2025-12-08 154909.png)
Null values replaced automatically with NaN

#### Checking for duplicates
![Duplicates](docs/Screenshot 2025-12-08 155422.png)
Zero duplicates

### Question 1: Total Revenue: How much revenue did we generate in total, and how has revenue changed month-to-month?
![TotalRevenue](docs/Screenshot 2025-12-08 163835.png)
Total Revenue is £1,364,600
![TotalRevenue](docs/Screenshot 2025-12-08 160539.png)

### Question 2: Top products by revenue and by units sold: Which products generate the most revenue, and which sell the most units?
![ProductsbyUnits](docs/Screenshot 2025-12-08 160903.png)

![ProductsbyUnits](docs/Screenshot 2025-12-08 161030.png)
Most number of products sold is Monitor - 503 units

![ProductsbyRevenue](docs/Screenshot 2025-12-08 163127.png)
We can see that the product with the highest revenue is Laptop (£696,000), even though the units sold was less than Monitor. This is very interesting! Let's find out why the revenue on Monitor is not commensurate with the total units sold. 

The unit price for laptop is £1,500 per piece, while the unit price for monitor per piece is £300. This explains the difference!

### Question 3: Returns by region: Which regions have the highest return rates and what is the financial impact of those returns?
First, let's see the returns by region!

![ReturnsbyRegion](docs/Screenshot 2025-12-08 164145.png)

Next, let's see the return rate by region

![ReturnRate](docs/Screenshot 2025-12-08 164822.png)

## Portfolio Skills Demonstrated
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical Correlation & Insights
- Data Visualization & Dashboarding
- Business Recommendation & Strategy
- Predictive Modeling (optional, advanced)

## Recommendations
1. Improve high-return product quality
2. Retain and upsell high-value customers
3. Optimize regional marketing
4. Tailor strategies by demographics
5. Maintain shipping pricing
6. Enhance product descriptions and reviews
7. Prioritize operational interventions based on financial impact
