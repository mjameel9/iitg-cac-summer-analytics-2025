# 🌱 NDVI Classification Hackathon Project

<p align="center">
  <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExdzQ1Nzl4Zng0NDNydnR4dmk1a3Jua3B2em1pamM1cHB4bWp4bDRwYyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l3V0megwbBeETMgZa/giphy.gif" width="250" alt="NDVI Animation"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Model-LightGBM-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Accuracy-99%2B%25-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Hackathon-IIT%20Guwahati-orange?style=for-the-badge"/>
</p>

---

## 🏆 Summer Analytics First Hackathon (Week 2) — IIT Guwahati

Welcome to the NDVI Classification project! This repository contains a powerful, beginner-friendly notebook for classifying vegetation using NDVI (Normalized Difference Vegetation Index) satellite data. The project was created as part of the Summer Analytics First Hackathon (Week 2) conducted by the Consulting & Analytics Club at the IIT Guwahati.

---

## 🚀 Project Overview

- **Goal:** Classify land cover types (e.g., water, forest) using NDVI time series data.
- **Data:** Satellite NDVI values for multiple dates per sample, provided in `hacktrain.csv` (train) and `hacktest.csv` (test).
- **Approach:**
  - Data cleaning and imputation
  - Feature engineering (statistics, trends, rolling features)
  - Model training with cross-validation
  - Pseudo-labeling for semi-supervised learning
  - Submission file generation

---

## 📁 Dataset Details

- **`hacktrain.csv`**: Training data with NDVI values, sample IDs, and class labels.
- **`hacktest.csv`**: Test data with NDVI values and sample IDs (no labels).
- Both files contain NDVI columns for different dates (e.g., `20150720_N`, `20150602_N`, ...).

---

## 📓 Notebooks

### 1️⃣ `ndvi-classification-with-lightgbm.ipynb` — LightGBM & Advanced Features

- **Model:** LightGBM (Gradient Boosted Trees)
- **Techniques:**
  - Data imputation (interpolation + mean)
  - Advanced feature engineering (trends, differences, rolling stats)
  - Stratified K-Fold cross-validation
  - Pseudo-labeling for semi-supervised learning
  - Feature importance analysis
- **Why use it?**
  - Fast, powerful, and handles complex patterns
  - Shows how boosting and feature engineering can push accuracy even higher

---

## 🧩 How to Use

1. **Clone this repo or download the files.**
2. **Install requirements:**
   - Python 3.13.2
   - `pandas`, `numpy`, `scikit-learn`, `lightgbm`, `jupyter`
3. **Open notebook in Jupyter or VS Code.**
4. **Run all cells.**
5. **Check the generated submission file:**
   - `submission.csv`

---

## 🧪 Example Workflow

```python
# Load data
train = pd.read_csv('hacktrain.csv')
test = pd.read_csv('hacktest.csv')

# Feature engineering, model training, pseudo-labeling...
# See the notebooks for full code and explanations!
```

---

## 🏅 About the Hackathon

- **Event:** Summer Analytics 2025 - Consulting & Analytics Club - IIT Guwahati
- **Week:** First Hackathon (Week 2)
- **Organizer:** IIT Guwahati
- **Challenge:** Classify land cover using NDVI time series
- **Skills:** Data cleaning, feature engineering, ML modeling, semi-supervised learning

---

<p align="center">
  <img src="https://www.clipartmax.com/png/middle/334-3342031_iit-guwahati-logo.png" width="120" alt="IIT Guwahati Logo"/>
  <img src="https://www.kaggle.com/static/images/site-logo.png" width="120" alt="Kaggle Logo"/>
</p>

---