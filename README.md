# Credit Risk Analysis
## Overview of the Project
### Purpose
We were tasked with predicting credit card risk through the use of machine learning algorithms. Good loans easily outnumber risky loans so we aimed to predict good candidates for loans which would lead to lower default rates. We utilized the RandomOverSampler and SMOTE algorithms to oversample the data. The ClusterCentroids algorithm was used to under sample the data and the SMOTEENN algorithm was used to over- and under sample the data. To predict credit risk with reduced bias, the BalancedRandomForestClassifier and EasyEnsembleClassifier algorithms were used. The performance of these approaches can be compared then evaluated to determine which, if any, algorithm is best to predict credit risk.
## Results
#### RandomOverSampler Algorithm Results
<img width="904" alt="RandomOverSampler" src="https://user-images.githubusercontent.com/103657822/187225023-73558b5f-689c-4f60-a2ad-eb2a8f863dc8.png">
<ul><li> The balanced accuracy score of the RandomOverSampler algorithm was 66.05%. For the high-risk category, there was a precision score of 1% and a recall score of 72%. For the low-risk category, there was a precision score of 100% and a recall score of 60%. </li></ul>

#### SMOTE Algorithm Results
<img width="885" alt="SMOTE" src="https://user-images.githubusercontent.com/103657822/187226122-22a35191-5459-4c75-ac74-b5dd64dba5fe.png">
<ul><li> The balanced accuracy score of the SMOTE algorithm was 66.27%. For the high-risk category, there was a precision score of 1% and a recall score of 63%. For the low-risk category, there was a precision score of 100% and a recall score of 69%. </li></ul>

#### ClusterCentroids Algorithm Results
<img width="908" alt="ClusterCentroids" src="https://user-images.githubusercontent.com/103657822/187226751-487d78fc-e1c5-4835-887b-c42bbd80558f.png">
<ul><li> The balanced accuracy score of the ClusterCentroids algorithm was 54.39%. For the high-risk category, there was a precision score of 1% and a recall score of 69%. For the low-risk category, there was a precision score of 100% and a recall score of 39%. </li></ul>

#### SMOTEENN Algorithm Results
<img width="906" alt="SMOTEENN" src="https://user-images.githubusercontent.com/103657822/187232462-7d0a5078-1556-4b42-b2d2-17e5248dee35.png">
<ul><li> The balanced accuracy score of the SMOTEENN algorithm was 64.47%. For the high-risk category, there was a precision score of 1% and a recall score of 72%. For the low-risk category, there was a precision score of 100% and a recall score of 57%. </li></ul>

#### BalancedRandomForestClassifier Algorithm Results
<img width="901" alt="RandomForestClassifier" src="https://user-images.githubusercontent.com/103657822/187232848-a2a504da-9d1d-4d31-bef9-690a70a49c5f.png">
<ul><li> The balanced accuracy score of the BalancedRandomForestClassifier algorithm was 68.30%. For the high-risk category, there was a precision score of 88% and a recall score of 37%. For the low-risk category, there was a precision score of 100% and a recall score of 100%. </li></ul>

#### EasyEnsembleClassifier Algorithm Results
<img width="907" alt="EasyEnsembleClassifier" src="https://user-images.githubusercontent.com/103657822/187233346-5d93fd43-89dc-4eeb-961c-266681111e53.png">
<ul><li> The balanced accuracy score of the EasyEnsembleClassifier algorithm was 93.17%. For the high-risk category, there was a precision score of 9% and a recall score of 92%. For the low-risk category, there was a precision score of 100% and a recall score of 94%. </li></ul>

## Summary
After analyzing the outcomes of the six Machine Learning algorithms, we can conclude that the Easy Ensemble Classifier algorithm performed the best; therefore, I would recommend ultilizing this model. When comparing the accuracy score of the Easy Ensemble Classifier method to the other methods, it performed expontentially better with a score of 93%. The other methods' accuracy scores ranged from 54% to 68%. Additionally, when analzying the recall score, which gives us the sensitivity of method, the Easy Ensemble Classifier algorithm performed the best again with a score of 92% for the high-risk credit risk. The other models' sensitivity results ranged from 37% to 72%.
