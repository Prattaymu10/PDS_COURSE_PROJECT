# **House Price Prediction Using Machine Learning**

**A data science project aimed at predicting housing prices using regression models like Linear Regression, Decision Tree, and Random Forest.**

---

## **Table of Contents**
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Technologies Used](#technologies-used)
4. [Project Structure](#project-structure)

---

## **Project Overview**

In this project, we aim to predict **house prices** using multiple **machine learning models**. By utilizing regression techniques like **Linear Regression**, **Decision Trees**, and **Random Forest**, we explore which model provides the best performance in predicting house prices.

### **Objective**
- Predict house prices based on various property features.
- Compare different machine learning models.
- Evaluate the models using **cross-validation**.

---

## **Dataset**

The dataset used in this project includes various features related to properties, such as square footage, number of rooms, and location. It’s critical for training the model to make accurate predictions on unseen data.

- **Dataset Link**: [Download CSV file here](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)

---

## **Technologies Used**

- **Python**: Main programming language for data processing and modeling.
- **Pandas**, **NumPy**: For data manipulation and numerical operations.
- **Scikit-Learn**: For machine learning models and evaluation.
- **Matplotlib**, **Seaborn**: For visualizing results.
- **Google Colab**: For the development environment.

---

## **Project Structure**

```plaintext
house-price-prediction/
├── data/                     # Dataset folder
│   └── train.csv
├── notebooks/                # Jupyter notebooks for EDA and modeling
│   └── house_price_prediction.ipynb
├── src/                      # Code for data processing and modeling
│   ├── data_processing.py    # Data preprocessing script
│   └── model_training.py     # Model training and evaluation script
├── requirements.txt          # Required Python dependencies
└── README.md                 # Project README
