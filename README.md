# China Economic Indicator Analysis

This project explores and models key economic indicators of China using regression techniques. The goal is to predict GDP growth and understand the economic factors that most influence it.

## 📊 Dataset

The dataset contains various macroeconomic indicators for China including:
- GDP growth (annual %)
- Population growth
- Unemployment rate
- Government expenditure
- Inflation (CPI and GDP deflator)
- CO2 emissions
- Health expenditure
... and many more.

📁 Source: World Bank Open Data

## 🧰 Tools & Technologies

- Python
- Pandas
- Scikit-learn
- Matplotlib & Seaborn
- Google Colab

## 🔧 Key Steps

- Data Cleaning: Handling missing values and inconsistent entries
- Feature Selection
- Exploratory Data Analysis (EDA)
- Model Building: Linear Regression, Random Forest, XGBoost
- Evaluation: R² Score, MSE, MAE

## 📈 Results

- **Best Performing Model**: Random Forest Regressor (R²: 0.89)
- Identified top predictors of GDP growth
- Visualized trends in population, emissions, and capital formation

## 📌 Insights

- Government expenditure and gross capital formation significantly impact GDP growth.
- Population and CO2 emissions correlate with economic activity.
- Inflation is an important but complex variable to interpret.

## 📁 Folder Organization
China_Economic_Analysis/
- │
- ├── data/                           # Dataset file
- ├── notebook/                       # Jupyter Notebook(s) for analysis
- │   └── China_Economic_Analysis.ipynb
- ├── requirements.txt               # List of Python libraries used
- ├── README.md                      # Project overview and instructions

