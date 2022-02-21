# Credit_Risk_Analysis

## Overview of Analysis:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

### Deliverables:
Deliverable 1: Use Resampling Models to Predict Credit Risk
Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

## Results:
The following are the results of each of the techniques for predicitve modeling for loan evaluating.
Deliverable 1: 
  - RandomOverSampling
  
  ![image](https://user-images.githubusercontent.com/90146132/155025897-5f57e62d-b25f-461c-8823-9186a860c71b.png)
  
  - SMOTE Oversampling
  
  ![image](https://user-images.githubusercontent.com/90146132/155025958-871db68d-fa42-4bed-a2b5-92d980445743.png)

  - ClusterCentroids Undersampling
  
  ![image](https://user-images.githubusercontent.com/90146132/155026066-b58eda15-5eb2-493a-91bd-90c809a9df54.png)

  - SMOTEENN
  
  ![image](https://user-images.githubusercontent.com/90146132/155026124-de8f2944-ec3d-4b7c-85c1-d6250d7154a2.png)

  - BalancedRandomForestClassifier
  
  ![image](https://user-images.githubusercontent.com/90146132/155026341-2161e942-562b-4d13-9ed4-840cb6517a1e.png)

    Feature Importance:
    
    ![image](https://user-images.githubusercontent.com/90146132/155026412-794b9561-c5a2-43b6-85a8-adc0b8d939f5.png)
    
  - EasyEnsembleClassifier
  
  ![image](https://user-images.githubusercontent.com/90146132/155026502-0addbf0d-b1d3-4b93-9a1c-450693ab2844.png)

## Summary:
After evaluating each model, it is clear that the most efficient model to use when determining credit risk is the EasyEnsembleClassifier. It had highest balanced accuracy score as well as a higher sensitivity for high and low risk credit making it better to predict a false high risk and finding it is actually not high risk. 










