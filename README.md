# Credit-Card-Default-Prediction-Model-using-Decision-Trees


Data
--
Data was sourced from the UCI Machine Learning Repository
https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients

Executive Summary
--

Aim is to forecast a customer defaulting on their credit card payment. Through this model, credit card companies would understand the customers who are more likely to default in their payments and make strategies to reduce/encounter those defaults. Moreover, banks and financial institutions can use this model to target their ideal credit card customer by analyzing the potential customer profiles.


In this data set, we have 24 attributes which include - personal information (like gender, education, marital status & age) and payment information of customers (like limit balance, number of delays in months and bill amount & previous payments from August to September).


Firstly, the data is cleaned by performing basic data treatment procedures like checks for outliers and missing values, etc. Further, new variables were created by feature engineering method which reduces the complexity from 13 variables (limit balance, bill amount & previous payments for 6 months) to 2 variables (credit utilization & remaining payment percentage) and they retain the same knowledge for the model. The bivariate analysis between independent variables and target variable also helped in identifying some interesting relations.


Finally, all different modeling techniques are performed on the cleaned data. After all the analysis and comparisons, Decision tree model was finalized which gave the best output with the maximum accuracy of 1 and lowest misclassification rate on the test dataset.

Conclusion
--
High positive co-relation was found between customers utilizing a higher portion of their credit limit with customers defaulting on their credit card. Level of education was also found to be inversely proportional to the default in payment.
Based on the findings, appropriate recommendations were made that can be used by credit card companies to reduce defaults or keep it in control.

