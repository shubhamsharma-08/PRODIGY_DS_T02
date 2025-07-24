# PRODIGY_DS_T02
# Titanic Dataset – Exploratory Data Analysis (EDA)

This project performs **data cleaning**, **exploratory data analysis (EDA)**, and basic visualizations on the Titanic dataset from [Kaggle](https://www.kaggle.com/competitions/titanic).

---

## 📦 Files Used

| File Name             | Description                                |
|-----------------------|--------------------------------------------|
| `train.csv`           | Main dataset with survival labels          |
| `test.csv`            | Test dataset for prediction (not used here)|
| `gender_submission.csv` | Sample submission format for predictions |

---

## 📊 EDA Goals

- Clean and prepare the dataset for analysis
- Handle missing values and drop irrelevant features
- Convert categorical variables to numeric
- Explore relationships between:
  - **Survival and Gender**
  - **Survival and Class**
  - **Age distribution**
  - **Fare vs. Survival**
- Generate visualizations using **Seaborn**, **Matplotlib**, and **Plotly**

---

## 🔧 Requirements

Install the following Python packages:

```bash
pip install pandas matplotlib seaborn plotly
# Optional (for saving charts as images)
pip install kaleido
