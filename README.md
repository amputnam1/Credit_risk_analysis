# Credit Risk Analysis

Using the credit c ard credit dataset from LendingClub, I oversampled the data using th RandomOverSampler and SMOTE algorithms, as well as the undersample data with the ClusterCentroids algorithm. This assignment also consistented of using a combinatorial approach to over- and undersampling. Next, I compared two new machine learning models in order to reduce bias and to predict credit risk. Through this, I was able to gathering findings in order to evaluate performance of these models to make a written recommendation provide here in the README

### Results of six machine learning models

When looking at the results we looked at the Balanced Accuracy Score as well as the Imbalanced Classification Report from each model. Since thie intent was to detect high credit risk indiiduals we looked at the ICR from the F1 (f-score) column which is the bottom average/total row and also the "high risk" row.

#### 1. Cluster Centroid 
The Cluster Centroid Undersampling provided the most disappointing results with an accuracy score of 0.5295. In other words, it did slightly better than 50% in accurating predicting credit risks.

 <img width="522" alt="Results1" src="https://user-images.githubusercontent.com/93094173/177222928-8e5a963f-fc29-4534-a50a-306b720fe0e1.png">

#### 2. Combination sampling

In comparison, the combination sampling had slightly better but disapppointing results as well, with an accurate score of only 0.6529. In other words, it did bettr than 65% accuracy to predict credit risks of individuals. 

<img width="527" alt="Results2" src="https://user-images.githubusercontent.com/93094173/177223071-40c0e32e-e5cf-43df-a8d4-8d96e57b2194.png">

#### 3. SMOTE Oversampling

This provided the third worst and unreliable results and generated an accuracy score of 0.662.

<img width="520" alt="Results3" src="https://user-images.githubusercontent.com/93094173/177223478-bec40d2b-cfb5-40c9-ab70-d330e008823a.png">

### 4. Naive Random Oversampling

This was approximately in the middle of the model performance when compared to the other models used. The model was in the top three best results with an accuracy score of 0.6732. It did somewhat better than the previsious models used, at 67%.

<img width="532" alt="Results4" src="https://user-images.githubusercontent.com/93094173/177223571-c577a11d-96ae-4638-807c-9131d0de1d41.png">

### 5. Balance Random forest Classifier

This machine learning model provided us the with 2nd best results with an accuracy score of 0.7615. Unfortunately, it still isn't reliable as it would only help in predicting 3/4 of potential credit risks. 

<img width="528" alt="Results5" src="https://user-images.githubusercontent.com/93094173/177223696-b8762376-4565-4ba5-b0c0-f9b1ec1488bc.png">


### Easy ensemble AdaBoost classifier

This model scored highest in terms of accuracy at 0.9319%, respectively. However, it should be noted that while it performed better than the other models comparatively it is still not perfect and there is still a margin of error that is possible at 7% inaccuracy.

<img width="531" alt="Results6" src="https://user-images.githubusercontent.com/93094173/177223779-3e07779a-b31c-455e-8783-1de572c56cb7.png">


## Summary

This exercise and challenge demonstrated to be that credit risk individuals is a tricky thing to predict even though we had tools and machine learning algorithms to help us. It appears that the Easy Ensemble AdaBoost Classifier model had the highest accuracy, however, the data set was not optimal. I think that using any of these models or automated mechanisms can't be relied on soley for information about accurately predicting high-risk individuals, and require a human, manual component in order to review the outputs, findings, and make a recommendation based on combined information or potentially other sources (e.g. Equifax, etc.). It is clear that there still exists and inherently unbalanced and complex classification problem 
