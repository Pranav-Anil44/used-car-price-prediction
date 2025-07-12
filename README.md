# 🚗 Used Car Price Prediction

This project demonstrates a complete end-to-end **Linear Regression** pipeline using real-world used car data. The main emphasis is not on achieving high accuracy, but on showcasing **strong data preprocessing skills**, **model creation**, and **evaluation techniques** — key steps in any supervised machine learning workflow.

---

## 📊 Dataset

The dataset consists of various features that affect the price of used cars such as:

- Brand
- Body type
- Engine volume
- Engine type
- Year of manufacture
- Registration status
- Mileage
- And more...

> Note: The dataset is for educational purposes and contains missing values and outliers which were handled during preprocessing.

---

## 🧹 Data Preprocessing Steps

Careful preprocessing was done to ensure data quality and consistency:

- ✅ Dropped rows with missing values in critical columns (`Price`, `EngineV`)
- ✅ Removed outliers based on domain knowledge (e.g., `EngineV > 6.5`, `Price > 10000`)
- ✅ Converted categorical variables using **One-Hot Encoding**
- ✅ Scaled numerical features using **StandardScaler** from `sklearn`

---

## 📈 Model Used: Linear Regression

A **Linear Regression** model was chosen to explore the linear relationship between car features and price.

- Splitting the dataset: `train_test_split` (80% training, 20% testing)
- Model training: `.fit()` method
- Model evaluation: 
  - ✅ **R² Score** – Measures how well the model fits the data
  - ✅ **MAE (Mean Absolute Error)** – Measures average error in prediction
  - ✅ **RMSE (Root Mean Squared Error)** – (optional, not emphasized)

---

## 📉 Evaluation Metrics (on test set)

- **R² Score**: `0.6298`
- **MAE**: `₹6189.54`
- *(RMSE was calculated but is not a focus here)*

---

## 🎯 Goal of This Project

This notebook is intended to:

- Demonstrate a solid understanding of **data cleaning and preprocessing**
- Show competence in building a **linear regression model using scikit-learn**
- Present knowledge of **evaluation metrics** for regression problems
- Showcase project versioning and documentation using **Git and GitHub**

---

## 📁 Files in the Repository

- `Used_car_price_prediction.ipynb` – Main notebook containing all code
- `README.md` – You are here!

---

## 💡 Skills Demonstrated

- Data Preprocessing (handling missing values, outliers, encoding)
- Feature Scaling and Selection
- Linear Regression modeling with `sklearn`
- Model evaluation and interpretation
- Version control with Git & GitHub

---

## 🛠 Tools Used

- Python 3.10
- Pandas
- NumPy
- Matplotlib
- scikit-learn
- Git + GitHub

---

## 🙋‍♂️ Author

**Pranav A Kumar**  
📫 [Connect with me on LinkedIn](https://www.linkedin.com/in/pranav-a-kumar-2a39b4358/)  
🔍 Passionate about Data Science | Transitioning from Software Engineer to Predictive Modeling


---
