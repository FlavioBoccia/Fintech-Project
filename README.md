# Fintech-Project
Hedge Fund replication using Linear Regression and Kalman Filter

The code is entirely written in Python, and we used Jupyter Notebook as the editor to insert comments. We recommend opening the notebooks in the following order:

1)Lasso Regression Validation: Here, we train the linear regression model with Lasso penalty in both weekly rebalancing and monthly rebalancing cases.

2)Lasso Regression Test: Here, we observe the performance of our model on the test set.

3)Feature Selection: Here, we briefly discuss the rationale behind the feature selection used in the Kalman filter.

4)Kalman Filter: Here, we implement the Kalman filter and observe its performance on the validation set without any parameter optimization. The goal is to compare the baseline performance with that of the Lasso regression.

5)Neural Network Anomaly Detection: Here, we implement and optimize a neural network to detect future market anomalies. At the end of the code, a new Excel file, VALORI_PREDETTI, should be created. We have already included it in the folder, hoping that no issues arise with file handling during the creation.

6)Kalman Filter Validation: Here, we search for the optimal hyperparameter for the classifier threshold to optimize our model.

7)Testing the performance of the new model by varying the alpha exposure parameter.
