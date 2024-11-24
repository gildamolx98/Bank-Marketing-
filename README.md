# Bank-Marketing

The Bank Marketing dataset contains information about a Portuguese banking institution's direct marketing campaigns. The dataset includes 45,211 instances, representing potential customers who were contacted by the bank to subscribe to a term deposit.

Our goal is to predict whether a customer will subscribe to a term deposit based on their characteristics and the marketing campaign's details.

We started by exploring the dataset, which revealed that the majority of customers did not subscribe to a term deposit. We also found that the age, job, marital status, education, and default variables are highly correlated with the target variable.

We then preprocessed the data by handling missing values, encoding categorical variables, and scaling numerical features.

Next, we split the data into training and testing sets and evaluated several machine learning models, including logistic regression, decision trees, random forests, and gradient boosting,....etc.

The random forest classifier outperformed the other models, achieving an accuracy of 89.4% on the testing set during hyperparameter tuning

*Dataset Description*

The dataset includes the following variables:

- age: The customer's age
- job: The customer's job type
- marital: The customer's marital status
- education: The customer's education level
- default: Whether the customer has defaulted on a loan
- balance: The customer's average yearly balance
- housing: Whether the customer has a housing loan
- loan: Whether the customer has a personal loan
- contact: The contact communication type
- month: The month of the year
- day: The day of the month
- duration: The duration of the contact
- campaign: The number of contacts performed during this campaign
- pdays: The number of days that passed by after the client was last contacted from a previous campaign
- previous: The number of contacts performed before this campaign
- poutcome: The outcome of the previous marketing campaign
- y: Whether the customer subscribed to a term deposit

*Analysis*

The analysis includes the following steps:

1. Data exploration and preprocessing
2. Feature selection and engineering
3. Model evaluation and selection
4. Hyperparameter tuning

*Results*

The random forest classifier achieved an accuracy of 89.4% on the testing set.

Hyperparameter tuning using grid search and random search further improved the model's performance.

*Conclusion*

This analysis demonstrates the effectiveness of machine learning models in predicting customer behavior. The random forest classifier's high accuracy suggests that it can be a valuable tool for banks seeking to improve their marketing campaigns.

Dataset link : https://drive.google.com/file/d/14Ioz_6QIbJPnGtNakboponJLY5FvVgfa/view?usp=sharing
