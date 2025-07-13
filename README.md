# CLV_Prediction
# Customer Lifetime Value (CLV) Prediction & Advanced Retail Analysis

## Project Status

Complete | End-to-End | Ready for portfolio/placement showcase

---

## Project Objective

The goal of this project is to predict the Customer Lifetime Value (CLV) for an online retail business.  
By analyzing past purchase history, frequency, and customer behavior, this system helps businesses:
- Identify and retain high-value customers
- Improve customer loyalty and retention
- Optimize marketing spend for maximum ROI
- Increase long-term revenue

---

## Dataset

- Source: [Kaggle - Online Retail Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)  
- Two sheets covering transactions from 2009–2011  
- Includes Invoice, Product, Quantity, Invoice Date, Unit Price, Customer ID, Country

---

## Tech Stack

- Python: pandas, numpy, seaborn, matplotlib, plotly
- Machine Learning: scikit-learn, RandomForestRegressor
- Association Rules: mlxtend
- Dashboard (optional): Streamlit

---

## Key Features

- End-to-End Data Cleaning and EDA:
  - Removed cancelled orders and missing Customer IDs
  - Handled duplicates and outliers
  - Created derived features like Total Price per transaction

- Comprehensive Feature Engineering:
  - RFM: Recency, Frequency, Monetary
  - Extended features: Lifespan, Average Basket Size, Average Order Value, Inter-Purchase Time
  - Time-based features: Weekday, Weekend flag, Hour of purchase

- Predictive Modeling:
  - Regression model using Random Forest to predict CLV
  - Evaluated with RMSE

- Customer Segmentation:
  - Clustering customers into segments based on purchasing behavior

- Cohort Analysis:
  - Tracked customer retention by cohort groups over months

- Market Basket Analysis:
  - Used Apriori algorithm to find product combinations and cross-selling opportunities

- Visualizations:
  - Revenue trends, top customers, product analysis, clusters, cohort heatmaps, and rules table

- Business Recommendations:
  - Target high CLV segments with loyalty offers
  - Upsell to medium CLV segments to increase their value
  - Identify churn-risk customers for win-back strategies
  - Create bundles for products often bought together

---

