Author -Preeti<br>
🏥 Insurance Cost Prediction

A Machine Learning project that predicts medical insurance charges based on customer demographic and health-related features.

This project demonstrates end-to-end ML workflow including EDA, feature engineering, model building, and evaluation.

📌 Problem Statement

Insurance companies need to estimate medical charges for customers based on factors like:

Age

BMI (Body Mass Index)

Smoking status

Gender

Number of dependents

Region

The objective is to build a regression model that accurately predicts insurance charges. ** 📊 Dataset Information**

Common dataset features:

Feature Description age Age of primary beneficiary sex Gender bmi Body Mass Index children Number of dependents smoker Smoking status region Residential region charges Medical insurance cost (Target variable)

🚀 Tech Stack

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

Jupyter Notebook

🔎 Project Workflow
1️⃣ Data Preprocessing

Handling categorical variables (One-Hot Encoding)

Feature scaling

Train-test split

2️⃣ Exploratory Data Analysis (EDA)

Correlation heatmap

Distribution plots

Outlier detection

Smoking impact analysis

3️⃣ Model Building

Linear Regression

Ridge / Lasso Regression

Random Forest Regressor

XGBoost (Optional)

4️⃣ Model Evaluation

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

RMSE

R² Score ** 📈 Sample Results** Model R² Score Linear Regression 0.78 Ridge Regression 0.81 Random Forest 0.87

(Results may vary depending on dataset and tuning)

****📂 Project Structure Insurance-Cost-Prediction/
│
├── data/
│ └── insurance.csv
│
├── notebooks/
│ └── EDA_Model.ipynb
│
├── src/
│ ├── preprocessing.py
│ ├── train.py
│ ├── evaluate.py
│
├── requirements.txt
└── README.md

💡 Key Insights

Smoking significantly increases insurance charges.

BMI positively correlates with medical costs.

Random Forest outperforms linear models in capturing non-linear relationships.
🔮 Future Improvements

Hyperparameter tuning (GridSearchCV)

Model deployment using Streamlit / Flask

Feature importance visualization

Real-time insurance cost prediction API**
