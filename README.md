# Credit Risk Analysis

## Overview of the analysis:

Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk. 

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes.

## Results:

- Naive Random Oversampling results: Our balanced accuracy test it 67%, the precision for the high_risk has a very low positivity at 1% and the recall is 74%
![image](https://user-images.githubusercontent.com/83035801/136713656-96628c6e-3ab0-47a3-92e0-5aaa69666a1c.png)

- SMOTE oversampling results: the accuracy score is 66.2%, the precision for the high_risk loans has a low positvity again at 1% and recall is 69% overall
![image](https://user-images.githubusercontent.com/83035801/136713675-e32e3955-ac5a-46c4-a8b6-71ba65e1694d.png)

- Undersampling results: balanced accuracy score is 66.2% overall, the precision is at 99% and the recall is 41%
![image](https://user-images.githubusercontent.com/83035801/136713684-9910dc5a-ec0e-4d1f-addb-b5146db11a89.png)

- Combination(over and undersampling) results: balanced accuracy score is 54.7% the precision is 99% and the recall is 57% overall
![image](https://user-images.githubusercontent.com/83035801/136713695-6bd7b5c4-f5a1-4900-ad5f-311219417b68.png)

- Balanced Random Forest Classifier results: the accuracy score is 77.2% the precision is 99% and the recall is 88%
![image](https://user-images.githubusercontent.com/83035801/136713624-39f89ae4-45c4-49ff-bc73-d233a070311c.png)

- Easy Ensemble AdaBoost Classifier results: the accuracy score is 91.7% the precision is 99% and the recall is 94%
![image](https://user-images.githubusercontent.com/83035801/136713634-fa5d94fd-acd1-4793-9ec9-719be70a7e4f.png)

## Summary

Easy Ensemble AdaBoost Classifier seems like the best to use with a high accuracy and good balance of precision and recall scores. 
