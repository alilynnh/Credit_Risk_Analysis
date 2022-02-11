# Credit Risk Analysis
## Project Overview
The purpose of this project was to evauate various predictive models in order to determine which should be used to classify low-risk and high-risk borrowers. Various sampling methods used in conjunction with logistic regression were evaluated, as well as balanced random forest and easy ensemble models. 

## Results
### Random Oversampling
When using naive random oversampling, the accuracy score was 66%, high-risk precision was 1%, and high-risk sensitivity was 72%.  
   
<img src="Resources/random_over.png" width="75%" height="75%">  

### SMOTE Oversampling
When using SMOTE oversampling, the accuracy score was 66%, high-risk precision was 1%, and high-risk sensitivity was 62%.    
   
<img src="Resources/smote_over.png" width="75%" height="75%">  

### Cluster Centroids Undersampling
When using cluster centroids undersampling, the accuracy score was slightly lower than the previous sampling techniques at 54%. The high-risk precision was 1% and high-risk sensitivity was 69%.  
      
<img src="Resources/cluster_under.png" width="75%" height="75%">  

### SMOTEEN Combination Sampling
The results of the SMOTEENN sampling method were similar to the naive random oversampling results. The accuracy score was 66%, high-risk precision was 1%, and high-risk sensitivity was 72%.   
   
<img src="Resources/smoteenn.png" width="75%" height="75%">  

### Balanced Random Forest Classifier
The balanced random forest model produced the second highest accuracy score at 79%. The high-risk precision was 3% and the high-risk sensitivity was 70%.   
    
<img src="Resources/brf.png" width="75%" height="75%">  

### Easy Ensemble Classifier
The easy ensemble classifier model produced the highest scores out of all of the methods evaluated. The accuracy score was 93%, the high-risk precision was 9%, and the high-risk sensitivity was 92%. 
      
<img src="Resources/ee.png" width="75%" height="75%">  

## Summary 
Based on the results of the various predictive models evaluated in this project, it is suggested that the Easy Ensemble model be used. This model had the highest accuracy score and also exhibits a high sensitivity for detecting high-risk borrowers. While this model may still have low precision and would reject some applicants who are low-risk, it is more important for the organization to act conservatively rather than try to reduce the false-positives. By being conservative, the organization can protect not only itself but also their customers from credit defaults.     