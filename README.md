![download (1)](https://github.com/CHAITANYA2605/Parameter-Optimization-of-SVM/assets/63853464/cba37b89-1853-4327-948a-6e2b5e99bc4b)# Parameter-Optimization-of-SVM

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning.

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

#Dataset
The dataset for the project has been downloaded from the UCI Machine Learning Repository. https://archive.ics.uci.edu/dataset/602/dry+bean+dataset

This dataset is used for estimating the precise number of occupants in a room using multiple non-intrusive environmental sensors like temperature, light, sound, CO2 and PIR. It is a multi-variate classification Dataset.

Number of Instances: 13611

Number of Attributes: 16

#Result Table
[{"index":0,"Sample":1,"Best Accuracy":0.93,"Best Kernel":"poly","Best Nu":"9.34","Best Epsilon":0.69},{"index":1,"Sample":2,"Best Accuracy":0.96,"Best Kernel":"linear","Best Nu":"3.56","Best Epsilon":7.3},{"index":2,"Sample":3,"Best Accuracy":0.87,"Best Kernel":"linear","Best Nu":"3.0","Best Epsilon":8.32},{"index":3,"Sample":4,"Best Accuracy":0.83,"Best Kernel":"poly","Best Nu":"8.89","Best Epsilon":5.81},{"index":4,"Sample":5,"Best Accuracy":0.91,"Best Kernel":"linear","Best Nu":"9.31","Best Epsilon":4.98},{"index":5,"Sample":6,"Best Accuracy":0.84,"Best Kernel":"rbf","Best Nu":"5.57","Best Epsilon":1.61},{"index":6,"Sample":7,"Best Accuracy":0.88,"Best Kernel":"linear","Best Nu":"9.04","Best Epsilon":2.78},{"index":7,"Sample":8,"Best Accuracy":0.91,"Best Kernel":"poly","Best Nu":"4.91","Best Epsilon":4.12},{"index":8,"Sample":9,"Best Accuracy":0.97,"Best Kernel":"poly","Best Nu":"1.57","Best Epsilon":9.28},{"index":9,"Sample":10,"Best Accuracy":0.97,"Best Kernel":"poly","Best Nu":"2.38","Best Epsilon":2.95}]

#Convergence Graph
![download (1)](https://github.com/CHAITANYA2605/Parameter-Optimization-of-SVM/assets/63853464/9d029f48-afa6-4323-a218-6d83a12b3622)
