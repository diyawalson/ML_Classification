**🧠 Stroke Prediction using Machine Learning**

This project uses supervised machine learning to predict whether a person is likely to suffer a stroke based on medical and demographic features. By applying classification techniques on real-world healthcare data, this project aims to assist in early detection and prevention of strokes.

**🎯 Objective:**

The primary objective is to build a classification model that can accurately predict stroke occurrence. The project walks through a complete machine learning pipeline—from data cleaning and preprocessing to model training, evaluation, and interpretation.

**📁 Files:**

> Stroke.ipynb — Jupyter Notebook with full code, EDA, and modeling

> stroke-data.csv — The dataset used for training and evaluation

> README.md — Project documentation

**📊 Dataset Overview:**

> Source: Kaggle Stroke Prediction Dataset

> Size: ~5,000 records

> Target: stroke (1 = stroke occurred, 0 = no stroke)

**Features:**

> Demographics: gender, age, residence_type

> Health: hypertension, heart_disease, avg_glucose_level, bmi

> Lifestyle: smoking_status, work_type

**🛠 Tools & Technologies:**

> Language: Python 3.x

**Libraries:**

> pandas, numpy — Data manipulation

> matplotlib, seaborn — Data visualization

> scikit-learn — ML models and evaluation

**📈 ML Pipeline Workflow:**

> Data Exploration and Cleaning

> Handling Missing Values (bmi)

> Label & One-Hot Encoding for Categorical Variables

> Feature Scaling (if needed)

> Train-Test Split

> Model Training (KNN, Naive, SVM, Decision Tree, Random Forest)

> Model Evaluation (Accuracy, Precision, F1-Score, Recall)

> Prediction and Interpretation

**📉 Evaluation Metrics:**

> Accuracy

> Precision & Recall

> F1-Score

> Confusion Matrix

⚠️ Note: The dataset is imbalanced, so extra attention is given to Recall and F1-score to minimize false negatives.

**🔍 Key Insights:**

> Age, glucose level, and hypertension were the most influential features.

> Ensemble models (e.g., Random Forest, XGBoost) outperformed simple linear models.

> Class balancing and tuning improved minority class (stroke = 1).
