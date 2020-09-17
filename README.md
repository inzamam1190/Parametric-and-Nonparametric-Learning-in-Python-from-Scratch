# Parametric-and-Nonparametric-Learning-in-Python-from-Scratch
The objective of this project is, first of all, to learn how to implement the two types of learning algorithms based on Baysian decision theory, namely, parametric learning and non-parametric learning. In parametric learning, I will implement the three cases of discriminant functions assuming Gaussian pdf. In non-parametric learning, I will implement kNN. Equally important, the second objective is to get familiar with the design flow when applying machine learning algorithms to solve real-world problems. Some practical considerations include, for example:
- The selection of the right pdf model (or in that regard, modeless pdf) to characterize the data distribution in the training set
- The selection of the right ratio of prior probability
- The different ways to evaluate the performance of the learning algorithm, and
- How differently the same ML algorithm performs when applied to different datasets.

## Datasets
Two datasets will be used from Ripley's Pattern Recognition and Neural Networks, both are 2-category classification problems. The first is a synthetic dataset with 2 features where there are about equal number of samples in each category. The second is a dataset for diabetes in Pima Indians with 7 features where the number of diabetic patients is much less than that of the normal patients.

## Performance Metrics
Three metrics are used to evaluate the performance of the ML algorithms, including 1) overall classification accuracy, 2) classwise classification accuracy, and 3) run time.

