# 🏠 Predicting California Housing Prices using Regression Models

This work explores how **machine learning regression techniques** can be applied to predict housing prices, illustrating the role of computational modeling in real-world data analysis.  
Using the **California Housing dataset**, several regression algorithms are trained and evaluated to determine which provides the most accurate price predictions.

---

## 📊 Overview

The goal of this analysis is to compare the performance of multiple regression algorithms on a structured dataset that captures housing characteristics such as:
- Median income  
- Average number of rooms  
- Population and household features  
- Proximity to urban centers  

The results provide insights into how different modeling approaches — from simple linear regression to ensemble and neural models — capture the complexity of real-world housing price data.

---

## ⚙️ Tools & Libraries

- **Python 3**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## 🧠 Models Implemented

| Model | Description |
|--------|--------------|
| **Linear Regression** | Establishes a linear relationship between features and house prices. |
| **Decision Tree Regressor** | Learns nonlinear relationships through hierarchical splitting. |
| **Random Forest Regressor** | Combines multiple decision trees for improved generalization. |
| **Gradient Boosting Regressor** | Builds models sequentially to minimize error. |
| **MLP Regressor (Neural Network)** | Uses hidden layers to model complex patterns in the data. |

---

## 📈 Evaluation

- **Cross-validation:** 5-fold  
- **Metric:** R² (coefficient of determination)

Each model was trained and evaluated using 5-fold cross-validation to ensure fair performance comparison.  
The mean R² score for each model was printed to summarize predictive accuracy.

---

## 🏁 Key Insights

- **Ensemble models (Random Forest, Gradient Boosting)** typically achieved higher R² scores than simple linear regression.  
- **MLP Regressor** showed potential but required fine-tuning for optimal performance.  
- This comparison highlights the importance of model selection and validation when building predictive models for real-world data.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/kastdash/CaliforniaHousingRegression.git
   cd CaliforniaHousingRegression
