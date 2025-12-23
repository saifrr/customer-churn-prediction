# Customer Churn Prediction Using Machine Learning

## Problem Statement
Customer churn is a major challenge for subscription-based businesses, as losing customers directly impacts revenue.  
The goal of this project is to predict whether a customer is likely to churn using historical telecom data and machine learning techniques.

## Dataset
This project uses the **Telco Customer Churn Dataset**, which contains customer demographic information, subscribed services, and billing details.

- Rows: ~7,000 customers  
- Target variable: `Churn` (Yes / No)

## Tools & Technologies
- Python  
- Pandas, NumPy (data processing)  
- Scikit-learn (machine learning models & evaluation)  
- Matplotlib, Seaborn (visualization)

## Approach
1. Loaded and explored the dataset  
2. Cleaned the data and handled missing values  
3. Encoded categorical features into numerical form  
4. Split the data into training and testing sets  
5. Trained a baseline **Logistic Regression** model  
6. Trained a **Random Forest** model for improved performance  
7. Evaluated models using accuracy and confusion matrix  
8. Analyzed feature importance to understand key churn factors  

## Models Used
- **Logistic Regression** (baseline model for binary classification)  
- **Random Forest Classifier** (final model due to better performance)

## Evaluation Metrics
- Accuracy  
- Confusion Matrix  
- Precision and Recall  

> In churn prediction, minimizing false negatives is important because failing to identify churn customers can lead to revenue loss.

## Results
- Random Forest outperformed Logistic Regression in terms of accuracy and recall  
- Important churn factors included contract type, tenure, and monthly charges  

## Conclusion
The project demonstrates how machine learning can be used to predict customer churn and provide actionable business insights.  
Random Forest proved to be more effective due to its ability to capture complex patterns in customer behavior.

## Future Improvements
- Hyperparameter tuning  
- Handling class imbalance  
- Deploying the model using a web interface (e.g., Streamlit)

