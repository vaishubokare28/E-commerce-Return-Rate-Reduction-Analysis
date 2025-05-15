 🛒 E-commerce Return Rate Reduction Analysis 

This project analyzes product return behavior in an e-commerce setting and builds a predictive model to identify high-risk returns. Using Python for machine learning and Power BI for interactive dashboards, it helps businesses reduce return-related losses and improve decision-making.

---

## 📌 Project Overview

**Objective:**
To analyze e-commerce return trends and build a logistic regression model that predicts the likelihood of a product being returned.

**Key Highlights:**

* Exploratory Data Analysis (EDA) using Python visualizations
* Logistic Regression classification model
* Export of high-return-risk items for further action
* Power BI dashboard for dynamic stakeholder insights

---

## 🧰 Tools and Technologies

| Task                 | Tool/Library                        |
| -------------------- | ----------------------------------- |
| Data manipulation    | `pandas`, `numpy`                   |
| Visualization        | `matplotlib`, `seaborn`, `Power BI` |
| Modeling             | `scikit-learn`                      |
| Dashboard            | `Power BI`                          |

---

## 📈 Project Workflow

### 1. Data Preparation

* Converted date columns to datetime format.
* Created a binary target variable: `Returned`.
* Handled missing values.
* Dropped irrelevant columns for modeling.

### 2. Exploratory Data Analysis (EDA)

* **Bar Plot:** Return rate by Product Category
* **Box Plot:** Return behavior across Payment Methods
* **Pie Chart:** Return rate by Shipping Method

### 3. Feature Engineering

* Applied one-hot encoding to categorical variables.
* Separated features and target.

### 4. Model Training

* Logistic Regression using `scikit-learn`
* 80/20 train-test split
* ROC AUC, confusion matrix, and classification metrics for evaluation

### 5. Risk Prediction & Export

* Predicted return probabilities on test set
* Flagged items with probability > 0.7 as high-risk
* Exported flagged data to `high_risk_products.csv`

### 6. Power BI Dashboard 

* Visualized insights such as:

  * Return rate trends by product category
  * Payment/shipping method impact
  * Filters for dynamic analysis

---

## ✅ Future Enhancements

* Deploy model via web app (Flask/Streamlit)
* Use advanced models (e.g., Random Forest, XGBoost)
* Integrate time-based return patterns
* Implement cost-sensitive modeling

---

## 🤝 Acknowledgments

This project is based on a synthetic dataset and is intended for educational and demonstrative purposes.

