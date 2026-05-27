# End-to-End Machine Learning Pipeline for California Housing Price Prediction

An end-to-end supervised machine learning project built using Scikit-Learn to predict median housing values in California districts.

This project implements a complete machine learning workflow including exploratory analysis, preprocessing, feature engineering, model selection, hyperparameter optimization, and evaluation using reproducible pipelines.

---

## Problem Statement

Predict the **median house value** of California housing districts using demographic and geographic attributes.

This project focuses on building a scalable and reproducible ML pipeline rather than optimizing purely for predictive performance.

---

## Dataset

Dataset: California Housing Dataset

Target Variable:
- `median_house_value`

Input Features include:
- Longitude
- Latitude
- Housing median age
- Total rooms
- Total bedrooms
- Population
- Households
- Median income
- Ocean proximity

---

## Repository Structure

```plaintext
.
├── 01_end_to_end_ml.ipynb
└── README.md
```

---

## Machine Learning Workflow

### 1. Data Loading and Exploration

- Dataset import and inspection
- Statistical summaries
- Missing value identification
- Distribution visualization
- Correlation analysis

Techniques:
- Histograms
- Scatter plots
- Correlation matrices

---

### 2. Data Preprocessing

Constructed preprocessing pipelines using Scikit-Learn.

Operations performed:

#### Numerical Features
- Missing value imputation
- Standardization
- Feature scaling

#### Categorical Features
- One-hot encoding

#### Pipeline Components
- `Pipeline`
- `ColumnTransformer`
- `SimpleImputer`
- `StandardScaler`
- `OneHotEncoder`

---

### 3. Feature Engineering

Applied transformations to improve model performance.

Examples:
- Derived ratio-based features
- Geographic feature transformations
- Radial basis feature generation
- Cluster-based feature generation

---

### 4. Model Development

Models evaluated:

### Linear Regression
Baseline linear model for comparison.

### Decision Tree Regressor
Captures nonlinear feature relationships.

### Random Forest Regressor
Ensemble learning approach using multiple decision trees.

---

### 5. Model Evaluation

Evaluation methodology:

- Train/Validation separation
- Cross-validation
- Error analysis

Primary Metric:

\[
RMSE=\sqrt{\frac{1}{n}\sum_{i=1}^{n}(y_i-\hat y_i)^2}
\]

Used:
- `cross_val_score`
- `mean_squared_error`

---

### 6. Hyperparameter Optimization

Performed hyperparameter search using:

```python
GridSearchCV
```

Parameters explored included:

- Number of geographic clusters
- Maximum feature subset size
- Pipeline configuration tuning

Objective:

```plaintext
Minimize Validation RMSE
```

---

## Libraries and Dependencies

Install manually:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

Main libraries used:

```plaintext
numpy
pandas
matplotlib
scikit-learn
jupyter
```

Core Scikit-Learn Modules:

```plaintext
model_selection
pipeline
compose
preprocessing
impute
ensemble
tree
linear_model
metrics
cluster
```

---

## Running the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```plaintext
01_end_to_end_ml.ipynb
```

Run all cells sequentially.

---

## Concepts Demonstrated

- End-to-End ML Pipeline Design
- Exploratory Data Analysis
- Feature Engineering
- Data Transformation
- Ensemble Learning
- Cross Validation
- Hyperparameter Search
- Regression Modeling
- Reproducible ML Workflows
