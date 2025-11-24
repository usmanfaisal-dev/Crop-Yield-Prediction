# Crop Yield Prediction using Machine Learning

## Project Overview
This project focuses on predicting crop yields using various Machine Learning models. Accurate crop yield prediction helps farmers, policymakers, and agribusinesses make better decisions regarding planting, irrigation, and resource management.

---

## Dataset
The dataset used in this project includes historical crop data with features such as:

- Soil characteristics (e.g., pH, nutrient content)
- Weather conditions (e.g., rainfall, temperature)
- Crop type
- Farming practices
- Other relevant environmental factors

> **Note:** Ensure to include your dataset in the `data/` folder or provide instructions to download it if it's large.

---

## Models Implemented
The following ML models were applied to predict crop yield:

| Model                   | Description |
|-------------------------|-------------|
| Linear Regression (LR)  | Basic linear approach to predict yield |
| Lasso Regression (LSS)  | Linear model with L1 regularization |
| Ridge Regression (RG)   | Linear model with L2 regularization |
| K-Nearest Neighbors (KNN)| Predict yield based on nearest neighbors |
| Decision Tree Regressor (DTR) | Tree-based model for non-linear relationships |
| Random Forest Regressor (RF)| Ensemble of decision trees for better accuracy |
| Gradient Boosting Regressor (GBR)| Boosting algorithm to reduce errors sequentially |
| XGBoost Regressor (XGB)| Optimized gradient boosting algorithm |

---

## Performance Metrics
The models were evaluated using **Mean Absolute Error (MAE)** and **R² Score**.  

| Model                   | MAE                     | R² Score |
|-------------------------|------------------------|----------|
| Linear Regression (LR)  | 1,773,053,077.32       | 0.7608   |
| Lasso Regression (LSS)  | 1,773,410,303.23       | 0.7607   |
| Ridge Regression (RG)   | 1,773,964,022.22       | 0.7607   |
| K-Nearest Neighbors (KNN)| 112,422,146.08        | 0.9848   |
| Decision Tree Regressor (DTR)| 146,360,768.71    | 0.9803   |
| Random Forest Regressor (RF)| 3,627.10            | 0.9872   |
| Gradient Boosting Regressor (GBR)| 25,234.71      | 0.7681   |
| XGBoost Regressor (XGB) | 8,549.99               | 0.9694   |

## How to Run
1. **Unzip the folder**:  
   - Right-click → Extract All → Choose destination folder.  

2. **Install required packages**:  
   - Open a terminal or command prompt.  
   - Navigate to the extracted folder.  
   - Run:  
   ```bash
   pip install -r requirements.txt

> **Note:** Random Forest and KNN perform best on this dataset.

---


