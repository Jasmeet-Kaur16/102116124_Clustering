# Cluster Analysis with PyCaret
This Python script performs cluster analysis using different clustering techniques including K-Means clustering, Hierarchical Clustering, and Birch Clustering. It utilizes the PyCaret library for clustering and visualization.

## Setup
### Requirements
* Python 3.2.0<br/>
* PyCaret library

Install the required libraries using pip:
```
pip install pycaret
```

## Script Overview
The script performs the following tasks:

1. Installation of PyCaret library.
2. Importing necessary libraries and dataset (Jewellery dataset from Pycaret library).
3. Setting up parameters for the clustering models.
4. Performing cluster analysis using different clustering techniques.
5. Visualizing the clustering results using various plots including elbow plot(to check the number of appropriate clusters), silhouette plot, and distribution plot.

## Assignment Overview
The following tasks are performed in the assignment:

1. The clustering is performed for different algorithms in the notebook.
2. After this, tables is formed for each algorithm on the basis of scores of different no. of clusters (c=3,4,5) on different parameters(normalization,transformation etc).(attached csv files)

-The plots, graphs etc are present in the notebook for better visualisation.

## Additional Notes

* The dataset used in this script is the Jewellery dataset, which is found in Pycaret library under clustering datasets.
* Different preprocessing techniques such as normalization, transformation, and PCA are also applied to the data before clustering.

## Author
Name- Jasmeet Kaur
Roll Number- 102116124
Group- 3CS12
