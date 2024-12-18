# Predicting Hospital Stay Duration  
## Project Overview  

This project focuses on predicting the duration of hospital stays using patient demographics, health conditions, admission types, and other related data. By leveraging machine learning techniques, the project aims to optimize hospital resource management, reduce patient wait times, and improve overall healthcare outcomes.  

---
## Key Features  

- **Advanced Data Analytics**: Comprehensive preprocessing, outlier handling, and exploratory data analysis.  
- **Machine Learning Models**: Implementation of multiple regression algorithms, including Linear Regression, Decision Trees, Random Forests, XGBoost, and more.  
- **Actionable Insights**: Business recommendations for healthcare resource optimization.  
- **Error Metrics**: Evaluation using R², RMSE, and MAPE for model comparison.  

---
## Dataset  

**Domain**: Healthcare Analytics  
**Key Features**:  
- **Numerical**: `Available_Extra_Rooms_in_Hospital`, `Visitors_with_Patient`, `Admission_Deposit`  
- **Categorical**: `Type_of_Admission`, `Severity_of_Illness`, `Department`, `Insurance`  
- **Target**: `Stay (in days)`  

Data preprocessing included handling missing values (e.g., 30% missing in `health_conditions`) and retaining outliers to preserve critical insights.  

---

## Technologies Used  

- **Programming Language**: Python  
- **Libraries**:  
  - Data Manipulation: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - Machine Learning: `scikit-learn`, `xgboost`  

---

## Installation and Setup  

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/yourusername/predict-hospital-stay.git  
   cd predict-hospital-stay  
