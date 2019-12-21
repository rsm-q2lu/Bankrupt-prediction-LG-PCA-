# Bankrupt prediction-LG & PCA

Load bankruptcy data from UCI :  5thYear.arff 

Feature explanation: https://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data

The data contains financial rates from 5th year of the forecasting period and corresponding class label that indicates bankruptcy status after 1 year. The data contains 5910 instances (financial statements), 410 represents bankrupted companies, 5500 firms that did not bankrupt in the forecasting period.

Logistic Regression Model
--------------

#### For imbalanced data, we can tuned class weight=’balanced’ and sample_weight to train the model and find the best parameter that gives the best metric (BER/F score etc.)


PCA
-------------------

#### Compressed the data from 64 dimensions to 30 dimensions to get the minimum BER.

#### PCA is useful in large dimension data and prevent overfitting. 


# Face Recognition-PCA

PCA
-------------------

#### First, we use PCA to compressed 1000+ features to 10~500 principal components. [br] Then, we used GridSearchCV to find the best estimater of the SVM. [br] Next, we combine each PCA result and the SVM to calculate the F1 score. And to find the best number of pca components. [br] The result showed that 300 components are the best. 

#### Here we the eigenfaces become eigenvectors and we can visulize them. Actually, PCA did a great job in face recognition.


