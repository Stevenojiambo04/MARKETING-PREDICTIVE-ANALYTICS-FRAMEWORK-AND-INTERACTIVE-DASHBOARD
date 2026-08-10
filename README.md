# MARKETING-PREDICTIVE-ANALYTICS-FRAMEWORK-AND-INTERACTIVE-DASHBOARD

## Project Overview

This project develops a Marketing Predictive Analytics Framework and Interactive Dashboard to support data-driven marketing decision-making.

The project uses customer demographic, purchasing, spending, and campaign response data to analyse customer behaviour and predict customer responses to marketing campaigns.

Python was used for data preprocessing, exploratory data analysis, feature engineering, and machine learning model development. Power BI was used to develop an interactive dashboard for presenting marketing insights and campaign performance.

## Project Objectives

- To analyse customer demographic and purchasing behaviour.
- To preprocess and prepare customer data for analysis.
- To develop machine learning models for predicting campaign responses.
- To evaluate and compare the performance of different classification models.
- To develop an interactive Power BI dashboard for marketing insights.
- To support data-driven marketing decision-making.

## Dataset

The project uses the iFood Marketing Campaign dataset.

The dataset contains information about customer demographics, income, purchasing behaviour, product expenditure, sales channels, and campaign responses.

The `data` folder contains:

- `iFood.xlsx` – Original dataset.
- `ifood_cleaned.csv` – Cleaned and processed dataset used for analysis and dashboard development.

## Machine Learning

Three classification models were developed and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

The models were evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report

Random Forest achieved an accuracy of approximately 82.09% and was selected as the preferred model based on its predictive performance and feature importance analysis.

## Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Power BI
- Microsoft Excel

## Repository Structure

```text
Marketing-Predictive-Analytics-Framework-and-Interactive-Dashboard
README.md
 data
 ── iFood.xlsx
── ifood_cleaned.csv
notebooks
  ── Marketing_Predictive_Analytics.ipynb
 dashboard
   ── MarketingDashboard.pbix

##Dashboard
The Power BI dashboard presents:

Customer demographics
Customer spending patterns
Campaign performance
Campaign response analysis
Key performance indicators
Marketing insights
Machine Learning Prediction

The Random Forest model can also be used to predict the response of a new customer using:

Income
Age
Total Spending
Total Purchases

The prediction returns:

1 – Customer likely to respond
0 – Customer not likely to respond
How to Use
Open the notebook in the notebooks folder using Google Colab or Jupyter Notebook.
Upload the iFood.xlsx dataset when prompted.
Run the notebook cells in order.
The notebook performs data preprocessing, exploratory analysis, model development, evaluation, and new-customer prediction.
Open the Power BI file in the dashboard folder to explore the interactive dashboard.

#Author
Steven Ojiambo

Academic Project

This repository was developed as part of a Diploma Data Science capstone project.
