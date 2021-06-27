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

### Oversampling Model

- The balanced accuracy score is 63.39%.
- The high_risk precision is about 1% only with 60% sensitivity which makes a F1 of 2% only.
- Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 67%.

![img1.1](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_1.PNG)
![img1.2](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_1.2.PNG)
![img1.1.3](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_1.3.PNG)

### SMOTE Model

The results are pretty similar to the previous model.
- The balanced accuracy score is 63.07%.
- The high_risk precision is about 1% only with 60% sensitivity which makes a F1 of 2% only.
Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 66%.

![img2.1](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_2.1.PNG)
![img2.2](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_2.2.PNG)
![img2.3](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_2.3.PNG)

### Undersampling Model

Here the balanced accuracy score is down to about 52.95%.
The high_risk precision is still 1% only with 61% sensitivity which makes a F1 of 1%.
Due to the high number of false positives, the low_risk sensitivity is only 45%.

![img3.1](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_3.1.PNG)
![img3.2](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_3.2.PNG)
![img3.3](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_3.3.PNG)

### Combination

The balanced accuracy score is about 62.3%.
The high_risk precision is still 1% only with 70% sensitivity which makes a F1 of only 2%.
Due to the high number of false positives, the low_risk sensitivity is 55%.

![img4.1](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_4.1.PNG)
![img4.2](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_4.2.PNG)
![img4.3](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_4.3.PNG)

### BalancedRandomForestClassifier model

The balanced accuracy score improved to about 78.77%.
The high_risk precision is still low at 4% only with 67% sensitivity which makes a F1 of only 7%.
Due to a lower number of false positives, the low_risk sensitivity is now 91% with 100% presicion.

![img5.1](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_5.1.PNG)
![img5.2](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_5.2.PNG)
![img5.3](https://github.com/ritwikthakar/Module-17-Credit-Risk/blob/main/img_5.3.PNG)

### EasyEnsembleClassifier model

Now, the balanced accuracy score is high to about 92.54%.
The high_risk precision is still low at 7% only with 91% sensitivity which makes a F1 of only 14%.
Due to a lower number of false positives, the low_risk sensitivity is now 94% with 100% presicion.


