☀️ Solar Cluster Performance Analysis using Machine Learning

This project analyzes the performance of solar power clusters using data science and machine learning techniques.
It focuses on understanding solar power generation patterns, evaluating cluster efficiency, and building predictive models to support data-driven decision making.

🎯 Project Objectives

Analyze solar power generation behavior across multiple clusters

Explore performance differences and efficiency patterns

Predict total power output using regression models

Classify clusters into high and low performance categories

Provide an interactive dashboard for visualization and insights

📁 Project Structure

notebooks/
Full data pipeline including preprocessing, exploratory data analysis (EDA), model training, and evaluation.

analysis/
Exploratory Data Analysis (EDA) visualizations exported as images to highlight key insights.

results/
Model evaluation results including metrics and visual outputs for regression and classification models.

dashboard/
Streamlit dashboard application used to visualize data, predictions, and classification results.

data/
Sample raw and processed datasets used for demonstration and testing purposes.

models/
Trained machine learning models used by the dashboard and analysis pipeline.

reports/
Final project report containing detailed methodology, analysis, and conclusions.

📊 Exploratory Data Analysis (EDA)

The exploratory analysis focuses on understanding solar power behavior through visual insights, including:

Relationship between solar irradiance and power output

Cluster-wise power generation comparison

Daily and hourly power generation trends

Efficiency distribution across clusters

These insights support feature engineering and informed model selection.

🤖 Machine Learning Models
Regression – Power Output Prediction

Task: Predict total power output (kW)

Model: Random Forest Regressor

Performance: High predictive accuracy (R² ≈ 0.92)

Classification – Cluster Performance

Task: Classify clusters as High or Low performance

Model: XGBoost Classifier

Metric: Strong classification performance (AUC ≈ 0.91)

Model evaluation results and visualizations are available in the results directory.

📈 Interactive Dashboard

An interactive Streamlit dashboard is included to:

Visualize solar performance trends

Display regression prediction results

Explore cluster performance classification

Dashboard screenshots are available inside the dashboard/assets folder.

🚀 How to Run the Project

Install the required dependencies listed in the requirements file.

Run the Streamlit dashboard application.

🧰 Technologies Used

Python (Pandas, NumPy)

Scikit-learn

XGBoost

Matplotlib

Seaborn

Streamlit

📄 Project Report

The complete project report is available in the reports folder under the name:
DATA_SCIENCE_FINAL_REPORT.pdf