#  Employee Attrition Prediction using Machine Learning

This project aims to address the growing concern of **employee attrition** by leveraging historical HR data and applying machine learning algorithms to predict which employees are likely to leave the company. The objective is to **help HR teams reduce attrition rates**, optimize recruitment efforts, and foster employee retention.

---


##  Business Problem

The **Human Resources department** is experiencing high attrition rates, resulting in increased **recruitment costs** and organizational instability.

###  Business Objective:
- Analyze historical employee data to **predict attrition**.
- Identify key drivers behind employee resignation.
- Use predictive modeling to proactively retain valuable employees.

---

##  Project Lifecycle

This project follows the complete **data science lifecycle**:
1. Understanding the business problem.
2. Data collection and cleaning.
3. Exploratory data analysis (EDA).
4. Feature selection and engineering.
5. Model development and evaluation.
6. Iterative improvement.
7. Deployment-ready framework for stakeholder use.

---

##  Data Overview

| Description                     | Count     |
|--------------------------------|-----------|
| Total Records                  | 1,470     |
| Total Columns                  | 35        |
| Numerical Columns              | 26        |
| Categorical Columns            | 9         |
| Target Distribution (Attrition)| No: 1,233 (84%)<br>Yes: 237 (16%) |

---

##  Exploratory Data Analysis

Key Observations:
- **High-performing employees** are less likely to leave.
- **Male employees** account for nearly **60%** of the attrition cases.
- Features like **OverTime**, **YearsAtCompany**, and **YearsSinceLastPromotion** are strong indicators of attrition risk.

---

##  Modeling

We explored the following machine learning models:

1. **Logistic Regression**
   - Suitable for binary classification tasks.
   - Interpretable model using a sigmoid function.
   - Predicts the probability of attrition (`Yes = 1`, `No = 0`).

2. **Decision Tree**
   - Non-linear model that captures complex patterns.
   - Handles both numeric and categorical features with ease.

3. **Random Forest**
   - Ensemble of multiple decision trees.
   - Handles overfitting and improves accuracy.
   - Final choice for best performance.

---

##  Model Evaluation

###  Evaluation Metric: **Accuracy Score**

| Model             | Accuracy |
|------------------|----------|
| Logistic Regression | ~77%   |
| Decision Tree       | ~71%   |
| **Random Forest**   | ~84% |

Evaluation Technique:
- **Confusion Matrix**: Used to assess True Positives, False Positives, etc.
- Focused on overall prediction accuracy and interpretability for stakeholders.

---

##  Key Insights

- Attrition is not random — it correlates strongly with:
  - Overtime
  - Lack of recent promotions
  - Low tenure
- HR can use these findings to design interventions:
  - Offer career growth pathways.
  - Improve work-life balance policies.

---

##  Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

##  Learning Outcomes

- Completed a job simulation involving real-world attrition problems.  
- Strengthened Python, EDA, and machine learning model building skills.  
- Gained proficiency in communicating technical results to business stakeholders.  
- Learned how to deploy HR analytics solutions to **reduce attrition rates**.  

---

*For suggestions or collaborations, feel free to reach out or raise an issue in the repository.*
