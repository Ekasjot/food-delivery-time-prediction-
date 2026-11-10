# 🍔 Food Delivery Time Prediction | Machine Learning

## 📌 Project Overview

This project focuses on predicting food delivery times using Machine Learning techniques. It uses factors such as distance, weather, traffic conditions, vehicle type, and courier experience to estimate delivery time.

The project explores different regression algorithms and compares their performance to understand how Machine Learning can be applied to real-world delivery operations.

## 🎯 Objectives

- Understand and preprocess real-world data.
- Handle missing values and categorical variables.
- Apply different regression algorithms.
- Evaluate and compare model performance.
- Understand the practical implementation of Machine Learning.

## 🛠️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## ⚙️ Project Workflow

1. **Data Loading & Exploration** – Loaded the dataset and explored its structure, columns, statistics, and missing values.
2. **Data Cleaning** – Handled missing categorical values using Mode and numerical values using Median.
3. **Data Visualization** – Used Seaborn to explore relationships and patterns in the dataset.
4. **Feature Encoding** – Applied Label Encoding and One-Hot Encoding to convert categorical variables into numerical representations.
5. **Feature & Target Selection** – Separated independent features (X) and the target variable (Delivery Time).
6. **Train-Test Split** – Divided the dataset into 80% training and 20% testing data.
7. **Model Training** – Implemented multiple regression algorithms.
8. **Model Evaluation** – Evaluated predictions using different performance metrics.

## 🤖 Machine Learning Algorithms Implemented

- Linear Regression
- Ridge Regression (L2 Regularization)
- Lasso Regression (L1 Regularization)
- Polynomial Regression (Degree 2)

## 📊 Model Evaluation Metrics

The models were evaluated using:

- **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted values.
- **MSE (Mean Squared Error):** Measures the average squared prediction error.
- **R² Score:** Measures how much variation in the target variable is explained by the model.

## 📂 Project Structure

```text
Food-Delivery-Time-Prediction/
│
├── Food_Delivery_Time_Prediction.ipynb
├── Food_Delivery_Times.csv
└── README.md
```

## 🚀 How to Run the Project

1. Clone this repository:

```bash
git clone YOUR_REPOSITORY_URL
```

2. Navigate to the project directory.

3. Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

4. Open the Jupyter Notebook or upload it to Google Colab.

5. Make sure the dataset is available at the specified file path.

6. Run the notebook cells sequentially.

## 📚 Key Learnings

Through this project, I gained practical experience in:

- Data preprocessing and cleaning.
- Handling missing values.
- Encoding categorical variables.
- Understanding regression algorithms.
- Applying regularization techniques.
- Evaluating Machine Learning models.

## 🔮 Future Improvements

- Perform hyperparameter tuning.
- Apply feature scaling before regularized regression.
- Compare model performance systematically.
- Experiment with additional Machine Learning algorithms.
- Improve prediction accuracy.

---

**Author:** Ekasjot Singh

**Project Type:** Machine Learning | Regression

**Status:** Completed

