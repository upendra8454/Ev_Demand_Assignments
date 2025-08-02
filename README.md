# 🚗 Electric Vehicle (EV) Adoption Prediction 📈

This project focuses on predicting the future adoption of Electric Vehicles (EVs) using historical data and a machine learning model — *Random Forest Regression*. The goal is to understand EV trends and forecast future usage patterns to support data-driven decision-making for businesses and governments.

## 🔍 Problem Statement

Using a cleaned dataset that includes EV populations, vehicle types, and past usage statistics, we aim to build a predictive model to forecast future EV adoption in upcoming years based on trend patterns.

## 💡 Solution

We employed a *Random Forest Regressor* to learn from historical EV data. By extracting key time-based features (like year, month) and cleaning the dataset, we trained the model to predict future EV adoption accurately. This model is fast, interpretable, and suitable for real-time use cases.

## 🧠 Methodology

1. Cleaned and explored the dataset to handle missing values and outliers.
2. Created time-based features like Year, Month, etc., for better trend understanding.
3. Used *RandomizedSearchCV* to optimize hyperparameters.
4. Trained a *Random Forest Regression* model.
5. Forecasted month-by-month EV adoption.
6. Evaluated the model’s performance using metrics like RMSE and visualized predictions using plots.

## 🔧 Tools & Technologies Used

- *Python* – Core programming language for processing, modeling, and visualization.
- *Pandas & NumPy* – For data manipulation and transformation.
- *Matplotlib & Seaborn* – For data visualization and trend analysis.
- *Scikit-learn* – For model building (Random Forest) and hyperparameter tuning.
- *Google Colab / Jupyter Notebook* – For writing, testing, and visualizing the code.

🧾 Dataset
📅 Date Range: January 2017 – February 2024
🏙 Geographic Scope: County-level registration data
🔌 Features: Battery Electric Vehicles (BEVs), Plug-in Hybrid EVs (PHEVs), Non-EVs, Total Vehicles, Percent EVs.
  Database Source :- **[Click here to view Dataset](https://www.kaggle.com/datasets/sahirmaharajj/electric-vehicle-population-size-2024)**

## 📊 Results

- Achieved accurate EV adoption predictions on unseen future months.
- Visualizations clearly demonstrated the increasing EV trend.
- Model performed efficiently on time-based datasets.
  

## 🔗 GitHub Repository

**[Click here to view the project](https://github.com/upendra8454/Ev_Demand_Prediction_Project/tree/main/EV_Demand_Prediction)**

## 📌 Future Scope

- Integrate with real-time APIs for continuous data updates.
- Expand model to include charging infrastructure, weather, and geographic data.
- Deploy the model with a dashboard for real-time analytics.



