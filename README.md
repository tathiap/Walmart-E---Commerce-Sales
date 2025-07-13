# Walmart E-Commerce Customer Behavior Analysis

This project explores Walmart's e-commerce customer data to uncover insights, drive strategic decision-making, and support predictive capabilities. Using a structured pipeline—from data cleaning and exploratory analysis to A/B testing, segmentation, forecasting, and Bayesian modeling—we analyze patterns that inform customer strategy and future planning.

## Project Goals

- Understand customer purchasing behavior
- Evaluate treatment effects through A/B testing
- Segment users into meaningful clusters
- Forecast revenue trends
- Predict high-value customers using logistic and Bayesian models

## Project Structure

1. **Exploratory Data Analysis (EDA)**  
   Visualize distributions, detect outliers, and understand purchase trends.

2. **User-Level Aggregation**  
   Derive behavioral features per user such as total spend, average purchase, and cart completion.

3. **K-Means Segmentation**  
   Group users into segments like "Power Shoppers" and "Window Shoppers" based on behavioral features.

4. **A/B Testing**  
   Evaluate differences in purchase behavior between control and test groups, including segment-based testing.

5. **Cohort Analysis** *(optional/expandable)*  
   Examine retention and revenue over time by acquisition cohort.

6. **Forecasting & Time Series**  
   Predict future revenue using Prophet and ARIMA.

7. **Predictive & Probabilistic Modeling**  
   Classify high spenders using logistic regression and PyMC-based Bayesian inference.

## Tools & Libraries

- **Python** (pandas, numpy, matplotlib, seaborn)
- **scikit-learn** (clustering, modeling)
- **Prophet** (forecasting)
- **PyMC** + **ArviZ** (Bayesian modeling)
- **Statsmodels** (statistical testing)

## Key Results

- Identified 4 clear customer segments with distinct purchasing patterns.
- A/B testing showed no significant uplift, with effect size near zero.
- Segment-based A/B testing revealed differences in segment behavior.
- Forecasting models provided reliable future revenue predictions.
- Logistic regression achieved >99% accuracy in predicting high spenders.
- Bayesian modeling added interpretable uncertainty to predictions.

