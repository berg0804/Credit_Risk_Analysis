# Credit Risk Analysis
## Overview
The purpose of this project is to train and evaluate models that will be used to determine if loans are good or risky in the context of a lendee's credit status. To evaluate the models, imbalanced-learn and scikit-learn libraries will be used. The dataset used is from LendingClub and multiple algorithms will be utilized.
## Results
- Naive Random Oversampling
- 
![Screen Shot 2022-08-09 at 9 03 34 AM](https://user-images.githubusercontent.com/67160240/183653775-7e2ac8c4-caf0-4fb7-9cd9-1e60e971f0a2.png)
 
  - Balanced accuracy: 0.6234041499089175
  - High risk loans: Precision = 0.01, Recall = 0.63
  - Low risk loans: Precision = 1.00, Recall = 0.62
- SMOTE Oversampling

![Screen Shot 2022-08-09 at 9 03 55 AM](https://user-images.githubusercontent.com/67160240/183653885-c53bb6bd-37a8-440d-a978-caf29528c518.png)

  - Balanced accuracy: 0.6241920711180668
  - High risk loans: Precision = 0.01, Recall = 0.60
  - Low risk loans: Precision = 1.00, Recall = 0.65
- Undersampling

![Screen Shot 2022-08-09 at 9 05 22 AM](https://user-images.githubusercontent.com/67160240/183654186-46158fa3-1de6-44b7-b57c-822e67da0a4c.png)

  - Balanced accuracy: 0.6241920711180668
  - High risk loans: Precision = 0.01, Recall = 0.59
  - Low risk loans: Precision = 1.00, Recall = 0.59
- Combination (Over and Under) Sampling 

![Screen Shot 2022-08-09 at 9 08 28 AM](https://user-images.githubusercontent.com/67160240/183654816-66e4142b-a121-4878-827f-320c5eaff53a.png)

  - Balanced accuracy: 0.5889553835248565
  - High risk loans: Precision = 0.01, Recall = 0.72
  - Low risk loans: Precision = 1.00, Recall = 0.57
- Balanced Random Forest Classifier

![Screen Shot 2022-08-09 at 9 10 27 AM](https://user-images.githubusercontent.com/67160240/183655170-3f69f9ea-9632-4d18-a871-a68ec36f7dca.png)

  - Balanced accuracy: 0.7885466545953005
  - High risk loans: Precision = 0.03, Recall = 0.70
  - Low risk loans: Precision = 1.00, Recall = 0.87
- Easy Ensemble AdaBoost Classifier

![Screen Shot 2022-08-09 at 9 18 34 AM](https://user-images.githubusercontent.com/67160240/183656794-22feb32a-4c05-40fa-b88f-c8a06dc484ce.png)
  
  - Balanced accuracy: 0.9316600714093861
  - High risk loans: Precision = 0.09, Recall = 0.92
  - Low risk loans: Precision = 1.00, Recall = 0.94
## Summary
Upon reviewing the six models, the Easy Ensemble AdaBoost Classifier procued the best results based on two factors: balanced accuracy and recall. In both instances, the goal is to be as close to 1.0 as possible and each of these domains produced the best results with a balnced accuracy of 0.93 and a recall of 0.92 for high risk loans and 0.94 fo rlow risk loans. Therefore, Easy Ensemble AdaBoost Classifier is the best learning maching model that was analyzed.
