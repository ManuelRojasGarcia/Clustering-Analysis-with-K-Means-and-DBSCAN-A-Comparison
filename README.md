# Clustering Analysis: Discovering Patterns with K-Means, DBSCAN, and OPTICS

## Introduction
This repository contains an analysis of clustering methods applied to raptor bird data. By using unsupervised learning techniques like **K-Means**, **DBSCAN**, and **OPTICS**, we explore how different clustering algorithms can identify patterns in physical features of raptors, such as wing size and weight.

## Objective
The goal of this project is to evaluate the effectiveness of these clustering methods in handling varying densities, noise, and complex data distributions in biological datasets.

## Methodology

### K-Means
- A centroid-based method for clustering spherical groups. Requires the number of clusters (K) to be predefined.
- Best suited for uniform data with minimal noise.

### DBSCAN
- A density-based method for finding arbitrarily shaped clusters.
- Excels at handling noise and irregular densities.

### OPTICS
- An extension of DBSCAN that identifies clusters with varying densities and produces a visually informative output.

## Results
The analysis demonstrates that **DBSCAN** and **OPTICS** outperformed **K-Means** when applied to this dataset, due to their ability to handle noise and varying densities.

## Files
- `Clustering-Analysis.Rmd`: R Markdown file for clustering analysis.
- `Clustering-Analysis.html`: Rendered HTML output from the analysis.
- `images/`: Folder containing images related to the analysis (clustering visualizations).

## Installation

1. Clone this repository
2. Install the required R packages:
   ```r
   install.packages(c("ggplot2", "cluster", "fpc", "dbscan"))
