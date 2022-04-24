# Credit Risk Analysis
## Overview of the Analysis
Six different models were fit to real world data in order to determine which one best predicts credit risk.  Credit risk is an inherently unbalanced classification problem because good loans easily outnumber risky loans. Different techniques of machine learning were employed to train and evaluate models with unbalanced classes.   

The credit dataset used in the modeling originated from LendingClub, a peer-to-peer lending services company.  Python programming with the help of the imbalanced-learn and scikit-learn libraries was used to build and evaluate models using resampling.  The six different models to predict credit risk included 1) oversampling data using the RandomOverSampler and 2) SMOTE algorithms, 3) undersampling the data using the ClusterCentroids algorithm, a 4) combinatorial approach of over- and undersampling using the SMOTEENN algorithm, and finally two learning models that reduce bias, the 5) BalancedRandomForestClassifier and 6) EasyEnsembleClassifier. An evaluation of the performance of these models and a written recommendation on whether they should be used to predict credit risk follows.

## Results
The results of six model fits are shown in the bullets below.  An imbalanced classification report was generated for each one.  The report, laid out in a table format, includes calculations for the precision (pre), recall (rec), specificity (spe), f1 score (f1), geometric mean (geo) and index balanced accuracy (iba) of the model. All of these are metrics for measuring performance of imbalanced classes.  

* RandomOverSampler: 
![Naive Random Oversampling model imbalanced classification report](screenshots/model1.png)

* SMOTE algorithm: 
![SMOTE Algorithm model imbalanced classification report](screenshots/model2.png)

* ClusterCentroids algorithm:
![Cluster Centroids algorithm model imbalanced classification report](screenshots/model3.png)

* SMOTEENN algorithm:
![SMOTEENN algorithm model imbalanced classification report](screenshots/model4.png)

* BalancedRandomForestClassifier:
![BalancedRandomForestClassifier model imbalanced classification report](screenshots/model5.png)

* EasyEnsembleClassifier:
![EasyEnsembleClassifier model imbalanced classification report](screenshots/model6.png)

## Summary
All six of the models fit to the data are intended to be used on imbalanced data sets.  Of the six, performed best performed worst


