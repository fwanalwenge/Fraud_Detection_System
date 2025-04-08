# 🛡️ Fraud Detection System using Machine Learning

A machine learning-based solution designed to detect fraudulent financial transactions. This project uses real-world-inspired data, advanced preprocessing, and supervised learning models to identify suspicious patterns and minimize false positives.

---

## 📌 Project Objectives

- Detect fraud using machine learning techniques
- Evaluate and compare model performance
- Serialize and save the best model for deployment
- Demonstrate end-to-end ML workflow: EDA → Modeling → Evaluation → Export

---

## 📊 Features

- ✅ Data Cleaning & Preprocessing (handling missing data, encoding, scaling)
- ✅ Exploratory Data Analysis (EDA) with visual insights
- ✅ Machine Learning models: Logistic Regression, Random Forest, XGBoost
- ✅ Hyperparameter Tuning with GridSearchCV
- ✅ Performance Evaluation using metrics like Accuracy, Precision, Recall, F1-Score, ROC-AUC
- ✅ Model Serialization using `pickle`
- ⚠️ Large model files managed via Git LFS

---

## 🚀 Tech Stack

| Tool/Library       | Purpose                     |
|--------------------|-----------------------------|
| Python             | Core programming language   |
| Pandas, NumPy      | Data manipulation           |
| Scikit-learn       | ML modeling & preprocessing |
| XGBoost            | Advanced classification     |
| Matplotlib, Seaborn| Visualization               |
| Pickle             | Model serialization         |

---

## 📁 Project Structure
Fraud_Detection_System/

├── data/                     # Folder to store raw or processed data (if not too large for version control)

│   ├── raw/                  # Raw data files (e.g., CSV, Excel)

│   └── processed/            # Processed data (e.g., cleaned, feature-engineered data)

├── notebooks/                # Jupyter Notebooks for EDA, model training, and analysis

│   ├── 01_EDA.ipynb          # Exploratory Data Analysis

│   ├── 02_modeling.ipynb     # Model training and tuning

│   └── 03_evaluation.ipynb   # Model performance evaluation

├── models/                   # Folder for model files (saved models)

│   ├── sklearn_best_model.pkl # Best performing model (Pickle format)

│   └── model.pkl             # Another version of the model (Pickle format)

├── src/                      # Python source code for preprocessing, training, evaluation, etc.

│   ├── preprocess.py         # Data preprocessing (e.g., cleaning, scaling, encoding)

│   ├── train.py              # Script for model training

│   ├── evaluate.py           # Script for model evaluation and metrics

│   └── utils.py              # Utility functions (e.g., helper functions for data loading)

├── requirements.txt          # Python dependencies (e.g., scikit-learn, pandas)

├── .gitignore                # Files to ignore by Git (e.g., models, data files)

├── README.md                 # Project overview and instructions

└── LICENSE                   # Project license (e.g., MIT License)

