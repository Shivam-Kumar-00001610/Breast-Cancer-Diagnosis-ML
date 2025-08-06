# 🧠 Breast Cancer Diagnosis - Data Analysis & Prediction

This project explores the **Breast Cancer Wisconsin Diagnostic Dataset** to build a machine learning model that can classify tumors as **malignant** or **benign** based on various medical imaging features.

Through exploratory data analysis (EDA), feature reduction, and supervised classification, this notebook demonstrates how data science can contribute to early and accurate cancer detection.

---

## 📂 Project Structure

- `Breast Cancer Data Analysis.ipynb`: Main Jupyter notebook with data cleaning, visualization, and modeling
- `Breast_cancer_dataset.csv`: The dataset used in the analysis
- `README.md`: Project documentation

---

## 🧬 Dataset Overview

- **Source:** UCI Machine Learning Repository
- **Observations:** 569 tumor samples
- **Features:** 30 numerical features derived from digitized images of fine needle aspirate (FNA) of breast masses
- **Target Variable:** `diagnosis`  
  - `M` = Malignant  
  - `B` = Benign

---

## 🔍 Key Components

### ✅ Data Preprocessing
- Dropped irrelevant columns (`id`, `Unnamed: 32`)
- Mapped categorical target variable to binary
- Handled multicollinearity by removing highly correlated features

### 📊 Exploratory Data Analysis (EDA)
- Count plots, correlation heatmap, and boxplots by diagnosis
- Insight into how feature values vary between benign and malignant cases

### 🤖 Modeling
- Trained machine learning models for binary classification
- Evaluated using metrics such as:
  - Accuracy
  - Precision & Recall
  - ROC-AUC Score
  - Confusion Matrix

---

## 💡 Conclusion
