# 🏠 Melbourne Housing Market Analysis 🏠

---

## 📑 Table of Contents
1. [Project Overview](#project-overview)
2. [Data Exploration and Visualization](#data-exploration-and-visualization)
3. [Linear Regression Model](#linear-regression-model)
4. [Model Evaluation](#model-evaluation)
5. [Lasso Regression](#lasso-regression)
6. [Out-of-Sample Performance](#out-of-sample-performance)

---

## 🔍 Project Overview
This project involves exploring the Melbourne housing market dataset, creating visualization, and building predictive models to estimate house prices. The objective is to understand the relationships between different features and the house prices, and to improve the model's prediction accuracy using linear and Lasso regression techniques.

---

## 📊 Data Exploration and Visualization
1. **Correlation Heatmap**
   - Reveals relationships between numerical features.
   - Insights on multicollinearity among features like rooms and bedrooms.

2. **Price Distribution by Number of Rooms**
   - Boxplot showing higher prices for houses with more rooms.
   - Price variance increases with the number of rooms.

3. **Year Built Distribution**
   - Histogram displaying construction trends over time in Melbourne.
   - Peaks in the 1930s, 1980s, and early 2000s.

4. **Geographical Heatmap of Prices**
   - Scatter plot illustrating geographical distribution of house prices.
   - Expensive homes concentrated in specific areas.

5. **Histogram of House Prices**
   - Shows a right-skewed distribution with most houses under 1 million.

---

## 🧮 Linear Regression Model
- Built a linear regression model to predict house prices based on various features.
- Evaluated the model using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared metrics.
- Insights indicate overfitting as the model performs significantly better on training data than on test data.

---

## 📉 Model Evaluation
- Detailed evaluation of the linear regression model's performance.
- Comparison of training and test errors to assess overfitting.

---

## 🔧 Lasso Regression
- Addressed overfitting by applying Lasso regularization.
- Selected the best alpha using cross-validation.
- Lasso regression outperformed linear regression in terms of MSE, RMSE, and R-squared, providing better predictive accuracy and generalization to unseen data.

---

## 📈 Out-of-Sample Performance
- Performed 5-fold cross-validation to estimate the models' true out-of-sample performance.
- Compared deviance values such as AIC, AICc, and BIC.
- Lasso regression demonstrated superior generalization capabilities compared to linear regression.

---

## 🌟 Insights
- Linear regression has a slightly better fit to training data but overfits compared to Lasso.
- Lasso regression provides better generalization and predictive accuracy on unseen data.
- Cross-validation metrics are crucial for assessing model performance beyond the training dataset.

---
