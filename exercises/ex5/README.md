# Exercise 5 - Data Quality Management

With this exercise you explore some of the features for master data quality management offered by SAP Master Data Governance, cloud edition (MDG Cloud). You will see how data quality rules for validation of master data are managed and how you can control their usage in master data processes. You will use the Evaluation Results app to analyze the results of a data quality evaluation and see how you can fix detected errors.

## Prerequisites

You have logged on to the tenant dedicated to your group. Please verify that your group’s number fits to the URL displayed in the browser.

You created several business partners in the previous exercise and changed the search term of several business partners to the value ABC. You can also perform this exercise without completing the previous exercises. However, there will be fewer business partners with erroneous data than in the screenshots of the exercises.

## Instructions

This exercise is split in 8 parts. It is required to perform each step after the other.

### Step 1: Define a validation rule for search terms

Launch the app Validation Rules and create a rule to check if the values for search term 1 and search term 2 are equal. Equal values should be considered as an error.

### Step 2: Implement the validation rule with BRFplus

For complex rules it might be required to involve an expert for rule implementation. For this simple rule, you also assume this role and continue by implementing the expressions in BRFplus.

### Step 3: Approve the validation rule for usage

You act again as the rule owner with the task to confirm the correct implementation of the rule and approve the rule for usage in the enabled usages.

### Step 4: Perform a data quality evaluation and analyze the results.

Evaluate the data quality of the business partners in your tenant by scheduling a job for a single and immediate execution.

### Step 5: Compare data quality by country

Now, with the evaluation results available, compare data quality per country of the business partner.

### Step 6: Correct the erroneous business partners

Change the filters to display only business partners with errors. Then use mass processing to fix the issues.

### Step 7: Refresh the evaluation results

Evaluation results are also visible in the Validation Rules app. Check the current status and perform another data quality evaluation to see the changes.

### Step 8: See the effect of the rule in central governance

Since you also enabled the usage Check in Central Governance, let’s now see the effect in the app Manage Business Partners – Central Governance.

## Step-by-Step Description and Solution

Follow [DA160-Exercise-5.pdf](./supplements/DA160-Exercise-5.pdf) for a step-by-step description.

## Summary

Congratulations! You created a validation rule in SAP Master Data Governance, cloud edition and used it to evaluate the quality of master data. You also corrected the errors that were found and saw some of the features to enhance and keep a great level of data quality!

This was the last exercise of this session. Thank you for attending!
