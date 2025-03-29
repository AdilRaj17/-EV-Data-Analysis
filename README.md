Electric Vehicle Data Analysis

Project Overview

This project analyzes an electric vehicle (EV) population dataset to explore trends, perform data visualization, and build a predictive model for electric range using linear regression.

Dataset

The dataset contains information about various electric vehicles, including:

Make & Model: Manufacturer and model of the EV.

Model Year: Year of manufacturing.

Base MSRP: Manufacturer’s Suggested Retail Price.

Electric Range: The estimated distance the vehicle can travel on a full charge.

County: Registration location of the EV.

CAFV Eligibility: Indicates if the EV qualifies for Clean Alternative Fuel Vehicle incentives.

Objectives

Identify the most common EVs and their distribution.

Analyze the adoption trend of EVs over the years.

Visualize EV distribution by county using heatmaps.

Predict electric range using machine learning (Linear Regression).

Project Files

electric_vehicle_analysis.py: Contains code for data exploration, visualization, and modeling.

Electric_Vehicle_Population_Data.csv: The dataset used for analysis.

README.md: Documentation of the project.

How to Use

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

Run the analysis script:

python electric_vehicle_analysis.py

Results & Insights

The dataset shows an increasing trend in EV adoption.

Certain manufacturers dominate the market, such as Tesla and Nissan.

Counties with strong incentives have higher EV registrations.

The linear regression model predicts electric range based on MSRP, model year, and make.

Future Improvements

Include additional features like battery capacity and efficiency.

Experiment with advanced models like Random Forest or Neural Networks.

Expand dataset to include more recent EV models.
