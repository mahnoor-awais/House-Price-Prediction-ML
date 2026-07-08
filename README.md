# 🏡 House Price Prediction using Multiple Linear Regression

A beginner-friendly Machine Learning project that predicts house prices using Multiple Linear Regression and the King County Housing dataset.

This project follows a complete Machine Learning workflow—from understanding the dataset to evaluating the final model.

---

## 🎯 Project Objective

The goal of this project is to predict the selling price of a house based on its characteristics such as:

- Bedrooms
- Bathrooms
- Living Area
- House Grade
- View
- Condition

Instead of jumping directly into model training, this project focuses on understanding the data first and then building an interpretable machine learning model.

---

## 📂 Dataset

**Dataset:** King County House Sales Dataset

Number of records: **21,613**

Number of columns: **21**

### Target Variable

- `price`

### Features Used

- bedrooms
- bathrooms
- sqft_living
- grade
- view
- condition

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading

- Loaded the CSV dataset using Pandas.

### 2. Data Inspection

Performed:

- Dataset shape
- Column inspection
- Data types
- Missing value analysis
- Duplicate detection
- Statistical summary

### 3. Exploratory Data Analysis (EDA)

Performed visualizations including:

- Distribution of House Prices
- Living Area vs Price
- Bathrooms vs Price
- Bedrooms vs Price
- Correlation Heatmap

### 4. Feature Selection

Selected the following features:

```python
[
    "bedrooms",
    "bathrooms",
    "sqft_living",
    "grade",
    "view",
    "condition"
]
```

### 5. Model Building

Algorithm used:

- Multiple Linear Regression

Workflow:

- Train/Test Split
- Model Training
- Predictions
- Performance Evaluation

---

## 📈 Model Performance

| Metric                         | Score       |
| ------------------------------ | ----------- |
| Mean Absolute Error (MAE)      | **156,751** |
| Root Mean Squared Error (RMSE) | **247,929** |
| R² Score                       | **0.593**   |

---

## 📚 What I Learned

During this project I learned:

- Understanding a dataset before training a model
- Performing Exploratory Data Analysis (EDA)
- Detecting unusual values and outliers
- Feature selection
- Correlation analysis
- Building a Multiple Linear Regression model
- Evaluating regression models using:
  - MAE
  - RMSE
  - R² Score

---

## 🚀 Future Improvements

- Perform feature engineering
- Handle outliers
- Use all relevant features
- Encode categorical variables when required
- Compare different regression algorithms
- Hyperparameter tuning
- Improve model accuracy

---

## 📁 Project Structure

```
house-price-prediction/
│
├── data/
│   └── kc_house_data.csv
│
├── notebooks/
│   └── House_Price_Prediction_Linear_Regression.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ⭐ Acknowledgements

Dataset: King County House Sales Dataset

This project was built as part of my Machine Learning learning journey to understand the complete workflow of a regression problem using Scikit-Learn.
