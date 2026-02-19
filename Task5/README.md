## 🚢 TASK-5  Exploratory Data Analysis (EDA)

##📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns, trends, and relationships that influenced passenger survival.

The goal is to use statistical and visual techniques to understand the dataset before applying machine learning models.

---

## 🎯 Objective

- Extract insights using statistical summaries
- Identify trends and relationships
- Visualize distributions and correlations
- Write observations for each visualization
- Summarize key findings

---

## 🛠 Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset Information

Dataset: Titanic Dataset  
Rows: 891  
Columns: 12  

### Key Features:

- PassengerId
- Survived (Target Variable)
- Pclass (Passenger Class)
- Sex
- Age
- Fare
- SibSp
- Parch
- Embarked

---

## 🔍 Steps Performed in EDA

### 1️⃣ Data Exploration
- Used `.info()` to check data types and null values
- Used `.describe()` for statistical summary
- Used `.value_counts()` for categorical analysis

### 2️⃣ Univariate Analysis
- Survival count plot
- Gender distribution
- Passenger class distribution
- Age histogram
- Fare histogram

### 3️⃣ Bivariate Analysis
- Survival vs Gender
- Survival vs Passenger Class
- Age vs Survival (Boxplot)
- Age vs Fare (Scatterplot)

### 4️⃣ Multivariate Analysis
- Correlation Heatmap
- Pairplot visualization

---

## 📊 Key Insights

- Survival rate was approximately 38%.
- Females had significantly higher survival rates than males.
- 1st class passengers survived more than 3rd class.
- Higher fare increased survival probability.
- Children had better survival chances.
- Age and Cabin columns contain missing values.
- Socioeconomic status strongly influenced survival.

---

## 📈 Visualizations Included

- Countplots
- Histograms
- Boxplots
- Scatterplots
- Heatmap
- Pairplot

---

## 📎 Project Deliverables

- Jupyter Notebook (.ipynb)
- PDF Report
- README.md

 ---

## 🧠 Conclusion

Gender, Passenger Class, and Fare were the most influential factors affecting survival on the Titanic.

The analysis highlights the importance of exploratory data analysis in understanding data patterns before building predictive models.

