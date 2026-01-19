# Customer Purchase Patterns Dashboard
![Customer Behavior Dashboard](Screenshots/Customer_Behavior.pdf)
## Project Overview
This project presents an interactive Power BI dashboard built to analyze customer purchasing behavior for **Trend Cart Apparel**, an online apparel retail company.
The dashboard focuses on understanding **how customers purchase, pay, and choose delivery options**, with the goal of identifying actionable patterns that can support business decision-making.

The analysis is structured around three core areas:
- **Customer Behavior Analysis** – identifying key customer segments, loyalty patterns, and purchasing trends
- **Delivery Type Analysis** – understanding shipping preferences and the impact of free shipping on customer behavior
- **Payment Method Analysis** – comparing preferred payment methods with actual payment behavior to uncover checkout friction
The dashboard is designed using multiple related tables and enhanced with **drill-through** and **tooltip** interactions, allowing users to move from high-level insights to detailed exploration without overwhelming the interface.

## Key Insights (Summary)
- **Customer loyalty is concentrated in the 55+ age group**, indicating that current revenue is driven by an older, repeat-customer base, while younger segments present growth opportunities.
- **Free shipping strongly influences purchase behavior**, acting as a key conversion driver rather than just a delivery option.
- **A gap exists between preferred and actual payment methods**, suggesting potential checkout friction and opportunities to improve the payment experience.

## Dashboard Walkthrough
### Page 1. Customer Behavior Overview
This page provides a high-level overview of customer purchasing behavior for **Trend Cart Apparel**. It highlights key customer segments, purchasing patterns, and loyalty distribution, serving as the entry point for deeper analysis across the dashboard.

#### Key Insights
- **Core Customer Segment:** Customers aged **55+** account for the largest share of total orders and show a higher concentration of **Loyal and VIP** customers. This indicates that current revenue is strongly supported by an older, more loyal customer base.
- **Stable Purchase Patterns:** Product size preferences (primarily **M and L**) and seasonal order volume remain relatively consistent, suggesting that demand is not heavily season-driven and is more influenced by customer segments.

### Page 2. Delivery Type Analysis
This page focuses on how customers choose delivery options and how shipping preferences relate to customer age and purchase history.

#### Key Insights
- **Free Shipping as a Conversion Driver:** A significant portion of orders use **Free Shipping**, indicating that shipping cost plays a critical role in purchase decisions.
- **Delivery Choice & Customer History:** Customers with more previous purchases tend to show consistent delivery preferences, suggesting that delivery choice is influenced by customer maturity rather than one-time behavior.

### Page 3. Payment Method Analysis
This page compares customers’ **preferred payment methods** with their **actual payment behavior**, helping identify gaps between intent and real checkout actions.

#### Key Insights
- **Preference vs. Reality Gap:** While **PayPal** is the most preferred payment method, **Credit Cards** are the most frequently used in actual transactions. This gap may indicate checkout friction, authentication issues, or external incentives influencing payment choices.
- **Payment Behavior & Discount Usage:** Discount usage varies by payment method. A **tooltip interaction** on the fourth chart reveals detailed discount-related metrics when hovering over each payment method, enabling deeper insights without overcrowding the dashboard.
  
## Future Improvements & Business Recommendations
### Page 1. Customer Behavior Overview

1. Expand Loyalty Conversion for Younger Customers
The 55+ age group currently drives the majority of orders and loyalty tiers. A potential improvement would be to design targeted campaigns for younger customers (18–34) to encourage repeat purchases and loyalty program enrollment. This could include personalized promotions or onboarding incentives.

2. Enhance Customer Segmentation Analysis
Future iterations could introduce deeper segmentation by combining age group, purchase frequency, and average order value. This would enable more precise targeting and support customer lifetime value (CLV)–driven strategies.

### Page 2. Delivery Type Analysis

1. Optimize Free Shipping Strategy
Since free shipping strongly influences customer behavior, future analysis could evaluate minimum purchase thresholds to qualify for free shipping. This would help balance conversion impact with logistics costs.

2. Personalize Delivery Options for Repeat Customers
Delivery preferences vary based on customer purchase history. Offering tailored shipping options or exclusive delivery benefits to repeat customers could improve retention without broadly increasing shipping expenses.

### Page 3. Payment Method Analysis

1. Reduce Friction Between Preferred and Actual Payment Methods
The gap between preferred (PayPal) and actual (Credit Card) payment methods suggests potential checkout friction. Future improvements could include analyzing drop-off rates during payment selection or testing simplified authentication flows.

2. Leverage Payment-Specific Promotions
Tooltip insights show variation in discount usage by payment method. Future dashboards could explore targeted promotions tied to specific payment methods to influence customer behavior more effectively.

### Dashboard & Technical Enhancements
- Introduce **product category–level analysis** across all pages to connect customer behavior with merchandising decisions.
- Add **predictive analytics** to forecast demand by customer segment and delivery type.
- Further optimize the data model to improve refresh performance as data volume increases.



