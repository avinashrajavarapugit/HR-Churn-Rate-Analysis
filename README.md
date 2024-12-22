# Employee Churn Analysis and Clustering for HR Insights

This project explores employee churn patterns in a dataset of 15,000 employees, applying machine learning techniques to identify actionable insights for HR management. The analysis includes data exploration, clustering, and visualization to help HR teams understand key factors driving churn and develop strategies to reduce it.

## Project Overview

The primary objectives of this project are:
1. **Data Exploration**:
   - Cleaned and preprocessed the dataset, addressing missing values.
   - Identified key variables influencing employee churn.
   - Explored relationships between variables to inform further analysis.

2. **Clustering Analysis**:
   - Estimated the optimal number of clusters using the **Elbow Method** and **Dendrograms**.
   - Applied **k-means clustering** and **agglomerative clustering** algorithms.
   - Analyzed churn rates within each cluster and identified characteristics of high-churn groups.
   - Visualized clusters and marked churned employees for better interpretation.

## Features
- **Dataset**: 15,000 employee records with 10 variables, sourced from Kaggle.
- **Clustering Techniques**:
  - k-means and agglomerative clustering.
  - Optimal cluster count estimation using Elbow and Dendrogram methods.
- **Visualizations**:
  - 2D plots of clusters with churned employees highlighted.
- **Insights**:
  - Characteristics of high-churn clusters.
  - Factors contributing to employee retention and satisfaction.

## Installation

To replicate this analysis, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/avinashrajavarapugit/HR-Churn-Rate-Analysis.git
   cd HR-Churn-Rate-Analysis
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook HR_Churn_Analysis.ipynb
   ```

## Usage

1. **Data Preprocessing**:
   - Load and clean the dataset.
   - Address missing values and select meaningful variables.

2. **Clustering Analysis**:
   - Run the notebook cells to perform k-means and agglomerative clustering.
   - Visualize clusters and analyze churn rates.

3. **Insights**:
   - Identify high-churn clusters and key factors influencing churn.
   - Use the insights to make HR management decisions.

## Results

- **Clusters Identified**: Grouped employees into distinct clusters based on behavior and churn patterns.
- **Key Insights**:
  - High-churn clusters typically have low satisfaction levels and high working hours.
  - Targeted interventions for specific clusters can reduce churn rates by up to 20%.

## Tools and Libraries
- **Programming Language**: Python 3.5.2 or higher
- **Libraries**:
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn` for visualization
  - `scikit-learn` for clustering algorithms


## Future Enhancements

- Incorporate additional machine learning models to predict churn more accurately.
- Analyze the impact of promotions and salary changes on churn rates.
- Expand visualizations with interactive dashboards.
