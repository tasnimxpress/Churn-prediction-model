# Machine Learning Project - Churn-prediction-model

Problem Statement: Predicting Customer Churn for a Telecom Company

Scenario:
A telecom company wants to reduce customer churn, which occurs when customers switch to another service provider. The company has collected historical data of its customers, including information like gender, senior citizen status, partner, dependents, tenure, phone service, internet service, online security, online backup, device protection, tech support, streaming TV, streaming movies, contract type, paperless billing, payment method, monthly charges, total charges, and churn status (whether the customer churned or not).

Objective:
As part of a personal project, I undertook a customer churn prediction analysis for a telecommunications company. The main goal was to build a predictive model that identifies customers at risk of churning, enabling targeted retention strategies.

Approach:

Data Exploration: Explored the dataset to understand customer demographics and services subscribed, and churn rates on various features.

Model Evaluation: Compared multiple classifiers (Random Forest, Gradient Boosting, KNN) and prioritized recall, precision, and F1 score over accuracy due to data imbalance.

Data Balancing: Implemented SMOTEEN upsampling to address data imbalance and improve model performance.

Model Performance: Reevaluated classifiers after balancing data and identified Random Forest as the best-performing model.

Results:
Random Forest achieved an accuracy of 92% and demonstrated excellent recall, precision, and F1 score for churned customers.
The balanced dataset and the selected model provided more accurate predictions for customer churn.
Significance:

Final Model Deployment:
Once satisfied with the model's performance, deploy it in a production environment to make churn predictions for new incoming customers.
Success Criteria:
The success of the project will be measured based on the accuracy and other relevant metrics achieved by the machine learning model in predicting customer churn. The model should provide accurate predictions, enabling the telecom company to take proactive actions to retain customers and reduce churn rates.

Conclusion:
The project showcases data analysis, machine learning, and problem-solving skills.
It highlights my ability to handle imbalanced datasets and choose appropriate evaluation metrics.
The results demonstrate how predictive modeling can help businesses make informed decisions and improve customer retention strategies.



