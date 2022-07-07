# Credit Risk Analysis

## Overview of the Analysis

The purpose of this analysis was to train a machine learning model to accurately precdict whether someone would be a risk to give a loan to based on various criteria.

## Results

### Naive Random Oversampling:
-Balanced Accuracy Score: 0.636 <br>
-Precision: 0.99 <br>
-Recall: 0.64 <br>
![NaiveRandomOver](https://i.imgur.com/4uqCQ4J.png)

### SMOTE Oversampling:
-Balanced Accuracy Score: 0.617 <br>
-Precision: 0.99 <br>
-Recall: 0.65 <br>
![SMOTEOver](https://i.imgur.com/ZRPpe5s.png)

### Undersampling:
-Balanced Accuracy Score: 0.617 <br>
-Precision: 0.99 <br>
-Recall: 0.65 <br>
![Under](https://i.imgur.com/rOmKwEA.png)

### SMOTEENN Over and Under Sampling:
-Balanced Accuracy Score: 0.671 <br>
-Precision: 0.99 <br>
-Recall: 0.58 <br>
![NaiveRandomOver](https://i.imgur.com/gRTCsgo.png)

### Balanced Random Forest Classifier:
-Balanced Accuracy Score: 0.954 <br>
-Precision: 1.00 <br>
-Recall: 0.91 <br>
![NaiveRandomOver](https://i.imgur.com/Y1mi2Rt.png)

### Easy Ensemble AdaBoost Classifier:
-Balanced Accuracy Score: 0.925 <br>
-Precision: 0.99 <br>
-Recall: 0.94 <br>
![NaiveRandomOver](https://i.imgur.com/p4Moh60.png)

## Summary

While all machine learning models had a high precision rate, four of them did not have particularly good recall or balanced accuracy scores. The ensemble models did much better than the other four, with recall rates and balanced accuracy scores in the 90's. I would recommend using either of these models, and possible recommending the the Balanced Random Forest Classifier over the Easy Ensemble because it had a higher balanced accuracy score.
