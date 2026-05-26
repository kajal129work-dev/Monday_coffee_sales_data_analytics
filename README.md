# Monday Coffee Sales Data Analysis

## Project Overview
This project involves an end-to-end data analysis of "Monday Coffee" sales performance. The goal was to identify the top three cities in India for potential retail expansion by analyzing customer demographics, sales revenue, and rental costs using SQL.

## Business Questions
I analyzed the following key metrics to support data-driven decision-making:
- **Market Potential:** Which cities have the highest sales volume and largest coffee-consuming population?
- **Customer Insights:** How does the average sales per customer vary across different regions?
- **Cost-Efficiency:** Which cities offer the best balance between rent and revenue generation?

## Tools & Technologies
- **Database Management:** MySQL
- **Data Analysis:** SQL (Data cleaning, aggregation, and filtering)

## Analysis Highlights
* **Customer Segmentation:** Identified unique customer behaviors across various cities.
* **Growth Trends:** Calculated monthly sales growth rates to identify high-performing periods.
* **Expansion Strategy:** Recommended the top 3 cities (Pune, Delhi, Jaipur) based on a low rent-to-sales ratio and high customer density.

## Project Structure
- `sales.csv`, `customers.csv`, `products.csv`, `city.csv`: Raw datasets used for the analysis.
- `Solutions.sql`: Contains all the MySQL queries used to extract insights.
- `README.md`: Project documentation.

## Key Questions Solved
I performed a comprehensive analysis in MySQL to answer these 10 business questions:

1. **Coffee Consumers Count:** Estimated the coffee-consuming population in each city (assuming 25% of the population).
2. **Total Revenue:** Calculated the total revenue generated from coffee sales in Q3 2023.
3. **Product Performance:** Counted the total units sold for each individual coffee product.
4. **Average Sales per City:** Determined the average sales amount per customer across different cities.
5. **City Demographics:** Mapped city populations against the estimated coffee-consuming population.
6. **Top Selling Products:** Identified the top 3 selling products in each city based on sales volume.
7. **Customer Segmentation:** Counted the number of unique customers in each city who have purchased coffee.
8. **Rent vs. Revenue:** Analyzed the relationship between average rent per customer and average sales per customer.
9. **Monthly Sales Growth:** Calculated the month-over-month percentage growth in sales to identify performance trends.
10. **Market Potential Analysis:** Ranked the top 3 cities for expansion based on high sales, customer density, and low rent costs.

## Recommendations
After analyzing the data, the recommended top three cities for new store openings are:

### City 1: Chennai
1. **Highest Revenue:** Generated the highest total revenue among the top three at 944,120.
2. **Cost Efficiency:** Offers a low average rent per customer (approx. 407), ensuring better operating margins.
3. **Strong Performance:** Supported by a robust base of 42 customers and the highest average sales per customer at 22,479.

### City 2: Bangalore
1. **Market Reach:** Represents the largest estimated coffee consumer market among these top cities at 3.08 million.
2. **Strong Demand:** Shows a healthy balance with 39 unique customers and high average sales per customer (22,054), indicating strong market demand.

### City 3: Pune
1. **Low Overhead:** Features the lowest total rent cost (15,300), significantly reducing initial operating expenses.
2. **Stable Returns:** Maintains a high average sales per customer (21,901), very competitive with Chennai and Bangalore.
3. **Low Risk:** Offers a solid potential market of 1.88 million coffee consumers, providing a high-growth opportunity with lower investment risk.

## Conclusion
The analysis successfully provided actionable insights for the business expansion team, highlighting cities where the return on investment for new coffee shops would be most favorable.
