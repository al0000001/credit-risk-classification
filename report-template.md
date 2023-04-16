# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:
* -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Explain the purpose of the analysis.
* The purpose of this analysis is to predict the loan status by learning train data.
* -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Explain what financial information the data was on, and what you needed to predict.
* Features include loan_size	interest_rate	borrower_income	debt_to_income	num_of_accounts	derogatory_marks	total_debt
* -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* loan_status, there are two type of outcome. Heath loan and high-risk loan
* -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Describe the stages of the machine learning process you went through as part of this analysis.
* Step 1 split data into test and train 
* Step 2 Fit train data into model
* Step 3 use test data make preditciton
* Step 4 make evaluation
* -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
* Logistic regression is a statistical method for predicting binary outcomes from data.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.
* -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
* Total Accuracy is 99% which means 99% prediction are correct.
* Precision: Out of all high risk loans that model predicted, 85 % actually are high risk loans
* Recall: Out of all actual high risk loans, the model predicted this outcome correctly for 91%
* -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
* Total Accuracy is 99% which means 99% prediction are correct.
* Precision: Out of all high risk loans that model predicted, 84 % actually are high risk loans
* Recall: Out of all actual high risk loans, the model predicted this outcome correctly for 99%
## Summary
* -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Summarise the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* If predicting high risk loans is priority, model 2 will provide better outcome as recall value is higher for model 2 in addition F1 value for model 2 is higher.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
* Yes, as for recall value represents the percentage of correct positive predictions[predicted high risk loan] relative to total acual positives[Actual high risk loans].
* If we positive outcome is important, then model 2 is better.

If you do not recommend any of the models, please justify your reasoning.
