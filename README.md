# NYC Taxi Trip Time Prediction

## Project Overview

The NYC Taxi Trip Time Prediction project aims to develop a machine learning regression model to predict the duration of a taxi trip in New York City based on various input features such as pickup and dropoff locations, time of day, and distance of the trip. The project utilizes historical data on taxi trips in NYC and applies regression algorithms to achieve accurate predictions. The goal is to improve the efficiency and convenience of taxi services by providing more accurate estimates of trip duration for both passengers and drivers.


<p align="left">
    <img src="https://img.shields.io/badge/Skill-Python-blue" alt="Python" />
    <img src="https://img.shields.io/badge/Skill-Pandas-yellow" alt="Pandas" />
    <img src="https://img.shields.io/badge/Skill-NumPy-orange" alt="NumPy" />
    <img src="https://img.shields.io/badge/Skill-Matplotlib-red" alt="Matplotlib" />
    <img src="https://img.shields.io/badge/Skill-Seaborn-green" alt="Seaborn" />
</p>

<p align="left">
    <img src="https://img.shields.io/badge/Tool-Jupyter%20Notebook-red" alt="Jupyter Notebook" />
    <img src="https://img.shields.io/badge/Tool-Google%20Colab-yellow" alt="Google Colab" />
    <img src="https://img.shields.io/badge/Tool-GitHub-lightgrey" alt="GitHub" />
</p>

<p align="left">
    <img src="https://img.shields.io/badge/Model-Linear%20Regression-lightblue" alt="Linear Regression" />
    <img src="https://img.shields.io/badge/Model-Lasso%20Regression-darkgreen" alt="Lasso Regression" />
    <img src="https://img.shields.io/badge/Model-XGBoost-critical" alt="XGBoost" />
    <img src="https://img.shields.io/badge/Model-Elastic%20Net%20Regression-brightgreen" alt="Elastic Net Regression" />
    <img src="https://img.shields.io/badge/Model-LightGBM-yellowgreen" alt="LightGBM" />
</p>

## Key Findings

- Important factors influencing taxi trip duration include pickup and dropoff locations, time of day, and distance of the trip.
- Vendor 2 is slightly more popular than Vendor 1 with a similar number of trips.
- Trip duration is shortest at 6 AM and longest during peak hours at 3 PM.
- Average trip duration increases from Monday to Thursday and then decreases until Sunday.
- Taxi trips with a higher number of passengers tend to have longer durations.
- There is a positive correlation between trip distance and trip duration.


| Model                   | MAE  | MSE  | RMSE | MAPE | R2   | Accuracy |
|-------------------------|------|------|------|------|------|----------|
| Linear Regression       | 3.95 | 25.78| 5.07 | 17.70| 0.55 | 82.29    |
| Lasso Regression        | 3.95 | 25.79| 5.07 | 17.72| 0.55 | 82.27    |
| Ridge Regression        | 3.95 | 25.78| 5.07 | 17.70| 0.55 | 82.29    |
| Elastic Net Regression | 3.95 | 25.78| 5.07 | 17.70| 0.55 | 82.29    |
| LightGBM                | 2.84 | 14.69| 3.83 | 12.96| 0.74 | 87.07    |
| XGboost                 | 2.88 | 15.01| 3.87 | 13.06| 0.73 | 86.93    |



## Tools and Skills

- **Python**: Coding and implementing machine learning algorithms.
- **Pandas**: Data manipulation and preprocessing.
- **NumPy**: Numerical computations.
- **Matplotlib** and **Seaborn**: Data visualization.
- **Scikit-learn**: Implementing machine learning models.

## Takeaways

- Effective data preprocessing and feature engineering are crucial for accurate predictive models.
- Machine learning models like LightGBM can achieve high accuracy in predicting taxi trip durations.
- Exploratory data analysis is essential for understanding underlying patterns and trends in the data.


## Acknowledgments

This project was completed as part of the Data Science Trainee program at AlmaBetter.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/navjot-khatri-5721a5179/)
