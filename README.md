# Predicting Customer Churn in a Telecom Industry
This project aims to predict customer churn in a telecom industry using machine learning techniques. The dataset used for this project contains information on customer demographics, usage patterns, and customer churn status. The goal of this project is to build a model that can accurately predict which customers are at risk of churning so that appropriate retention strategies can be developed.
## Dependencies
This project was developed using Python 3.7. The following Python libraries are required:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- catboost
- xgboost

These dependencies can be installed using the following command: <br>
**pip install -r requirements.txt**

## Usage
To reproduce the results of this project, follow these steps: <br>
### Clone this repository:
git clone https://github.com/Abdulraqib20/telecom-churn-prediction.git <br>
### Install the dependencies:
cd telecom-churn-prediction
pip install -r requirements.txt

## Results
The best performing model was an XGBoost classifier with an accuracy score of 81%. The feature importance analysis showed that the most important predictors of churn were account age, monthly charges, and contract type.

## Conclusion
This project demonstrates the use of machine learning techniques for predicting customer churn in a telecom industry. The best performing model can be used to identify customers who are at risk of churning, allowing for targeted retention strategies to be developed.
