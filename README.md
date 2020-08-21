# Credit-Card-Fraud-Detection

## Description-  
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

## Content

The datasets contains transactions made by credit cards. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.  

The Data is Transformed into PCA except Time and Amount.

## Inspiration
Identify fraudulent credit card transactions.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

## Steps Performed-  
1-Exploratory Data Analysis.  
2-Createing Dependent and Independent Features.  
4-Defineing Outlier Detection Parameter for Isolation Forest Algorithm and also for Local Outlier Factor Algorithm.    
3-Fit and Predict the Data.   

Result-  
1. After Comparing the Accuracy Score and Classification Report we can say Isolation Forest Algorithm outperformed Local Outlier Factor Algorithm.  
2. Isolation Forest detected 73 errors versus Local Outlier Factor detecting 97 errors
3. Isolation Forest has a 99.74% more accurate than LOF of 99.65%
4. When comparing error precision & recall for 2 models , the Isolation Forest performed much better than the LOF as we can see that the detection of fraud cases is around 27 % versus LOF detection rate of just 2 %.
