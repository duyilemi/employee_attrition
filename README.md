### **Project Overview**

This project aims to predict employee turnover at Salifort Motors using machine learning techniques. By identifying factors contributing to attrition, the company can implement targeted strategies to improve retention and reduce costs associated with recruitment and onboarding.

### **Tools and Libraries**

- **Python:** The primary programming language used for data analysis and machine learning.
- **Pandas:** A powerful data manipulation and analysis library.
- **NumPy:** A library for numerical computations and array operations.
- **scikit-learn:** A comprehensive machine learning library with algorithms for classification, regression, clustering, and more.
- **XGBoost:** A gradient boosting framework known for its speed and performance.
- **Matplotlib:** A plotting library for creating visualizations.
- **Seaborn:** A high-level data visualization library built on top of Matplotlib.

### **Methodology**

1. **Data Exploration:** Conducted exploratory data analysis (EDA) to understand the data distribution and identify potential relationships between variables.
2. **Data Preprocessing:** Cleaned and prepared the data, handling missing values, outliers, and encoding categorical variables.
3. **Feature Engineering:** Created new features or transformed existing ones to improve model performance.
4. **Model Selection:** Evaluated Random Forest and XGBoost algorithms for their suitability in predicting employee turnover.
5. **Model Training:** Trained both models on the dataset, optimizing hyperparameters using techniques like GridSearchCV.
6. **Model Evaluation:** Assessed model performance using metrics such as accuracy, precision, recall, F1-score, and AUC.

### **Results**

- **Best Model:** XGBoost consistently outperformed Random Forest in terms of overall accuracy, precision, recall, and F1-score.
- **Key Predictors:** The most important features influencing employee turnover were identified as `average_monthly_hours`, `satisfaction_level`, `last_evaluation`, `number_of_projects`, `tenure`, and `salary`.

### **Conclusion**

The XGBoost model provides a valuable tool for predicting employee turnover at Salifort Motors. By focusing on factors like work-life balance, job satisfaction, performance management, and workload balance, the company can implement targeted strategies to improve retention and reduce costs associated with employee turnover.

### **Future Work**

- **Explainability:** Explore techniques like SHAP values to understand the specific reasons behind the model's predictions.
- **Deployment:** Integrate the model into the company's HR systems for real-time predictions.
- **Monitoring:** Continuously monitor the model's performance and retrain it as needed to adapt to changes in the data or business conditions.
