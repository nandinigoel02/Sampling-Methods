# Sampling
Sampling is the process of selecting a subset of data from a larger dataset.
##
In this, we are applying five different sampling techniques on Credit card Fraud detection dataset.We will further analyze their accuracies and discuss the results.<br>
## Methodolgy
### 1. Converting Imbalanced dataset to balanced dataset: <br>
   In the given dataset, the class '1' has less number of samples. We solved this issue by oversampling class '1' instances
   and making them equal to class '0' instances.
   
### 2. Generating samples using five different sampling techniques: <br>
   1. *Simple Random Sampling* : A simple random sample is a subset of individuals chosen from a larger set in which a subset of individuals are chosen randomly, all       with the same probability. We found the sample size using Sample size detection formula :

   2. *Systematic Sampling* : Systematic sampling is a probability sampling method where researchers select members of the population at a regular interval. We             defined the step size by passing the arguments. 
      
   3. *Stratified Sampling* : Stratified sampling is a method of sampling from a population which can be partitioned into subpopulations. Here it is based on the           class attribute. Then we select equal number of instances of both the subpopulations.
      
   4. *Cluster Sampling* : A probability sampling method in which you divide a population into clusters   and then randomly select some of these clusters as your            sample.  
   5. *Convenience Sampling* :Convenience sampling is a non-probability sampling method where units are selected for inclusion in the sample because they are the            easiest for the researcher to access.
### 3. Applying five ML Models on above four samples: <br>

   - *Random Forest*
   - *Decision Tree*
   - *K-Nearest Neighbour*
   - *Logisitic Regression*
   - *SVM*

### 4. Table : <br>
|               | Simple Random | Systematic | Cluster | Stratified | Convenience |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Logistic Regression  | 93.814433 | 80.0 | 92.592593 | 90.526316 | 98.0 |
| SVM  | 67.010309 | 60.0 | 69.444444 | 70.526316 | 99.0 |
| KNN  | 88.659794 | 40.0 | 95.833333 | 91.578947 | 99.0 |
| Decision Tree | 92.783505 | 50.0 | 96.296296 | 90.526316 | 99.0 |
| Random Forest | 100.0 | 90.0 | 99.537 | 100.0 | 98.0
   
   
## Conclusion
 Random Forest Classifier is giving the best result in each sample.
