# Credit-Risk-Analysis-for-Default-Loan-Dataset

- Given a loan dataset with information on each customer, we are to design a predictive model which will firstly predict the chances of any given customer defaulting payments and further estimating the corresponding losses.


#### Conclusion
- We were able to calculate expected loss on given loan instance, using 4 different ML algorithms (Logistic Regression, Support Vector Classifier, Random Forest Classifier, XGBoosting Classifier), and implemented 2 different strategies for combining algorithms (Stacking Classifier, Weighted Ensemble Strategy).

- We were able to compare each of these models for 5 different metrics (Accuracy, Precision, Recall, F1 Score, ROC AUC).

- Resulting metrics were around ~0.99 which means the models were either overfitted for the dataset, or the dataset could have an imbalance in defaulted vs non-defaulting customers, or even though there is a difference in the expected loss values, the prediction for defaulting were correct.
