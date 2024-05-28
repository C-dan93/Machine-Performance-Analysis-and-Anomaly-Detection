# Machine-Performance-Analysis-and-Anomaly-Detection
This repository contains a Python script for analyzing machine performance data. The script performs the following steps:

The script performs the following steps:

Data Cleaning: Handles missing values and saves the modified data.

Exploratory Data Analysis (EDA): Explores the relationship between machine types and failure types, calculates and visualizes the proportions of different error types, and creates a heatmap to show the distribution of failure counts across machine types.

Machine Availability Index Calculation: Calculates and visualizes the machine availability index for each machine type.

Feature Engineering: Adds features like total operating time, total failures, machine availability index, and failure rate for each observation.

Time-Based Analysis: Visualizes availability and failure rates over time for different years and groups of failure types.

Correlation Analysis: Calculates and visualizes correlation matrices for different target values and features.

Anomaly Detection: Performs anomaly detection using Isolation Forest, One-Class SVM, and Local Outlier Factor (LOF) algorithms.

Feature Selection: Employs bootstrapping and permutation importance techniques to identify the most influential features for predicting machine failures, enhancing the accuracy and efficiency of subsequent predictive modeling.
