
# Canada Per Capita Income Prediction using Machine Learning

## 📌 About

This project uses a simple linear regression model to predict **Canada's per capita income** over the years. The goal is to understand economic growth trends and project future income levels based on historical data.

---

## 🧠 Problem Statement

Analyzing economic indicators like per capita income helps in policy-making and investment planning. This project builds a regression model using historical data from 1970 to 2017 to forecast future income levels.

---

## 📁 Dataset

- **File**: `Canada_per_capita_income.csv`
- **Columns**:
  - `year`: Ranging from 1970 to 2017
  - `per capita income (US$)`: Income in US dollars per person

The dataset is clean and contains no missing values.

---

## 🧰 Tools and Technologies

- Python
- Pandas, Numpy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🏗️ Model Used

- **Linear Regression** from Scikit-learn
- Feature: `year`
- Target: `per capita income (US$)`

The model is trained to find the best-fit line and is evaluated by its R² score and visual inspection of predictions.

---

## 🚀 Training Process

- Data loaded using Pandas
- Exploratory data analysis performed
- Model trained using `LinearRegression()`
- Visualized predicted vs actual values

---

## 📊 Results

- The regression model fits the data well
- Achieved a high R² score
- Used the model to predict income for a given future year (e.g., 2025)

---

## 🛠️ Requirements

Install with pip:

```bash
pip install numpy pandas matplotlib scikit-learn

## 🔭 Future Work
- Use polynomial regression to capture non-linear trends

- Add economic features (GDP, inflation) for multivariate prediction

- Create a simple web app using Streamlit to make predictions

## 🙏 Acknowledgments
- Dataset by Krish Naik (used in tutorials)

- Scikit-learn documentation and community
