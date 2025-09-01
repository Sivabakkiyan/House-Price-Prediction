# 🏡 House Price Prediction using XGBoost

This project predicts house prices using the **California Housing Dataset** and the **XGBoost Regressor**.  
It includes exploratory data analysis, correlation visualization, and model evaluation.

## 📊 Dataset
- Built-in **California Housing dataset** from `sklearn.datasets`.
- Features: MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude.
- Target: Median house price.

## ⚙️ Project Workflow
1. Import libraries and load dataset.
2. Convert dataset to Pandas DataFrame.
3. Perform basic EDA (head, shape, describe, null check).
4. Plot correlation heatmap.
5. Split dataset into training and testing sets.
6. Train model using **XGBoost Regressor**.
7. Evaluate performance using:
   - R² Score
   - Mean Absolute Error (MAE)
8. Visualize results (scatter plot).

## 📈 Results
- Training R² Score: ~0.8+
- Testing R² Score: ~0.7+
- Visualizations: Heatmap, Scatter plot of actual vs predicted prices.

## 🚀 How to Run
1. Open the notebook in **Google Colab**.
2. Run all cells sequentially.
3. View the plots and metrics.


---
Made with ❤️ in Python (Colab + Scikit-learn + XGBoost + Seaborn)
