Model Results and Evaluation

This folder contains the evaluation results of the machine learning models developed for the Solar Cluster Performance project.
The results focus on assessing model accuracy, reliability, and practical usefulness through quantitative metrics and visual outputs.

Overview

Two types of machine learning tasks are evaluated in this project:

Regression for predicting total solar power output

Classification for identifying high and low performance solar clusters

The results are presented using evaluation metrics and visualizations to ensure clarity and easy interpretation.

Regression Results – Power Output Prediction

The regression task aims to predict the total power output (kW) based on solar irradiance, time, and cluster information.

Included files:

metrics.json
Contains quantitative performance metrics such as Mean Squared Error (MSE) and R² score.

actual_vs_predicted.png
Visual comparison between actual and predicted power output values.

sample_predictions.png
Sample regression predictions presented as an image for quick visual inspection.

The regression model demonstrates strong predictive performance and captures non-linear relationships in the data.

Classification Results – Cluster Performance

The classification task focuses on categorizing solar clusters into high or low performance groups based on efficiency.

Included files:

metrics.json
Contains classification metrics including AUC score and confusion matrix values.

confusion_matrix.png
Visual representation of correct and incorrect classifications.

roc_curve.png
Receiver Operating Characteristic (ROC) curve illustrating model discrimination ability.

sample_predictions.png
Sample classification predictions presented visually for clarity.

The classification model shows strong discrimination capability between high and low performing clusters.

Notes

Sample predictions are provided as images instead of raw CSV files to keep the repository lightweight.

All results are generated from the trained models described in the analysis notebook.

Metrics and visualizations are intended for both technical and non-technical audiences.