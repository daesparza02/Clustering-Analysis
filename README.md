# Unsupervised Learning: Clustering Analysis

This repository contains a comprehensive analysis of Unsupervised Machine Learning techniques applied to dataset segmentation. The goal of this project is to identify distinct groups (clusters) within the data to uncover hidden patterns and insights without labeled outcomes. It was a project for an Artificial Intelligence course.

**Authors:** David Esparza, Jorge Arboleya, and Cristina Gómez.

## Project Overview

In this project, we explore various clustering algorithms to segment data based on similarities. The workflow includes:

* **Exploratory Data Analysis (EDA):**
  * Data distribution visualization.
  * Correlation analysis (Heatmaps).
* **Data Preprocessing:**
  * Feature Scaling (StandardScaler/MinMaxScaler).
  * Handling missing values (if applicable).
  * Dimensionality Reduction using PCA (Principal Component Analysis) for visualization.
* **Clustering Algorithms Applied:**
  * K-Means Clustering: Iterative centroid-based grouping.
  * Hierarchical Clustering: Agglomerative approach with Dendrograms.
  * DBSCAN: Density-based spatial clustering.
* **Model Evaluation:**
  * Elbow Method: To determine the optimal number of clusters (k).
  * Silhouette Score: To validate the consistency within clusters.

## Requirements

To run this notebook locally, install the necessary dependencies:

```bash
pip install -r requirements.txt
