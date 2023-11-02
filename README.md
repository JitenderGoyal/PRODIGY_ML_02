# Customer Segmentation and Visualization in a Shopping Mall Dataset

This repository contains a Python script that performs customer segmentation and visualization using a shopping mall dataset. It uses Python libraries like Pandas, Matplotlib, Seaborn, and scikit-learn for data analysis and clustering.

## Dataset

The dataset used in this project is named "Mall_Customers.csv." It contains information about mall customers, including their age, annual income, and spending score.

## Code Overview

The repository contains a Python script that performs the following tasks:

1. Data Loading and Exploration
   - Loads the dataset using Pandas.
   - Displays basic information about the dataset.

2. Data Visualization
   - Creates a pair plot to visualize pairwise relationships between 'Age', 'Annual Income (k$)', and 'Spending Score (1-100)'.
   - Generates two side-by-side box plots to visualize the distribution of 'Annual Income (k$)' and 'Spending Score (1-100)'.
   - Calculates and displays the correlation matrix for selected features.

3. Clustering
   - Selects the 'Annual Income (k$)' and 'Spending Score (1-100)' features for clustering.
   - Uses the K-means clustering algorithm to determine the optimal number of clusters (K) through the elbow method.
   - Performs K-means clustering with K=5 and adds cluster labels to the original dataset.
   - Visualizes the clusters and cluster centers.

## Usage

To run the code, you'll need the following dependencies installed:

- Python
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

You can run the code by executing the Python script provided.

```python
python customer_segmentation.py
