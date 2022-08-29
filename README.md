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

#### ClusterCentroids Algorith Resuls
<img width="908" alt="ClusterCentroids" src="https://user-images.githubusercontent.com/103657822/187226751-487d78fc-e1c5-4835-887b-c42bbd80558f.png">
<ul><li></li></ul>
