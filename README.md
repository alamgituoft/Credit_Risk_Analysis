# Credit_Risk_Analysis
## Overview of the analysis
A data analysis project that tested 6 supervised machine learning models in order to review which model is best to accurately predict credit risk. 

## Resources
Software: Python 3.8.5 (mlenv environment), Jupyter Notebook 6.1.4

## Results 
6 machine learning models were tested and the results of the balanced accuracy scores, precision and recall scores for the models are shown below:

**Naive Random Oversampling Model**
* **Balance accuracy score: 67.4%**
* **Precision high risk score: 1%**
* **Precision low risk score: 100%**
* **Recall high risk score: 74%**
* **Recall low risk score: 61%**
<img width="712" alt="Naive Sampling" src="https://user-images.githubusercontent.com/81877387/130325407-efbe89a6-e47c-484a-8349-f0644444b375.png">


**SMOTE Oversampling Model**
* **Balance accuracy score: 64.4%**
* **Precision high risk score: 1%**
* **Precision low risk score: 100%**
* **Recall high risk score: 72%**
* **Recall low risk score: 57%**
<img width="717" alt="SMOTE" src="https://user-images.githubusercontent.com/81877387/130325421-cd2aa9ee-c145-4206-84f6-3b36e5b717ca.png">


**Cluster Centroid Undersampling Model**
* **Balance accuracy score: 54.4 %**
* **Precision high risk score: 1%**
* **Precision low risk score: 100%**
* **Recall high risk score: 69%**
* **Recall low risk score: 40%**
<img width="708" alt="Cluster Centriods" src="https://user-images.githubusercontent.com/81877387/130325472-0b20a810-2250-44b7-9c2c-57416eb790a9.png">


**SMOTEENN Sampling Model**
* **Balance accuracy score: 64.4 %**
* **Precision high risk score: 1%**
* **Precision low risk score: 100%**
* **Recall high risk score: 72%**
* **Recall low risk score: 57%**
<img width="709" alt="SMOTEEN" src="https://user-images.githubusercontent.com/81877387/130325979-e520b41b-a017-4416-b645-b1b9af793c83.png">



**Balanced Random Forest Classifier**
* **Balance accuracy score: 76%**
* **Precision high risk score: 3%**
* **Precision low risk score: 100%**
* **Recall high risk score: 64%**
* **Recall low risk score: 88%**
<img width="717" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/81877387/130325677-2950e7d8-2f9a-4321-96d6-3722983dc3b2.png">


**Easy Ensemble Classifier**
* **Balance accuracy score: 93.1%**
* **Precision high risk score: 9%**
* **Precision low risk score: 100%**
* **Recall high risk score: 92%**
* **Recall low risk score: 94%**
<img width="711" alt="Easy Ensemble Classifier" src="https://user-images.githubusercontent.com/81877387/130325720-991a20fb-cc47-4ee0-b86c-4f69d3873087.png">

## Summary
In reviewing the results, an overview of both high and low risk as well as accuracy score should be looked at in order to select the best model. 
Overall the Easy Ensemble model had the highest accuracy score (93%) and highest recall risk score for both high (92%) and low risk (94%). As all these statistics are relatively high compared to the rest of the models (all above 90% for these stats), this would be the recommended model for predicting high risk loans. 
