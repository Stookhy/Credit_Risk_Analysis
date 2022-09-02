# Credit_Risk_Analysis

## Overview of the Analysis

  1.  Explain how a machine learning algorithm is used in data analytics.
  2.  Create training and test groups from a given data set.
  3.  Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
  4.  Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
  5.  Compare the advantages and disadvantages of each supervised learning algorithm.
  6.  Determine which supervised learning algorithm is best used for a given data set or scenario.
  7.  Use ensemble and resampling techniques to improve model performance.

## Results Six Machine Learning Models

  ### 1.  Naive Random Oversampling
   *   Balanced accuracy scores is 0.6456130066757718
   *   Precision scores high risk is 0.01 low risk is 0.68
   *   Recall scores high risk is 0.61 low risk is 0.68
![This is an image](https://github.com/Stookhy/Credit_Risk_Analysis/blob/main/Resources/Naive%20Random%20Oversampling.png?raw=true)

  ### 2.  SMOTE Oversampling
   *   Balanced accuracy scores is 0.6234433606890912
   *   Precision scores high risk is 0.01 low risk is 1.00
   *   Recall scores high risk is 0.61 low risk is 0.64
![This is an image](https://github.com/Stookhy/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20Oversampling.png?raw=true)

  ### 3.  Undersampling
   *  Balanced accuracy scores is 0.6234433606890912
   *  Precision scores high risk is 0.01 low risk is 1.00
   *  Recall scores high risk is 0.61 low risk is 0.43
![This is an image](https://github.com/Stookhy/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png?raw=true)

  ### 4.  Combination (Over and Under) Sampling
   *  Balanced accuracy scores is 0.5146760216106459
   *  Precision scores high risk is 0.01 low risk is 1.00
   *  Recall scores high risk is 0.70 low risk is 0.58
![This is an image](https://github.com/Stookhy/Credit_Risk_Analysis/blob/main/Resources/Combination%20(Over%20and%20Under)%20Sampling.png?raw=true)

  ### 5.  Balanced Random Forest Classifier
   *  Balanced accuracy scores is 0.7885466545953005
   *  Precision scores high risk is 0.03 low risk is 1.00
   *  Recall scores high risk is 0.70 low risk is 0.87
![This is an image](https://github.com/Stookhy/Credit_Risk_Analysis/blob/main/Resources/Balanced%20Random%20Forest%20Classifier.png?raw=true)

 ### 6.  Easy Ensemble AdaBoost Classifier
   *  Balanced accuracy scores is 0.9316600714093861
   *  Precision scores high risk is 0.09 low risk is 1.00
   *  Recall scores high risk is 0.92 low risk is 0.94
![This is an image](https://github.com/Stookhy/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier.png?raw=true)

## Summary

   After looking at the balanced accuracy scores, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. The credit card data set shows that the Easy Ensemble AdaBoost Classifier is the best model to choose, with its 93% balanced accuracy. The other models that were used were less effective and below 80% in balanced accuracy. 
   The precision for all models used are similar and lies within an appropriate range. In addition, the recall score requires falling within 0 and 1, with numbers closer to 1 indicating that it is the better model. 
   As a result, the Easy Ensemble AdaBoost Classifier had the highest recall score and is therefore the final best machine learning model to choose for additional analysis related to credit card scores.
