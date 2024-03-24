# Building a model to identify the potential customers who have a higher probability of purchasing a loan.


### Introduction

 This hands-on project focuses on predicting  whether a liability customer will buy personal loans,Which variables are most significant and Which segment of customers should be targeted more.



### Dataset

The dataset has the following columns;
* ID: Customer ID
* Age: Customer’s age in completed years
* Experience: #years of professional experience
* Income: Annual income of the customer (in thousand dollars)
* ZIP Code: Home Address ZIP code.
* Family: the Family size of the customer
* CCAvg: Average spending on credit cards per month (in thousand dollars)
* Education: Education Level. 1: Undergrad; 2: Graduate;3: Advanced/Professional
* Mortgage: Value of house mortgage if any. (in thousand dollars)
* Personal_Loan: Did this customer accept the personal loan offered in the last campaign? (0: No, 1: Yes)
* Securities_Account: Does the customer have securities account with the bank? (0: No, 1: Yes)
* CD_Account: Does the customer have a certificate of deposit (CD) account with the bank? (0: No, 1: Yes)
* Online: Do customers use internet banking facilities? (0: No, 1: Yes)
* CreditCard: Does the customer use a credit card issued by any other Bank (excluding All life Bank)? (0: No, 1: Yes)



### Project Steps

Follow these steps to understand and reproduce the project:

1. Import Libraries: Import necessary libraries and initialize Comet ML.
2. Load and Explore Data: Load dataset and perform exploratory data analysis (EDA).
3. Preprocessing: Prepare the data for analysis - Missing value Treatment, Outlier Detection, Feature Engineering, Prepare data for modelling and check the split.
4. Model Training: Train multiple machine learning models, including Logistic Regression, and Decision Trees
5. Model performance evaluation and improvement: Evaluate the model on appropriate metric.



This project will give you insights into dealing with classification problems, and utilizing pruning techniques to enhance predictive performance.



