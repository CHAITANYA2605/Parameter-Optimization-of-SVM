# Parameter-Optimization-of-SVM

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning.

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

# Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository. https://archive.ics.uci.edu/dataset/602/dry+bean+dataset

This dataset is used for estimating the precise number of occupants in a room using multiple non-intrusive environmental sensors like temperature, light, sound, CO2 and PIR. It is a multi-variate classification Dataset.

Number of Instances: 13611

Number of Attributes: 16

# Result Table

Sample	Best Accuracy	Best Kernel	Best Nu	Best Epsilon
0	1	0.95	poly	9.70	5.76
1	2	0.95	linear	3.77	5.85
2	3	0.97	linear	2.25	7.06
3	4	0.93	poly	5.73	9.54
4	5	0.94	linear	8.62	4.05
5	6	0.82	rbf	7.08	8.11
6	7	0.88	linear	9.73	2.50
7	8	0.95	poly	4.54	6.71
8	9	0.97	poly	9.79	6.83
9	10	0.96	poly	1.49	2.08

# Convergence Graph

(https://github.com/CHAITANYA2605/Parameter-Optimization-of-SVM/assets/63853464/9d029f48-afa6-4323-a218-6d83a12b3622)
