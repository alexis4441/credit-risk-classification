# credit-risk-classification

# Background
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

# Instructions
The instructions for this Challenge are divided into the following subsections:
- Split the Data into Training and Testing Sets
- Create a Logistic Regression Model with the Original Data
- Write a Credit Risk Analysis Report

## Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:
1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
3. Split the data into training and testing datasets by using train_test_split.

## Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:
1. Fit a logistic regression model by using the training data (X_train and y_train).
2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
3. Evaluate the model’s performance by doing the following:
  - Generate a confusion matrix.
  - Print the classification report.
4. Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

## Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.
Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:
1. An overview of the analysis: Explain the purpose of this analysis.
2. The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
3. A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

# Credit Risk Analysis Report
1. Explain the purpose of the analysis.
   - The purpose of this analysis is to generate a model that will help predict the accuracy of a healthy loan or a high-risk loan. Using a logistic regression model in this analysis was beneficial in predicting the accuracy for credit risk classifications.
2. Explain what financial information the data was on, and what you needed to predict.
   - The financial information that the data included were loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and the total debt. Using this data, we needed to predict the high-risk loan.
3. Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
   - The variables we were trying to predict was the loan status, which helped in determining the results for the healthy loan or high-risk loans. After performing the analysis, there was a high accuracy.
4. Describe the stages of the machine learning process you went through as part of this analysis.
   - The stages of machine learning performed in this analysis included, creating a DataFrame and cleaning it, splitting the data into training and testing datasets with 'train_test_split', creating a logistic regression model using the training data and developing predictions, and concluding with evaluating the model's performance.
5. Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
   - The method we used was logistic regression to identify the predictions for healthy loans and high-risk.
  
Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
  1. Accuracy: 99%
  2. Precision: 92%
  3. Recall: 97%
 
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
  - Using a Logistic Regression model seemed to perform best as the outcome had very high results and accuracy. I would recommend using this method as it was simple to perform, as well as analyze the results. 
