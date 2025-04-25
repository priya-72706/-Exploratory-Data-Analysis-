# 📊 Task 2: Exploratory Data Analysis (EDA)

## 🎯 Objective
To explore and understand the Titanic dataset using summary statistics and visualizations, and identify patterns, relationships, and anomalies that influence survival.

---

## 🛠️ Tools & Libraries
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Plotly (optional)](https://plotly.com/python/)

---

## 📂 Dataset
- **Titanic Dataset** (loaded via Seaborn)
- Includes passenger data like `age`, `sex`, `fare`, `pclass`, and `survived`.

---

## 📈 Steps Performed

### 1. Summary Statistics
- Used `describe()`, `mean()`, `median()`, and `std()` to understand central tendency and spread.

### 2. Histograms and Boxplots
- Plotted histograms for distribution.
- Used boxplots to identify outliers and compare survival impact.

### 3. Pairplot & Correlation Matrix
- Pairplot: Explored relationships between numeric features like `age`, `fare`, and `pclass`, colored by survival.
- Correlation matrix: Identified strong/weak feature correlations using heatmap.

### 4. Identifying Patterns & Anomalies
- Higher survival for females and 1st class passengers.
- Outliers in `fare` suggest wealthy passengers paid more and had higher survival.
- Children had higher survival chances than middle-aged adults.

### 5. Feature-Level Inferences
- **Sex**: Strong influence on survival.
- **Pclass**: Higher class, higher chance of survival.
- **Fare**: Positive correlation with survival.
- **Age**: Non-linear relationship with survival.

---

## 📸 Sample Visualizations
- 📊 Barplots of survival by gender and class.
- 🎯 Boxplot of fare by survival.
- 🔗 Pairplot of age, fare, and class with survival.
- 🔥 Heatmap of feature correlation.

---

## ✅ Conclusion
This EDA helped extract useful insights that can be applied to build predictive models in future tasks.

---


