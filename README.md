# AIRBNB_DATA_ANALYSIS
🏠 Airbnb Data Analysis
📌 Project Overview
This project explores and analyzes Airbnb listing data to uncover trends in pricing, availability, and neighborhood patterns. 
The goal is to understand factors that influence Airbnb rentals and to extract insights that can help both hosts and travelers make better decisions.

📊 Dataset Description
Source: Airbnb Open Data
File: airbnb_raw_data.csv.gz

Key Features:
id: Listing ID
name: Title of the listing
host_id: Unique ID of the host
neighbourhood: Location of the property
room_type: Type of room (Entire home, Private room, etc.)
price: Price per night (USD)
minimum_nights: Minimum nights required to book
number_of_reviews: Total reviews received
availability_365: Availability throughout the year

⚙️ Tools & Technologies
Programming Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn
Platform: Jupyter Notebook

🔎 Analysis Performed
Data Cleaning
Handled missing values and duplicates
Removed extreme outliers in price and minimum nights
Exploratory Data Analysis (EDA)
Distribution of prices across neighborhoods
Room type vs. pricing insights
Availability patterns and host activity
Review counts and their relationship with listings
Visualizations
Bar charts for neighborhood and room type distribution
Boxplots for price comparisons
Correlation heatmap of numerical features

📈 Key Insights
Price Distribution: Most listings are affordable, but a few extreme outliers heavily skew the average price.
Neighborhood Trends: Central neighborhoods generally have higher prices, reflecting demand and location advantages.
Room Type: Entire homes/apartments dominate the market but private rooms provide more budget-friendly options.
Host Behavior: A small percentage of hosts manage a large number of listings, indicating professional hosting.

🚀 Future Scope
Build a predictive model to estimate listing prices based on features.
Use clustering to group neighborhoods by pricing and availability.
Apply sentiment analysis on listing reviews for deeper insights.
Add interactive dashboards using Plotly or Tableau for better visualization.

🏆 Conclusion
This project provides a detailed exploration of Airbnb listings data, highlighting how location, room type, and host activity affect pricing and availability. 
By extending this project into predictive modeling and interactive dashboards, it can evolve into a powerful decision-making tool for both Airbnb hosts and guests.
