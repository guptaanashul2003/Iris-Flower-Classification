# 🏠 Simple Linear Regression on Housing Prices

This project applies **Simple Linear Regression** to predict housing prices using the **California Housing Dataset**. The goal is to understand how factors like income, house age, population, and location affect median house prices.

---

## 📌 Project Overview
- Dataset: **California Housing Dataset** (20,640 samples, 8 features)  
- Tools: **Python, Pandas, Seaborn, Matplotlib, Scikit-learn**  
- Goal: Build a regression model to predict **Median House Value**.  

---

## 🛠️ Steps Performed
1. **Data Exploration**
   - Inspected dataset, checked missing values.
   - Summary statistics and correlation heatmap.  
   
2. **Preprocessing**
   - Split data into train (80%) and test (20%).
   - Standardized features using **StandardScaler**.  

3. **Model Training**
   - Applied **Linear Regression**.  

4. **Evaluation**
   - Metrics: **Mean Squared Error (MSE)**, **R² Score**.  
   - Scatter plot of Actual vs Predicted prices.  

---

## 🔑 Key Insights
- **Median Income** is the strongest predictor of house prices.  
- Linear Regression achieved **R² ~0.6**, meaning it explains ~60% of price variance.  
- Strong linear relationship, but variance suggests trying advanced ML models (Random Forest, XGBoost).  

---

## 📂 Files
- `Housing_Regression.ipynb` → Full Jupyter/Colab notebook with code & results  
- `README.md` → Project documentation  

---

## 🚀 How to Run
```bash
git clone https://github.com/<your-username>/Housing-Prices-Regression.git
pip install pandas seaborn matplotlib scikit-learn
