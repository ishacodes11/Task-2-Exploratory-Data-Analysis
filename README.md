# Task 2 - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project is part of my AI & ML Internship Task 2.

The objective of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The analysis focuses on understanding the dataset through descriptive statistics, data visualization, feature relationships, patterns, and potential anomalies.

## 🎯 Objectives

- Generate descriptive statistics for numerical features.
- Understand the distribution of numerical variables.
- Identify potential outliers using boxplots.
- Analyze relationships between numerical features.
- Study survival patterns across different passenger groups.
- Identify patterns, trends, and anomalies in the dataset.

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

## 📊 Dataset

The Titanic dataset was used for this analysis.

The dataset contains information about passengers, including:

- Survival status
- Passenger class
- Gender
- Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Fare
- Embarkation information

## 🔍 Exploratory Data Analysis

### 1. Dataset Inspection

The dataset was inspected to understand:

- Number of rows and columns
- Column names
- Data types
- Missing values
- Duplicate records

### 2. Descriptive Statistics

Summary statistics such as:

- Mean
- Median
- Standard deviation
- Minimum
- Maximum
- Quartiles

were calculated for numerical features.

### 3. Histograms

Histograms were created for numerical features such as:

- Age
- Fare
- SibSp
- Parch

These visualizations helped understand the distributions of the variables.

### 4. Boxplots

Boxplots were created to identify the spread of numerical variables and detect potential outliers.

The Fare variable showed noticeable high-value observations compared with most passengers.

### 5. Correlation Analysis

A correlation matrix and heatmap were created to examine relationships between numerical features.

The correlation matrix helps identify positive, negative, and weak linear relationships between variables.

### 6. Pairplot

A pairplot was created to visualize relationships between numerical features and compare them according to passenger survival status.

### 7. Survival Analysis

Survival rates were compared across:

- Gender
- Passenger class

Age distributions were also compared between passengers who survived and those who did not.

## 💡 Key Insights

- Numerical variables have different distributions and ranges.
- Fare contains some unusually high observations that can be considered potential outliers.
- Survival rates differ across passenger groups.
- Passenger class and gender show noticeable differences in survival patterns.
- Correlation analysis provides useful information about relationships between numerical variables.
- Visualization makes patterns and potential anomalies easier to identify.

## 📁 Project Files

- `Task_2_EDA.ipynb` - Google Colab/Jupyter Notebook containing the complete analysis.
- `README.md` - Project documentation.

## ✅ Conclusion

Exploratory Data Analysis was performed using descriptive statistics and multiple visualization techniques.

The analysis helped understand the structure and characteristics of the Titanic dataset, identify potential outliers, examine feature relationships, and discover differences in survival patterns between passenger groups.

EDA is an important step before applying machine-learning algorithms because it helps understand the data and identify potential issues before modeling.
