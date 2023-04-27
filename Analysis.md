 
### Analysis:
Accuracy is more for Support Vector than any other models used. Same high accuracy is obtained for logistic regression for 80-20 split of the dataset into train and test datasets. These results are supported by confusion matrix and classification report.
Precision is more for Support Vector which implies more correctness of the model. (implies it has less false positives)
Logistic Regression implementation is best instead of Linear Regression because the target variable in the dataset is of type categorical, not continuous. So, my dataset is not suitable for linear regression.

Precision is more for SVC which implies more correctness of the model. (implies it has less false positives)
Neural Networks resulted in slightly less accuracy because of some features.

There are some interesting relations between target and feature variables.
Example - For sex=0, more chance of heart disease compared to sex=1 . Similarly it is calculated for all target versus feature & checked if there are any combinations that can lead to better results.


As the data is supervised, PCA is not applicable . As the data which I considered has only 2 classes for prediction, LDA is not supportable due to the below statement: n components cannot be larger than min(n_features, n_classes - 1 ).  So, dimensional analysis is not possible!

We can improve the model using new approach for predicting click through rate based on Deep Neural Network via Attention Mechanism.