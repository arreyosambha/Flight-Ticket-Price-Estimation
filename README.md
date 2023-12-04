# Flight-Ticket-Price-Estimation

README.md

Airfare Price Prediction

Overview

This code is designed for predicting airfare prices based on various features like airline, flight details, departure time, stops, arrival time, destination city, class, duration, and days left. The prediction is achieved through a comprehensive pipeline involving data analysis, visualization, model training, evaluation, and stacking/ensemble techniques.

Requirements

Python
Jupyter Notebook
Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, xgboost, catboost, lightgbm
Data

Ensure your dataset (e.g., "clean_Dataset.csv") is in the specified file path.

Code Structure

Data Loading and Analysis
The load_and_analyze_data function reads the dataset, providing insights like the number of observations and missing values.
Data Visualization
plot_visualizations creates visualizations depicting the density and distribution of airfare prices, flight counts by airlines, average price trends concerning days left, and more.
Model Training and Evaluation
Various regression models, including XGBoost, CatBoost, and LightGBM, are trained and evaluated using mean squared error (MSE), mean absolute error (MAE), and R-squared metrics.
Stacking and Blending
The stack_blend_regression function implements a stacking/ensemble technique, blending predictions from multiple models to enhance overall predictive performance.
Prediction Visualization
The final predictions are compared with actual prices through a line plot, visualizing the model's performance based on days left for departure.
How to Use

Install required libraries using pip install -r requirements.txt.
Adjust the file path in the code to your dataset location.
Run the code in a Jupyter Notebook or any Python environment.
