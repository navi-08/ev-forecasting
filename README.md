# ev-forecasting      
## Stock Clustering Analysis Summary

### Total Explained Variance
The total explained variance of the three principal components is  99.09%. This indicates that the three PCA about 99.09% of the total variance in the original data, providing a good representation of the variability present in the dataset.

### Comparison of Best K Values
- The best k value for both original and PCA-transformed data was found to be 3.
- However, the inertia, which represents the within-cluster sum of squares, was lower for the original data (22.8044) compared to the PCA data (32.278).
- This suggests that while the clustering structure remains similar between the original and PCA data, the original data had slightly better clustering performance as indicated by the lower inertia.

### Impact of Using Fewer Features
- The analysis of stock data using K-Means clustering revealed an optimal number of clusters, k=3, regardless of whether using the original features or PCA-transformed data.
- While PCA reduced dimensionality, it also slightly increased the inertia compared to the original features.
- The choice between using original features and PCA depends on the trade-off between interpretability and clustering accuracy.

### Overall Impact
The analysis provided valuable insights into the underlying structure of the stock data, identifying three distinct clusters. This insight can be utilized by investors and financial analysts for portfolio diversification, risk management, and stock selection strategies. Additionally, the comparison between clustering results from original and PCA-transformed data highlighted the importance of feature selection and dimensionality reduction techniques in clustering analysis.

# Stock Clustering Analysis

## Overview
This repository contains the code and analysis for clustering analysis performed on stock data obtained from Yahoo Finance. The analysis aims to identify distinct clusters of stocks based on their growth rates using the K-Means clustering algorithm. The primary focus is to compare the clustering results obtained using the original features with those obtained after applying Principal Component Analysis (PCA) for dimensionality reduction.

## Data Source
The stock data used in this analysis was sourced from Yahoo Finance. It includes information on the annual, monthly, and weekly growth rates of various stocks.

## Files
- **data/**: This directory contains the raw and processed stock data files.
- **notebooks/**: This directory contains Jupyter notebooks with the code for data preprocessing, clustering analysis, and visualization.
- **output/**: This directory contains the output files generated during the analysis, such as CSV files with clustering results.
- **README.md**: This file provides an overview of the repository and instructions for replicating the analysis.

## Analysis Workflow
1. **Data Preprocessing**: The raw stock data is loaded and preprocessed to prepare it for clustering analysis. This involves cleaning the data, handling missing values, and scaling the features.
2. **Clustering Analysis**: The preprocessed data is used to perform K-Means clustering. Two sets of clustering analyses are conducted: one using the original features and another using PCA-transformed data.
3. **Visualization**: The clustering results are visualized using scatter plots to compare the clustering patterns between the original and PCA-transformed data.
4. **Evaluation**: The inertia values and explained variance ratios are computed to evaluate the quality of clustering and the effectiveness of dimensionality reduction.
5. **Conclusion**: The findings of the analysis are summarized, highlighting the impact of using fewer features on clustering accuracy and interpretability.

## Usage
To replicate the analysis, follow these steps:
1. Clone this repository to your local machine.
2. Navigate to the `notebooks` directory and run the Jupyter notebooks in sequential order.
3. Review the output files in the `output` directory for the clustering results.
4. Modify the code or experiment with different parameters as needed.

## Dependencies
- Python
- Pandas
- matplotlib
- NumPy
- Scikit-learn
- hvPlot
- Jupyter Notebook
-html
## Contributors
- [Navjeet Singh Ghuman,
Max Owens,
Judd Sanders ,
Zhongxuan Si
)
