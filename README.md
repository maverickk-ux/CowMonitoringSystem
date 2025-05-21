# CowMonitoringSystem
This is a comprehensive AI/ML based project which was done as a part of Aivancity Summer School Program 2025.

# 🐄 Cow Calving Ease Prediction (Agriculture Sector)

## 📌 Project Overview

This project focuses on predicting the **Calving Ease Score (CES)** of cows using behavioral data. CES indicates how easy or difficult the calving (birthing) process was for a cow, scored on a scale from 1 (very easy) to 5 (very difficult):

- **1**: Quick, easy birth without assistance  
- **2**: More than two hours of labor, but no assistance  
- **3**: Minimal assistance, but no difficulty in calving  
- **4**: Obstetrical chain was used  
- **5**: Extremely difficult birth requiring mechanical assistance  

Early identification of calving difficulty can improve animal welfare, reduce postpartum recovery time, and increase milk yield by minimizing production gaps.

---

## 🧠 Objective

To build a machine learning classification model that can predict the CES score based on behavioral features such as:
- Lying time
- Standing time
- Rumination time
- Walking speed
- Eating time
- Steps taken  
... and other sensor-based data.

---

## 🧪 Technical Tasks

- ✅ Build a Python-based machine learning pipeline for classification.
- ✅ Predict the CES score ranging from 1 to 5.
- ✅ Implement and compare algorithms including:
  - Logistic Regression
  - Random Forest
  - XGBoost

---

## 📁 Dataset

- `cowmonitoringsystem.csv`  
  Provided via course Blackboard.

This dataset contains cow activity data recorded over a period, which is used to train and evaluate the prediction models.

---

## ⚙️ Features and Engineering

- Label encoding for categorical columns.
- Imputation of missing numeric values.
- Feature engineering for ratios and interactions:
  - `lying_time * steps`
  - `eating_time / standing_time`
  - `rumination_time / walking_speed`
- Scaled and cleaned for machine learning pipelines.

---

## 📊 Evaluation Metrics

- Accuracy
- Cross-validation scores
- Weighted F1 Score
- Classification report

---

## 🧭 Ethical Inquiry

This project also explores **AI ethics in agriculture**, including:

### 🔍 Bias
> Can the algorithm fairly detect all CES levels without underrepresenting certain scores?

### 👩‍🌾 Farmer/Cow Interactions
> Will widespread use of such predictions alter how farmers monitor or handle their livestock?

### 🏛️ Societal Implications
> How could automated CES prediction change perceptions of farming, labor, and care?

### 🐮 Animal Welfare
> Could reliance on prediction systems compromise or enhance animal welfare?

---

## 📌 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/cow-calving-ease-prediction.git
   cd cow-calving-ease-prediction

## Contributera
1. K V Shashank Pai
2. Suyash Gupta
3. Vishal Sriram
