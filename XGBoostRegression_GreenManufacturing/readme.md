Code source : Sun Young Kim

License : BSD 3 clause

Mercedes-Benz Greener Manufacturing
The goal of this project is to reduce the time that cars spend on the test bench. Others will work with a dataset representing different permutations of features in a Mercedes-Benz car to predict the time it takes to pass testing. Optimal algorithms will contribute to faster testing, resulting in lower carbon dioxide emissions without reducing Mercedes-Benz’s standards.

Steps to be performed:

1. For any column(s), if the variance is equal to zero, then remove those variable(s).

2. Check for null and unique values for test and train sets.

3. Apply label encoder.

4. Perform dimensionality reduction.

5. Split train and test dataset

6. Use RandomizedSearchCV and GridSearchCV for hyperparameter tunning.

7. Perform k-fold validation.

8. Prediction on test dataset using XGBoost.
  
9. Plot actual target values of train dataset and predicted target values of test dataset.

10. Plot feature importance.
