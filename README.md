## **README File for Salifort Motors Employee Turnover Prediction**

### **Project Overview**

This project aims to predict employee turnover at Salifort Motors using machine learning techniques. By identifying factors contributing to attrition, the company can implement targeted strategies to improve retention and reduce costs associated with recruitment and onboarding.

### **Dataset**

- **Source:** Simulated data (reference: [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv))
- **Size:** 15,000 rows x 10 columns
- **Variables:**
  - `satisfaction_level`: Employee-reported job satisfaction level (0-1)
  - `last_evaluation`: Score of employee's last performance review (0-1)
  - `number_project`: Number of projects employee contributes to
  - `average_monthly_hours`: Average number of hours employee worked per month
  - `time_spend_company`: How long the employee has been with the company (years)
  - `Work_accident`: Whether or not the employee experienced an accident while at work (binary)
  - `left`: Whether or not the employee left the company (binary - target variable)
  - `promotion_last_5years`: Whether or not the employee was promoted in the last 5 years (binary)
  - `Department`: The employee's department (categorical)
  - `salary`: The employee's salary (U.S. dollars)

### **Methodology**

1. **Data Exploration:** Conducted exploratory data analysis (EDA) to understand the data distribution and identify potential relationships between variables.
2. **Feature Engineering:** Considered feature engineering techniques to create new variables or transform existing ones if necessary.
3. **Model Selection:** Evaluated Random Forest and XGBoost algorithms for their suitability in predicting employee turnover.
4. **Model Training:** Trained both models on the dataset, optimizing hyperparameters using techniques like GridSearchCV.
5. **Evaluation:** Assessed model performance using metrics such as accuracy, precision, recall, F1-score, and AUC.

### **Results**

- **Best Model:** XGBoost consistently outperformed Random Forest in terms of overall accuracy, precision, recall, and F1-score.
- **Key Predictors:** The most important features influencing employee turnover were identified as `average_monthly_hours`, `satisfaction_level`, `last_evaluation`, `number_of_projects`, `tenure`, and `salary`.

### **Conclusion**

The XGBoost model provides a valuable tool for predicting employee turnover at Salifort Motors. By focusing on factors like work-life balance, job satisfaction, performance management, and workload balance, the company can implement targeted strategies to improve retention and reduce costs associated with employee turnover.

### **Future Work**

- **Explainability:** Explore techniques like SHAP values to understand the specific reasons behind the model's predictions.
- **Deployment:** Integrate the model into the company's HR systems for real-time predictions.
- **Monitoring:** Continuously monitor the model's performance and retrain it as needed to adapt to changes in the data or business conditions.
