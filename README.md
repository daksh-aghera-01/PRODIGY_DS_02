# 🚢 Titanic Survival Analysis — Jupyter Notebook

This project performs data cleaning, exploratory data analysis (EDA), and visualization on the Titanic dataset using Python and Jupyter Notebook.

---

## 📁 Project Structure

- `data/`
  - `train.csv`: Original dataset from Kaggle
  - `titanic_cleaned.csv`: Cleaned and feature-engineered version used for analysis

- `notebooks/`
  - `titanic_eda.ipynb`: Jupyter Notebook containing complete analysis

- `visuals/`
  - `survival_by_class_and_gender.png`: Key visualization created with seaborn

---

## 🧼 Data Cleaning Highlights

- Dropped irrelevant columns (`PassengerId`, `Cabin`, `Ticket`, etc.)
- Filled missing values in `Age` and `Embarked`
- Created new features:
  - `FamilySize = SibSp + Parch + 1`
  - `IsChild = Age < 18`

---

## 📊 Key Insights

- **Females** had a higher survival rate than males
- **1st class** passengers had higher chances of survival
- **Children (Age < 18)** survived more often
- Most passengers boarded from port **S**

---

## 📌 Libraries Used

- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 🔗 Dataset Source

[Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

---

## 📎 License

MIT License
