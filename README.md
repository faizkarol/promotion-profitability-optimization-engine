# Promotion Profitability Optimization Engine (PPOE)

Machine learning and analytics engine for predicting FMCG promotion ROI and recommending profit-maximizing campaign strategies using clustering, regression, and decision-support logic.

---

# Project Overview

Promotional campaigns in the FMCG industry often involve significant spending without clear visibility into profitability outcomes. This project develops a data-driven analytics engine capable of forecasting promotional Return on Investment (ROI), segmenting campaign performance, and recommending high-performing promotion strategies.

The project was developed around a simulated FMCG business environment inspired by real-world promotional structures used in the German confectionery sector.

---

# Business Problem

FMCG companies frequently struggle with:

- Inefficient promotional spending
- Low-ROI campaigns
- Lack of predictive planning
- Poor visibility into promotion effectiveness
- Manual decision-making based on intuition rather than analytics

This project addresses these challenges by combining machine learning, clustering, and recommendation logic into a unified decision-support workflow.

---

# Objectives

The main objectives of the project were:

- Analyze promotion performance patterns
- Predict campaign ROI using machine learning
- Segment promotions using clustering techniques
- Identify high-performing promotional configurations
- Build recommendation logic for future campaign planning

---

# Tech Stack

## Programming & Analytics
- Python
- Pandas
- NumPy
- Scikit-learn

## Visualization
- Matplotlib
- Seaborn

## Machine Learning
- Random Forest Regression
- Random Forest Classification
- K-Means Clustering
- PCA

## Model Storage
- Joblib / Pickle

---

# Repository Structure

```text
promotion-profitability-optimization-engine/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
├── models/
└── README.md
```

---

# Dataset

The project uses a synthetically generated FMCG promotions dataset designed to simulate realistic promotional scenarios while preserving confidentiality.

The dataset includes:

- Promotion types
- Product categories
- Sales metrics
- Promotion costs
- Gross margins
- ROI values
- Channel information
- Promotional duration

---

# Methodology

## 1. Data Cleaning & Preparation

Performed:

- Missing value handling
- Duplicate removal
- Feature engineering
- Data normalization
- ROI calculations
- Promotion efficiency metrics

---

## 2. Clustering Analysis

K-Means clustering was used to identify promotion performance segments.

Key variables included:

- Promo Cost
- Units Sold
- Gross Margin
- ROI
- Promotion Efficiency Score

Principal Component Analysis (PCA) was used for cluster visualization.

---

## 3. ROI Prediction

A Random Forest Regressor was trained to predict promotion ROI using features such as:

- Promotion Type
- Channel
- Promo Duration
- Sales Metrics
- Promotion Cost
- Product Category

### Model Performance

| Model | R² Score | RMSE |
|------|------|------|
| Linear Regression | 0.85 | 8.5 |
| Gradient Boosting | 0.96 | 4.2 |
| Random Forest Regressor | 0.98 | 3.08 |

The Random Forest model achieved the strongest predictive performance.

---

## 4. ROI Classification

Promotions were classified into:

- Low ROI
- Medium ROI
- High ROI

A Random Forest Classifier was used to support promotion categorization and interpretability.

---

## 5. Recommendation Engine

A rule-based recommendation system was implemented to identify:

- Repeat-worthy promotions
- Promotions requiring optimization
- Underperforming campaigns

Recommendation logic considered:

- Predicted ROI
- Gross Margin
- Cluster membership
- Historical promotion behavior

---

# Key Insights

- Promotion cost and units sold during campaigns were the strongest ROI predictors.
- Short-duration campaigns frequently produced high ROI clusters.
- Certain promotion-channel combinations consistently underperformed.
- Clustering revealed distinct strategic campaign segments.
- Recommendation logic helped filter low-performing campaign structures.

---

# Results

The project successfully demonstrated how machine learning and analytics can support:

- Promotion planning
- ROI forecasting
- Campaign optimization
- Business decision support
- Strategic resource allocation

---

# Future Improvements

Potential future enhancements include:

- Power BI dashboard integration
- Real-time prediction pipelines
- External market variable integration
- Cloud deployment
- Streamlit dashboard application
- Automated recommendation APIs

---

# Files Included

## Datasets
- Raw promotional dataset
- Cleaned analytical dataset

## Notebook
- Full end-to-end analysis notebook

## Model
- Trained ROI prediction model (.pkl)

---

# Disclaimer

This project was originally developed as part of a university consulting and analytics project focused on FMCG promotion optimization. The dataset used is synthetically generated for educational and analytical purposes.

---

# Author

Faiz Nizamuddin Karol

LinkedIn: https://linkedin.com/in/faiz-karol
