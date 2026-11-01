# Food Delivery Time Prediction

A machine learning project that analyzes food delivery data and predicts **Delivery Time (minutes)** using regression techniques.

## Project Overview

This project explores the relationship between delivery time and factors such as:

- Distance
- Weather
- Traffic level
- Time of day
- Vehicle type
- Preparation time
- Courier experience

The notebook performs data exploration, preprocessing, visualization, feature encoding, model training, and model evaluation.

## Dataset

The dataset contains **1,000 records and 9 columns**.

### Columns

| Column | Description |
|---|---|
| `Order_ID` | Unique order identifier |
| `Distance_km` | Delivery distance in kilometers |
| `Weather` | Weather condition |
| `Traffic_Level` | Traffic level |
| `Time_of_Day` | Time period of the order |
| `Vehicle_Type` | Delivery vehicle |
| `Preparation_Time_min` | Food preparation time |
| `Courier_Experience_yrs` | Courier experience in years |
| `Delivery_Time_min` | Target variable: delivery time in minutes |

## Machine Learning Models

The notebook explores multiple regression approaches, including:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Polynomial Regression

Model performance is evaluated using regression metrics such as:

- R² Score
- Adjusted R²
- Mean Squared Error (MSE)

The project also includes actual-vs-predicted visualizations and correlation analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Project Structure

```text
Food-Delivery-Time-Prediction/
│
├── Linear_Regression.ipynb
├── Food_Delivery_Times.csv
├── README.md
└── .gitignore
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/piyushydv07/Food-Delivery-Time-Prediction.git
cd Food-Delivery-Time-Prediction
```

### 2. Install the required libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 3. Open the notebook

```bash
jupyter notebook Linear_Regression.ipynb
```

You can also open the notebook directly using **Google Colab**.

## Target Variable

The model predicts:

```text
Delivery_Time_min
```

which represents the estimated food delivery time in minutes.

## Purpose

This project was created for learning and portfolio purposes to practice:

- Exploratory Data Analysis
- Data preprocessing
- Categorical feature encoding
- Regression modeling
- Model comparison
- Model evaluation
- Data visualization

## Disclaimer

This is an educational machine learning project. The predictions are intended for learning and demonstration purposes and should not be treated as production-grade delivery estimates.
