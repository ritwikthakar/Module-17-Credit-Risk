# Module-17-Credit-Risk

## Analysis Overview
In this project, we will use Python to create and assess many machine learning models to estimate credit risk.
We will adopted the following procedures:
- oversample the data using the **RandomOverSampler** and **SMOTE** algorithms.
- Undersample the data using the **ClusterCentroids** algorithm.
- Use a combinatorial approach of over- and undersampling using the **SMOTEENN** algorithm.
- Compare two machine learning models that reduce bias, **BalancedRandomForestClassifier** and **EasyEnsembleClassifier**.

We will evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

## Results (Balanced Accuracy Scores, Confusion Matrixes and Imbalanced Classification Reports)

### RandomOverSampler model

- The balanced accuracy score is 63.39%.
- The high_risk precision is about 1% only with 60% sensitivity which makes a F1 of 2% only.
- Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 67%.
![img1]()
