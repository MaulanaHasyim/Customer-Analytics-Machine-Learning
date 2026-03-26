# Bank Customer Analytics: Segmentation & Prediction Pipeline
This repository contains two interconnected machine learning projects completed as part of the IDCamp 2025: Data Scientist Learning Path by Dicoding Indonesia. The project aims to identify distinct customer segments and build a predictive model to classify new customers based on their behavioral patterns.
<img width="2048" height="2048" alt="image" src="https://github.com/user-attachments/assets/cc2e4a52-5d30-40b1-b551-964f515802f3" />

1. Customer Segmentation (Clustering)
Objective: To group customers based on their financial behavior and demographics to enable targeted marketing strategies.
Tools & Library: Python, Pandas, Scikit-Learn, Matplotlib, Seaborn.

Methodology:
*Data Preprocessing & Feature Scaling (StandardScaler).
*Dimensionality Reduction using Principal Component Analysis (PCA) for better visualization.
*Optimal cluster determination using the Elbow Method.
*Clustering execution using K-Means Algorithm.

Key Insight: Successfully identified distinct segments such as High-Value Professionals (Cluster 0) and Active Young Transactors (Cluster 1), providing a clear understanding of the customer base.


2. Customer Segment Prediction (Classification)
Objective: To develop a supervised learning model that can automatically assign new customers to the previously identified clusters.
Tools & Library: Python, Scikit-Learn, Joblib, Google Colab.

Methodology:

*Feature Encoding (One-Hot Encoding) for categorical variables.
*Data Splitting (Train-Test Split).
*Model Benchmarking: Comparing Decision Tree and Random Forest.
*Hyperparameter Tuning using GridSearchCV to optimize model performance.

Result: The final Random Forest model achieved an accuracy of 1.00 (100%), demonstrating high reliability in replicating the clustering logic for future data.

Project Structure
[Clustering]_Submission_Akhir.ipynb: Full notebook for the clustering process.
[Klasifikasi]_Submission_Akhir.ipynb: Full notebook for the classification process.
/models: Contains saved .h5 model files (Decision Tree, Random Forest, and Tuned Models).
