📊 ZARA Sales Analysis & Sales Prediction
📌 Overview

This project performs end-to-end data analysis and machine learning on ZARA product sales data to understand customer demand patterns and predict sales performance. It focuses on how price, promotions, seasonality, and product categories influence sales volume in the fashion retail industry.

The project is implemented entirely in Python using Jupyter Notebook and follows real-world data science workflows used in retail analytics.

🎯 Business Problem

Fashion retailers like ZARA deal with:

Seasonal demand fluctuations

Price sensitivity

Promotion effectiveness

Inventory planning challenges

The objective of this project is to:

Identify key drivers of sales

Predict future sales volume

Support data-driven business decisions

🧠 Objectives

Perform Exploratory Data Analysis (EDA) on ZARA sales data

Identify patterns in sales across seasons and categories

Analyze the impact of price and promotions

Engineer features suitable for machine learning

Build a sales prediction model

Provide insights useful for marketing and inventory teams

📂 Dataset Description

The dataset consists of product-level sales information, including:

Feature	Description
Product ID	Unique identifier for each product
Product Category	Category/type of clothing
Price	Product price
Price Range	Categorized pricing
Promotion	Promotion information
Seasonal	Season tag
Sales Volume	Target variable
Brand	Brand name
SKU	Stock keeping unit
Product Description	Text description

The dataset was cleaned, preprocessed, and transformed before analysis.

🔍 Exploratory Data Analysis (EDA)

EDA was conducted to:

Understand data distribution and structure

Detect missing values and outliers

Analyze sales trends by category and season

Compare promoted vs non-promoted products

Segment products into sales performance categories

Key EDA Techniques:

Descriptive statistics

Bar charts and distribution plots

Category-wise and season-wise comparisons

Promotion impact analysis

⚙️ Data Preprocessing & Feature Engineering

Handled missing and inconsistent values

Converted categorical variables into numerical form

Created:

Promotion flags

Sales categories (Low / Medium / High)

Removed irrelevant or redundant features

Prepared final dataset for modeling

🤖 Machine Learning

Problem Type: Regression

Target Variable: Sales Volume

ML Workflow:

Feature selection

Train-test split

Model training

Prediction on unseen data

Performance evaluation

The model predicts expected sales volume based on product attributes.

📊 Model Evaluation

Compared predicted vs actual sales

Evaluated model performance using regression metrics

Assessed model reliability for business usage

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

📁 Project Structure
ZARA-Sales-Analysis/
│
├── ZARA Sales Analysis & Sales Prediction.ipynb
├── README.md

📈 Key Insights

Promotional products consistently achieve higher sales

Seasonal demand plays a major role in product performance

Certain price ranges perform better across categories

High-selling products show repeatable sales patterns

🚀 Results & Impact

This project demonstrates how data analytics and machine learning can help fashion retailers:

Optimize pricing strategies

Improve promotional planning

Forecast product demand

Reduce inventory risk

🔮 Future Enhancements

Use advanced models (Random Forest, XGBoost)

Implement time-series forecasting

Add customer behavior or review sentiment data

Deploy model using Streamlit or Flask

Create an interactive dashboard

👤 Author

Aditi Petkar
Aspiring Data Scientist

Skills:
Python • Data Analysis • Machine Learning • SQL • Retail Analytics

