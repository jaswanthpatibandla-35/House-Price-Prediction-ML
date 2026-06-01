# 🏠 House Price Prediction Using Linear Regression

## 📌 Project Overview

This project implements a Machine Learning model to predict house prices based on property area (Square Feet) using the Linear Regression algorithm.

The project demonstrates the complete Machine Learning workflow, including data preparation, exploratory analysis, model training, prediction, performance evaluation, and visualization. It serves as a practical example of applying supervised learning techniques to real-world real estate pricing problems.

---

## 🎯 Project Objectives

- Analyze the relationship between house area and market price.
- Build a predictive Machine Learning model using Linear Regression.
- Evaluate model performance using industry-standard metrics.
- Visualize actual and predicted housing prices.
- Demonstrate practical implementation of Machine Learning concepts.

---

## 📊 Dataset Information

The dataset contains residential property information with the following features:

| Feature | Description |
|----------|-------------|
| Square_Feet | Area of the property |
| Price | Market price of the property |

### Dataset Size

- Total Records: 25
- Features: 1 Input Feature
- Target Variable: House Price

---

## 🛠️ Technologies & Libraries Used

| Technology | Purpose |
|------------|----------|
| Python 3.x | Programming Language |
| Pandas | Data Processing & Analysis |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Scikit-learn | Machine Learning Model Development |
| Jupyter Notebook | Development Environment |

---

## 🤖 Machine Learning Model

### Algorithm Used

**Linear Regression**

Linear Regression is a supervised machine learning algorithm used to model the relationship between a dependent variable and one or more independent variables.

The model learns the relationship between:

```text
House Area (Square Feet) → House Price
```

and predicts future prices based on property size.

---

## ⚙️ Project Workflow

### 1️⃣ Data Collection

- Housing data collected and organized
- Area and price values prepared for analysis

### 2️⃣ Data Preprocessing

- Dataset creation using Pandas
- Feature selection
- Target variable preparation

### 3️⃣ Data Splitting

Dataset divided into:

- Training Data (78%)
- Testing Data (22%)

using:

```python
train_test_split()
```

### 4️⃣ Model Training

Model trained using:

```python
LinearRegression()
```

### 5️⃣ Prediction

The trained model predicts house prices based on property area.

### 6️⃣ Evaluation

Model performance evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### 7️⃣ Visualization

Visualization generated to compare:

- Actual House Prices
- Predicted House Prices

---

## 📈 Evaluation Metrics

### Mean Absolute Error (MAE)

Measures average prediction error.

### Mean Squared Error (MSE)

Measures squared prediction error.

### Root Mean Squared Error (RMSE)

Provides error measurement in the original price units.

---

## 📷 Project Screenshots

### Dataset Preparation
![Dataset](code_data.png)

### Model Training
![Model Training](code_model.png)

### Prediction Process
![Prediction](code_pred.png)

### Output Visualization
![Output Graph](output.png)

---

## 📊 Sample Output

The model generates:

- Predicted house prices
- Regression line visualization
- Performance metrics
- Price estimation based on square footage

---

## 🔍 Key Learning Outcomes

Through this project, the following concepts were implemented:

- Data Analysis
- Data Visualization
- Machine Learning Fundamentals
- Supervised Learning
- Linear Regression
- Model Evaluation
- Real Estate Price Prediction

---

## 📂 Repository Structure

```text
House-Price-Prediction-ML/
│
├── First_Work_ML_House price forecast.ipynb
├── README.md
├── LICENSE
├── code_data.png
├── code_model.png
├── code_pred.png
├── output.png
└── .gitignore
```

---

## 🚀 How to Run the Project

### Clone Repository

```bash
git clone <repository-link>
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib scikit-learn
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Open Notebook

```text
First_Work_ML_House price forecast.ipynb
```

Run all cells to train the model and generate predictions.

---

## ✅ Project Deliverables

- Data Preparation
- Machine Learning Model
- House Price Prediction
- Performance Evaluation
- Data Visualization
- Documentation
- GitHub Repository
- Screenshots

---

## 👨‍💻 Author

**Patibandla Jaswanth**

B.Tech Information Technology Student

Machine Learning | Data Science | Artificial Intelligence Enthusiast

---

## 🏆 Horizon Intern Submission

This project was completed as part of the **Horizon Intern Virtual Internship Program**.

### Skills Demonstrated

- Python Programming
- Data Analysis
- Machine Learning
- Linear Regression
- Data Visualization
- Problem Solving

**#horizonintern**
