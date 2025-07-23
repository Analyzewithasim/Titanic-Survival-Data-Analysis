# Titanic-Survival-Data-Analysis
A data-driven analysis of the Titanic disaster using Python. This project explores survival patterns based on gender, age, class, and other features through data cleaning, visualization, and basic feature engineering.

---

## 📘 Project Description

This project performs **Exploratory Data Analysis (EDA)** on the historical Titanic dataset to uncover meaningful insights about **survival likelihood**. By analyzing demographic and travel-related features, we aim to understand **who had a better chance of surviving** and why.

---

## 🎯 Problem Statement

The main objectives of this project are:

- Determine the **key factors** that influenced survival on the Titanic.
- Clean and preprocess the data to handle missing values.
- Perform **univariate and bivariate analysis** on survival rate.
- Prepare the dataset for future machine learning models.

---

## 🛠️ Tools and Technologies

- **Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn  
- **Platform**: Google Colab / Jupyter Notebook  
- **Dataset**: [`train.csv`](https://www.kaggle.com/competitions/titanic/data)

---

## ⚙️ Steps Performed

### 1. 🔍 Data Exploration
- Checked dataset structure using `.info()`, `.describe()`, `.shape`, and `.head()`.

### 2. 🧹 Data Cleaning
- Dropped `Cabin` column (77% missing values).
- Filled missing values in:
  - `Age` with the **mean**
  - `Embarked` with the **mode ('S')**

### 3. 🧮 Feature Engineering
- Encoded `Sex` into `Gender` (male → 1, female → 0)
- Created dummy variables for `Embarked` using `pd.get_dummies()`

### 4. 📊 Data Visualization
- Used **bar plots** and **count plots** to analyze:
  - Survival distribution
  - Survival by gender
  - Survival by passenger class

---

## 📊 Key Insights

| Feature             | Insight                                                                 |
|---------------------|-------------------------------------------------------------------------|
| 🧍‍♀️ **Gender**          | Females had a significantly **higher survival rate** than males         |
| 🛳️ **Passenger Class** | Passengers in **1st class** had the best survival rate, followed by 2nd |
| 👶 **Age**             | Children had slightly higher survival rates                            |
| ⚓ **Embarked**        | Most passengers boarded from port `'S'`, but survival was more influenced by gender and class |

---

## ✅ Conclusion

This analysis clearly shows that **gender, class, and age** significantly influenced survival rates on the Titanic. Proper data cleaning and visualization helped uncover these insights and prepare the dataset for **machine learning models** like logistic regression or decision trees.

---


## 🚀 Run the Project

1. Clone the repository:
```bash
git clone https://github.com/analyzewithasim/titanic-survival-analysis.git
cd titanic-survival-analysis

Launch the notebook:

jupyter notebook Titanic.ipynb
# or open in Google Colab
```
---

## 📄 License
This project is open-source and available under the [`MIT License`]

---
## 🤝 Connect With Me
📷 **Instagram**: @analyzewithasim

📧 **Email**: asim.analystdata@gmail.com

💼 **LinkedIn**: Asim Pardeshi




