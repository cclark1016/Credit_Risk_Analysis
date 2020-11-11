# Credit Risk Analysis

## Purpose
The purpose of this analysis is to take the unbalanced credit card dataset from the lending services company LendingClub and determine which machine learning models are most effective at identifying high risk loan applicants. 

## Analysis
- Naïve Random Oversampling
  - Accuracy Score: .649
  
    ![PNG](https://github.com/cclark1016/Credit_Risk_Analysis/blob/main/Naive_Random_Oversampling.PNG)

- SMOTE Oversampling
  - Accuracy Score: .649
  
    ![PNG](https://github.com/cclark1016/Credit_Risk_Analysis/blob/main/Smote_Oversampling.PNG)

- Undersampling
  - Accuracy Score: .649
  
  ![PNG](https://github.com/cclark1016/Credit_Risk_Analysis/blob/main/Undersampling.PNG)
  
- SMOTEENN 
  - Accuracy Score: .54
  
  ![PNG](https://github.com/cclark1016/Credit_Risk_Analysis/blob/main/SMOTEENN.PNG)
  
- Balanced Random Forest Classifier
  - Accuracy Score: .789
  
  ![PNG](https://github.com/cclark1016/Credit_Risk_Analysis/blob/main/Balanced_Random_Forest.PNG)
  
- Easy Ensemble AdaBoost Classifier
  - Accuracy Score: .945
  
  ![PNG](https://github.com/cclark1016/Credit_Risk_Analysis/blob/main/Easy_Ensemble_AdaBoost.PNG)
  
  # Summary
All models except for the Balanced Random Forest had a high risk precision score of below 10%. While the models had high recalls this lack of precision led to many falase negatives. The exception is the Balanced Random Forest model, which .9 precision on identification of high risk applicants. While this model is not the highest in accuracy the precision gives it the highest F1 score of all models and is therefore the recommendation to use if a company had to choose one. 
