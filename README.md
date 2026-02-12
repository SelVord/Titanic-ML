# 🚢 Titanic Survival Prediction (Kaggle)

Machine Learning project for predicting passenger survival on the Titanic using classification models.

This project demonstrates a full ML workflow:
- data cleaning
- feature engineering
- preprocessing pipelines
- model training
- evaluation
- Kaggle submission

---

## 📊 Problem

Predict whether a passenger survived the Titanic disaster.

Target:
- 1 → Survived
- 0 → Died

Dataset: Kaggle Titanic Competition

---

## 🛠 Tech Stack

- Python
- pandas
- numpy
- scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```
titanic-ml/
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│   └── ML_Titanic.ipynb
│
├── models/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

```bash
git clone https://github.com/SelVord/titanic-ml.git
cd titanic-ml

python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows

pip install -r requirements.txt
```

---

## 🚀 Workflow

### 1. Exploratory Data Analysis
- missing values
- distributions
- correlations

### 2. Feature Engineering
- Title extraction from Name
- Family size
- Cabin grouping
- Encoding categorical features

### 3. Preprocessing
- Imputation
- Scaling
- One-hot encoding
- sklearn Pipelines

### 4. Modeling
- Building model
- Model tuning

### 5. Evaluation
- Accuracy
- Cross-validation
