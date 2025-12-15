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

The region with the highest returns and return rate is the West Region -38.62%

### Question 4: Average spending / Average Order Value (AOV): What is the average order value and how does it vary by region and gender
First, let's find the overall AOV
![AOV](docs/Screenshot 2025-12-15 083014.png)

Now let's see the most products ordered by both genders
![AOV](docs/Screenshot 2025-12-15 083032.png)

Now, let's look at the top products ordered by each gender
![AOV](docs/Screenshot 2025-12-15 083059.png)

Next, let's visualise this to see the top 5 products returned by both gender
![AOV](docs/Screenshot 2025-12-15 083337.png)

The most products returned by both gender is Monitor and Laptop.

### Question 5: Age group trends — revenue, orders, AOV, and return behavior: How do different age groups behave (orders, revenue, AOV, returns)?Average spending / Average Order Value (AOV): What is the average order value and how does it vary by region and gender?
First, let's create age groups and calculate key perfomance metrics per age group
![AgeGroup](docs/Screenshot 2025-12-15 124404.png)

Next, let's see the top 5 products per age group
![Top5Products](docs/Screenshot 2025-12-15 124435.png)

![Top5Products](docs/Screenshot 2025-12-15 124521.png)

### Question 6:  Top customers (lifetime value / repeat purchase): Who are the top customers by lifetime revenue and how many repeat purchases do they make?
First, let's calculate total revenue and the number of orders by customer
![CLV](docs/Screenshot 2025-12-15 084041.png)

Next, let's visualise the top customers by CLV
![TopCustomers](docs/Screenshot 2025-12-15 084159.png)

Now, let's see the relationship between the number of orders and the revenue
![Correlation](docs/Screenshot 2025-12-15 084240.png)

There's clearly a positive correlation betweeen the number of orders and CLV; Customers who buy more often generate more total revenue over time.

### Question 7: Product return hotspots (products with high return rates): Which products have unusually high return rates and deserve investigation?
![ReturnHotspots](docs/Screenshot 2025-12-15 085859.png)

Now, let's visualise the top 10 most returned products
![ProductsReturn](docs/Screenshot 2025-12-15 090043.png)

### QUESTION 8: Shipping fee impact on returns (correlation check): Do orders with higher/lower shipping fees have different return rates?

First, let's find the correlation between shipping fee and returned orders
![Shipping Fee Impact](docs/Screenshot 2025-12-15 090332.png)
Correlation between Shipping Fee and Returns: -0.07661235763648058, which suggests that higher shipping fees are very weakly associated with slightly fewer returns, but the effect is negligible.

Next, Let's compare return rates among shipping fee ranges. To do this, we need to create shipping fee ranges/buckets. Our max shipping fee is £19.98
![ShippingFeenReturn](docs/Screenshot 2025-12-15 090720.png)

![ShippingFeeImpact](docs/Screenshot 2025-12-15 090828.png)

There's literally no correlation between shipping fee and return rate

## Recommendations
- Investigate top-returned products for quality issues, breakage, incorrect sizing, or misleading product descriptions. This will directly reduce return costs, improve customer satisfaction, and protect overall profitability.
- Focus Retention & Upsell Efforts on High-Value Customers. This maximizes Customer Lifetime Value (CLV) and protects the brand’s most valuable revenue source.
- Shipping Fee Does Not Affect Returns, therefore, no need to change pricing. Instead, focus on product quality, expectation setting, and packaging.
- Since returns are not driven by shipping fees or customer demographics alone, the root cause is likely product-related. Therefore, to reduce return rates and improve customer trust, Improve product photos, descriptions, size guides, and introduce “Return Reason” tagging if data is available.
- Evaluate Operational Impact of Returns. Prioritize fixing issues in regions/products with highest financial return impact, not just highest return counts.

Overall, the data suggests that product-related factors (quality, expectations, and category-specific issues) are the primary drivers of returns, not shipping fees or customer segments. Meanwhile, a small set of high-value customers drives a large portion of revenue, making retention and personalized marketing critical. Optimizing regional strategies, improving product QA, and focusing on high-value customers will significantly enhance revenue while reducing operational losses from returns.

## Portfolio Skills Demonstrated
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical Correlation & Insights
- Data Visualization & Dashboarding
- Business Recommendation & Strategy

## 🚀 Next Steps:
While this analysis provides valuable insights into customer behavior, returns, and revenue drivers, several opportunities exist to extend the project further:
- Build a return prediction model (logistic regression or tree-based models) to identify high-risk orders before shipment.
- Incorporate return reasons (if available) to better understand product defects, sizing issues, or expectation gaps.
- Segment customers using RFM analysis (Recency, Frequency, Monetary).
- Build an interactive dashboard using Power BI or Tableau.


