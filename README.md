# 📘 Machine Learning Internship – TechnoHacks Solutions  

This repository contains my work for the **Machine Learning Internship at TechnoHacks Solutions Pvt. Ltd.**  
I completed **Task 3 (Linear Regression Model)** and **Task 6 (Model Evaluation Metrics)** as part of the internship program.  

---

## 🔹 Task 3: Linear Regression Model  

### 📌 Objective  
Build a **Linear Regression model** to understand how features affect a target variable and make predictions.  

### 🛠 Steps Followed  
1. **Dataset Preparation**  
   - Loaded dataset (`scikit-learn diabetes dataset`).  
   - Selected features (X) and target (y).  
2. **Train-Test Split**  
   - 80% training, 20% testing.  
3. **Model Training**  
   - Used `LinearRegression()` from Scikit-learn.  
4. **Prediction**  
   - Applied trained model on unseen test data.  
5. **Output**  
   - Model **intercept** and **coefficients**.  
   - Initial performance using **MSE** and **R² score**.  

### 📊 Results  
- **Intercept**: 153.62  
- **Coefficients**: `[10.005, -294.81, 447.41, ...]`  
- **Mean Squared Error (MSE)**: 3139.53  
- **R² Score**: 0.47  

---

## 🔹 Task 6: Model Evaluation Metrics  

### 📌 Objective  
Evaluate the regression model using multiple metrics and visualize its performance.  

### 🛠 Metrics Used  
- **MAE (Mean Absolute Error)** → Average absolute difference between actual and predicted values.  
- **MSE (Mean Squared Error)** → Squared error, penalizes larger mistakes.  
- **RMSE (Root Mean Squared Error)** → Error in the same units as the target variable.  
- **R² Score** → Variance explained by the model (closer to 1 = better).  

### 📊 Results (from Diabetes dataset)  
- **MAE**: ~42.79  
- **MSE**: ~3139.53  
- **RMSE**: ~56.03  
- **R² Score**: ~0.47  

---

## 🔹 Visualizations  

### 1. Actual vs Predicted Scatter Plot  
Shows how close predictions are to real values.  
- Red dashed line = Perfect prediction line.  
- Blue dots = Predictions.  

### 2. Residuals Distribution  
Shows distribution of prediction errors.  
- Errors mostly centered near 0 → Balanced predictions.  

---

## 📂 Repository Structure  
│── linear-regression.ipynb # Task 3 – Linear Regression model
│── model-evaluation.ipynb # Task 6 – Evaluation metrics & plots
│── README.md # Project documentation
---

## 🚀 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/linear-regression-evaluation.git
   cd linear-regression-evaluation
   pip install -r requirements.txt
   ```
🙌 Acknowledgment

This project is part of my Machine Learning Internship at TechnoHacks Solutions Pvt. Ltd.
Grateful to TechnoHacks and Sandip Gavit for the guidance and opportunity.
