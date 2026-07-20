# Data Analysis and Regression 2026
**5th Year MSFM Course Materials**

Welcome to the 2026 iteration of the Data Analysis and Regression course. This repository contains the Jupyter Notebooks for all 5 classes, as well as the accompanying homework assignments.

## Course Structure & Syllabus

The course is split into 5 core classes:

1. **Class 1: Introduction to Data Analysis**
   - Univariate Data Analysis (PDF/CDFs, moments, simulation)
   - Supervised Learning & Bias Variance Tradeoff
   - Geometric Interpretation of OLS

2. **Class 2: Hands-On Regression**
   - Inference and Goodness of Fit ($r^2$, F-stat, T-stat)
   - Significance Testing & Confidence Intervals
   - Diagnostics (QQ Plot, Outliers, Leverage)
   - Multicollinearity (VIF) & Residuals vs Fitted Plots
   - Generalized Least Squares (GLS) & Robust Standard Errors

3. **Class 3: Beyond OLS**
   - Regularization: Ridge, LASSO, Elastic Net
   - Robust Regression (Huber & Tukey's Biweight)
   - Bayesian Priors and Re-weighting
   - Time Series: Stationarity, AR models, ARIMA, GARCH

4. **Class 4: Curve Fitting**
   - Basis Functions (Polynomials, Splines, Gaussian/Lognormal RBFs)
   - Yield Curve Application (Nelson-Siegel / Svensson)
   - Logistic Regression

5. **Class 5: Other Data Analysis Techniques (Machine Learning)**
   - Principal Component Analysis (PCA)
   - Trees, Bagging, Random Forests, Boosting
   - Random Forest Feature Importance (Permutation & Gini)
   - Clustering (K-means, DBSCAN)

## Getting Started

1. Set up your Python environment:
   ```bash
   python3 -m venv .env
   source .env/bin/activate
   pip install -r requirements.txt
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```