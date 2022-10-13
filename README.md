# Credit_Risk_Analysis
Use Resampling Models to Predict Credit Risk, Use the SMOTEENN Algorithm to Predict Credit Risk, and use Ensemble Classifiers to Predict Credit Risk.

# Background
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Overview
### - Deliverable 1: Use Resampling Models to Predict Credit Risk
#### - For all three algorithms, the following have been completed:
 - An accuracy score for the model is calculated.
 - A confusion matrix has been generated.
 - An imbalanced classification report has been generated.

### RandomOverSampler
 - An accuracy score for the model is calculated as 0.8325
 - A confusion matrix has been generated.

![Screen Shot 2022-10-13 at 1 29 53 PM](https://user-images.githubusercontent.com/105253626/195666090-b4c8305c-ad73-4017-add1-7769c7368107.png)

 - An imbalanced classification report has been generated.
 
 ![Screen Shot 2022-10-13 at 1 35 31 PM](https://user-images.githubusercontent.com/105253626/195666679-60463321-48ed-4e8a-9e3d-94ad2436474a.png)


### SMOTE
 - An accuracy score for the model is calculated as 0.844
 - A confusion matrix has been generated.

![Screen Shot 2022-10-13 at 1 38 27 PM](https://user-images.githubusercontent.com/105253626/195667342-1e9111e9-1903-4e41-a855-cbb614f2b8cb.png)

 - An imbalanced classification report has been generated.
 
 ![Screen Shot 2022-10-13 at 1 38 48 PM](https://user-images.githubusercontent.com/105253626/195667379-fa2ed435-af87-4eea-ba63-0d38aa3e1314.png)


### ClusterCentroids
 - An accuracy score for the model is calculated as 0.844
 - A confusion matrix has been generated.
 
 ![Screen Shot 2022-10-13 at 1 41 23 PM](https://user-images.githubusercontent.com/105253626/195667794-6227afaa-40bd-4082-af63-44908dee0c9d.png)

 
 - An imbalanced classification report has been generated.

![Screen Shot 2022-10-13 at 1 41 42 PM](https://user-images.githubusercontent.com/105253626/195667814-fc343d7c-237f-45e4-a420-c22af560b426.png)


### - Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
 - An accuracy score for the model is calculated.
 - A confusion matrix has been generated.
 - An imbalanced classification report has been generated.


### - Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
 #### - The BalancedRandomForestClassifier algorithm does the following:
  - An accuracy score for the model is calculated.
  - A confusion matrix has been generated.
  - An imbalanced classification report has been generated.
  - The features are sorted in descending order by feature importance.
  
 #### - The EasyEnsembleClassifier algorithm does the following:
  - An accuracy score of the model is calculated.
  - A confusion matrix has been generated.
  - An imbalanced classification report has been generated.
