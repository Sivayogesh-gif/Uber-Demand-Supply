Uber Supply-Demand Gap Analysis
📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on Uber ride request data to identify patterns in demand vs. supply, particularly during peak hours. The goal is to understand key operational challenges such as driver shortages, high cancellation rates, and unfulfilled requests, and to provide actionable business recommendations for improving service efficiency.

🎯 Business Problem
Uber often faces supply-demand mismatches, especially during peak hours. Riders experience delays or cancellations due to a lack of available drivers, impacting customer satisfaction and company revenue. This project aims to:

Analyze ride request patterns.

Identify peak demand hours and problem zones.

Suggest strategies to minimize the supply-demand gap.

📂 Dataset Details
File Name: Uber Request Data.csv

Rows: ~6,769

Columns: 6

Key Features:

Request id: Unique identifier for each request.

Request timestamp: Time when the ride was requested.

Drop timestamp: Time when the trip ended (if completed).

Pickup point: City or Airport.

Status: Trip status (Completed / Canceled / No Cars Available).

📌 Steps Followed
1. Data Cleaning
Converted timestamps to datetime format.

Extracted new features: Request Hour, Request Day.

Handled missing values in Drop timestamp.

Removed duplicate records.

2. Data Exploration
Checked for missing/null values.

Explored data distribution and unique values for each column.

3. Data Visualization
Univariate Analysis: Distribution of ride statuses, pickup points.

Bivariate Analysis: Status vs. Hour, Pickup Point vs. Status.

Multivariate Analysis: Heatmaps showing demand and supply gaps.

📊 Key Insights
High Demand Hours: 7 AM–10 AM and 5 PM–9 PM.

Supply Gap: City pickups during peak hours experience the highest gap.

Airport Trips: Generally well-served compared to city trips.

Status Breakdown: Large number of requests show No Cars Available or Canceled during rush hours.

✅ Business Recommendations
Incentivize Drivers: Provide bonuses during peak hours to increase supply.

Predictive Allocation: Use demand forecasting to position drivers in high-demand areas.

Real-Time Monitoring: Implement surge notifications and driver alerts.

Customer Communication: Provide estimated wait times and alternate options during shortages.

🛠️ Technologies Used
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

Environment: Google Colab / Jupyter Notebook