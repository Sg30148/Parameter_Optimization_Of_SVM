# Parameter_Optimization_Of_SVM

Support Vector Machine (SVM) is a popular supervised learning algorithm used for classification and regression analysis. It is a powerful tool for finding the optimal boundary that separates the two classes. SVM works by creating a hyperplane in a high-dimensional space that optimally separates the data points into their respective classes.

To achieve optimal performance, SVM requires careful selection of various parameters, such as the kernel type, regularization parameter, and the kernel coefficient. These parameters can significantly affect the performance of the SVM model, and their optimal values can be determined through a process called parameter optimization.

Parameter optimization is the process of finding the best set of parameter values that maximize the performance of the SVM model on a given dataset. There are several methods for parameter optimization, such as grid search, random search, and Bayesian optimization. These methods involve systematically searching through the parameter space to find the best combination of parameter values that yield the highest accuracy on the test data.

## Tasks Performed
1. Download the dataset
2. Pre-process the dataset
3. Create ten samples 
4. Split the samples in  70 : 30 for training and testing
5. Optimise SVM using randomisation for every sample and report best accuracy and best parameters
6. For the best sample plot the convergence graph


## Dataset used:https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation

Number of Instances:10129
Number of Attributes:16




## Final Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.88 | Poly | 5.82 | 4.35 |
| 2 | 0.95 | Linear | 5.13 | 0.30 |
| 3 | 0.96 | Linear | 3.13 | 6.32 |
| 4 | 0.96 | Poly | 1.49 | 3.26 |
| 5 | 0.91 | Linear | 3.52 | 7.34 |
| 6 | 0.83 | RBF | 5.60 | 3.14 |
| 7 | 0.95 | Poly | 0.29 | 7.71 |
| 8 | 0.95 | Poly | 4.87 | 5.57 |
| 9 | 0.97 | Poly | 1.27 | 6.87 |
| 10 | 0.92 | Poly | 0.34 | 5.50 |


## Submission by :
**Name** : Saumya Gupta
<br>
**Roll No** : 102017036
