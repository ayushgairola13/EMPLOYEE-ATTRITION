# **EMPLOYEE ATTRITION PREDICTION**

## **OVERVIEW**
This project aims to analyze and predict employee attrition using data machine learning. Through exploratory data analysis (EDA), feature correlation, and model building, the goal is to understand the key factors that influence whether an employee is likely to leave an organization.

## **OBJECTIVES**

1. To explore and visualize patterns in employee data.
2. To identify the major factors contributing to employee attrition.
3. To build a predictive model that can help HR departments take proactive retention measures.

## **DATASET DESCRIPTION**

The dataset contains detailed information about employees, including demographics, job satisfaction, salary, experience, and work environment details.

Feature	Description
Age	Age of the employee
Department	Department of the employee
JobRole	Designation/Role
Education	Level of education
Gender	Male/Female
MonthlyIncome	Salary per month
YearsAtCompany	Total number of years in the organization
Attrition	Whether the employee left the company (Yes/No)


## **LIBRARIES USED**

* NumPy – Numerical computations
* Pandas – Data manipulation and analysis
* Matplotlib – Data visualization
* Seaborn – Statistical visualization and heatmaps
* Scikit-learn – Data preprocessing, model training, and evaluation
* Joblib – Model serialization

## **APPROACH**

### **1. Data Preprocessing and Exploration**
   * Imported and explore the dataset using Pandas.
   * Checked data types, null values, and statistical summaries.
   * Cleaned and handled categorical variables.

### **2. Exploratory Data Analysis (EDA)**
Visualized data distributions and relationships using:
   * seaborn.pairplot() for pairwise correlations.
   * seaborn.heatmap() for correlation matrices.
   * Created pie charts and bar plots to analyze attrition by department, gender, and other factors.

### **3. Feature Engineering**
   * Encoded categorical features using one-hot encoding.
   * Normalized numerical columns where necessary.
   * Identified and removed redundant features.

4. Model Building

Split data into training and testing sets.

Trained multiple machine learning models such as:

Logistic Regression

Random Forest Classifier

Decision Tree

Evaluated model performance using accuracy, precision, recall, and F1-score.

5. Model Saving and Deployment

Saved the final trained model using Joblib for future use.

Prepared for future integration with a web interface or dashboard.

## **VISUALIZATIONS**

* **Pair Plot:** Displays scatter plots between numerical features and their relationships.
* **Correlation Heatmap:** Highlights strong positive and negative correlations.
* **Attrition Distribution:** Pie chart showing percentage of retained vs. attrited employees.
* **Feature Importance:** Bar chart showing which features most affect attrition.

## **RESULTS**

Identified key drivers of employee attrition such as:
   * Low monthly income
   * High overtime hours
   * Low job satisfaction
   * Limited career growth opportunities
   * Built a predictive model capable of identifying employees at risk of leaving with strong accuracy.

## **CONCLUSION**

The Employee Attrition Prediction Model provides data-driven insights into workforce dynamics.
It can be used by HR departments to:
   * Improve retention strategies
   * Design better policies
   * Reduce turnover costs

**Author**
Ayush Gairola
Data Science Trainee (https://www.linkedin.com/in/ayush-gairola1310/) (https://github.com/ayushgairola13)
