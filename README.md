#  Salary Prediction System

A Machine Learning project that predicts salary based on employee and job-related attributes using **Random Forest Regression**.

## 📌 Project Overview

The **Salary Prediction System** is a Machine Learning-based project developed to analyze salary-related data and predict the expected salary based on the given input features.

The project follows a complete Machine Learning workflow, including:

**Data Collection → Data Preprocessing → Exploratory Data Analysis → Model Training → Prediction → Model Evaluation**

---

## 🎯 Problem Statement

To build a Machine Learning model that can predict an individual's salary based on relevant features available in the dataset.

The system learns patterns from existing salary data and uses those patterns to estimate salary for new data.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical data visualization
* **Scikit-learn** – Machine Learning
* **Google Colab / Jupyter Notebook**

---

## 🤖 Machine Learning Algorithm

### Random Forest Regression

The project uses **Random Forest Regression** for salary prediction.

Random Forest is an ensemble Machine Learning algorithm that combines multiple Decision Trees to produce a more reliable prediction.

### Why Random Forest?

Random Forest was selected because it:

* Handles nonlinear relationships effectively
* Works well with multiple features
* Reduces overfitting compared to a single Decision Tree
* Provides good performance for regression problems
* Can identify important features affecting predictions

---

## 📊 Dataset

The project uses a salary prediction dataset containing information related to employees and their job characteristics.

The dataset is used for:

* Understanding salary patterns
* Performing exploratory data analysis
* Training the Machine Learning model
* Testing the model
* Predicting salary values

Dataset file:

```text
salary_prediction_data.csv
```

---

## 🔍 Data Preprocessing

The dataset is processed before training the Machine Learning model.

The preprocessing workflow includes:

1. Loading the dataset
2. Understanding the dataset structure
3. Checking for missing values
4. Data cleaning
5. Handling categorical data
6. Preparing features and target variable
7. Splitting the dataset into training and testing data

---

## 📈 Exploratory Data Analysis

Exploratory Data Analysis is performed to understand the relationships between different features and salary.

The analysis includes:

* Understanding the distribution of salary
* Analyzing relationships between features
* Identifying patterns in the dataset
* Visualizing important variables
* Studying correlations between numerical features

Visualization libraries such as **Matplotlib** and **Seaborn** are used for analysis.

---

## 🧠 Model Training

The processed dataset is divided into:

* **Training Data** – Used to train the model
* **Testing Data** – Used to evaluate the model

The Random Forest Regression model is trained using the training dataset and then used to predict salary values for the testing dataset.

---

## 📏 Model Evaluation

The model performance is evaluated using regression metrics such as:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted salary values.

### Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

Measures the standard deviation of prediction errors and represents the error in the same unit as the target variable.

### R² Score

Measures how well the model explains the variation in the target salary values.

---

## 📂 Project Structure

```text
Salary-Prediction-System/
│
├── salaryPredictionSystem.ipynb
├── salary_prediction_data.csv
├── problemstatement.txt
└── README.md
```

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/ramyasekaran0410/Salary-Prediction-System.git
```

### 2. Open the Project

Open the project using **Google Colab** or **Jupyter Notebook**.

### 3. Open the Notebook

```text
salaryPredictionSystem.ipynb
```

### 4. Install Required Libraries

If required, install the dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 5. Run the Notebook

Run the cells sequentially to:

* Load the dataset
* Preprocess the data
* Perform EDA
* Train the Random Forest model
* Generate predictions
* Evaluate the model

---

## 📚 Learning Outcomes

This project helped in understanding:

* Python programming for Machine Learning
* Data preprocessing
* Exploratory Data Analysis
* Data visualization
* Feature preparation
* Regression
* Random Forest Regression
* Train-test splitting
* Model prediction
* Model evaluation
* MAE, MSE, RMSE and R² Score
* Working with real-world datasets

---

## 🔮 Future Enhancements

The project can be improved further by:

* Comparing different regression algorithms
* Performing hyperparameter tuning
* Improving model performance
* Adding more relevant features
* Deploying the trained model as a web application
* Creating an interactive user interface

---

## 👩‍💻 Author

**Ramya**

B.E. Computer Science and Engineering

---

## ⭐ Project

**Salary Prediction System using Random Forest Regression**

This project demonstrates the application of Machine Learning techniques to predict salary using historical salary-related data.
