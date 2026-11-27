# Diabetes Prediction Using Machine Learning

## 1. Project Overview

This project uses Machine Learning classification algorithms to identify whether an individual belongs to the diabetes or prediabetes group based on health-related indicators.

The goal is to explore health data, train classification models, and compare their performance using different evaluation metrics.

## 2. Dataset Information

- **Dataset Name:** CDC Diabetes Health Indicators
- **Source:** UCI Machine Learning Repository
- **Total Rows:** 253,680
- **Total Features:** 21
- **Target Column:** `Diabetes_binary`
- **Class 0:** No Diabetes
- **Class 1:** Diabetes or Prediabetes

**Dataset Link:** https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators

## 3. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 4. Project Workflow

1. Data Understanding
2. Exploratory Data Analysis (EDA)
3. Target Class Distribution Analysis
4. Train-Test Split
5. Missing Value Imputation
6. Feature Scaling
7. ColumnTransformer
8. Machine Learning Pipeline
9. Model Training
10. Model Evaluation

## 5. Machine Learning Models

Three classification algorithms were implemented:

- Logistic Regression
- Linear Support Vector Machine (SVM)
- Random Forest Classifier

## 6. Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 0.7143 | 0.3183 | 0.7601 | 0.4487 |
| Linear SVM | 0.7103 | 0.3155 | 0.7645 | 0.4467 |
| Random Forest | 0.8248 | 0.4253 | 0.4140 | 0.4196 |

### Additional Evaluation

| Model | ROC-AUC | PR-AUC |
|---|---:|---:|
| Logistic Regression | 0.8106 | 0.4121 |
| Linear SVM | 0.8103 | 0.4132 |
| Random Forest | 0.8001 | 0.4038 |

### Provisional Model Selection

Logistic Regression was provisionally selected based on its highest F1-score and ROC-AUC.

Further validation and threshold tuning are required before final model selection.

## 7. Limitations

- The dataset is based on self-reported survey information.
- The dataset represents information collected in 2015.
- The model does not predict future diabetes onset.
- Model predictions are not verified clinical diagnoses.
- Further external validation is necessary.

## 8. How to Run This Project

1. Clone or download this repository.
2. Open `diabetes_prediction.ipynb` in Google Colab or Jupyter Notebook.
3. Download the dataset from the official UCI repository.
4. Upload the dataset to your working environment.
5. Run the notebook cells sequentially.

## 9. Repository Structure

```text
diabetes-prediction-ml/
│
├── diabetes_prediction.ipynb
├── diabetes_project_summary.pdf
└── README.md
```

## 10. Disclaimer

This project is developed for educational and research purposes only. It must not be used as a substitute for professional medical advice, diagnosis, or treatment.

---

**Project:** Diabetes Prediction Using Machine Learning
