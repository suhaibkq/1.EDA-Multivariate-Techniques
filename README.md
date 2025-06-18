# FoodHub Data Analytics Project

## Overview
FoodHub is an online food aggregator that analyzes customer order data to enhance restaurant partnerships, improve delivery efficiency, and optimize customer satisfaction. This project leverages data analytics to uncover insights and provide actionable business recommendations to drive growth and improve operational performance.

## Project Summary
This project analyzes a dataset containing 1,898 food orders. The goal is to answer key business questions related to:
- Which cuisines and restaurants are most in demand?
- How do cost, ratings, and delivery times impact customer satisfaction?
- How efficient are food preparation and delivery logistics?
- How do order trends vary between weekdays and weekends?

## Key Insights
- **Cuisine Demand:** American, Japanese, and Italian cuisines are most frequently ordered.
- **Delivery Impact on Ratings:** Faster deliveries lead to higher customer ratings.
- **Revenue Insights:** Shake Shack is the top revenue-generating restaurant.
- **Weekday vs. Weekend Trends:** Delivery times are generally shorter on weekends.
- **Cost Preferences:** Orders priced between $10–$30 are most popular.

## Methodology
1. **Data Collection & Understanding:**
   - Dataset containing 1898 orders with key attributes like order cost, delivery time, cuisine type, and restaurant name.
   
2. **Data Cleaning & Preprocessing:**
   - Missing ratings labeled as "Not given".
   - Data types were validated for accuracy, and outliers were assessed.

3. **Exploratory Data Analysis (EDA):**
   - Popular cuisines and restaurants were identified.
   - Order cost and delivery time distributions were analyzed.
   - Customer ratings were studied to understand satisfaction.

4. **Business Insights & Visualization:**
   - Visualizations created to identify demand trends, correlations, and patterns.

5. **Business Recommendations:**
   - Optimize restaurant operations for better delivery performance.
   - Use customer ratings to improve service and gather valuable feedback.
   - Promote top-performing restaurants to drive growth.

## Data Overview
- **Size:** 1898 rows, 9 columns.
- **Key Attributes:**
  - **Numeric:** Order cost, food preparation time, delivery time.
  - **Categorical:** Cuisine type, restaurant name, day of the week, rating.
- **Missing Data:** Missing ratings marked as “Not given.”
- **Outliers:** Assessed for cost and time-related features.

## Exploratory Data Analysis (EDA)
- **Univariate Analysis:**
  - Most orders cost between $10–$30.
  - The average food preparation time is ~27 minutes.
  - Delivery times are mostly between 15–30 minutes.
  - Weekends see a higher order volume than weekdays.

- **Multivariate Analysis:**
  - Higher ratings correlate with shorter delivery and preparation times.
  - Higher-cost orders tend to come from French cuisine, while Korean and Vietnamese cuisines are more affordable.
  - Weekday orders are slower, and weekend orders have more variation in delivery times.

## Key Recommendations
1. **Optimize Delivery and Preparation Times:**
   - Focus on restaurants with long preparation times to improve efficiency.
   - Increase weekday delivery resources to match weekend efficiency.

2. **Leverage High-Performing Restaurants:**
   - Offer promotions to top revenue-generating restaurants to increase customer retention.

3. **Improve Customer Engagement:**
   - Encourage more customer feedback to monitor service quality and identify areas for improvement.

4. **Revenue Growth Strategies:**
   - Introduce premium meal bundles for high-cost cuisines.
   - Optimize pricing to ensure competitive and profitable order costs.

## Future Work
- Expand data analysis to include seasonal trends and more detailed customer preferences.
- Investigate customer loyalty and repeat ordering patterns.
- Develop a predictive model for order delivery times.

## Conclusion
By implementing these strategies, FoodHub can enhance customer experience, streamline operations, and maximize profitability. This project provides actionable insights that will drive improvements in business performance and customer satisfaction.

## License
This project is proprietary and all rights are reserved. Unauthorized use or distribution is prohibited.
