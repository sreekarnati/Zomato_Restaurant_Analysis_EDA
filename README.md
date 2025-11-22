🍽️ Zomato Restaurant Market Analysis (Exploratory Data Analysis)

This project conducts a comprehensive Exploratory Data Analysis (EDA) on a dataset of Zomato restaurants to identify key market drivers for success, focusing on factors that correlate with high customer ratings and engagement.

The goal is to provide actionable business intelligence for potential restaurant owners or marketing strategists.

🎯 Project Goal

To understand the core dynamics of the restaurant market by answering:

What characteristics (cost, specialization, online presence) lead to higher customer ratings?

Which restaurant service models and individual cuisine types are currently generating the highest customer engagement (total rating volume)?

Which individual restaurants are consistently top-performing?

⚙️ Methodology & Tools

Dataset: Zomato Restaurant Listing CSV.

Tools: Python, Pandas, NumPy, Matplotlib, Seaborn.

Approach:

Data Cleaning: Handled missing values, standardized binary columns (online_order, table_booking), converted text ratings (New, -) to numeric, and performed aggressive string cleaning on key columns (restaurant name, restaurant type) to ensure accurate grouping.

Feature Engineering: Created the num_cuisines feature to quantify restaurant specialization.

Visualization & Analysis: Used scatter plots, box plots, and bar plots to analyze correlations and identify market trends.

✨ Key Findings & Business Insights

1. Specialization Drives Quality (Rating)

The analysis demonstrated a strong inverse correlation between the number of cuisines offered and the average rating. Restaurants specializing in 1-2 cuisines generally maintain higher average quality ratings than those offering 5 or more diverse cuisine types.

Recommendation: New ventures should focus on a narrow, high-quality offering rather than an expansive, generalized menu.

2. Online Presence is Critical for Ratings

Restaurants that offer online ordering showed a noticeable uplift in average ratings compared to those that do not.

Recommendation: Investing in seamless online ordering (or integration with a platform like Zomato/Swiggy) is essential for customer satisfaction and market performance.

3. Most Popular Restaurant Service Models

By analyzing the total volume of ratings received, the highest customer engagement is concentrated in the following service models:

Combined Categories (e.g., "Quick Bites, Beverages"): Shows the top multi-service categories driving traffic.

Individual Service Types (Deconstructed):

Quick Bites and Takeaway emerged as the single most popular individual types, indicating a market preference for speed, convenience, and delivery/on-the-go consumption.

Recommendation: Focus on optimizing the Quick Bite/Delivery infrastructure for rapid return on investment.

4. Top Performing Restaurants

The project identified the highest-rated restaurants with a high volume of customer reviews (minimum 50), providing a benchmark for operational excellence in the market.

📈 Running the Analysis

Clone the Repository:

git clone [Your Repository URL]


Ensure Data: Place the Zomato_Restaurants.csv file in the root directory.

Execute: Run the script using Python:

python Zomato_Restaurant_Analysis.py
