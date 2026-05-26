# 🏠 End-to-End Machine Learning Project – California Housing Price Prediction

An end-to-end Machine Learning project built using Python and Scikit-Learn to predict California housing prices using demographic and geographic features.

This project follows a complete ML workflow:
- Data collection and loading
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Feature engineering
- Model training
- Hyperparameter tuning
- Model evaluation
- Final prediction pipeline

---

## 📌 Project Overview

The objective of this project is to build a machine learning pipeline capable of predicting median house values in California districts.

The workflow was designed to simulate a real-world ML development process rather than focusing only on model accuracy.

---

## 📂 Project Structure

```plaintext
.
├── 01_end_to_end_ml.ipynb     # Main notebook
├── datasets/
│   └── housing.csv
├── images/                   # Optional visualizations
├── README.md
└── requirements.txt
```

---

## 🛠 Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

---

## 🔍 Workflow

### 1. Data Loading
- Imported California Housing dataset
- Loaded and inspected data structure

### 2. Exploratory Data Analysis
- Distribution analysis
- Correlation analysis
- Visualization of housing trends
- Geographic insights

### 3. Data Preprocessing
- Missing value handling
- Feature scaling
- One-hot encoding
- Custom transformations
- Scikit-Learn pipelines

### 4. Feature Engineering
- Generated additional useful features
- Applied transformations for improved learning

### 5. Model Training
Models explored:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

### 6. Model Evaluation
Evaluation techniques:
- Cross Validation
- RMSE (Root Mean Squared Error)
- Train vs Validation comparison

### 7. Hyperparameter Tuning
Used:
- `GridSearchCV`

Optimized:
- Random Forest parameters
- Pipeline preprocessing parameters

---

## 📈 Results

Final model achieved improved performance after:
- Pipeline optimization
- Hyperparameter tuning
- Feature preprocessing

Evaluation Metric:
- **RMSE (Root Mean Squared Error)**

---

## 🚀 How to Run

### Clone the repository

```bash
git clone <your-repo-link>
cd <repo-name>
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch notebook

```bash
jupyter notebook
```

Open:

```plaintext
01_end_to_end_ml.ipynb
```

---

## 📚 Key Concepts Practiced

- Machine Learning Pipelines
- Data Cleaning
- Feature Engineering
- Cross Validation
- Model Selection
- Hyperparameter Tuning
- End-to-End ML Workflow
- Production-style preprocessing

---

## 🎯 Future Improvements

- Deploy model using Flask/FastAPI
- Add experiment tracking
- Containerize using Docker
- Build interactive dashboard

---
