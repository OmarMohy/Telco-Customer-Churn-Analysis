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
The goal is to analyze all relevant customer data and predict behavior to retain customers.

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
The monthly charges take a moderate range of values from 18 to 120 dollars. It seems that most charges range from 18 to 25 dollars with lower peaks at 50, 70 and 90 dollars.
From the Tenure distribution it seems we have two peaks that indicates we have loyal customers that have remained with company 6 years and newly joined customers with stay of 0-1 month only.                                            

As from scatter distribution of Monthly charge Vs. Tenures and intutively, it appears that loyal customers are with highest monthly charges, and as customer stays for longer period a more trust is bulit therefore higher charges.

Interestingly from the heatmap of Monthly charge Vs. Tenures, it appears that more new customers have higher monthly charges (around 70 dollars) than customers that stayed in company for 2.5-4 years.

Customers whose monthly charges are high are more likely to leave the company. We also can see most of churned customers their monthly charges were high in the range of 80-100 dollars. Therefore, we can infer than customers churn due to high monthly charges.

Customers whose contracts are monthly basis are very likely to leave the company, compared to customers with one year contract and very much less likely for two year contract.
We can see that Senior Citizens monthly charges are much higher han younger citizens. We can also see for senior who churned the range of prices were in 80-100 dollars most of the time than those who didn't churn, had more variability in monthly charges.      

- For no Churn:
* There are more customers using streaming movies services in a month-month contract than one and two years contract due to mostly no internet service.           
- For Churned Customers:
* For monthly contract it most of customers are streaming movies also. But interstingly for longer duration contracts such as one and two years most of them were streaming movies and they churned.                      

So we can infer than either streaming movies is expensive for longer contracts which should be unlikely or the streaming service itself is not likeable to the customers and has a factor even if it is small for them to churn.
