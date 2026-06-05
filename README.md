Loan Default Prediction System
Project Overview

Financial institutions such as banks and lending companies face significant challenges when borrowers fail to repay their loans. Loan defaults can result in substantial financial losses, increased Non-Performing Assets (NPAs), and poor credit risk management.

Banks collect large volumes of customer information, including income details, employment history, credit scores, loan amounts, and interest rates. However, manually analyzing this data to identify high-risk borrowers is inefficient, time-consuming, and prone to errors.

This project addresses these challenges by applying Exploratory Data Analysis (EDA), Linear Regression Modeling, and Interactive Dashboard Visualization to understand borrower behavior, identify risk factors, and support better lending decisions.

Problem Statement

Loan default is one of the major risks faced by financial institutions. Incorrect loan approval decisions can lead to:

Increased Non-Performing Assets (NPAs)a
Financial losses
Poor credit risk management
Reduced organizational stability

Therefore, there is a need for an automated system that can analyze borrower data, identify patterns, and help detect potential loan defaulters before loan approval.

Objectives

The primary objectives of this project are:

Load and analyze real-world loan data.
Perform data cleaning and preprocessing.
Understand borrower behavior using Exploratory Data Analysis (EDA).
Identify factors influencing loan default.
Perform group-based and relationship analysis.
Build a Linear Regression model.
Evaluate model performance using statistical metrics.
Create interactive dashboards for visualization and decision-making.
Dataset Description
Dataset Source

Kaggle – Lending Club Loan Data

Dataset Features
Column Name	Description
loan_amnt	Loan amount (Target Variable)
term	Loan duration
int_rate	Interest rate
annual_inc	Annual income
emp_length	Employment length
home_ownership	Ownership status
purpose	Loan purpose
grade	Loan grade (Risk level)
credit_score	Derived/Estimated credit score
loan_status	Fully Paid / Default
Technology Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Plotly
Google Colab
System Architecture
1. Data Collection
Load loan dataset from Kaggle.
Understand dataset structure and features.
Inspect data types and attributes.
2. Data Cleaning & Preprocessing
Handle missing values.
Replace missing income values using median.
Remove duplicate records.
Convert categorical variables into usable formats.
Transform loan terms into numeric values.
3. Exploratory Data Analysis (EDA)
Descriptive Statistics

Calculate:

Average loan amount
Average annual income
Interest rate distribution
Data spread and variation
Default Behavior Analysis

Compare:

Fully Paid Loans
Defaulted Loans

Identify:

High-risk borrower groups
Common characteristics of defaulters
4. Group-Based Analysis

Analyze:

Income vs Default
Employment Length vs Default
Loan Purpose vs Default
Home Ownership vs Default

Purpose:

Identify borrower segments with higher risk.
5. Relationship Analysis

Study relationships between:

Loan Amount vs Default
Interest Rate vs Default
Annual Income vs Loan Amount

Purpose:

Discover factors strongly affecting loan repayment behavior.
6. Risk Analysis

Classify borrowers into:

Low Risk
Medium Risk
High Risk

Based on:

Income
Interest Rate
Loan Grade
Credit Score
Loan Status
Predictive Modeling
Linear Regression Model
Independent Variables (X)
annual_inc
int_rate
term
Dependent Variable (y)
loan_amnt
Model Development Steps
Split dataset into training and testing sets (80:20).
Train Linear Regression model.
Predict loan amounts.
Compare predicted and actual values.
Model Evaluation

The model performance is evaluated using:

R² Score

Measures how well the model explains variations in the target variable.

RMSE (Root Mean Squared Error)

Measures prediction error between actual and predicted values.

Lower RMSE indicates better model performance.

Data Visualization

The project includes the following visualizations:

Loan Status Distribution
Bar Chart
Default vs Fully Paid comparison
Income Distribution
Histogram
Loan Amount Distribution
Histogram
Interest Rate Analysis
Scatter Plot
Default Behavior Analysis
Box Plots
Correlation Analysis
Heatmap
Risk Analysis
Risk Category Distribution
Interactive Dashboard

An interactive dashboard is created using Plotly.

Dashboard Components
Income vs Loan Amount
Loan Distribution
Loan Status Comparison
Interest Rate Trends
Interactive Features
Dynamic Charts
Filtering Options
Loan Purpose Analysis
Loan Term Analysis
System Pipeline Flow
Raw Loan Dataset
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Risk & Relationship Analysis
        │
        ▼
Feature Selection
        │
        ▼
Train-Test Split (80:20)
        │
        ▼
Linear Regression Model
        │
        ▼
Prediction & Evaluation
        │
        ▼
Interactive Plotly Dashboard
        │
        ▼
Business Insights & Decision Support
Key Insights
Identify high-risk borrowers.
Understand borrower financial behavior.
Detect factors contributing to loan default.
Improve loan approval strategies.
Support data-driven decision-making.

Visualisation
<img width="1665" height="718" alt="image" src="https://github.com/user-attachments/assets/913ac6f2-9bcf-45e2-b563-346c686c8abb" />
<img width="1657" height="702" alt="image" src="https://github.com/user-attachments/assets/c2bb3726-4768-432e-97ce-7d5617519e1e" />

Conclusion

The Loan Default Prediction System demonstrates how data analytics, predictive modeling, and visualization techniques can assist financial institutions in minimizing loan defaults and improving credit risk management. By combining EDA, Linear Regression, and interactive dashboards, the system provides valuable insights that support safer and more informed lending decisions.
