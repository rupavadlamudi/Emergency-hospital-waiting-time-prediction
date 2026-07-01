# Hospital Emergency Department Waiting Time Prediction Using Machine Learning

## Project Overview

This project focuses on predicting the waiting time for patients in a hospital emergency department using machine learning techniques. Accurate waiting time prediction helps hospitals improve patient flow, optimize resource allocation, and enhance the overall patient experience.

By analyzing factors such as patient condition, hospital workload, and staff availability, the system estimates how long a patient is likely to wait before receiving medical attention.

## Dataset

The dataset consists of hospital emergency department records containing the following features:

* Patient Age
* Gender
* Patient Code
* Arrival Time
* Triage Level
* Queue Length
* Doctors Available
* Nurses Available
* Emergency Type
* **Patient Wait Time (Target Variable)**

## Machine Learning Models

The following regression models were trained and evaluated:

* Linear Regression
* Random Forest Regressor
* Support Vector Regression (SVR)
* XGBoost Regressor
* CatBoost Regressor

## Project Workflow

1. Data Collection and Understanding
2. Data Preprocessing

   * Handling missing values
   * Feature encoding
   * Feature scaling (where required)
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Performance Comparison
9. Result Visualization

## Evaluation Metrics

The models were evaluated using:

* Mean Absolute Error (MAE)
* R² Score (Coefficient of Determination)

## Results

Among all the models tested, **CatBoost Regressor** achieved the best overall performance by providing the lowest prediction error and the highest R² score. Its ability to handle complex relationships and categorical features made it the most effective model for this dataset.

## Visualizations

The project includes several visualizations to better understand the data and model performance, including:

* Waiting Time Distribution
* Feature Importance Analysis
* Actual vs Predicted Waiting Time
* Model Performance Comparison
* Error Analysis Graphs

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* CatBoost
* Jupyter Notebook

## Project Highlights

* Predicts emergency department waiting time using multiple machine learning algorithms.
* Compares the performance of five regression models.
* Identifies the most influential factors affecting patient waiting time.
* Demonstrates a complete end-to-end machine learning workflow, from data preprocessing to model evaluation and visualization.

## Future Improvements

* Integrate real-time hospital data for live waiting time prediction.
* Deploy the model as a web application using Flask or Streamlit.
* Incorporate additional features such as hospital occupancy, bed availability, and seasonal trends.
* Improve prediction accuracy through hyperparameter tuning and ensemble learning techniques.

## Author

**Rupa**
Aspiring Data Analyst | Data Scientist | Machine Learning Enthusiast

