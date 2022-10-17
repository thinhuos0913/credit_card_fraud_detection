# Purpose 
Implement machine learning models which are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
# Content
The dataset contains transactions made by credit cards in September 2013 by European cardholders (Download here in Kaggle: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

This dataset presents transactions that occurred in two days, where have 492 frauds out of 284,807 transactions. The dataset is highly imbalanced, the positive class (frauds) account for 0.172% of all transactions. It contains only numerical input variables which are the result of a PCA transformation due to confidentiality.
# Solution
- Preprocess data (drop missing values, normalize data, ...)
- Apply classification algorithms into original imbalanced dataset to evaluate their performance.
- Apply undersampling, oversampling method to solve imbalanced issue.
- Re-apply classifications algorithms into undersampled/oversampled dataset to see if the performance of models is improved.
- Try to apply ensemble methods (Bagging, RandomForest, Boosting, ...) into undersampled/oversampled dataset to evaluate performance.
