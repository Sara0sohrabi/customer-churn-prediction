# customer-churn-prediction
Customer Churn Prediction Platform using Machine Learning, Data Mining, Explainable AI, and Business Intelligence to identify customers at risk of leaving and improve retention strategies.
Customer Churn Prediction Platform
Overview

Customer Churn Prediction Platform is an end-to-end analytics solution designed to identify customers who are likely to stop using products or services.

The platform leverages Machine Learning, Data Mining, Data Warehouse, and Business Intelligence technologies to proactively detect churn risk and support customer retention strategies.

Business Problem

Customer acquisition costs are significantly higher than customer retention costs.

Organizations often lose valuable customers without understanding the underlying reasons.

This project helps businesses:

Predict customer churn
Identify churn drivers
Improve retention rates
Optimize marketing campaigns
Increase customer lifetime value
Architecture
Data Sources
      ↓
SQL Server
      ↓
ETL & Data Integration
      ↓
Data Cleaning & EDA
      ↓
Feature Engineering
      ↓
Churn Prediction Models
      ↓
Explainable AI (SHAP)
      ↓
Customer Risk Scoring
      ↓
Results Database
      ↓
REST APIs
      ↓
BI Dashboard
Data Sources

The model can use:

Customer Information
Age
Gender
Location
Occupation
Insurance Information
Policy Count
Premium Amount
Policy Duration
Product Type
Claims Information
Claim Frequency
Claim Amount
Loss Ratio
Customer Behavior
Renewal History
Payment Delays
Customer Complaints
Digital Engagement
Key Features
Data Quality Assessment
Missing Value Analysis
Duplicate Detection
Outlier Detection
Data Validation
Exploratory Data Analysis
Churn Distribution
Customer Behavior Analysis
Correlation Analysis
Trend Analysis
Feature Engineering

Generated Features:

Customer Lifetime
Renewal Rate
Average Premium
Claim Ratio
Payment Behavior
Customer Activity Score
Machine Learning Models

Implemented Models:

Logistic Regression
Decision Tree
Random Forest
XGBoost
Gradient Boosting

Future Models:

Deep Learning
AutoML
Ensemble Models
Explainable AI

SHAP values are used to explain:

Why a customer is likely to churn
Most influential variables
Customer-level risk factors
Model transparency
Workflow
Step 1 – Data Collection

Collect customer, policy, claims, and transaction data.

Step 2 – Data Cleaning
Handle missing values
Remove duplicates
Standardize variables
Step 3 – EDA

Analyze:

Churn trends
Customer behavior
Product performance
Step 4 – Feature Engineering

Create predictive variables related to customer engagement and loyalty.

Step 5 – Model Training

Train machine learning models using historical customer data.

Step 6 – Churn Prediction

Predict probability of churn for each customer.

Step 7 – Risk Classification

Classify customers:

Low Risk
Medium Risk
High Risk
Critical Risk
Step 8 – Dashboard Reporting

Visualize churn KPIs and customer retention metrics.

Insurance Use Cases
Renewal Prediction

Predict customers unlikely to renew policies.

Retention Campaigns

Identify customers requiring intervention.

Customer Loyalty Analysis

Measure loyalty and retention patterns.

Agent Performance Analysis

Analyze customer retention by agent.

Cross-Sell Opportunities

Identify customers suitable for additional products.

KPIs
Churn Rate
Retention Rate
Renewal Rate
Customer Lifetime Value (CLV)
Average Premium
Loss Ratio
Retention Campaign Success Rate
Technology Stack
Programming
Python
Data Processing
Pandas
NumPy
Machine Learning
Scikit-Learn
XGBoost
Explainable AI
SHAP
Database
SQL Server
Analytics
Data Warehouse
ETL
OLAP
API
Flask
Visualization
Power BI
Streamlit
Business Value
Increased Customer Retention
Reduced Churn Rate
Improved Customer Experience
Higher Customer Lifetime Value
Better Marketing ROI
Data-Driven Decision Making
Future Roadmap
Real-Time Churn Prediction
Customer Recommendation Engine
Next Best Offer
AI Retention Assistant
Generative AI Insights
Author
## Architecture

![Customer Churn Prediction Architecture](customer_churn_prediction_architecture.png)

Sara Sohrabi

Data Science | Machine Learning | Insurance Analytics | BI & Data Warehouse
