# credit-risk-classification  
## Module 20 Challenge

**_Overview of the Analysis_**

In this analysis, I have used a Logistic Regression Model to train and evaluate a model based on loan risk. I then tested the model using a confusion matrix and produced a classification report.

* The purpose of the analysis is to be able to predict if providing a loan could result in the loan being defaulted on.
* The financial information included in the data was the following:
    - Loan size
    - Interest rate
    - Borrowers income
    - Debt to income ratio
    - Number of accounts
    - Derogatory marks
    - Total debt  
* I needed to predict if the loan would default or not.  The data provided included 75,036 health loans and 2,500 high risk of defaulting loans.

**_Results_**

* Machine Learning Model using test data:

![image](https://github.com/wickedwes78/credit-risk-classification/assets/127099343/f76a4c8f-4c01-4a0e-bd3e-873cbdb777c9)


* Machine Learning Model using train data:

![image](https://github.com/wickedwes78/credit-risk-classification/assets/127099343/10037759-4cc3-48ac-b486-30028daf49f5)


**_Summary_**

The Logistic Regression model (LMR) does very well at predicting healthy loans with accuracy, precision and recall close to 100%, if not 100%. The LMR does not perform as well at predicting high-risk loans where it has a precision and recall of slightly less than 90%. This suggests that this model is less able to classify high risk loans than healthy loans. This has potentially arisen due to the data provided, where only 3.3% is in the high risk loans category.

When you review the LMR against the train data, similar predictions are obtained.
