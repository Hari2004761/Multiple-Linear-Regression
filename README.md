# 📊 Startup Profit Prediction

This project uses **Multiple Linear Regression** to predict the **profit of a startup** based on various features such as R&D Spend, Administration, Marketing Spend, and the State in which the startup operates.

## 📁 Dataset

The dataset used is `50_Startups.csv`, which contains the following columns:

- `R&D Spend` – Money spent on research and development.
- `Administration` – Administrative expenses.
- `Marketing Spend` – Money spent on marketing.
- `State` – The U.S. state in which the startup is located (categorical).
- `Profit` – The actual profit earned (target variable).

## 📌 Objective

To build a regression model that can predict **Profit** of a startup given the input features.

## 🛠️ Tools & Libraries

- Python 🐍
- Pandas 📊
- NumPy 🔢
- scikit-learn 🔧
- Matplotlib 📈
- Seaborn 🌊 (optional, for visualizations)

## 📚 Methodology

1. **Load the dataset**
2. **Preprocess the data**
   - Handle categorical data using one-hot encoding
   - Avoid dummy variable trap
3. **Split the dataset** into training and test sets
4. **Train a Multiple Linear Regression model**
5. **Make predictions** on the test set
6. **Visualize and compare** actual vs predicted results
7. **Evaluate the model** using metrics like R² Score

## 📈 Results

The model was able to predict startup profits with good accuracy. A scatter plot of Actual vs Predicted profits was used to visually inspect model performance.
