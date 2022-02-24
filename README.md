# Rider_Driven_Cancellation_Prediction

- [Hackathon Conducted on kaggle](https://www.kaggle.com/c/cascade-cup-22/overview) by Consulting & Analytics Club, IIT Guwahati.

## **INTRODUCTION**

Given the order and rider details, create a model that can predict rider-driven cancellation in advance (i.e. before getting marked as cancelled or delivered)

## **TECHNOLOGIES USED**

*Python, Numpy, Pandas, Matplotlib, Scikit-learn*

## **METHODOLOGY**

##### **Data importing and exploration**

- We used pandas framework to import the data and perform further analysis on it.
- Used basic feature engineering.
- Scaled Data and selected required features
- Plotted correlation matrix using matplotlib

##### **Training model using different techniques**

- Splitted data into test and train datasets.
- We used logistic regression classifier,SVM, Gradient Boost Classifier, Random Forest on training dataset.
- Tuned hyperparameters.
- Calculated accuracy and ROC_AUC on the test dataset and train dataset.
- Plotted accuracy vs ROC_AUC score using matplotlib.
- Visualised predictions using confusion matrix using sklearn.

##### **Model Comparison**

- Compared models based on accuracy and ROC_AUC score on the test dataset.
- Predicted results using best hyperparameters.
