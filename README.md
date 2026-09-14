# 🏠 House Price Prediction Using Linear Regression

## 📌 Project Overview

This project focuses on predicting house sale prices using machine learning techniques. The **Ames Housing Dataset** was used to build and evaluate a Linear Regression model.

The project covers the complete machine learning workflow, including data loading, exploratory data analysis, data cleaning, feature selection, categorical encoding, model training, evaluation, visualization, and model interpretation.

## 🎯 Objective

The main objective is to develop a machine learning model that can predict house prices based on different characteristics of a property, such as:

- Overall house quality
- Living area
- Neighborhood
- Year built
- Number of bedrooms
- Number of bathrooms
- Garage capacity
- Basement area

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

## 📂 Dataset

The project uses the **Ames Housing Dataset**.

- **Rows:** 2,930
- **Columns:** 82
- **Target Variable:** `SalePrice`

The `TestData.csv` file was kept separate and was not used during model training or evaluation.

## 🔍 Exploratory Data Analysis

The following analyses were performed:

- Dataset structure and dimensions
- First rows of the dataset
- Missing-value analysis
- Descriptive statistics
- House-price distribution
- Numerical feature correlation
- Correlation heatmap

## 🧹 Data Preprocessing

### Missing Values

Missing numerical values were handled using the **median**.

Missing categorical values were handled using the **most frequent value**.

### Categorical Variables

Categorical variables were converted into numerical representations using **One-Hot Encoding**.

## 🎯 Feature Selection

Important predictors considered included:

- `Overall Qual`
- `Gr Liv Area`
- `Garage Cars`
- `Total Bsmt SF`
- `Year Built`
- `Full Bath`
- `Bedroom AbvGr`
- `Neighborhood`

Feature selection was supported by correlation analysis and domain reasoning.

## 🤖 Machine Learning Models

### Linear Regression

Linear Regression was the primary model.

The data was divided into:

- **80% Training Data**
- **20% Testing Data**

### Ridge Regression

Ridge Regression was used as a bonus comparison model.

### Lasso Regression

Lasso Regression was also used as a bonus comparison model.

## 📊 Model Evaluation

The models were evaluated using:

- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

Lower MSE and RMSE indicate better performance, while a higher R² indicates that the model explains more variation in house prices.

## 📈 Visualizations

The project includes:

- House Price Distribution
- Correlation Heatmap
- Actual vs Predicted Prices
- Residual Plot

## 📌 Coefficient Analysis

Linear Regression coefficients were analyzed to identify features with the strongest positive and negative relationships with predicted house prices.

A positive coefficient indicates an association with a higher predicted price, while a negative coefficient indicates an association with a lower predicted price, while holding other model features constant.

## 📁 Project Structure

```text
House-Price-Prediction/
│
├── AmesHousing.csv
├── TestData.csv
├── House_Price_Prediction.ipynb
└── README.md
```

## 🚀 How to Run

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open `House_Price_Prediction.ipynb` and run the cells from top to bottom.

## 📋 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Exploratory Data Analysis
   ↓
Missing Value Handling
   ↓
Feature Selection
   ↓
One-Hot Encoding
   ↓
Train/Test Split (80/20)
   ↓
Linear Regression
   ↓
Predictions
   ↓
MSE / RMSE / R²
   ↓
Visualization
   ↓
Coefficient Analysis
   ↓
Ridge & Lasso Comparison
```

## 💡 Key Learning Outcomes

- Data loading and exploration
- Data cleaning
- Missing-value handling
- Feature selection
- One-Hot Encoding
- Train/test splitting
- Linear Regression
- Ridge and Lasso Regression
- Model evaluation
- Data visualization
- Residual analysis
- Model coefficient interpretation

## 👨‍💻 Author

**Yonas Alene**

Information Technology Graduate  
Jimma University

## 📄 License

This project was created for educational and learning purposes.
