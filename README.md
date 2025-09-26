# 🏥 Healthcare Insurance Premium Prediction

## 📌 Project Overview
This project predicts healthcare insurance charges based on customer details such as age, sex, BMI, smoking status, and region.  
We apply machine learning techniques to preprocess data, analyze features, train models, evaluate them, and deploy the best-performing model.

---

## 📂 Project Structure
- **data/** → contains dataset (`insurance.csv`)
- **notebooks/** → Jupyter notebook with full workflow
- **models/** → saved ML models (`.pkl` files)
- **src/** → helper functions (optional)
- **README.md** → project documentation
- **requirements.txt** → Python dependencies

---

## ⚙️ Workflow
1. Data inspection (missing values, duplicates)
2. Exploratory Data Analysis (Univariate, Bivariate, Multivariate)
3. Outlier detection (boxplots, IQR method)
4. Feature engineering (encoding categorical, scaling numerical)
5. Train-test split (80-20)
6. Model selection:
   - Linear Regression
   - Decision Tree
   - Random Forest
   - Gradient Boosting
7. Model evaluation (MAE, RMSE, R²)
8. Model comparison (visualizations)
9. Predictions on new data
10. Feature importance & residual analysis
11. Hyperparameter tuning
12. Save final model for deployment
13. Conclusions & future scope

---

## 📊 Results
- **Best Model**: Random Forest / Gradient Boosting
- **Key Features**: Smoker, BMI, Age
- **Business Insight**: Smoking has the largest impact on insurance charges.

---

## 🚀 How to Run
```bash
# Clone repo
git clone https://github.com/yourusername/Healthcare_Insurance_Premium_Prediction.git
cd Healthcare_Insurance_Premium_Prediction

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook notebooks/Healthcare_Insurance_Premium_Prediction_Project.ipynb
