# DS_Imbalance
#### This in an Imbalanced Classification Dataset which was provided to us as part of an in class Kaggle Competition.
#### The data set for this competition is a subset of publicly available data. The variable names were masked to hide the identity of the data set. Few missing values were added to a couple of variables. 
### Dependent Variable
#### The dependent variable is 'Target'. It is a binary variable and takes only two values - 0 and 1. We were required to train our model to predict this variable.

### Evaluation Metric Used - F2 Score
#### Since the data set is imbalanced, we have around 1% positive (1's) for the target variable. We want to focus on the positive class. Further, false negatives are more important. Therefore, the evaluation metric for the competition is F2-Score. 

### Files
#### The competition had three files.

#### (1) train.csv- This file was used to train the data. 
#### (2) test.csv - The best model trained using train.csv file was used to to make a prediction on this data. The test.csv did not have a 'Target' Variable. We had to predict the values of 'Target' variable for this data. We used the predicted values and Id's from test.csv to   generate the submission file.

### Algorithms Implemented:
#### 	Basic Algorithms:

##### 1.	Logistic Regression
##### 2.	Decision Tree
##### 3.	k-Nearest Neighbors
##### 4.	Support Vector Machine (optional as it may take long time to run)
##### 5.	Random Forest
##### 6.	Extra Trees
##### 7.	Gradient Boosting
##### 8.	XgBoost

#### 2.	Cost Sensitive Algorithms:
##### 9.	Logistic Regression
##### 10.	Decision Trees
##### 11.	Support Vector Machines (optional as it may take long time to run)
##### 12.	Random Forest
##### 13.	XGBoost
##### 14.	Extra Trees
##### 15.	Bagging decision tree with under sampling


#### 3.	Data Sampling Algorithms:
##### 16.	Logistic Regression
##### 17.	Decision Tree
##### 18.	k-Nearest Neighbors
##### 19.	Support Vector Machine (optional as it may take long time to run)
##### 20.	Random Forest
##### 21.	Easy Ensemble Classifier
##### 22.	XgBoost
##### 23.	Neural Network (scikit learn MLPClassifier)

#### 4.	Stacking Classifiers: 
##### I tried to combine various models to create stacking models. Generally diverse models gives us better results. 

##### Apart from the above algorithms, I also implemented LightGBM with RandomSearch, LDA and Voting Classifiers.

