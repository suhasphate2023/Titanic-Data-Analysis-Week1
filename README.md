# Titanic-Data-Analysis
internship project on data acquisition, data cleaning, preprocessing and exploratory data analysis using Python.


## 📌 Project Overview

This project focuses on data acquisition, data cleaning, preprocessing, and exploratory data analysis (EDA) using the Titanic dataset. The project was completed as part of Week 1 of an internship to demonstrate the basic data science workflow using Python.

## 🎯 Objectives

* Acquire and understand a publicly available dataset
* Inspect the structure and quality of the data
* Identify and handle missing values
* Check and remove duplicate records
* Perform data preprocessing
* Conduct exploratory data analysis
* Create meaningful visualizations
* Identify important patterns and insights

## 📊 Dataset

The Titanic dataset contains information about 891 passengers and 12 variables.

Important variables include:

* PassengerId
* Survived
* Pclass
* Name
* Sex
* Age
* SibSp
* Parch
* Ticket
* Fare
* Cabin
* Embarked

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🧹 Data Cleaning

The following preprocessing steps were performed:

1. Missing values were identified.
2. Missing Age values were replaced using the median.
3. Missing Embarked values were replaced using the mode.
4. Cabin was removed because it contained a large number of missing values.
5. Duplicate records were checked and removed if present.
6. Data types were inspected before analysis.

## 📈 Exploratory Data Analysis

The following visualizations were created:

* Passenger Survival Distribution
* Passenger Age Distribution
* Survival by Passenger Class
* Age vs Fare
* Correlation Heatmap

## 🔍 Key Findings

* The dataset contains both numerical and categorical variables.
* Missing values were mainly observed in Age, Cabin and Embarked.
* Survival patterns differed across passenger classes.
* Passenger ages covered a wide range.
* Fare and passenger class showed a noticeable relationship.
* The cleaned dataset can be used for further statistical analysis and machine-learning applications.

## 📁 Project Structure

```text
Titanic-Data-Analysis-Week1/
│
├── Titanic-Dataset.csv
├── Titanic_Analysis.ipynb
├── Titanic_Week1_Internship_Report.docx
├── visualizations/
└── README.md
```

## 🚀 Future Scope

The project can be extended by applying statistical hypothesis testing, feature engineering, and machine-learning classification algorithms to predict passenger survival.

## 👨‍💻 Author

Suhas Phate
