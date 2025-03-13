Project Overview
This project focuses on predicting airline fare prices using various machine learning techniques. By leveraging historical fare data, flight schedules, and market demand, the model identifies key factors that influence fare fluctuations.

📊 Data Sources
The dataset includes:

Flight Fare Data: Historical pricing data for various routes, carriers, and travel dates.
Flight Schedules: Departure and arrival times, flight duration, and carrier details.
Market Demand Data: Scaled demand and market share insights for different routes.
Holiday Information: US public holidays in 2018 to analyze fare variations during peak periods.
🏗️ Project Workflow
Data Preprocessing:

Merging multiple datasets to enrich fare prediction features.
Handling missing values and encoding categorical variables.
Converting time-based features (departure time, travel week, etc.).
Exploratory Data Analysis (EDA):

Understanding fare distribution across different routes and carriers.
Analyzing the impact of departure time, weekdays, and holidays on fares.
Identifying unfulfilled demand for various routes.
Feature Engineering:

Creating new variables such as "days before departure," "weekend indicator," and "peak hour flag."
Target encoding categorical features (e.g., airline carrier, city pairs).
Model Training & Evaluation:

Machine Learning Models:
Random Forest Regressor (Best Performing)
XGBoost & CatBoost (Comparative Analysis)
Linear Regression (Baseline Model)
Evaluation Metrics:
R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Mean Absolute Percentage Error (MAPE).
Insights & Findings:

Flight duration, days before departure, and departure time significantly impact fare prices.
Short-haul flights tend to have higher last-minute fare surges.
There are unfulfilled demand gaps in various sectors, indicating potential market opportunities.
🔥 Key Results
Best Model: Random Forest Regressor with Hyperparameter Tuning (89% R² on Validation Set).
Most Important Features: Days before departure, flight duration, carrier type, and departure time.
Market Analysis: Significant demand gaps exist in certain routes, suggesting scope for new market entrants.
📌 Future Improvements
Hyperparameter tuning for XGBoost & CatBoost with larger parameter space.
Expanding the dataset to multiple years to capture seasonality effects.
Incorporating cookie-based user behavior data for dynamic fare predictions.
