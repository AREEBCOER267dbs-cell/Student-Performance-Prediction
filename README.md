# Student Performance Prediction

## 📌 Project Overview

This project predicts student academic performance using machine learning techniques.

The project uses the **Student Performance Dataset** and applies data preprocessing, feature conversion, model training, prediction, and model evaluation.

## 🎯 Objectives

* Load and explore the student performance dataset.
* Convert categorical Yes/No values into numerical values.
* Prepare the data for machine learning.
* Split the dataset into training and testing data.
* Train machine learning models.
* Predict student performance.
* Evaluate and compare model performance.

## 📊 Dataset

The project uses the **Student Performance Dataset (`student-mat.csv`)**.

The dataset contains information about students such as:

* Age
* Study time
* School support
* Family support
* Paid classes
* Activities
* Higher education plans
* Internet access
* Free time
* Going out
* Health
* Absences
* Other student-related attributes

The dataset contains **33 columns**.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## 🔄 Project Workflow

1. Load the dataset using Pandas.
2. Explore the dataset and its columns.
3. Convert categorical Yes/No values into numerical values.
4. Separate features and target variable.
5. Split the data into training and testing sets.
6. Train a Linear Regression model.
7. Make predictions on test data.
8. Evaluate the model using:

   * MAE
   * MSE
   * RMSE
   * R² Score
9. Train a Random Forest model.
10. Evaluate and compare the models.
11. Visualize actual vs predicted student performance.

## 🤖 Machine Learning Models

### Linear Regression

Linear Regression is used as one of the prediction models for estimating student performance.

### Random Forest

Random Forest is also trained and evaluated to compare its performance with Linear Regression.

## 📈 Evaluation Metrics

The models are evaluated using:

* **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted values.
* **MSE (Mean Squared Error):** Measures the average squared prediction error.
* **RMSE (Root Mean Squared Error):** Square root of MSE.
* **R² Score:** Measures how well the model explains the variation in the target values.

## 📉 Visualization

The project includes a graph comparing **Actual G3** values with **Predicted G3** values to visualize the model's predictions.

## 📁 Project Structure

```text
Student-Performance-Prediction/
│
├── Student-Performance-Prediction.ipynb
├── README.md
└── data/
    └── student-mat.csv
```

## ▶️ How to Run

1. Download or clone this repository.
2. Open `Student-Performance-Prediction.ipynb` in Jupyter Notebook.
3. Make sure the dataset is placed in the correct `data` folder.
4. Run the notebook cells in order.

## 👨‍💻 Project

**Student Performance Prediction**

This project was created as a machine learning project for studying and predicting student academic performance.
