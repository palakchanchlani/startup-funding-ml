# Startup Funding Prediction (Machine Learning Project)

This project uses machine learning to analyze startup funding data and identify key parameters that influence funding amounts. The goal is to build a predictive model and extract insights about which industries, cities, and investment types are most strongly associated with higher funding.

## Project Overview

- Dataset: Startup funding records with details like city, industry vertical, investment type, and funding amount.
- Objective: Predict funding amounts and understand which features have the highest impact.
- Approach: Compared multiple regression models and tuned them for best performance.

## Workflow Summary

1. Data cleaning and preprocessing
2. Feature encoding and normalization
3. Model comparison:
   - Linear Regression
   - Decision Tree
   - Random Forest
   - Gradient Boosting
4. Hyperparameter tuning for Random Forest and Gradient Boosting
5. Feature importance analysis using the tuned Random Forest model

## Results

- Best performing model: Random Forest (after tuning)
- Root Mean Squared Error: ~132 million USD
- Top influential features:
  - Industry: Transportation, eCommerce, Online Marketplace
  - City: Bangalore, Gurgaon, Mumbai
  - Investment Type: Seed Funding, Private Equity, Series B–D

## Files Included

- `startup.ipynb`: Full Colab notebook with code and outputs
- `random_forest_model.pkl`: Saved trained Random Forest model
- `feature_importance_chart.png`: Visual showing top influential features (optional)

## Author

Palak Chanchlani  
Final-year B.Tech (Information Technology) student  
Vivekanand Education Society’s Institute of Technology, Mumbai
