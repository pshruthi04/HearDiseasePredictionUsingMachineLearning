## Explorations

### Exploratory Data Analysis
As it is always better to check the correlation between the features, I analyzed that which feature is negatively correlated and which is positively correlated so, I checked the correlation between various features. 

after analyzing correlation with the target variable, Four features  “cp”, “restecg”, “thalach”, “slope”  are positively correlated with the target feature.
Other features are negatively correlated with the target feature.
So, as I have done enough collective analysis now I did analysis of the individual features which comprises both univariate and bivariate analysis.

Checked range of age in the dataset.
Did analysis for feature 'sex'
Analysis for chestpain
Analyzing chestpain vs target


##### Models used:
Logistic Regression is a statistical and machine-learning technique classifying records of a dataset based on the values of the input fields. It predicts a dependent variable based on one or more set of independent variables to predict outcomes. Logistic Regression is incredibly easy to implement and very efficient to train. 

(Logistic Regression implementation is best instead of Linear Regression because the target variable in the dataset is of type categorical, not continuous. So, my dataset is not suitable for linear regression.)
-> After using logistic regression, I have implemented through decision tree classifier, which did not meet the accuracy of logistic regression.But definitely, both models have shown that they can be very successful in solving classification problems.

Decision Tree Classifier
Support vector Classifier(There is no much difference between support vector classifier without kernel and SVC with kernel).
Random Forest Classifier
Neural Networks

### Links to Notebooks
-[Initial Exploration](initial_exploration.ipynb)

-[linear_regression](linear_regression.ipynb)

-[Classification](classification.ipynb)

-[Clustering & NN](Clustering.ipynb)

Visualizations can be found in Initial Exploration.
