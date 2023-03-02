# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* This analysis identifies the creditworthiness of borrowers, by using various techniques to train and   
  evaluate models with imbalanced classes.
* This data covers the creditworthiness of borrowers, and looks at key information points such as debt-to-income, loan size, and total 
  debt.

* Some of the key prediction variables, include 'loan status', the 'value counts' which scores the data for its balance.
* This model uses the standard phases of machine learning which are model-fit-predict-evaluate.
* The following methods were used to analyze the data, LogisticRegression, and RandomOverSampler, .

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
 
 Balanced accurcy score: 0.95 *(detects true positives and true negatives)*

                Percision   Recall    
          0       1.00      0.99 
          1       0.85      0.91  

*Percision detecting the users that were actually going to default*

*Recall correctly clasified a higher percentage of the truly defaulting borrowers*

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

Balanced accurcy score: 0.99 *(detects true positives and true negatives)*

                Percision   Recall    
            0       1.00      0.99     
            1       0.84      0.99

*Percision detecting the users that were actually going to default*

*Recall correctly clasified a higher percentage of the truly defaulting borrowers*
## Summary

the Machine learning model 2 seems to overall, be a better fit than Machine learning model 1.
