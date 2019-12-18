# Bankrupt-prediction-LG-PCA-

Load bankruptcy data from UCI :  5thYear.arff 

Feature explanation: https://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data

The data contains financial rates from 5th year of the forecasting period and corresponding class label that indicates bankruptcy status after 1 year. The data contains 5910 instances (financial statements), 410 represents bankrupted companies, 5500 firms that did not bankrupt in the forecasting period.

Logistic Regression Model
=================

#### For imbalanced data, we can tuned class weight=’balanced’ and sample_weight to train the model and find the best parameter that gives the best metric (BER/F score etc.)


PCA
=======

#### Compressed the data from 64 dimensions to 30 dimensions to get the minimum BER.

#### PCA is useful in large dimension data and prevent overfitting. 



