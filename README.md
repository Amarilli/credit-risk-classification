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
