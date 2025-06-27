# Medical Insurance Cost Prediction 🩺💰

This project builds a regression model to **predict medical insurance charges** using demographic and health-related features such as age, BMI, smoking habits, and region. It's a classic regression task aimed at understanding how different variables influence healthcare costs.

---

## 📌 Project Description

This notebook walks through a complete machine learning pipeline:

- **Data Exploration & Cleaning**
- **Exploratory Data Analysis (EDA)** using visualizations
- **Encoding categorical features**
- **Model building** with algorithms like Linear Regression and Random Forest
- **Model evaluation** using metrics like R² and RMSE

---

## 🧰 Tech Stack

- **Python 3**
- **Jupyter Notebook**
- `pandas`, `numpy` for data manipulation  
- `matplotlib`, `seaborn` for data visualization  
- `sklearn` for machine learning models  

---

## 🧾 Dataset Description

The dataset includes the following columns:

| Column   | Description |
|----------|-------------|
| `age`     | Age of the person |
| `sex`     | Gender (`male`/`female`) |
| `bmi`     | Body Mass Index |
| `children` | Number of children covered by insurance |
| `smoker` | Smoking status (`yes`/`no`) |
| `region` | Residential area in the US |
| `charges` | Annual medical insurance charges (Target variable) |

---

## 📊 Model Evaluation

Regression models were evaluated using:

- **R² Score**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

---

## 🔍 Key Takeaways

- Smoking and BMI are major drivers of medical insurance costs.
- Encoding categorical variables is crucial for model performance.
- Random Forest performed better than simple Linear Regression in this case.

---
