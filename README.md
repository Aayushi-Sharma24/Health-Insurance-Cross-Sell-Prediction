# Health-Insurance-Cross-Sell-Prediction

# Problem Statement :
The task is to use existing Health and Vehicle Insurance Customer Data to predict whether the any new Customers are open to purchasing Vehicle Insurance from this company .

# About the Data :
We have the data of existing Health Insurance Customers , this Data includes 12 relevant data points such as age, gender, sales channel data, vehicle ownership data. And most importantly , the target variable : whether the customer has vehicle insurance or not . The Data is available for 390K existing customers .

# Approach taken :
The task was divided into 2 main parts : 
1. Statistical Analysis over the dataset to discover relationships between each feature and the target variable. So that this relationship information can be used by the management in making better Business decisions 
2. Creating a Machine Learning Pipeline , that can take in the data of any new customer and predict whether they will be interested in vehicle insurance . It was required to kepp this pipeline modular , such that it can be retrained often when new data is collected

Modelling:
*  Logistic Regression 
*  K-Nearest Neighbors 
*  Random Forest 
*  XGBoost 
*  CatBoost 
Used GridSearchCV and BayesSearchCV for HyperParameter Tuning Comparing both F1 and AUC-ROC Score , we can see that Random Forest and XGBoost model performs the best . Best AUC-ROC = 0.86 , Best F1=0.44

Conclusions : Insights from exploring the Data :
● Customers of age between 30 and 70 are more likely to buy insurance.
● Customers with Driving Licence have higher chance of buying Insurance. 
● Customers with Vehicle Damage are more likely to buy insurance. 
● Customers with Vehicle age between 1 and 2 years are more likely to interested.
● Customer who are not insured previously are more likely to be interested.

# Python Libraries used
## Datawrangling :

* Numpy
* Pandas

## For Graphing :

* Matplotib
* Seaborn


## Machine learning :

* Scikit-Learn
* SK-Opt
* XGBoost
* CatBoost


