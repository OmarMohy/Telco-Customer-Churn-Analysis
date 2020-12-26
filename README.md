# Telco-Customer-Churn-Analysis
Kaggle dataset to be used in "Udacity Advanced Data Analysis Final Project"

## Table of contents
* [Dataset](#dataset)
* [Context](#context)
* [Features](#features)
* [Setup](#setup)
* [Inspiration](#inspiration)
* [Insights](#insights)

## Dataset
This data is taken from kaggle https://www.kaggle.com/blastchar/telco-customer-churn.
There are 7043 customers in the dataset with 20 features. With 3 numeric features (`Seniorcitizen and Monthlycharges` are **continous**, and `Tenure` is **discrete**), 1 **ordinal** feature (`Contract`) and the rest are **nominal** features.

## Context
"Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs." [IBM Sample Data Sets]

## Features
- **`customerID`**
- **`gender`:** male or female
- **`SeniorCitizen`:** Whether the customer is a senior citizen or not (1, 0) (an elderly person especially : one who has retired)
- **`Partner`:** Whether the customer has a partner or not (Yes, No)
- **`Dependents`:** Whether the customer has dependents or not (Yes, No)
- **`tenure`:** Number of months the customer has stayed with the company
- **`PhoneService`:** Whether the customer has a phone service or not (Yes, No)
- **`MultipleLines`:** Whether the customer has multiple lines or not (Yes, No, No phone service)
- **`InternetService`:** Customer’s internet service provider (DSL, Fiber optic, No)
- **`OnlineSecurity`:** Whether the customer has online security or not (Yes, No, No internet service)
- **`OnlineBackup`:** Whether the customer has online backup or not (Yes, No, No internet service)
- **`DeviceProtection`:** Whether the customer has device protection or not (Yes, No, No internet service)
- **`TechSupport`:** Whether the customer has tech support or not (Yes, No, No internet service)
- **`StreamingTV`:** Whether the customer has streaming TV or not (Yes, No, No internet service)
- **`StreamingMovies`:** Whether the customer has streaming movies or not (Yes, No, No internet service)
- **`Contract`:** The contract term of the customer (Month-to-month, One year, Two year)
- **`PaperlessBilling`:** Whether the customer has paperless billing or not (Yes, No)
- **`PaymentMethod`:** The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- **`MonthlyCharges`:** The amount charged to the customer monthly
- **`TotalCharges`:** The total amount charged to the customer
- **`Churn`:** Whether the customer churned or not (Yes or No)

## Setup
This project uses Python 3 and is designed to be completed through the Jupyter Notebooks IDE. It is highly recommended that you use the Anaconda distribution to install Python, since the distribution includes all necessary Python libraries as well as Jupyter Notebooks. The following libraries are expected to be used in this project:

* NumPy                                         
* pandas                                                   
* Matplotlib                                 
* Seaborn  


## Inspiration
To explore this type of models and learn more about the subject.

                                                

## Insights

