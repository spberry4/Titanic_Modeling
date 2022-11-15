# Titanic_Modeling

Classic Titanic Modeling problem in order to determine the survivability of people with the data provided on kaggle. The data is located here: https://www.kaggle.com/competitions/titanic/overview

The following models were tested in order to try and achieve highest accuracy:

Voting Classifier
Random Forest
SVM
XGBoost

SMOTE was also used in order to balance the classes in order to attempt to better model the data.

The highest accuracy I was able to achieve in the contest was 0.77272.

In reviewing the data further I had orginially removed the column "Cabin" due to the amount of missing data but the missing cabin data could have meant that they did not have a cabin at all.
