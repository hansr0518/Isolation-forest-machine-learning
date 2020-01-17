# Isolation-forest-machine-learning
Data was gathered for 10 days per 100 millisecond from 100 sensors.

It has train & test data set and final data set for validation.  

The path of data location : /Sensors/problem1/train01.csv & /Sensors/problem1/test01.csv

# Links 
Isolation forest : https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html

# Process
1. To build more robust model, compared one class SVM with Isolation forest.  
> Isolation Forest has more pricise accuracy. 
2. Used Grid search to tune the parameters in Isoloation forest. 
> Result : {'contamination': 0.01, 'random_state': 333, 'max_samples': 25, 'max_features': 32}
