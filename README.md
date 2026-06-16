# CodSoft Data Science Internship
 
A collection of machine learning projects completed as part of the **CodSoft Data Science Internship**. Each task explores a classic ML problem using real-world datasets, covering classification and regression techniques.

## 📂 Repository Structure

```
CodSoft/
├── Task-1.ipynb            # Titanic Survival Prediction
├── Task-3.ipynb            # Iris Flower Classification
├── Task-4.ipynb            # Sales Prediction using Advertising Data
├── Titanic-Dataset.csv     # Dataset for Task 1
├── IRIS.csv                # Dataset for Task 3
├── advertising.csv         # Dataset for Task 4
└── test.txt                # Notes / scratch file
```

## 🚀 Tasks Overview

### 🚢 Task 1 — Titanic Survival Prediction
- **Dataset**: `Titanic-Dataset.csv`
- **Goal**: Predict whether a passenger survived the Titanic disaster
- **Type**: Binary Classification
- **Key Features**: Passenger class, age, sex, fare, embarked port, number of siblings/spouses and parents/children aboard

### 🌸 Task 3 — Iris Flower Classification
- **Dataset**: `IRIS.csv`
- **Goal**: Classify iris flowers into one of three species — *Setosa*, *Versicolor*, or *Virginica*
- **Type**: Multi-class Classification
- **Key Features**: Sepal length, sepal width, petal length, petal width

### 📈 Task 4 — Sales Prediction using Advertising Data
- **Dataset**: `advertising.csv`
- **Goal**: Predict product sales based on advertising spend across TV, Radio, and Newspaper channels
- **Type**: Regression
- **Key Features**: TV budget, Radio budget, Newspaper budget

## 🛠️ Tech Stack

- **Python** — Core programming language
- **Jupyter Notebook** — Interactive development environment
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computing
- **Matplotlib / Seaborn** — Data visualization
- **Scikit-learn** — Machine learning models and evaluation

## 📦 Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Javeed004/CodSoft.git
cd CodSoft
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open any `.ipynb` file to explore the respective task.

## 🎯 How Each Task Works

1. **Data Loading** → Import CSV dataset using Pandas
2. **Exploratory Data Analysis (EDA)** → Understand distributions, correlations, and missing values
3. **Preprocessing** → Handle nulls, encode categorical variables, scale features
4. **Model Training** → Fit ML model on training data
5. **Evaluation** → Assess performance using appropriate metrics
6. **Insights** → Summarize findings and feature importance

## 📊 ML Models Used

| Task | Model(s) |
|------|----------|
| Task 1 — Titanic Survival | Logistic Regression, Random Forest |
| Task 3 — Iris Classification | K-Nearest Neighbors, Decision Tree |
| Task 4 — Sales Prediction | Linear Regression |

## 📝 Evaluation Metrics

- **Classification Tasks (Task 1 & 3)**: Accuracy, Confusion Matrix, Precision, Recall, F1-Score
- **Regression Task (Task 4)**: Mean Absolute Error (MAE), Mean Squared Error (MSE), R² Score

## 🏢 About CodSoft

[CodSoft](https://www.codsoft.in/) is a tech company offering virtual internship programs in domains like Data Science, Web Development, and Artificial Intelligence. This repository reflects the work submitted during the **Data Science Internship**.

## 👤 Author

**Javeed** — [@Javeed004](https://github.com/Javeed004)
