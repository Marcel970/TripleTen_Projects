# EDA--Instacart

## Overview
* Instacart is a grocery delivery platform where customers can place a grocery order and have it delivered to them, similar to how Uber Eats and Door Dash work. This particular dataset was publicly released by Instacart in 2017 for a Kaggle competition.

## Features
1. Data exploration and preprocessing of 3+ million orders
2. Feature engineering for user, product, and order-level behavior
3. Predictive modeling to recommend next products
4. Visualization of customer trends and market insights

## Problems Addressed
* Instacart wants to better understand customer buying habits so they can optimize marketing strategies, personalize recommendations, and improve the shopping experience.

## Tools Used
* Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost)
* Jupyter Notebook

## Results & Insights
* Identified frequently reordered items such as milk, bananas, and organic produce.
* Observed that weekend orders are significantly higher than weekday orders.
* Trained a predictive model to recommend products with an F1 score of 0.42 (baseline improvement from random recommendations).
* Found that time of day and days since prior order are strong predictors of purchase behavior.

## Roadmap
* Improve model with advanced techniques (LightGBM, deep learning).
* Build a recommendation dashboard for product suggestions.
* Deploy as a web app using Flask or Streamlit.

## Contributors
* Project Lead: Marcellus Riverz
* Dataset provided by Instacart via Kaggle
