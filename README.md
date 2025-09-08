New York Airbnb 2024 – Exploratory Data Analysis
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on New York Airbnb data (2024) to uncover trends and patterns in rental listings.
We leverage Pandas, NumPy, Matplotlib, and Seaborn for data cleaning, visualization, and analysis.

🎯 Objectives

The goal of this project is to:

1.Analyze room types, prices, and availability across neighborhoods.
2.Understand host behavior and listing patterns.
3.Detect and handle outliers in prices.
4.Provide actionable recommendations for both guests and hosts.

📂 Dataset

The dataset contains 20,765 entries and 22 features, including:

#id → Unique identifier for each listing
#name → Title of the Airbnb listing
#host_name → Name of the host
#neighborhood_group → Borough where the listing is located
#latitude / longitude → Geolocation of the listing
#price → Nightly rental price
#room_type → Type of accommodation (Entire home, Private room, Shared room)
#reviews_per_month → Average monthly reviews
#availability_365 → Number of available days in a year

🔄 Workflow
1️⃣ Data Cleaning

1.Handled missing values in price, neighborhood, and beds.
2.Converted last_review to datetime format.
3.Removed outliers → Listings with prices > $1,000 were capped.

2️⃣ EDA (Exploratory Data Analysis)

1.Room Type Distribution → Bar plots showed Entire home/apt as the most common.
2.Neighborhood Insights → Manhattan had the highest average prices.
3.Availability Trends → Heatmaps revealed correlations among price, availability_365, reviews, and beds.
4.Price Distribution → Most listings fall in the $50–$300 range.
5.Host Listings → Boxplots highlighted professional hosts managing multiple listings.
6.Review Behavior → Pair plots explored relationships among reviews, prices, and availability.

3️⃣ Visualization Techniques

1.Pairplots → Price vs. Availability vs. Reviews.
2.Heatmaps → Correlation among numerical features.
3.Histograms & Boxplots → Outlier detection in prices.
4.Bar Charts → Distribution of room types & neighborhood groups.

📊 Key Findings
💰 Price Trends

1.Manhattan is the most expensive, followed by Brooklyn.
2.Entire homes/apartments cost significantly more than private/shared rooms.

🏘️ Room Type Distribution

1.Entire homes/apartments dominate the market.
2.Private rooms provide affordable alternatives.

⚠️ Outliers in Price

1.Listings priced $10,000+ exist → required filtering for clarity.

📅 Availability Patterns

1.High-availability listings tend to be cheaper and receive more reviews.

👥 Host Behavior

1.Several hosts manage multiple properties → indicating professional hosting trends.

🎯 Recommendations
✅ For Guests

1.Choose high-availability listings with good reviews for a better experience.
2.Private rooms in Brooklyn are a budget-friendly alternative to Manhattan.

✅ For Hosts

1.Keep calendars open and respond actively to reviews.
2.Competitive pricing improves visibility within borough markets.

🔮 Future Work

1.Build a Machine Learning model to predict Airbnb prices.
2.Perform sentiment analysis on guest reviews.
3.Develop an interactive dashboard (Plotly / Tableau / Streamlit) for live Airbnb insights.

🏁 Conclusion

This project provides actionable insights into New York’s Airbnb market. By applying EDA techniques, we discovered key pricing patterns, host behaviors, and guest preferences.
Future enhancements will involve predictive analytics and real-time dashboards to further empower guests and hosts.
