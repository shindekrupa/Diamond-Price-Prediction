# 💎 Diamonds Price Prediction

## 📌 Project Overview

The **Diamonds Price Prediction** project uses Machine Learning and Data Analysis techniques to study diamond characteristics and build predictive models.

The project analyzes different features of diamonds, performs data preprocessing, visualizes relationships between variables, encodes categorical data, scales features, and applies regression techniques.

The main goal is to understand how different diamond characteristics influence the target variable and use Machine Learning to make predictions.

---

## 📊 Dataset

The dataset used in this project is:

```text
diamonds.csv
```

The dataset contains diamond-related features such as:

- `carat` – Weight of the diamond
- `cut` – Quality of the diamond cut
- `color` – Diamond color
- `clarity` – Diamond clarity
- `depth` – Total depth percentage
- `table` – Width of the top of the diamond
- `price` – Price of the diamond
- `x` – Length
- `y` – Width
- `z` – Depth

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Missingno
- YData Profiling
- Scikit-learn

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Checking Missing Values
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Feature Encoding
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Linear Regression
   ↓
Model Evaluation
```

---

## 🔍 Exploratory Data Analysis

The dataset was explored using:

- `head()`
- `shape`
- `info()`
- `describe()`

The project also includes:

- Missing value analysis
- Correlation analysis
- Data visualization
- Scatter plots
- Bar graphs
- Heatmaps

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were used:

### Checking Missing Values

The dataset was checked for null values using:

```python
df.isnull().sum()
```

### Encoding Categorical Variables

Categorical features were converted into numerical values.

- Label Encoding
- One-Hot Encoding

### Feature Scaling

`RobustScaler` was used to scale the features.

---

## ✂️ Train-Test Split

The dataset was divided into training and testing data using:

```python
train_test_split()
```

The data is split into training and testing sets for model development and evaluation.

---

## 🤖 Machine Learning

The project uses Linear Regression techniques.

### Linear Regression

Linear Regression is used to build a predictive model based on the relationship between input features and the target variable.

The general equation is:

```text
y = mx + c
```

Where:

- `m` = Coefficient / Slope
- `c` = Intercept
- `y` = Predicted value

The project also uses Scikit-learn's:

```python
LinearRegression()
```

---

## 📏 Model Evaluation

The model is evaluated using the following metrics:

### Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

Measures the square root of the Mean Squared Error.

### R² Score

Measures how well the model explains the variation in the target variable.

---

## 📁 Project Structure

```text
Diamonds-Price-Prediction/
│
├── Diamonds_Price_Prediction.ipynb
├── diamonds.csv
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone <your-repository-url>
```

### 2. Navigate to the Project Folder

```bash
cd Diamonds-Price-Prediction
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the Project

Open:

```text
Diamonds_Price_Prediction.ipynb
```

Run all cells to perform data analysis and model training.

---

## 📈 Key Learning Outcomes

Through this project, I learned:

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Missing Value Analysis
- Correlation Analysis
- Categorical Data Encoding
- Feature Scaling
- Train-Test Splitting
- Linear Regression
- Model Evaluation
- Using Scikit-learn

---

## 🔮 Future Improvements

Possible improvements include:

- Trying multiple Machine Learning models
- Comparing model performance
- Hyperparameter tuning
- Improving feature selection
- Creating a web application for predictions
- Deploying the trained model

---

## 👩‍💻 Author

**Krupa Shinde**

---

⭐ If you found this project interesting, consider giving the repository a star!
