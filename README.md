Projects:
Predicting whether the bank client has subscribed for the term deposit or not.

Objectives:
Exploring Insights/Inferences by performing EDA on the given data. Relevant graphs were plotted to get some insights on data using seaborn package. Model fitting via Logistic Regression by Importing sklearn package.

Python Libraries Used:
Pandas
Numpy
Matplotlib
Seaborn
Scikit learn
Joblib
Methodology:
Data copying and cleaning:

Read the csv file
copy the data
check for null values and other informations
Exploratory Data Analysis:

Conduct all the necessary EDA using various graphs on the dataset
interpret the graphs
check for outliers and correlation among the coloumns
perform one hot encoding in case of categorical columns
Sampling of data:

Divide the data into x and y
standardize the data using StandardScaler lib
import test_train_split from sklearn.model_selection
divide the data into training and testing
Modelling of data:

import LogisticRegression and initialize it
fit the model
predict the model
Model validation (Error Calculation):

From sklearn.metris import accuracy_score, precision_score, confusion_matrix
check the accuracy of the model
Save the Model:

import joblib
save the model
Bank-Deposit data Probelm:
File name: Bank-Deposit-data-files

EDA Inferences:
Toatl Bank clients are 45211 , out of which 39922 did not subscribed for term deposit.
There are large number of clients with manangement and blue-collar job profiles and are more likely to opt for term deposit.
Clients with secondary education type are more compared to other and are the one opted for term deposited in large number.
Bank has more married clients followed by single and divorced.
From analysing job, education and martial data, clients with more balance are more likely to opt for term deposit.
The same is true in case of duration of call, the clients with maximum call duration are more likely to opt for term deposit.
The data is normally distributed for age and Age and day features.
Balance, duration, campaign, pdays, previous are skewed towards left and might have outliers present.
Salary and Age of the customers are correalted with the Iphone purchase.
There are outliers present in all the features of the dataset except day feature.

Logistic Regression Model Results:
The accuracy of the model is came out to be:

Accuracy Score: 0.90

Precision Score:0.65

Contribution: Still Learning,

So feel free, Anything You wanna contirubute.
Still Learning,

So feel free, Anything You wanna contirubute.
