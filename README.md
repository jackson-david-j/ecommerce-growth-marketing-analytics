# E-Commerce Growth & Marketing Analytics

End-to-end business analytics project using Python, SQL, DAX, and Power BI to analyze historical e-commerce sales, customers, products, delivery performance, and customer reviews using the Olist public dataset.

## Business Problem

The e-commerce business data is spread across multiple tables covering orders, customers, products, sellers, payments, reviews, and delivery information.

The objective of this project is to combine and analyze these data sources to answer key business questions related to:

- Sales performance
- Product category performance
- Customer purchasing behavior
- Geographic sales distribution
- Delivery performance
- Customer reviews
- Business growth and customer experience opportunities

## Business Questions

This project was designed to answer seven business questions:

1. How much are we selling, and how are sales changing over time?
2. Which product categories perform best and worst?
3. What do customers' purchasing patterns look like?
4. Which customer locations generate the most sales?
5. How well are orders being delivered?
6. What factors are associated with better or worse customer reviews?
7. What actions could improve business growth and customer experience based on the available evidence?

## Dataset

This project uses the Olist Brazilian E-Commerce Public Dataset, which contains historical marketplace data mainly from 2016 to 2018.

The analysis uses nine tables covering:

- Customers
- Orders
- Order items
- Payments
- Reviews
- Products
- Sellers
- Product category translation
- Geolocation

Key dataset considerations:

- The dataset is historical and should not be treated as current market data.
- Product sales are based on `order_items.price`.
- Freight is not included in product sales.
- Profitability cannot be determined because cost and margin data are not available.
- Customer repeat behavior is measured only within the available observation period.

## Tools & Technologies

### Python
Used for data cleaning, validation, missing-value checks, duplicate handling, and preparation of the cleaned datasets.

### SQL
Used to answer the seven business questions, calculate business metrics, validate results, and investigate customer, sales, delivery, geographic, and review patterns.

### Power BI
Used to build the data model, create DAX measures, design the interactive dashboard, and present business insights.

### DAX
Used to create validated KPI measures for sales, orders, delivery performance, customer behavior, and review analysis.

## Project Workflow

The project follows an end-to-end analytics workflow:

1. Define the business problem and business questions
2. Clean and prepare the raw data using Python
3. Analyze the cleaned data using SQL
4. Import the cleaned tables into Power BI
5. Build and validate the Power BI data model
6. Create DAX measures for key business metrics
7. Build the interactive dashboard
8. Validate dashboard results against SQL analysis
9. Identify business insights
10. Develop evidence-based recommendations

## Power BI Dashboard

The final Power BI report contains three main analytical pages:

### Executive Overview
Provides a high-level view of:
- Delivered product sales
- Delivered orders
- Average order value
- Late delivery rate
- Average review score
- Repeat customer rate
- Customer counts
- Monthly sales trend

### Sales & Geographic Analysis
Focuses on:
- Top product categories by delivered product sales
- Top customer states by delivered product sales
- Sales concentration across categories and regions

### Delivery & Customer Experience
Focuses on:
- Late delivery rate
- Delivery time
- Customer review scores
- Low-rating rate
- Late delivery performance by state
- Review score by delivery-time group

The dashboard includes page navigation, date slicers, KPI cards, and interactive cross-filtering between visuals.
