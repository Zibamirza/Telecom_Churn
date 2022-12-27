# Predicting Telecom Churn
The object of this challenge is to predict customer behavior to develop focused customer retention programs – to predict if given certain information like demographic, nature of the contract and relationship with the company, can we predict if this customer will churn or not 
Here we focus on recall – since we want to minimize false negatives – so the model does not predict that a customer will not churn when the future data shows that the customer has left the company 
Let is now understand what churn means  - churn is a measure of the number of customers who have left the company for another service provider. Reasons for churn could be internal like price, produc quality, state of the business (eg. If resources are directed at sales rather than service) etc. or they could be external like offers that the competition makes 
Our approach towards predicting customer churn was the following:
  - Understanding the data and performing a small amount of clean up 
  - Visualizing the data 
  - Finding correlation between features 
  - Understand the data imbalance between churn and no churn so the model is well represented
From here we tried to find out preliminary model using auto ML and low code ML with Pycaret 
We decided on three models to explore - Random Forest and Logistic Regression
