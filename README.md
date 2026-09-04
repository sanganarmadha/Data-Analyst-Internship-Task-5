# Task 5 – Exploratory Data Analysis (EDA)

## 📌 Project Title
Exploratory Data Analysis on Titanic Dataset

## 🎯 Objective
The objective of this task is to perform Exploratory Data Analysis (EDA)
on the Titanic dataset to identify important patterns, trends,
relationships, missing values, and possible anomalies.

## 🛠️ Tools and Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Dataset

The Titanic dataset contains information about passengers who travelled
on the Titanic.

Important variables used in the analysis include:

- `survived` – Survival status
- `pclass` – Passenger class
- `sex` – Gender
- `age` – Passenger age
- `fare` – Ticket fare
- `embarked` – Port of embarkation

## 🔍 Analysis Performed

The following EDA techniques were performed:

### 1. Data Understanding
- Displayed the first few records
- Checked dataset shape
- Examined column names
- Checked data types
- Generated statistical summaries

### 2. Missing Value Analysis
- Identified missing values
- Calculated missing-value percentages
- Visualized missing values
- Handled missing values where required

### 3. Univariate Analysis
- Survival count
- Passenger class distribution
- Age histogram
- Age boxplot

### 4. Bivariate Analysis
- Survival vs Gender
- Survival vs Passenger Class
- Age vs Fare scatterplot

### 5. Multivariate Analysis
- Correlation matrix
- Correlation heatmap
- Pairplot

## 📈 Key Findings

- The number of passengers who did not survive was higher than those
  who survived.
- Gender showed an important relationship with survival.
- Passenger class was associated with survival outcomes.
- Passenger ages were distributed across different age groups.
- Fare values varied considerably among passengers.
- Missing values were present in some columns.
- Correlation analysis helped identify relationships between numerical
  variables.

## 📁 Files Included

```text
Task-5-EDA-Titanic/
│
├── Task_5_EDA_Titanic.ipynb
├── Task_5_EDA_Titanic_Report.pdf
├── titanic.csv
└── README.md
