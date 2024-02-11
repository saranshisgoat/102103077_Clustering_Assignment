Clustering Analysis on Air Quality Dataset

This repository contains a comparative performance study of different clustering algorithms (K-Means, Hierarchical, and K-Means Shift) applied to the Air Quality dataset obtained from the UCI Machine Learning Repository. The analysis includes various preprocessing techniques and evaluates clustering performance using different numbers of clusters on multiple evaluation parameters.

Dataset
The selected dataset is the Air Quality dataset, which contains measurements related to air quality, such as carbon monoxide (CO) levels, nitrogen oxides (NOx), and more.

Repository Contents
Clustering_Analysis_Air_Quality.ipynb: Jupyter Notebook containing the Python code for the clustering analysis, preprocessing steps, and evaluation metrics.
AirQualityUCI.xlsx: The Air Quality dataset in Excel format.

Steps Involved
Import Necessary Libraries: Importing required libraries, including NumPy, Pandas, Scikit-learn, Matplotlib, and Seaborn.
Data Loading and Exploration: Loading the Air Quality dataset, exploring its structure, and summarizing its statistics.
Data Pre-processing: Converting 'Time' to datetime, handling outliers, and reapplying standardization.
Clustering Algorithms: Implementing K-Means, Hierarchical, and K-Means Shift clustering.
Evaluation Metrics: Calculating silhouette score, Calinski-Harabasz index, and Davies-Bouldin index for each clustering algorithm.
Visualizations: Creating scatterplots to visualize clustering results.
Conclusion: Summarizing the findings and performance metrics.

Dependencies
Python 3.x
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn
Results
The results, visualizations, and performance metrics for each clustering algorithm are presented in the notebook. For a detailed analysis, refer to the Jupyter Notebook.

By
Saransh(102103077)
