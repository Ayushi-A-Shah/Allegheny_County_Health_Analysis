# Allegheny_County_Health_Analysis
A machine learning project analyzing county-level health outcomes in Allegheny County using clustering and supervised learning techniques. The project applies unsupervised methods to uncover structural patterns across health indicators and supervised models to predict outcome variables based on socioeconomic and behavioral features.

## Project Overview
Public health outcomes are shaped by a complex interaction of socioeconomic, environmental, and behavioral factors. This project explores those relationships using the County Health Rankings dataset, focusing on Allegheny County.

## The analysis combines:
- Clustering to identify latent structure across health indicators
- Regression and regularization techniques to model and interpret outcome drivers
- Model evaluation to assess predictive performance and generalization

## Notebook
The full analysis, including data preprocessing, clustering, modeling, and evaluation, is available in the Jupyter notebook:
Notebook: notebooks/allegheny_county_clustering_classification.ipynb

## Rendered Output (HTML)
A rendered HTML version of the notebook is included for easy viewing without running code.
It contains visualizations, model outputs, and results:
HTML Output: reports/allegheny_county_clustering_classification.html

## Data Source

The dataset is sourced from the County Health Rankings & Roadmaps program and includes:
Health outcomes and behaviors
Clinical care access and quality
Social and economic factors
Physical environment indicators
The analysis focuses on preprocessing, feature scaling, and dimensional consistency before modeling.

## Methods
1. Data Preprocessing
- Missing value imputation
- Feature scaling using standardization
-Train-test splitting for supervised models

2. Unsupervised Learning
- MiniBatch K-Means clustering
- Silhouette score for cluster validation
- Interpretation of cluster structure

3. Supervised Learning
- Random Forest regression
- Lasso regression with cross-validation
- Feature importance and coefficient analysis

4. Evaluation
- Mean Squared Error (MSE)
- R² score
- Comparative model performance

## Key Insights
- Clustering reveals meaningful structure across health and socioeconomic indicators
- Tree-based models capture nonlinear relationships more effectively than linear baselines
- Regularization highlights a small subset of features driving predictive performance
- Health outcomes are strongly associated with socioeconomic and behavioral variables

## How to Run This Project Locally
### Clone the repository
git clone https://github.com/Ayushi-A-Shah/Allegheny-County-Health-Analysis.git
cd Allegheny-County-Health-Analysis

## Install dependencies
pip install -r requirements.txt

## Launch Jupyter Notebook
jupyter notebook
Then open: notebooks/allegheny_county_clustering_classification.ipynb

## Future Improvements
- Extend analysis to multi-county comparisons
- Apply dimensionality reduction (PCA, UMAP)
- Evaluate additional clustering methods
- Incorporate classification targets
- Build an interactive dashboard for policymakers

License
- This project is released under the MIT License.
