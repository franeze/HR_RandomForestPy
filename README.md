# **HR project: Predicting Employee Attrition with Machine Learning**  
**Capstone Project: Providing Data-Driven Suggestions for HR**  
This capstone project was completed as part of the **Google Advanced Data Analytics Professional Certificate.**  

---

# **Predicting Employee Attrition Using Machine Learning**  

## **Project Overview**  
Employee turnover is a major concern for businesses, as hiring and training new employees can be costly. This project analyzes HR data to identify factors contributing to employee attrition and builds a predictive model to help businesses proactively address retention issues. The dataset contains employee-related factors such as **job satisfaction levels, performance reviews, and the average number of hours worked per month.** Using machine learning models, I predict whether an employee is likely to leave the company.  

## **Business Understanding**  
Salifort Motors, a large consulting firm, seeks data-driven insights to improve employee retention. The HR department has collected workforce data but needs help understanding key attrition drivers. By leveraging predictive analytics, this project provides actionable insights to reduce turnover and improve employee satisfaction.  

## **Data Understanding**  
The dataset used in this analysis comes from [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv) and contains **15,000 records** with **10 features**, including job satisfaction levels, performance evaluations, work accidents, promotion history, and salary levels. It covers multiple departments and provides a mix of categorical and numerical variables.  

**Key considerations:**  
- **Source:** [HR Analytics and Job Prediction](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv) on Kaggle.  
- **Timeframe:** The dataset does not specify a time range, so the analysis assumes all records are recent.  
- **Data Quality:** Missing values and duplicate records were handled during data cleaning.  
- **Exploratory Data Analysis (EDA):** Visualizations were created to identify patterns in employee attrition.  

## **Modeling and Evaluation**  
Machine learning models were trained to predict employee attrition, including:  
- **Decision Tree**  
- **Random Forest**  

**Evaluation Metrics:**  
- Accuracy, Precision, Recall, F1-score, and ROC-AUC were used to assess model performance.  
- Both models showed very similar scores, except for **ROC-AUC, where the Random Forest model slightly outperformed the Decision Tree model.**  

## **Conclusion**  
The analysis identified key factors contributing to employee attrition, such as the **number of projects an employee is assigned to, performance evaluation scores, and long working hours.** The model enables HR teams to focus on high-risk employees and implement retention strategies. Future work could involve incorporating additional features, such as **employee feedback or external market conditions,** to enhance predictions.  

---
