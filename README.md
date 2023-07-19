# Loan-Payment-Classifier
Building a neural network classifier to classify a loan applicant either as someone who would pay back their loan or not based on 20+ parameters and over 300,000 applicants.

# Dataset:
LendingClub dataset from Kaggle: https://www.kaggle.com/wordsforthewise/lending-club 

## Possible changes we can implement on model to optimize further:
- Impute missing mort_acc values using KNNImpute and utilize a correlation table to find what variable mort_acc correlates with the mmost and determine a way to impute
- Scale data using MinMaxScaler and other different ways
- Change up model i.e. hiddeln layers, activation functions, dropout rates etc.
