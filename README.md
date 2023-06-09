# Machine-Learning-Project-Starter
Repository of all project documentation and Code

## State of the project
1. Logistic Regression is used to implement the model
2. Decision Tree Classifier is used to implement the model
3. Tried K means clustering using elbow method 

**Important Results for logistic regression**

               precision    recall  f1-score   support

           0       0.82      0.75      0.79        44
           1       0.79      0.85      0.82        48

    accuracy                           0.80        92
   macro avg       0.81      0.80      0.80        92
weighted avg       0.81      0.80      0.80        92

**Important Results for decision tree classifier**:
- accuracy   0.77
- precision  0.78
- recall     0.78
- f1_score   0.78

**Predicting the values for testing set using support vector model
Notably, the accuracy for SVC is 83% which is higher than that of decision tree classifier i.e., 78%**

## Overview of the project
In this project, I worked with the heart data of people to develop a machine learning model. This System predicts the arising possibilities of heart disease. 
Considering all the features taken, will contribute to the output prediction if a person has a disease or not. This will be more of a classification type which will predict 1 for positive result that is person suffering from heart disease and 0 that is negative for a person not suffering from heart disease.

## Important Features
| # |Column |  Non-Null Count | Dtype |  
| ---    |   ---   | ---        |  ----- |
| 0 |  age |   304 non-null |  int64 |  
| 1 |  sex |   304 non-null |  int64 |
| 2 |  cp |    304 non-null |  int64 |
|3   |trestbps  |304 non-null    |int64 | 
| 4 |  chol |     304 non-null|    int64 | 
 |5 |  fbs  |     304 non-null|    int64|  
 |6 |  restecg|   304 non-null|    int64|  
 |7 |  thalach|   304 non-null|    int64|  
 |8 |  exang  |   304 non-null|    int64 | 
| 9 |  oldpeak |  304 non-null|    float64|
 |10|  slope  |   304 non-null|    int64|  
 |11|  ca     |   304 non-null|    int64|  
 |12|  thal   |   304 non-null|    int64|   

There were some interesting relations between the features in dataset which I have shown using visualization.

The target variable is 'target'. This variable can have two possible outcomes: 0 or 1 where 0 refers to the case where a person don't have a heart disease and 1 refers to a case where a person has a heart disease.

## Exploratory Data Analysis
Through Exploratory Data Analysis, After doing univariate and Bivariate feature analysis I came up with some important results such as Four features “cp”, “restecg”, “thalach”, “slope”  are positively correlated with the target feature.
Other features are negatively correlated with the target feature.
So, we have done enough collective analysis now let’s go for the analysis of the individual features which comprises both univariate and bivariate analysis.I came up with some interesting questions on the dataset and I tried to find answers for the same during EDA process through visualization.

## Data Preprocessing
Performed - 
1. Removing missing values
2. Feature scaling 
3. Splitting the data into training and testing sets

## Models used:
Logistic Regression is incredibly easy to implement and very efficient to train. 

(Logistic Regression implementation is best instead of Linear Regression because the target variable in the dataset is of type categorical, not continuous. So, my dataset is not suitable for linear regression.)

Then I trained the model with decision tree classifier and support vector classifier where I ended up with more accuracy for SVC. And I also trained with random forest classifier and Neural networks.

Used confusion matrix to evaluate the metrics.

### Challenge:
This project is not 100% accurate. It gives correct results up to some extent. As this is mainly related to heart, some incorrect results may lead to different consequences. That needs to be taken care by balancing thin line between precision and recall.


## Conclusion: 
I found that adding features to the data can help overcome underfitting, getting more data i.e., increasing records in data can help overcome overfitting. 
random_state, splitter, max_depth are the parameters used in decision tree classifier. I used best for splitter and max depth as 5, If I increase max depth then it leads to overfitting. If max depth is less, it will lead to underfitting.
From this project milestone, I have learnt that- If there are n features and a target variable which is a categorical one, then using the classifier algorithms, a model can be generated by giving the labelled training data to the model. The model learns the patterns that are present in the training data and this patterns can be used to predict the values of the testing data.

### Links to other 4 sections:

-[RAW_DATA](Raw_Data.md)

-[Data](Data.md)

-[Analysis](Analysis.md)

-[Conclusion](Conclusion.md)







