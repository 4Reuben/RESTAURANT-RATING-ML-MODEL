# Restaurant-Rating-ML-Model

🙋‍♂️ Author
Reuben Thomas John

Intern @ Cognifyz Technologies

Project Duration: 4 Weeks

# 🍽️ Restaurant Rating Prediction using Machine Learning - TASK - 1

This project uses machine learning techniques to predict the **aggregate rating** of restaurants based on features like location, cuisine, price range, votes, and delivery options. The dataset used is based on real-world restaurant information, and a Decision Tree Regression model was trained and evaluated for performance.

---

## 📌 Objective

To build a regression model that predicts a restaurant’s aggregate rating using features such as:
- Cuisines
- Locality
- Online delivery availability
- Price range
- Votes
- Geographic location

---

## 🧾 Dataset Overview

- 📂 **Total Records:** 9,551  
- 📊 **Features:** 21  
- 🔍 **Target Variable:** `Aggregate rating`

Missing values were minimal (only 9 rows in `Cuisines`) and were safely dropped during preprocessing.

---

## 🛠️ Technologies & Tools Used

- Python
- Google Colab
- Scikit-learn
- Pandas, NumPy
- Seaborn, Matplotlib

---

## 🧪 Model Summary

### ✅ Model Used: `DecisionTreeRegressor`

| Metric                | Value  |
|-----------------------|--------|
| Mean Squared Error    | 0.18   |
| R² Score              | 0.92   |

🔁 **Comparison (Linear Regression):**
- MSE: 1.12
- R²: 0.51

The Decision Tree model clearly outperformed linear regression for this non-linear, complex dataset.

---

## 📈 Visualizations

### 1️⃣ Rating Distribution  
Shows the overall spread of restaurant ratings.

### 2️⃣ Top 10 Feature Importances  
Votes were the most influential feature by far.

### 3️⃣ Actual vs Predicted Ratings  
A near-perfect alignment shows a well-fitted model.

### 4️⃣ Residuals Plot  
Most prediction errors are close to zero.

---

## 🔍 Key Insights

- **Votes** had the highest impact on the final rating, showing that popularity and user engagement strongly influence perceived quality.
- Features like **Cuisines**, **Geolocation**, and **Online Delivery** had moderate importance.
- **Decision Tree Regression** provided high accuracy and handled categorical and non-linear relationships effectively.

---

## 💻 How to Use

1. 📂 Download or copy the file and dataset 
2. ▶️ Run each cell step-by-step
3. 📊 Analyze results and tweak parameters as needed

---

## 📦 Requirements

You can install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
