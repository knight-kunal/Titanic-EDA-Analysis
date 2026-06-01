# Titanic Dataset - Exploratory Data Analysis (EDA)

## Objective
Perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand patterns, trends, correlations, and important insights using statistics and visualizations.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Dataset

Titanic Dataset

Features include:
- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

---

## Tasks Performed

### 1. Data Loading
- Imported dataset using Pandas.

### 2. Data Inspection
- Checked shape
- Checked data types
- Missing values analysis
- Statistical summary

### 3. Data Cleaning
- Filled missing Age values using median.
- Filled missing Embarked values using mode.
- Dropped Cabin column because of excessive missing values.

### 4. Data Visualization

Created:
- Histograms
- Boxplots
- Survival Count Plot
- Survival by Gender
- Survival by Passenger Class
- Correlation Heatmap
- Pairplot

### 5. Insights

- Female passengers had a higher survival rate.
- First-class passengers survived more frequently.
- Fare distribution is highly skewed.
- Age contains several outliers.
- Passenger class and fare influence survival.

---

## Files Included

- Titanic_EDA.ipynb
- train.csv
- README.md
- Generated Visualizations

---

## Conclusion

EDA helps understand data characteristics before machine learning model development. Through visualizations and statistical analysis, important patterns and relationships were identified in the Titanic dataset.

---

## Author

kunal chaudhary
