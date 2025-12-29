# Payroll_DataAnalysis
This project demonstrates an end-to-end Payroll Analytics and Machine Learning system designed to solve real-world HR and finance problems using data-driven insights. The goal of this project is to analyze payroll data, predict employee salaries, identify attrition risks, and detect anomalies such as payroll errors or potential fraud.

The dataset includes employee demographic details, job roles, departments, experience, attendance, leave records, salary components, and tax information. Extensive Exploratory Data Analysis (EDA) was performed to understand salary distribution, experience impact, department-wise trends, and attrition patterns. Visualizations such as histograms, box plots, scatter plots, and correlation heatmaps were used to extract meaningful insights.

Feature engineering techniques were applied to improve model performance, including the creation of derived features like total leaves, leave ratio, and salary per year of experience. Categorical variables were encoded, and numerical features were prepared for machine learning models.

Two primary machine learning models were developed:

Salary Prediction Model using regression techniques to estimate employee net salary based on role, experience, attendance, and payroll attributes.

Attrition Prediction Model using classification algorithms to identify employees who are at risk of leaving the organization.

Additionally, an anomaly detection module using Isolation Forest was implemented to flag unusual salary or allowance patterns, supporting payroll audits and fraud detection.

The project uses Python, Pandas, NumPy, Scikit-learn, and Jupyter Notebook, following clean coding practices and ML pipelines. This project highlights how AI can enhance payroll accuracy, reduce operational risks, and support strategic HR decision-making.
