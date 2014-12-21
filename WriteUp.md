Predicting the Quality Excercise Using Accelerometers

Background
In this report we will try to predict the quality of an barbell exercise performed by six different subjects.
The data used in this report comes from the Human Activity Recognition project. In this study,
several athletes were asked to perfrom some barbell curl exercises in 5 different ways, only one of which correct. 

The project supplied two datasets, a training and testing datasets. Each of these datasets contain
several variables recorded from accelerometers were placed on the belt, forearm, arm and dumbell of the 6 participants.
160 measurements were taken that will be used to predict the outcome of the "classe" variable. Or more simply, which class 
given exercise belongs to. The classe varible is a factor variable with four levels A,B,C,D,E.
This report we will be trying to predict the classe for each of the 20 observations provided in the testing dataset.

Steps:
1. Data Preparation/Cleaning</br>
2. Building Random Forest Model</br>
3. Checking Model Accuracy</br>
4. Cross-Validation Accuracy (Out-of-Sample)</br>
5. Predicting Outcome of Test Set</br>
