# Employee Attrition Analysis

## Project Overview
Employee attrition is a major challenge for organizations as it directly impacts productivity, hiring costs, and team stability. This project focuses on analyzing and predicting employee attrition using machine learning techniques to help organizations identify employees at risk of leaving and take proactive retention measures.

---

## Objectives
- Analyze key factors influencing employee attrition  
- Perform exploratory data analysis (EDA) on HR data  
- Build classification models to predict attrition  
- Evaluate models using business-relevant metrics  

---

## Dataset
- **Source:** IBM HR Analytics Employee Attrition Dataset  
- **Records:** 1,470 employees  
- **Target Variable:** `Attrition` (Yes / No)

### Key Features
- Age, gender, marital status  
- Job role and department  
- Monthly income and salary hike  
- Job satisfaction and work-life balance  
- Years at company and promotion history  

---

## Data Preprocessing
- Removed non-informative columns (`EmployeeNumber`, `EmployeeCount`, `Over18`, `StandardHours`)  
- Encoded categorical variables using Label Encoding  
- Converted target variable into binary format  
- Applied feature scaling using StandardScaler  

---

## Models Implemented

### Logistic Regression
- Used as a baseline model  
- Provides interpretable results  

### Random Forest Classifier
- Captures non-linear relationships  
- Handles feature interactions effectively  
- Used as the primary model  

---

## Model Evaluation
Models were evaluated using:
- **Accuracy**
- **Recall** (important for identifying employees likely to leave)
- **ROC-AUC Score**

The Random Forest model outperformed Logistic Regression across evaluation metrics, making it more suitable for attrition prediction.

---

## Results Summary

| Model | Accuracy | Recall | ROC-AUC |
|------|----------|--------|--------|
| Logistic Regression | Moderate | Moderate | Good |
| Random Forest | Higher | Higher | Better |

*Exact metric values may vary slightly due to random state initialization.*

---

## Key Insights
- Employees with low job satisfaction and poor work-life balance show higher attrition  
- Monthly income and years at company are strong predictors  
- Career stagnation increases attrition risk  

---

## Conclusion
This project demonstrates how machine learning can help organizations understand employee attrition patterns and predict potential resignations. The insights gained can support data-driven HR strategies focused on retention, engagement, and workforce planning.

---

## Future Enhancements
- Hyperparameter tuning and cross-validation  
- Feature importance visualization  
- Dashboard integration for HR teams  
- Explainability using SHAP or LIME  

---

## Author
**Gitesh Patil**  
Data Science Intern
