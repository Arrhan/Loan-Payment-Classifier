# Loan-Payment-Classifier
Building a neural network classifier to classify a loan applicant either as someone who would pay back their loan or not based on 20+ parameters and over 300,000 applicants.

# Dataset:
LendingClub dataset from Kaggle: https://www.kaggle.com/wordsforthewise/lending-club 

## Possible changes we can implement on model
- Impute missing mort_acc values using KNNImpute and utilize a correlation table to find what variable mort_acc correlates with the mmost and determine a way to impute
- Determine if issue_d variable does contribute to determining loan_status by finding percentages. If correlation present do include in model
