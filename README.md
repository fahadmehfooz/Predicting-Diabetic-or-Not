# Predicting-Patient is Diabetic-or-Not: Project Overview 
* Objective: To predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.
* Dealt with class imbalance using SMOTE. Divided the data into train and test data. Performed oversampling on train dataset/
* Trained on multiple models like Logistic Regression, SVM, Bernoulli Naive Bayes, Gaussian Naive Bayes, KNN, and XGBoost.

## Languages Used 
**Python Version:** 3.9.0

## Resources and Tools Used
**Tools:** Jupyter Notebook

**Packages:** Pandas, NumPy, sklearn, Matplotlib, seaborn, imblearn and counter.

## Data Used
**Data Source**: https://www.kaggle.com/uciml/pima-indians-diabetes-database

**About the data:**

* The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.
* Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.


## Data Wrangling 
* Null values found, filling missing values using appropriate functions.
* Converting categorical columns to continuous.
* Plotting heatmap to find the correlation between continuous features.
* Plotting violinplots, barplots, distplots, KDEplots, pairplots and stripplots for the features.
* Oversampling the train data to get more balanced data.
* Used MinMaxScaling for scaling the data.

## Data Visualization
Some of the visualizations are shown here:

![alt text](https://github.com/fahadmehfooz/Predicting-Diabetic-or-Not/blob/main/images/kde.png)
![alt text](https://github.com/fahadmehfooz/Predicting-Diabetic-or-Not/blob/main/images/pairplot.png)
![alt text](https://github.com/fahadmehfooz/Predicting-Diabetic-or-Not/blob/main/images/violinplot.png)


## Model Building 

I took a split on the data with training data as 80% and test data as 20%. 
I tried different models like Logistic Regression, SVM, Bernoulli Naive Bayes, Gaussian Naive Bayes, KNN, and XGBoost.

## Metrics Used For Evaluation

* Accuracy
* Preciion and Recall 

## Model performance

**Results:**

* The accuracy of Logistic Regression is :  70.12987012987013 %
  Precision score for Logistic Regression is : 56.33802816901409 %
  Recall score for Logistic Regression is : 72.72727272727273 %

* The accuracy of Gaussian Naive Bayes is :  74.02597402597402 %
 Precision score for Gaussian Naive Bayes is : 60.56338028169014 %
 Recall score for Gaussian Naive Bayes is : 78.18181818181819 %

* The accuracy of Bernoulli Naive Bayes is :  46.103896103896105 %
  Precision score for Bernoulli Naive Bayes is : 38.70967741935484 %
  Recall score for Bernoulli Naive Bayes is : 87.27272727272727 %

* The accuracy of SVM is :  68.83116883116884 %
  Precision score for SVM is : 54.794520547945204 %
  Recall score for SVM is : 72.72727272727273 %

* The accuracy of KNN is :  68.83116883116884 %
  Precision score for KNN is : 55.932203389830505 %
  Recall score for KNN is : 60.0 %

* The accuracy of XGBoost is :  72.07792207792207 %
  Precision score for XGBoost is : 58.333333333333336 %
  Recall score for XGBoost is : 76.36363636363637 %

## Conclusion

* Class Imbalance was found.
* Gaussian Naive bayes is performing the best in context of precision and recall.
