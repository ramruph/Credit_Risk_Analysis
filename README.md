# Credit_Risk_Analysis
Using Machine Learning to predict credit card risk

# Overview of the analysis

Using these algorithms, (Naive Random Sampling, SMOTE, SMOTEEN, RandomForest, AdaBoost), I resampled the dataset, viewed the count of the target classes, trained a logistic regression classifier, calculated the balanced accuracy score, generated a confusion matrix, and generated a classification report.



# Results

After using different Random Over and Under sampling we got the following results:

- The Naive Random Oversampling resulted in an accuarcy score of 64%
    - It had a precision of 1% for high risk and 100% for low_risk
    - Recal for high risk  is 66% and 62% for low risk

- SMOTE had an accuarcy of 50%
    - Precision of 61% for high risk and 69% for low risk
    -  Recall for high risk of 1% and low risk of 100%


- the combined SMOTEEN accuracy of 66%
    - precision of 1% for high risk and 100% for low risk
    - recall of 75% for high risk and 56% for low risk

- Balanced Random Forest accuracy of 79%
    - precision of 3% for high risk and 100% for low risk
    - recall  of 70% for high risk and 87% for low risk

- AdaBoost had an accuracy score of 93%
    - precision of 9% for high risk and 100% for low risk
    - recall of 92% and 94% respectivly


# Summary 

The results from using the three different over and undersampling models is that each model has their own areas where they did better than the other.

The SMOTE model had a higher precision score than both the Random Oversampling and the SMOTEEN. The SMOTE however had a lower recall than the other two as well. None of the models had a high accuracy rate, but out of the three SMOTEEN had the highest at 66%. I wouldn't use any of the models at the point where they are now because of the accuracy rate. The model with the highest accuracy is the AdaBoost model with 93% accuracy. It also had the highest precisions and recalls from all the other models including the RandomForest Model. I would use the AdaBoost Model to identify Credit Risk from this sets of models.

