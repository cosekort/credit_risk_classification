credit_risk_classification 

Overview of the Analysis
The purpose of this analysis is to take lending data showing high and lower-risk loans to determine overall approval odds of borrowers.The dataset used is historical loan and credit information from a lending company. 
  
  Dataset: 
    Loan Size
    Interest Rate
    Borrowers Income 
    Debt to Income Ratio 
    Number of Accounts
    Derogatory Marks 
    Total Debts 
    Loan Status

Using the dataset, we split the colomns into taining and test models. After splitting the data we were able to fit and predict the model using the Logistic Regression technique.

Results
High Risk results (1)

* Precision- 87%
* Recall- 89%
* Accuracy- 99%
  
Low Risk results (0)

* Precision- 100%
* Recall- 100%
* Accuracy- 99%

Summary
The Logistic Regression model used within the analysis would be a recommended choice for determining approval odds of different risk loans. We know this preforms best as both higher and lower risk accuracy is 99%. It is adviseable to predict high risk loan applicants over low risk applicants as there is less precision and recall. 
