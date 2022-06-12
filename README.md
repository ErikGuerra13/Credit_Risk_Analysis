# Credit_Risk_Analysis

# Overview of the analysis
- For this analysis we are using imbalanced-learn and scikit-learn libraries to build models and evalue them using a resampling method to predict credit risk from our loan stats data. We focused on using supervised learning with our dataet to achieve these predictions. 

# Results

## Deliverable 1
- For our dataset we using the loan status column to determine if a application are low or high risk credit application. As shown in the in the image below you can see that about 99% of applications were considered to be low risk. 

![](Resources/dataset.PNG)

- Using the RandomOverSampler model the results we achieved a balanced accuracy score of 64%.

![](Resources/randomoversampler.PNG)

- Results from using RandomOverSampler model

![](Resources/results1.PNG)

- Using the SMOTE model had a slightly higher balanced accuracy score of 66%

![](Resources/SMOTE.PNG)

- Results from using SMOTE model

![](Resources/SMOTEresults.PNG)

## Undersampling

- Using the ClusterCentroids Model had a lower balanced accuracy score of 54%

![](Resources/clustercentroids.PNG)

- Results from using the CluisterCentroids Model

![](Resources/clustercentroidsR.PNG)

## Deliverable 2

- We used the SMOTEENN model that combines both oversampling and undersampling. 

- SMOTEENN balanced accuracy score of 54%

![](Resources/SMOTEENN.PNG)

- Results using the SMOTEENN model

![](Resources/SMOTEENN1.PNG)

# Summary

- As shown in the examples above the SMOTE model achieved the highest balanced accuracy score of 66% and the lowest being the SMOTEENN model. I believe that machine learning is a great tool that can be used in a variety of different applications to make predictions.

