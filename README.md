# Bank GoodCredit – Credit Default Prediction

## Overview

This project focuses on predicting whether a credit card customer is likely to default (30+ days past due).

The objective is to classify customers into:

- 0 → Good Credit History  
- 1 → Default Risk  

The solution is built using machine learning techniques on financial and transactional data.

---

## Business Problem

Banks face significant losses due to credit defaults.  
This project helps in identifying high-risk customers in advance so that better credit decisions can be made.

---

## Dataset

- Total Records: 23,896  
- Total Features: 78  
- Target Variable: `Bad_label`

The dataset contains financial attributes such as:

- Credit limits  
- Balance amounts  
- Payment history  
- Interest rates  
- Enquiry details  
- Transaction-related features  

---

## Model Used

Random Forest Classifier was selected for:

- Handling high-dimensional data  
- Managing non-linear relationships  
- Strong performance on financial risk data  

---

## Key Steps

- Data Cleaning  
- Feature Engineering  
- Encoding of categorical variables  
- Model Training  
- Model Evaluation  
- Model Saving for prediction  

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Joblib  

---

## Result

The model predicts the probability of a customer defaulting and classifies the customer into Good or High Risk category.

---

## Author

Jevin Kanani  
Data Science & Machine Learning
