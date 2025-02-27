# Customer Churn Prediction 📊 

## Overview 📌
Customer churn is defined as when customers or subscribers discontinue doing business with a firm or service. Customer churn prediction is a crucial task for businesses to identify customers who are likely to leave and take preventive actions. 
Customers in the telecom industry can choose from a variety of service providers and actively switch from one to the next. The telecommunications business has an annual churn rate of 15-25 percent in this highly competitive market. Customer churn is a critical metric because it is much less expensive to retain existing customers than it is to acquire new customers. 

## Objectives 📌
* Finding the % of Churn Customers and customers that keep in with the active services.
* Analysing the data in terms of various features responsible for customer Churn
* Finding a most suited machine learning model for correct classification of Churn and non churn customers.

## Dataset 📂
[Telco Custpmer Churn](https://www.kaggle.com/code/bhartiprasad17/customer-churn-prediction/data)

### The data set includes information about:
* Customers who left within the last month – the column is called Churn
* Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
* Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
* Demographic info about customers – gender, age range, and if they have partners and dependents
* 
## Features 🚀
📌 Data Preprocessing & Feature Engineering: Handling missing values, encoding categorical variables, and scaling features.

📊 Exploratory Data Analysis (EDA): Visualizing trends, correlations, and distributions in customer data.

🤖 Model Training: Implementation of Decision Tree and Random Forest models for predicting customer churn.

📈 Performance Evaluation: Assessing models using metrics like Accuracy, Precision, Recall, and F1-score.

🔧 Hyperparameter Tuning: Optimizing models for improved performance.

📊 Model Interpretability: Analyzing feature importance and decision rules.

## Few glimpses of EDA 📊 
![Untitled design (1)](https://github.com/user-attachments/assets/8f287577-f612-4634-a9ec-28864bdeddc2)
 1. Churn distribution:26.6 % of customers switched to another firm.
 2. There is negligible difference in customer percentage who chnaged the service provider. Both genders behaved in similar fashion when it comes to migrating to another service provider.
 3. About 75% of customer with Month-to-Month Contract opted to move out as compared to 13% of customrs with One Year Contract and 3% with Two Year Contract.
 4. Major customers who moved out were having Electronic Check as Payment Method. Customers who opted for Credit-Card automatic transfer or Bank Automatic Transfer and Mailed Check as Payment Method were less likely to move out.
 5. Several customers choose the Fiber optic service and it's also evident that the customers who use Fiber optic have high churn rate, this might suggest a dissatisfaction with this type of internet service. Customers having DSL service are majority in number and have less churn rate compared to Fibre optic service.
 6. Most customers churn due to lack of online security.
 7. Most of the senior citizens churn; the number of senior citizens are very less in over all customer base.
 8. Customers with higher Monthly Charges are also more likely to churn. New customers are more likely to churn.

## Final Model: Voting Classifier
We have selected Gradient boosting, Logistic Regression, and Adaboost for our Voting Classifier.
![Screenshot (98)](https://github.com/user-attachments/assets/97992670-828d-43a2-9270-718ddf41ff4c)
From the confusion matrix we can see that: There are total 1383+166=1549 actual non-churn values and the algorithm predicts 1400 of them as non churn and 149 of them as churn. While there are 280+280=561 actual churn values and the algorithm predicts 280 of them as non churn values and 281 of them as churn values.

## Contact 📧
If you have any feedback, please reach out at majumdersrijita2002@gmail.com.

