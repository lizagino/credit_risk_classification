Credit Risk Classification
Background
Credit risk classification is a challenging problem due to its inherent class imbalance. Healthy loans significantly outnumber risky loans in lending datasets. In this challenge, you will explore various techniques to train and evaluate models dealing with imbalanced classes. The goal is to build a model that can accurately identify the creditworthiness of borrowers using a dataset containing historical lending activity from a peer-to-peer lending services company.

What You're Creating
In this project, you will leverage your knowledge of the imbalanced-learn library to develop a logistic regression model and compare its performance using two different versions of the dataset:

Original Dataset: You will work with the unaltered dataset as it is.
Resampled Dataset: You will resample the data using the RandomOverSampler module from the imbalanced-learn library to address the class imbalance.
For both scenarios, your tasks include:

Counting the target classes to understand the class distribution.
Training a logistic regression classifier on the dataset.
Calculating the balanced accuracy score to assess model performance.
Generating a confusion matrix to visualize prediction results.
Creating a classification report to provide detailed model evaluation metrics.
This project will help you gain valuable experience in handling imbalanced datasets and building classification models for credit risk assessment.
