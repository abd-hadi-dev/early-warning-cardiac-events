# early-warning-cardiac-events
AI/ML Internship Project - Data Cleaning for Heart Risk Prediction

This project is part of my AI/ML internship. The goal is to clean and prepare health data for predicting cardiac events using machine learning.

## 📁 Files Included
- `heart_cleaning.ipynb`: Notebook with step-by-step data preprocessing
- `data/heart_raw.csv`: Original raw dataset
- `data/heart_cleaned.csv`: Cleaned and normalized dataset

## 🧰 Tools Used
- Python
- Pandas, NumPy
- Matplotlib & Seaborn (for visualization)
- Scikit-learn (for preprocessing & scaling)

## 📊 Techniques Covered
- Handling missing and invalid values
- Encoding categorical features
- Feature scaling
- Outlier detection

## 🎯 Prediction Target
- `RiskOfUpcomingCardiacEvent` — 1 = High Risk, 0 = Low Risk

## ✅ Task 2: Exploratory Data Analysis (EDA)
- Generated summary statistics (mean, median, std, etc.)
- Visualized distributions with histograms and boxplots
- Explored feature relationships using a correlation matrix and pairplot
- Compared key features (heart rate, BP, cholesterol) across cardiac event groups
- Included an optional interactive Plotly chart
- Gained early insights for feature importance and risk prediction

🗂 Notebook: [`heart_EDA.ipynb`](./heart_EDA.ipynb)

# 💓 Heart Risk Prediction using Logistic Regression

## 📌 Objective
Build a binary classification model to predict the risk of an upcoming cardiac event using Logistic Regression.

## 📁 Dataset
- `heart_cleaned.csv`: Preprocessed dataset
- Target: `RiskOfUpcomingCardiacEvent` (0 = Not at Risk, 1 = At Risk)

## 🛠️ Tools Used
- Python, Pandas, Scikit-learn, Matplotlib, Seaborn

## 🔍 Workflow
1. Loaded cleaned heart dataset
2. Performed train-test split and feature scaling
3. Trained Logistic Regression model
4. Made predictions and evaluated using:
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1)
   - ROC-AUC Score and Curve
5. Tuned threshold for improved recall
6. Explained sigmoid function

## 📈 Key Metrics
- Confusion Matrix
- ROC-AUC Score
- Threshold tuning to balance recall and precision

## 📂 Files
- `logistic_regression_heart_prediction.ipynb`: Complete notebook
- ROC Curve and confusion matrix included in notebook output

