# Predicting Customer Churn in a Telecom Industry
This project aims to predict customer churn in the telecom industry using machine learning techniques. The goal is to build a model that can accurately identify customers who are likely to churn, enabling the company to take proactive measures to retain them. 

## Project Overview
1. Dataset: The dataset used in this project contains information about telecom customers, including various features such as demographics, usage patterns, and customer service data.

2. Data Preprocessing: The dataset underwent preprocessing steps such as handling missing values, encoding categorical variables, and scaling numerical features. Additionally, a stratified train-test split was performed to ensure balanced class distribution.

3. Model Selection and Pipeline: The project utilized the XGBoost algorithm as the predictive model. A pipeline was constructed, incorporating preprocessing steps and feature selection using SelectKBest.

4. Evaluation Metrics: The model's performance was assessed using several evaluation metrics, including ROC-AUC score, precision, recall, F1 score, and F2 score. These metrics provide insights into the model's ability to correctly classify churn and non-churn customers.

5. Hyperparameter Tuning: Hyperparameter tuning was performed using Optuna, an automatic hyperparameter optimization framework. This step aimed to find the best combination of hyperparameters for the XGBoost model, further improving its performance.

## Results
After preprocessing, model training, and hyperparameter tuning, the following performance metrics were achieved on the test set:

- ROC AUC Score: 0.7645005037588158
- Recall Score: 0.8101604278074866
- Accuracy Score: 0.7430801987224982
- Precision Score: 0.51010101010101
- F1 Score: 0.6260330578512396
- F2 Score: 0.7248803827751197

Classification Report:
               precision    recall  f1-score   support

           0       0.91      0.72      0.80      1035
           1       0.51      0.81      0.63       374

    accuracy                           0.74      1409
   macro avg       0.71      0.76      0.72      1409
weighted avg       0.81      0.74      0.76      1409


These results indicate that the XGBoost model performs reasonably well in predicting customer churn in the telecom industry.
**I also exported the trained Machine Learning models so it can be reused for future preductions on new data or even be applied to another problem without retraining the model from scratch.**

## Usage
To replicate and extend this project, follow these steps:
1. Clone the repository:
`git clone` https://github.com/Abdulraqib20/telecom-churn-prediction.git
2. Install the required dependencies:
`pip install -r requirements.txt`
 
 ## Conclusion
Customer churn prediction is a critical task for businesses in the telecom industry. By accurately identifying customers at risk of churning, companies can implement targeted retention strategies to reduce customer attrition and improve customer satisfaction.

This project demonstrates the application of machine learning techniques, specifically XGBoost, for customer churn prediction. The optimized model achieved promising results, providing insights into customer behavior and facilitating data-driven decision-making.
