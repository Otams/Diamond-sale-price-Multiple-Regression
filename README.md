# Diamond Price Prediction

This project uses neural network regression to predict the sale prices of diamonds based on their characteristics. The workflow includes data cleaning, exploratory data analysis, model training, and deploying the final model as a Flask web app.

## 📌 Project Objectives

- Understand the basics of regression and neural networks
- Clean and preprocess data (handle missing values, outliers, etc.)
- Perform correlation analysis and feature selection
- Train a neural network regression model
- Deploy the model using Flask

## 💎 Problem Statement

Diamonds are valued based on a combination of attributes such as cut, color, clarity, and more. In this project, we predict the sale price of a diamond using these measurable characteristics.

## 📊 Dataset

- Source: [Kaggle - Diamond Dataset](https://www.kaggle.com/shivam2503/diamonds)
- ~220,000 diamond samples with various features
- Target: `price` (sale price in dollars)

### Key Features:
- **Cut**: Quality of the diamond cut
- **Color**: Graded from D (best) to Z (worst)
- **Clarity**: Degree of internal inclusions
- **Carat, Depth, Table, etc.**: Physical attributes affecting value

## 🚀 Deployment

The trained model is deployed as a **Flask web app**, allowing users to input diamond attributes and receive price predictions instantly.

## 🧠 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow/Keras (for Neural Networks)
- Flask (for Web Deployment)

## 🔧 Getting Started

```bash
pip install -r requirements.txt
python app.py
