# 🚢 Titanic Exploratory Data Analysis (EDA)

This project explores the Titanic dataset to uncover patterns related to passenger survival during the infamous maritime disaster. The goal is to apply statistical analysis and visual exploration to extract meaningful insights that can inform predictive modeling.

---

## 📂 Dataset

- `train.csv`: Main dataset with passenger info and survival status
- `test.csv`: For future testing/prediction
- `gender_submission.csv`: Benchmark prediction file

---

## 🧰 Tools & Libraries Used

- Python 3 (Jupyter Notebook via Anaconda)
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🧪 EDA Techniques Applied

- `.info()`, `.describe()`, `.value_counts()`
- Handling missing values (`Age`, `Embarked`, `Cabin`)
- Feature engineering (e.g., Family Size)
- Correlation heatmap (`sns.heatmap()`)
- Distributions & outlier detection (`sns.boxplot()`, `sns.histplot()`)
- Relationships: (`sns.pairplot()`, `groupby()`, crosstabs)

---

## 📈 Visuals Included

- Histogram of Age & Fare
- Boxplots of Age/Fare vs Survival
- Violin plots by Sex, Pclass, Embarked
- Heatmap of feature correlations
- Pairplot of numerical columns

---

## 💡 Key Insights

- Females had a higher survival rate than males
- 1st class passengers were more likely to survive
- Children had a better chance of survival
- High Fare → higher survival likelihood
- Embarked location (Cherbourg) had more survivors (likely linked to class)

---

## 📌 Deliverables

- `Titanic_EDA.ipynb` – Jupyter Notebook with full EDA
- `Titanic_EDA_Report.docx` – Full report summary (optional PDF version)
- Visuals included inline in notebook

---

## 👤 Author

**Name:** Biswarup Das  
**Date:** July 2025  
**Tools:** Python (Jupyter), Anaconda, Matplotlib, Seaborn

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
