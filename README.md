# Restaurant-Rating-ML-Model

# 🍽️ Restaurant Rating Prediction using Machine Learning

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/YOUR_COLAB_NOTEBOOK_LINK_HERE)

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

![Rating Distribution](images/rating_distribution.png)

---

### 2️⃣ Top 10 Feature Importances  
Votes were the most influential feature by far.

![Feature Importance](images/feature_importance.png)

---

### 3️⃣ Actual vs Predicted Ratings  
A near-perfect alignment shows a well-fitted model.

![Actual vs Predicted](images/actual_vs_predicted.png)

---

### 4️⃣ Residuals Plot  
Most prediction errors are close to zero.

![Residuals](images/residuals_plot.png)

---

## 🔍 Key Insights

- **Votes** had the highest impact on the final rating, showing that popularity and user engagement strongly influence perceived quality.
- Features like **Cuisines**, **Geolocation**, and **Online Delivery** had moderate importance.
- **Decision Tree Regression** provided high accuracy and handled categorical and non-linear relationships effectively.

---

## 💻 How to Use

1. 🔗 Click the badge above to open the notebook in **Google Colab**
2. 📂 Upload the dataset or mount your Google Drive
3. ▶️ Run each cell step-by-step
4. 📊 Analyze results and tweak parameters as needed

---

## 📦 Requirements

You can install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
