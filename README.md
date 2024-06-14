Munich Housing Price Analysis
Overview
This project analyzes housing rental prices per square meter (qm²) in Munich using machine learning techniques. It preprocesses the rental data, explores correlations, builds a predictive model, and evaluates its performance.
Steps and Features
Data Preprocessing:
Cleans and processes the rental data from rents_munich.csv.
Extracts numerical values from 'Price' and 'qm²' columns.
Computes 'price_per_qm' as the ratio of 'Price' to 'qm²'.
Exploratory Data Analysis (EDA):
Computes descriptive statistics and correlation matrix.
Visualizes correlation with heatmaps and distributions.
Model Development:
Uses Gradient Boosting Regressor for predicting 'price_per_qm'.
Conducts hyperparameter tuning using GridSearchCV.
Model Evaluation:
Evaluates model performance using Mean Squared Error (MSE).
Visualizes actual vs predicted prices.
Regional Insights:
Calculates average 'price_per_qm' for different regions.
Identifies the most expensive and cheapest regions.
Future Improvements
Incorporate additional datasets for enriched features.
Optimize model hyperparameters for better predictions.
Improve model interpretability for clearer insights.
Usage
Setup:
Ensure Python and necessary libraries are installed (pandas, numpy, matplotlib, seaborn, scikit-learn, scipy).
Execution:
Run the notebook or script (munich_housing_analysis.ipynb) to execute the analysis.
Dataset:
Place rents_munich.csv in the project directory for data processing.
