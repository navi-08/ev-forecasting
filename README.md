# ev-forecasting      
## Stock Clustering Analysis Summary

Report 1.  

Based on the provided stock analysis report:

1. Clustering using K-means:
   - The elbow method suggests that the optimal number of clusters is 3, with an inertia value of 32.131941.
   - The sum of explained variance ratio of the principal components in PCA is approximately 98.82%.

2. Top Companies in Each Cluster:
   - Cluster 0: These companies are characterized by negative or low growth rates.
     - VWAGY, PII, RIVN, HMC, GWLLY, GELYF, DNFGF, EVTV, NIO, GM, F, HYZN, KNDI, LCID, FUV, PSNY, SOLO, NKLA, GOEV, FSR, CENN, FFIE, MULN
   - Cluster 1: These companies have relatively higher annual and monthly growth rates.
     - ISUZY, MBGYY
   - Cluster 2: These companies exhibit moderate to high annual and monthly growth rates.
     - TSLA, HYMTF, MAHMF, LI, FUJHY, MZDAY, VLVLY, RACE, BMWYY, XPEV, NSANY, TM, ARGGY, RNLSY, BYDDF

3. Conclusion:
   - The analysis categorizes companies into three clusters based on their growth rates: low growth, moderate growth, and high growth.
   - Companies in Cluster 2 are expected to have higher growth potential, while those in Cluster 1 may have moderate growth. Cluster 0 companies are likely facing challenges in growth.
   - Investors can use this information to identify potential investment opportunities based on the growth prospects of individual companies and clusters.


Prediction report 2

Based on the clustering analysis using K-means, the companies have been grouped into different clusters based on their growth patterns. Here's a summary of the findings:

**Cluster Analysis using K-means:**

- Number of clusters (k): 3
- Inertia: 30.311200

**Cluster 0 (High Growth Potential):**
- Companies with positive growth potential.
TSLA, HYMTF, MAHMF, LI, FUJHY, MZDAY, VLVLY, RACE, BMWYY, XPEV, NSANY, TM, BYDDF, ARGGY, RNLSY, NKLA, GOEV, FSR, CENN, FFIE, MULN.

**Cluster 1 (Average Growth):**
- Companies with average growth potential.
-  ISUZY, MBGYY.

**Cluster 2 (Low Growth or No Growth):**
- Companies with low or negative growth potential.
- VWAGY, PII, RIVN, HMC, GWLLY, GELYF, DNFGF, EVTV, NIO, GM, F, HYZN, KNDI, LCID, FUV, PSNY, SOLO.

Based on this analysis, investors may consider investing in companies from Cluster 0, as they have higher growth potential. Companies in Cluster 1 may also be considered for investment, as they exhibit average growth potential
Comparing the two reports, we can see some similarities and differences in the clustering results and top companies identified. Here's a summary:

**Similarities:**
- Both reports use K-means clustering with the optimal number of clusters determined to be 3.
- Both reports identify clusters representing companies with high growth potential, average growth, and low or no growth.
- The top companies in Cluster 0 (high growth potential) are largely consistent between the two reports.

**Differences:**
- The inertia values and explained variance ratios differ slightly between the two reports.
- There are differences in the composition of companies within each cluster, particularly in Clusters 1 and 2.
- The order of the top companies within each cluster may vary between the two reports.

**Top 10 Companies:**
Based on the similarities between the two reports and considering the top companies in Cluster 0 (high growth potential), here are the top 10 companies:

1. TSLA
2. HYMTF
3. MAHMF
4. LI
5. FUJHY
6. MZDAY
7. VLVLY
8. RACE
9. BMWYY
10. XPEV

These companies consistently appear as top performers in terms of growth potential across both reports.


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
  -Machine Learning(Unsupervised)
## Contributors
- [Navjeet Singh Ghuman,
Max Owens,
Judd Sanders ,
Zhongxuan Si
) 
