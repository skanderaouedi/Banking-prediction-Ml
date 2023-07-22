# Banking-prediction-Ml
Data Overview and Dividing Data in train and Test
Applying Logistics Regression Algorithm & Prediction
Applying Random Forest Algorithm & Prediction
K-Fold Cross Validation for improving the output
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. 

The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. 

We use train test split method of sklearn model section library to split the data in training and testing dataset.

Logistic Regression is used in classification problems. It helps getting the binary prediction.

For example: 
Whether the credit card customer will do fraud or not
Whether someone will have the cancer or not
Whether a team will win a match or not

It is an advance classification and regression algorithm that gives much better classification accuracy, also it is used in the regression problems as well for the purpose of forecasting.

It works like a decision tree and create hundreds of trees and prune them to get the quality aggregated output.
K-Fold cross validation helps overcome the issue of overfitting as it exposes the entire data to train and test algorithm while training the alogorithm.

Based on then number we choose for K, it creates k-1 sets for training and the rest one set for testing. And repeat the process k-1 times.

For ex. If the value of k is 10, then it will divide the datset in 10 fold where in first iteration first 9 sets will be used in training and 10th will be used in testing. In the 2nd iteration, first 8 and 10th set will be used in training and 9th set will be used in testing. It repeats this step 9 times.

Model Evaluation Techniques
Classification model is evaluated by two different techniques

Confusion Matrix
ROC Curve
![image](https://github.com/skanderaouedi/Banking-prediction-Ml/assets/50297457/b6ff23e1-02da-42b1-8316-ba8c367630c6)



