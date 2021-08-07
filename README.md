# Neural_Network_Charity_Analysis

## Overview of Analysis
The purpose of this analysis was to measure the success of charitable donations using deep learning neural networks. This was done with TensorFlow and Python.

## Results
- The IS_SUCCESSFUL columnrefers to whether or not the referred donation was used effectively. This is the target variable for the deep learing model.
- Features: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.
- The EIN and Name columns were removed from the dataset because they are identifaction information.

## Summary
This model did not reach it's target accurcay of 75%. Since the target is a binary classification, we recommend using a supervised machine learning model. This will look have higher accuracy and perform better in future analysis.
