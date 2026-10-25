
# 🏥 Medical Cost Prediction

##  Project Overview

Medical Cost Prediction is a machine learning project that analyzes personal and demographic information to estimate individual medical insurance charges.

The project uses data analysis, visualization, and regression models to explore the factors associated with medical expenses and predict insurance costs.

## 🎯 Objectives

- Analyze medical insurance data to understand patterns in medical expenses.
- Explore the relationship between age, BMI, smoking habits, gender, number of children, and region with medical charges.
- Perform data preprocessing and exploratory data analysis (EDA).
- Build machine learning regression models to predict medical costs.
- Visualize patterns and relationships within the dataset.

## 🛠️ Technologies Used

- **Python** — Programming and data analysis
- **Pandas** — Data manipulation and preprocessing
- **NumPy** — Numerical computations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical data visualization
- **Scikit-learn** — Machine learning
- **Jupyter Notebook** — Development and experimentation

## 📊 Dataset

The project uses the `insurance.csv` dataset, containing 1,338 records and 7 columns.

### Dataset Features

| Feature | Description |
|---|---|
| `age` | Age of the individual |
| `sex` | Gender |
| `bmi` | Body Mass Index |
| `children` | Number of children |
| `smoker` | Smoking status |
| `region` | Residential region |
| `charges` | Medical insurance charges (target variable) |

The `charges` column is the target variable, while the remaining features are used as inputs for prediction.

## 🔄 Project Workflow

### 1. Data Loading and Exploration
- Loaded the dataset using Pandas.
- Examined the dataset structure, data types, and descriptive statistics.
- Explored the distribution of numerical and categorical variables.

### 2. Data Preprocessing
- Converted categorical variables into numerical representations.
- Prepared input features and the target variable for model training.
- Split the dataset into training and testing sets.

### 3. Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand patterns and relationships within the dataset.

The analysis included:
- Age distribution
- Gender distribution
- BMI distribution
- Number of children
- Smoking status analysis
- Medical charge distribution
- Correlation heatmap
- Medical charges by smoking status
- Relationship between age and medical charges
- Medical expenses for individuals with BMI above and below 30

### 4. Machine Learning Models

Implemented two regression models using Scikit-learn:

**Linear Regression**
- Trained a regression model to estimate medical insurance charges.
- Generated predictions using the test dataset.

**Decision Tree Regression**
- Implemented a decision tree-based regression model.
- Used the model to predict medical insurance charges.

### 5. Data Visualization

Created visualizations to explore data distributions, identify patterns, and understand relationships between medical expenses and different features.

## 📈 Visualizations

The project includes:

- Histograms for age, BMI, and medical charges
- Count plots for gender, smoking status, region, and number of children
- Correlation heatmap
- Box plots comparing medical charges by smoking status and gender
- Scatter plots showing the relationship between age and medical charges
- Actual versus predicted visualizations for the regression models

## 🔍 Key Findings

- Medical insurance charges vary across individuals with different demographic and lifestyle characteristics.
- Age and BMI are important variables to explore when analyzing medical expenses.
- Smoking status provides another useful factor for understanding differences in insurance charges.
- Regression models can be used to estimate medical costs based on the available features.
- Data visualization helps identify patterns and relationships within the insurance dataset.

## 🚀 Future Improvements

- Apply improved encoding techniques for categorical variables.
- Explore additional machine learning regression algorithms.
- Perform cross-validation and hyperparameter tuning.
- Investigate feature importance and model interpretability.
- Develop a user-friendly interface for medical cost prediction.

## 🏁 Conclusion

This project demonstrates the use of data analysis, visualization, and machine learning to estimate medical insurance charges. By exploring the insurance dataset and implementing Linear Regression and Decision Tree Regression, the project provides practical experience in data preprocessing, exploratory data analysis, and predictive modeling.

## 👩‍💻 Author

**Maheen Shahid**
