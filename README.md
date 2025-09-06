# 🩺 Diabetes Prediction using Machine Learning
# 📖 Project Overview
- This project applies supervised machine learning algorithms to predict diabetes based on clinical and lifestyle attributes.
- Five models—Logistic Regression, Decision Tree, KNN, SVC, and XGBoost—were trained and compared to evaluate their effectiveness in early diabetes detection.
# 📊 Dataset
- Source: Kaggle – https://www.kaggle.com/datasets/sujithmandala/easiest-diabetes-classification-dataset/data
- Records: 128
- Features: Age, Gender, BMI, Blood Pressure, Fasting Blood Sugar, HbA1c, Family History, Smoking, Diet, Exercise, Diagnosis
# ⚙️ Methodology
- Data Preprocessing: One-hot encoding (categorical), scaling (numerical)
- Exploratory Data Analysis: Summary statistics, distributions, correlations
- Model Training: Logistic Regression, Decision Tree, KNN, SVC, XGBoost
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrices
# ✅ Results
- Top Performing Models: Logistic Regression, SVC, and XGBoost (all achieved highest accuracy and F1-score)
- Decision Tree: Performed well but slightly overfitted
- KNN: Lowest recall, less effective for this dataset
# 📌 Key Insights
- Combining clinical indicators (HbA1c, FBS) with lifestyle factors (diet, exercise, smoking) improves prediction.
- SVC, Logistic Regression, and XGBoost showed strong generalization and reliability for small healthcare datasets.
