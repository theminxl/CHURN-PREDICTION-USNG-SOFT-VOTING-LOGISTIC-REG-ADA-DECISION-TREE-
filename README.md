# CHURN-PREDICTION-USNG-SOFT-VOTING-LOGISTIC-REG-ADA-DECISION-TREE-
This project develops a predictive modeling pipeline using Logistic Regression and Decision Tree algorithms to analyze customer data and predict telecom customer churn.
Customer Churn Prediction – Predictive Modeling Pipeline

Project Overview: This project builds an end-to-end predictive modeling pipeline to predict telecom customer churn using machine learning techniques. The goal is to identify customers who are likely to leave the service so that companies can implement strategies to improve customer retention.

Business Problem: Customer churn is a major challenge for telecom companies. When customers leave a service provider, it results in revenue loss and increased customer acquisition costs. Predicting churn behavior helps companies take proactive measures such as offering discounts, improving services, or launching retention programs.

Dataset: The project uses the Telco Customer Churn Dataset, which contains information about telecom customers including:
Customer demographics (gender, senior citizen status, dependents)
Service usage (internet service, phone service, streaming services)
Billing information (monthly charges, total charges, payment method)
Contract details
Target variable: Churn (0 = No, 1 = Yes)

Machine Learning Models Used:
The following machine learning algorithms were implemented:
Logistic Regression: A probability-based linear classification algorithm used for binary classification.
Decision Tree: A rule-based classification algorithm that splits the dataset into branches based on feature conditions.
Soft Voting (Ensemble Method): Combines predictions from multiple models by averaging their predicted probabilities to improve overall prediction accuracy.

Project Workflow:
Data collection and dataset loading
Data preprocessing and cleaning
Feature selection and encoding
Feature scaling using StandardScaler
Train-test split of dataset
Model training using Logistic Regression and Decision Tree
Model evaluation using accuracy, confusion matrix, precision, recall, and F1-score
Model comparison and ensemble prediction using soft voting


Evaluation Metrics:
The models were evaluated using the following metrics:
Accuracy Score
Confusion Matrix
Precision
Recall
F1 Score
These metrics help assess how well the models predict customer churn.


Key Insights: Customers with short tenure are more likely to churn.
Customers with higher monthly charges tend to leave the service.
Month-to-month contracts have higher churn rates compared to long-term contracts

Technologies Used: Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook / Google Colab

Conclusion: The predictive modeling pipeline successfully analyzed customer churn patterns using machine learning techniques. Among the implemented models, Logistic Regression showed slightly better performance than the Decision Tree model. The results demonstrate how predictive analytics can help businesses improve customer retention strategies.

Future Improvements: Implement advanced models such as Random Forest or Gradient Boosting
Perform hyperparameter tuning
Deploy the model as a web application
Integrate real-time customer analytics
