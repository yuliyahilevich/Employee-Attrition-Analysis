# Employee-Attrition-Analysis

## **Overview**
This project focuses on analyzing employee attributes to identify key factors influencing attrition and job satisfaction. The dataset provides insights into employee demographics, job roles, compensation, and organizational dynamics, enabling actionable recommendations to improve employee retention and satisfaction.

## **Objectives**
- **Analyze employee attributes** to uncover patterns related to attrition and job satisfaction.
- **Perform Exploratory Data Analysis (EDA)** to visualize trends across different features.
- **Build predictive models** using Logistic Regression, Decision Trees, and Random Forests to predict employee attrition.
- **Conduct Multivariate Regression** to understand factors influencing job satisfaction.
- **Perform ANOVA** to assess variations in job satisfaction across departments.

## **Key Features**
1. **Exploratory Data Analysis (EDA):**
   - Visualized attrition trends across demographics (e.g., age, gender, job role).
   - Identified correlations between features such as income, distance from home, and attrition.

2. **Predictive Modeling:**
   - Built models using Logistic Regression, Decision Trees, and Random Forests to predict employee attrition.
   - Evaluated model performance using metrics like accuracy, ROC-AUC, and feature importance.

3. **Job Satisfaction Analysis:**
   - Conducted multivariate regression to identify significant predictors of job satisfaction (e.g., overtime, income).
   - Performed ANOVA to assess department-wise job satisfaction differences.

4. **Key Insights:**
   - Overtime strongly negatively affects job satisfaction and increases attrition risk.
   - Younger employees and those in certain job roles (e.g., Laboratory Technician) are more likely to leave.
   - Employees with higher income and job levels report greater satisfaction.

## **Tech Stack**
- **Programming Language:** Python
- **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels, Lime, Plotly, Imbalanced-learn
- **Environment:** Google Colab

## **Dataset**
The analysis uses the **HR Analytics Employee Attrition & Performance**, which contains employee attributes, compensation details, and job satisfaction levels. Key columns include:
- **Job Satisfaction**
- **Attrition**
- **Monthly Income**
- **OverTime**
- **Department**
