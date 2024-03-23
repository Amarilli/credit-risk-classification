# Credit Risk Classification

## Split the Data into Training and Testing Sets

I read the `lending_data.csv` data from the `Resources` folder into a Pandas `DataFrame`.

I created the labels set (y) from the `loan_status` column and the features (X) DataFrame from the remaining columns.

I split the data into training and testing datasets by using `train_test_split`.

## Create a Logistic Regression Model with the Original Data

I fitted a logistic regression model using the training data (X_train and y_train).

Using the testing feature data (X_test) and the fitted model, I saved the predictions for the testing data labels.

I evaluated the model’s performance by:

- generating a confusion matrix

- printing the classification report

## Write a Credit Risk Analysis Report

### Overview of the analysis

This analysis aims to create and test a data model that predicts borrowers' creditworthiness using a dataset of historical lending activity from a peer-to-peer lending services company. The model will be developed and evaluated using machine learning techniques to assist lenders in making more informed decisions when evaluating loan applications.

### Results 

The logistic regression model exhibits exceptional performance in accurately predicting healthy loans. 
- a precision score of 1.00, 
- recall score of 0.99, 
- f1-score of 1.00 

The results confirm the reliability and confidence the machine learning model can instill in users.

While the model performs well, it shows a noticeable decline in identifying high-risk loans:
- precision score of 85% 
- recall score of 91%. 

This suggests that the model's ability to classify high-risk loans is weaker than its performance with healthy loans. This discrepancy is likely due to the data skew, with only about 3 percent of the sample falling into the high-risk loans category.

Overall, the accuracy score is 99%.

### Summary and conclusions

Due to its accuracy, the machine learning model is highly recommended for both healthy and high-risk loans.


.
