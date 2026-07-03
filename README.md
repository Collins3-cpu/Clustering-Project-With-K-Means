# Clustering-Project-With-K-Means
Unsupervised Learning Project: Identifying Performance Clusters in Standardized Test Scores
This project applies K-Means clustering to analyze relationships between SAT/ACT scores, age, gender, and education level. It explores optimal cluster numbers and visualizes student performance segments.

📋 Project Overview

Dataset: sat.act from the pydataset library (SAT and ACT scores with demographic variables)

Goal: Cluster students based on test performance and demographics
Techniques: Elbow method for cluster selection, K-Means clustering, PCA visualization

📈 Key Insights

# Dataset Features

Numerical: age, ACT, SATV (SAT Verbal), SATQ (SAT Quantitative)

Categorical: gender, education

Target Exploration: Performance levels derived from test scores (e.g., Weak, Average, Strong)

# Clustering Analysis

Elbow Method: Evaluated distortions for K=1 to 9 clusters to determine optimal K.

K-Means Results: Identified meaningful clusters based on SAT/ACT combinations.

Visualization: Scatter plots of SATV vs SATQ colored by performance clusters, revealing clear groupings.

# Performance Patterns

Strong correlation between SAT Verbal and Quantitative scores.

Clusters differentiate students by overall academic strength.

Potential insights into how age and education level relate to test performance.

🔍 Analysis Highlights

Data Preparation: Loaded via pydataset, cleaned NaN values.

Optimal Clusters Determination: Elbow plot of within-cluster sum of squares.

Clustering & Visualization: Applied K-Means and projected results for interpretability.

💡 Recommendations

# Educational Insights:

Use clusters to identify students needing targeted support (e.g., low SATQ group).

Analyze demographic factors (age/gender) within clusters for equity studies.

# Model Improvements:
Experiment with different K values or alternative algorithms (Hierarchical, DBSCAN).
Incorporate additional features if available (e.g., GPA, study hours).

# Applications:

College admissions: Personalized recommendations based on cluster profiles.

Test prep: Tailored programs for different performance segments.

🛠️ Technologies Used

Data Handling: pandas, pydataset

Clustering: scikit-learn (KMeans)

Visualization: matplotlib

Environment: Python 3, Jupyter
