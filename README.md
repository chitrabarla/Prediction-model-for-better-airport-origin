# Prediction-model-for-better-airport-origin

Dataset: http://stat-computing.org/dataexpo/2009/the-data.html

Developed a prediction model which suggests a better airport origin
either OAK (Oakland) or SFO(San Francisco) given a date and 
destination using data mining and machine learning methods.

Input Parameters:
Year.     
Month	
DayofMonth	
DayOfWeek	
CRSDepTime	
CRSArrTime	
UniqueCarrier	
FlightNum	
ArrDelay
DepDelay
Origin	
Dest	
Distance 

Total delay has to be predicted and suggestion is made based on the airport which has lesser delay.

The following ml models were used: 
Support Vector Machine
Naïve Bayes Classifier
Decision Tree
Random Forest
Logistic Regression
