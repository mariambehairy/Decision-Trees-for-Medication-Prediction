# Decision-Trees-for-Medication-Prediction

## Introduction

This project aims to build a model for predicting the appropriate medication/drug type for patients based on their Age, Sex, Blood Pressure, and Cholesterol levels using the "Drag.csv" dataset. Two experiments are conducted to evaluate the model's performance under different scenarios.

## Tasks
1- Data Preprocessing  
2- First Experiment: Fixed Train-Test Split Ratio  
* Divide the dataset into a training set (70%) and a testing set (30%).
* Repeat the experiment five times with different random splits.
* Report sizes and accuracies of decision trees in each experiment.
* Compare and select the model with the highest overall performance.
  
3- Second Experiment: Range of Train-Test Split Ratios  
For each training set size:
* Run the experiment with five different random seeds.
* Calculate mean, maximum, and minimum accuracy.
* Measure mean, maximum, and minimum tree size.
* Store statistics in a comprehensive report.
* Create plots: accuracy vs. training set size, nodes in the final tree vs. training set size.
