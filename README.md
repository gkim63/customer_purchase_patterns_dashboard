# Customer Purchase Patterns Dashboard
## Data Source
The original dataset used in this project is available at:

🔗 [Kaggle: Customer Shopping Trends Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset)

## OverView
This project analyzes customer purchase data and visualizes seasonal trends, payment method preferences, shipping method patterns, and regional order distribution through a Power BI dashboard. Insights help identify shifts in customer preferences, purchasing behaviors, and emerging trends, enabling the development of personalized services and the establishment of KPIs based on future demand forecasts.


## Dataset Description
- File: `shopping_trends.csv`  
- Rows: 3,900 | Columns: 18  

## Dashboard Feature

**Dashboard 1: Home**
- Total Orders, Average Purchase Amount, Subscription Rate, Discount Usage Rate
- Delivery Method Distribution
- Order Volume by Season
- Top 5 Most Frequently Used Payment Methods
- Top 5 States by Order Volume

**Dashboard 2: Payment & Discount Analysis**
- Order Volume by Payment Method: Actual vs Preferred
- Average Order Value by Payment Method
- Payment Conversion Efficiency
- Impact of Payment Method on Discount Usage
- Top Actual Payment
- Top Preferred Payment

**Dashboard 3: Customer Behavior**
- Delivery Method Distribution
- Seasonal Purchase Patterns by Product Size
- Impact of Payment Methods on Discount Usage
- Top Age Group by Orders, Average Review Rate, Popular Color Rate

**Dashboard 4: Delivery Type**
- Order Count by Delivery Type
- Free Shipping Orders by Age Group
- Average of Previous Purchases by Delivery Type
- Promo Code Usage Rate, Top Shipping Type, Popular Color Rate

**Dashboard 5: State Analysis**
- Top Ordering States: Total Sales, Rate, Payment Method, Preferred Payment Method
- Top 5 States by Order Volume
- Total Orders & Amount by State
- Bottom 5 States by Order Volume
- Purchase Patterns by Age Group & State

## Key Insights

**1. Top Order Age Group: 55+ (1,178 out of 3,900 orders)**
- Approximately one-third of customers are aged 55+ in this store. Since this is an uneven distribution, the marketing team should decide which other age groups to focus on.
- If focusing on the 55+ group, it is necessary to identify which product categories or promotions can encourage higher consumption from this age group.
- If focusing on all age groups, the store should investigate gaps in product offerings or marketing strategies to appeal to different age segments and determine which products each group prefers.
- 
**2. Discount Usage (43%) and Promo Code Usage (43%)**
  - Since discount and promo code usage percentages are identical, it can be assumed that both represent the same group of customers.
  - When the system applies automatic discounts, the promo code discount may be counted as duplicate information; future dashboards should consider removing one of the columns.
  - Promo codes appear to have a significant effect on customer behavior, indicating that customers are well aware of store promotions.
  - 
**3. Customer Preferred Payment vs. Actual Payment**
- While customers prefer to use PayPal, the actual payment method used is Credit Card, indicating a gap between preference and behavior.
- Possible reasons include:
    - Customers may avoid logging in or connecting their PayPal account at the time of payment.
    - Credit Card payments may offer benefits or cashback that influence the choice.
    - Certain products or payment environments may not support PayPal.

## Tech Stack
- Power BI
- DAX
- Tooltip
- Drill Through

## Future Improvements
- Add deeper analysis by product category and season
- Implement predictive analytics for demand forecasting
- Improve dashboard interactivity and filters for user experience
- Optimize data model for faster refresh and performance
