# 🏠 House Price Prediction Using Machine Learning

A Machine Learning project that predicts house prices based on various property features such as area, number of bedrooms, bathrooms, stories, parking availability, furnishing status, and other amenities. The project uses data preprocessing, exploratory data analysis (EDA), and a Linear Regression model to estimate property prices.

---

## 📌 Project Overview

Accurately estimating house prices is an important task in the real estate industry. This project analyzes housing data and builds a predictive model capable of estimating house prices based on property characteristics.

The workflow includes:

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Encoding
* Model Training
* Model Evaluation
* Data Visualization

---

## 🚀 Features

* Load and preprocess housing dataset
* Handle categorical variables using encoding
* Visualize relationships between features and house prices
* Train a Linear Regression model
* Predict house prices on unseen data
* Evaluate model performance using regression metrics
* Generate insights from the dataset

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / VS Code

---

## 📂 Dataset Features

The dataset contains the following attributes:

| Feature          | Description                   |
| ---------------- | ----------------------------- |
| price            | House price (Target Variable) |
| area             | Area of the house             |
| bedrooms         | Number of bedrooms            |
| bathrooms        | Number of bathrooms           |
| stories          | Number of floors              |
| mainroad         | Access to main road           |
| guestroom        | Availability of guest room    |
| basement         | Availability of basement      |
| hotwaterheating  | Hot water heating facility    |
| airconditioning  | Air conditioning availability |
| parking          | Number of parking spaces      |
| prefarea         | Located in preferred area     |
| furnishingstatus | Furnishing condition          |

---

## 📊 Exploratory Data Analysis

Several visualizations were created to understand the data:

* Correlation Heatmap
* House Price Distribution
* Area vs Price Scatter Plot
* Bedrooms vs Price Box Plot
* Regression Plot
* Actual vs Predicted Price Comparison

These visualizations helped identify important factors affecting house prices.

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---


## 🤖 Machine Learning Model

The project uses:

### Linear Regression

The model was trained using:

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)
```

The model learns the relationship between house features and their prices.

---

## 📈 Evaluation Metrics

Model performance is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score


## 📷 Sample Visualizations

### Correlation Heatmap

Identifies relationships between features and house prices.

### Actual vs Predicted Prices

Compares model predictions against actual values.

### Price Distribution

Shows how house prices are distributed across the dataset.

---

## 💡 Key Findings

* House area is one of the strongest predictors of price.
* Properties in preferred locations tend to have higher prices.
* Additional amenities such as air conditioning and parking positively influence pricing.
* Furnished houses generally command higher market values.

---

## 📁 Project Structure

```text
House-Price-Prediction/
│
├── housing.csv
├── house_price_prediction.py
├── House_Price_Prediction.ipynb
├── requirements.txt
├── README.md
└── images/
    ├── heatmap.png
    ├── scatterplot.png
    └── predictions.png
```

---

## 🔮 Future Improvements

* Implement Random Forest Regressor
* Add XGBoost for improved accuracy
* Hyperparameter tuning
* Deploy as a Streamlit web application
* Create an interactive dashboard

---

  
