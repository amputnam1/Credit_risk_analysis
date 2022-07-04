# Credit Risk Analysis

Using the credit c ard credit dataset from LendingClub, I oversampled the data using th RandomOverSampler and SMOTE algorithms, as well as the undersample data with the ClusterCentroids algorithm. This assignment also consistented of using a combinatorial approach to over- and undersampling. Next, I compared two new machine learning models in order to reduce bias and to predict credit risk. Through this, I was able to gathering findings in order to evaluate performance of these models to make a written recommendation provide here in the README

### Results

When looking at the results we looked at the Balanced Accuracy Score as well as the Imbalanced Classification Report from each model. Since thie intent was to detect high credit risk indiiduals we looked at the ICR from the F1 (f-score) column which is the bottom average/total row and also the "high risk" row.

#### Cluster Centroid 
The Cluster Centroid Undersampling provided the most disappointing results with an accuracy score of 0.5295. In other words, it did slightly better than 50% in accurating predicting credit risks.

 <img width="522" alt="Results1" src="https://user-images.githubusercontent.com/93094173/177222928-8e5a963f-fc29-4534-a50a-306b720fe0e1.png">

#### Combination sampling

In comparison, the combination sampling had slightly better but disapppointing results as well, with an accurate score of only 0.6529. In other words, it did bettr than 65% accuracy to predict credit risks of individuals. 

<img width="527" alt="Results2" src="https://user-images.githubusercontent.com/93094173/177223071-40c0e32e-e5cf-43df-a8d4-8d96e57b2194.png">


## Summary

This exercise and challenge demonstrated to be that credit risk individuals is a tricky thing to predict even though we had tools and machine learning algorithms to help us. It appears that the Easy Ensemble AdaBoost Classifier model had the highest accuracy, however, the data set was not optimal. I think that using any of these models or automated mechanisms can't be relied on soley for information about accurately predicting high-risk individuals, and require a human, manual component in order to review the outputs, findings, and make a recommendation based on combined information or potentially other sources (e.g. Equifax, etc.). It is clear that there still exists and inherently unbalanced and complex classification problem 
