# Youtube-Trending-Data-Analysis
Regression-based ML pipeline analyzing YouTube trending videos to predict final reach using early engagement signals and feature engineering.
# YouTube Trending Video Reach Prediction

## 📌 Project Overview

This project analyzes trending YouTube videos in Germany to understand how early engagement metrics influence the final reach of a video.

The main objective is to predict **final video views** using **initial-day interaction signals**.

---

## 🎯 Problem Statement

When a video trends on YouTube, its early engagement (likes, comments, dislikes, tags) may determine its long-term reach.
This project explores that relationship and builds regression models to predict final views.

---

## 📊 Dataset

Germany YouTube Trending Videos dataset containing:

* Video metadata
* Daily engagement metrics
* Trending dates
* Tags and category information

---

## ⚙️ Data Processing & Feature Engineering

* Removed videos marked as error or removed
* Aggregated multiple trending entries into video-level summaries
* Extracted initial-day engagement metrics
* Created new feature: **tag_count**
* Applied **log transformation** to handle skewness
* Outlier inspection and visualization
* Train-test split and feature scaling

---

## 📈 Exploratory Data Analysis

Key findings:

* Strong correlation between initial likes/comments and final views
* Dislikes show weaker but positive signal
* Tag count has limited predictive power
* Engagement metrics exhibit heteroscedasticity
* Log transformation improves linear relationships

---

## 🤖 Models Implemented

* Linear Regression
* Ridge Regression (with hyperparameter tuning)
* Random Forest Regressor (with randomized search)

---

## 📏 Evaluation Metrics

* Root Mean Squared Error (RMSE)
* R² Score

---

## 🚀 Key Insights

* Early engagement strongly predicts final reach
* Log transformation significantly stabilizes variance
* Tree-based models capture nonlinear relationships better
* Regularized regression helps manage correlated features

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib
* Scikit-learn

---

## 🔮 Future Improvements

* Gradient Boosting models (XGBoost/LightGBM)
* Time-series modeling of trending dynamics
* Feature importance & SHAP explainability
* NLP analysis of video titles and tags
* Cross-country dataset comparison

---

## 👤 Author

[Your Name]
