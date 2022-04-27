# Credit_Risk_Analysis

## Project Overview
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.  In this project we employ different machine learning techniques to train and evaluate models with unbalanced classes.  Libraries used are imbalanced-learn and scikit-learn.  Data is oversampled using the RandomOverSampler and SMOTE algorithms, undersampled using ClusterCentroids algorithm, combined approach using the SMOTEENN algorithm, and then compared using two new machine learning models to reduce bias including BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results

- Naive Random Oversampling

![Naive Random Oversampling](https://user-images.githubusercontent.com/96347933/165421756-35eaed91-945c-4614-bf22-7b99366087ad.PNG)

- SMOTE Oversampling

![SMOTE](https://user-images.githubusercontent.com/96347933/165421784-41a774af-dd76-498b-8f70-45beb16e0d9f.PNG)

- Undersampling

![Undersampling](https://user-images.githubusercontent.com/96347933/165421821-562d27e1-56dc-440d-94fd-9da0c89d1d97.PNG)

- Combined Sampling

![SMOTEENN](https://user-images.githubusercontent.com/96347933/165421878-49c3d89a-4866-4d4a-a15e-018c84815228.PNG)

- Balances Random Forest Clasifier

![Random Forest](https://user-images.githubusercontent.com/96347933/165421966-9f320fe8-a30c-40d0-9768-7242e020a47d.PNG)

- Easy Ensemble AdaBoost Classifier

![Easy Ensemble](https://user-images.githubusercontent.com/96347933/165421997-6a48c310-07c8-46ff-ad38-2d448e8384ea.PNG)

## Summary
In this scenario I recommend the Easy Ensemble model, as the score reveal it is most liekly to accurately identify and predict high risk loans.  
