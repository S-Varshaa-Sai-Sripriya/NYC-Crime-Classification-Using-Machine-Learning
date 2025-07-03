# NYC Crime Classification Using Machine Learning

A statistical computing project analyzing New York City’s crime data using supervised machine learning techniques. Explored spatial, temporal, and categorical crime patterns to build models that classify crimes by borough.

![Gemini_Generated_Image_msmg1kmsmg1kmsmg](https://github.com/user-attachments/assets/e21f6750-b5f3-47a6-83f7-619398baf2a3)

> 🎓 Final Project: Statistical Computing Final Project | Stony Brook University

---

## 📌 Overview

This project leverages 360K+ crime complaint records across NYC's five boroughs. It applies data science workflows including EDA, feature engineering, data cleaning, and machine learning — all executed in **R**.

**Goal:** Predict the **borough** where a crime occurred, based on offense type, timing, and other attributes.

---

## 🔍 Key Features

- 📦 **Data Source**: [NYPD Complaint Data (2016)](https://data.world/data-society/nyc-crime-data)
- 🔎 **EDA**: Heatmaps, hexbin plots, 2D density mapping, box plots
- 🧪 **Models Used**:
  - Logistic Regression
  - Decision Tree
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Random Forest (Ensemble)
- 🧼 **Data Cleaning**: Coordinate pruning, date parsing, imputation, removal of highly correlated features
- 📊 **Evaluation**:
  - Accuracy, Confusion Matrix, Kappa Score, AUC
  - Class balancing and cross-validation

---

## 🧠 Results Snapshot

| Model              | Train Accuracy | Test Accuracy | Key Notes                          |
|-------------------|----------------|---------------|------------------------------------|
| Random Forest      | 99.87%         | 99.24%        | Top performer, excellent generalization |
| Decision Tree      | 95.66%         | 95.65%        | Simple and interpretable           |
| Logistic Regression| 92.05%         | 92.17%        | Robust, well-generalized           |
| KNN (K=3)          | 73.28%         | —             | Sensitive to neighborhood size     |
| SVM (RBF Kernel)   | 70.46%         | 66.99%        | Computationally expensive          |

---

## 🧾 Highlights

- 🔥 Created borough-specific classifiers using real crime reports
- 🌆 Uncovered strong spatial clustering in Manhattan & Bronx
- 🗓️ Detected seasonal and weekly crime peaks (Friday–Saturday nights)
- 🌐 Used correlation-based pruning to avoid overfitting
- 🧠 Leveraged ensemble learning (Random Forest) for 99%+ accuracy
