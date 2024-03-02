# ev-forecasting      


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
- NumPy
- Scikit-learn
- hvPlot
- Jupyter Notebook
-html
## Contributors
- [Navjeet Ghuman
Max Owens
Judd Sanders 
Zhongxuan Si
)
