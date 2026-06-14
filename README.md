# Student Stress Analysis Using Unsupervised Machine Learning

## Project Overview

This project applies unsupervised machine learning techniques to analyze student stress data and identify hidden patterns without using predefined labels.

The dataset contains academic, psychological, social, and environmental factors that influence student stress levels. Multiple clustering algorithms were implemented and compared to discover meaningful student groups.

---

## Dataset

**Dataset Name:** StressLevelDataset.csv

**Total Records:** 1100 Students

**Total Features:** 21

Features include:

* Anxiety Level
* Self Esteem
* Depression
* Mental Health History
* Sleep Quality
* Academic Performance
* Study Load
* Future Career Concerns
* Social Support
* Peer Pressure
* Bullying
* Stress Level
* and other related factors

---

## Machine Learning Techniques Used

### 1. K-Means Clustering

Used to identify natural student groups based on stress-related characteristics.

### 2. Hierarchical Clustering

Applied using Ward Linkage and visualized through a dendrogram.

### 3. Divisive Clustering

Implemented using Bisecting K-Means to recursively divide clusters.

### 4. DBSCAN

Density-based clustering used to identify hidden groups and detect outliers.

### 5. Principal Component Analysis (PCA)

Used for dimensionality reduction and cluster visualization.

---

## Evaluation Metrics

The following clustering metrics were used:

* Silhouette Score
* Davies-Bouldin Score
* Calinski-Harabasz Index

---

## Results Summary

| Model        | Silhouette Score | DB Score |
| ------------ | ---------------- | -------- |
| K-Means      | 0.4264           | 1.0607   |
| Hierarchical | 0.4237           | 1.0495   |
| Divisive     | 0.4148           | 1.1495   |
| DBSCAN       | 0.4884           | 1.1224   |

---

## Visualizations

The project includes:

* Histograms
* Boxplots
* Correlation Heatmap
* Elbow Method Graph
* Dendrogram
* PCA Cluster Visualizations
* DBSCAN Cluster Visualization

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Author

Nadia Bibi

Machine Learning Project

2026
# student-stress-unsupervised-learning
Unsupervised Machine Learning project on student stress analysis using K-Means, Hierarchical Clustering, DBSCAN, and PCA.
