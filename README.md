# Telecommunication Customer Churn Analysis

<b>1. Project Overview</b>
- This project analyzes customer churn in a telecommunications company. The goal is to identify key factors influencing churn and provide actionable insights to improve customer retention.

<b>2. Dataset Description</b>
- Dataset: "churn_clean.csv"
- Key Features:
  

 <b>3. Problem Statement</b>
 - Customer churn significantly impacts revenue. By gaining insights into key factors and identifying customer segments at risk, the organization can use churn analysis not only to enhance services for current customers but also to foster long-term business growth.

<b>4. Data Cleaning & Preprocessing</b>
- Handling missing values and duplicates
- Identify outliers
- Encoding categorical variables

<b>5. Exploratory Data Analysis (EDA)</b>
- Identify distribution of each variable (Univariate)
- Analyze the relationship between churn vs. non-churn customers across each predictor (Bivariate)

<b>6. Model Development</b>
- Machine learning model used: Logistic Regression
- Performance metrics: Accuracy, Precision, F1 Score

<b>7. Key Findings & Business Recommendations</b>
- Key variables:
  - `Gender`: Customer self-identification as male, female, or nonbinary
  - `Tenure`: Number of months the customer has stayed with the provider
  - `Techie`: Whether the customer considers themselves technically inclined
  - `Multiple`: Whether the customer has multiple lines
  - `OnlineBackup`: Whether the customer uses an online backup add-on
  - `TechSupport`: Whether the customer uses a technical support service
  - `StreamingTV`: Whether the customer has TV streaming add-on
  - `StreamingMovies`: Whether the customer has movie streaming add-on
  - `InternetService`: Customer's internet service provider
  - `Contract`: Contract term of the customer
  - `PaymentMethod`: Customer's payment method
- Confusion Matrix:

- Performance Metrics:
  - Accuracy: 0.8996
  - Precision: 0.8275
  - F1 Score: 0.8133
