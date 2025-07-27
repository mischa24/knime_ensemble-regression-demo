# KNIME Ensemble Regression Project

This project demonstrates an **ensemble regression approach** implemented in the KNIME Analytics Platform. By combining predictions from three different regression models—**Linear Regression**, **Decision Tree**, and **Random Forest**—a final prediction is computed using the **Math Formula** node.

## 🔍 Objective

To showcase the concept of model averaging in regression problems. By taking the arithmetic mean of the outputs of three regression models, we aim to improve prediction accuracy and reduce model-specific bias.

## 🧠 Methodology

- Developed in **KNIME** using the educational workflow:  
  `eLearning_regression_II_part_2.knwf`
- Predictions are computed individually using:
  - Linear Regression
  - Decision Tree Regression
  - Random Forest Regression
- The **Math Formula** node is used to calculate the average:

```math
FinalPrediction = (Pred_LR + Pred_DT + Pred_RF) / 3
