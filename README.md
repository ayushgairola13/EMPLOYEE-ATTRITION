# **EMPLOYEE ATTRITION PREDICTION**

## **OVERVIEW**
This project aims to analyze and predict employee attrition using data machine learning. Through exploratory data analysis (EDA), feature correlation, and model building, the goal is to understand the key factors that influence whether an employee is likely to leave an organization.

## **OBJECTIVES**

* To explore and visualize employee data effectively.
* To understand key factors influencing employee attrition.
* To analyze trends in income, job level, age, and experience that impact attrition.

## **DATASET DESCRIPTION**

The dataset contains detailed information about employees, including demographics, job satisfaction, salary, experience, and work environment details.

| **Feature**        | **Description**                                         |
| ------------------ | ------------------------------------------------------- |
| **Age**            | Age of the employee                                     |
| **Department**     | Department where the employee works                     |
| **JobRole**        | Employee’s job designation                              |
| **Education**      | Level of education                                      |
| **Gender**         | Male/Female                                             |
| **MonthlyIncome**  | Monthly salary of the employee                          |
| **YearsAtCompany** | Total number of years spent in the organization         |



## **LIBRARIES USED**

* NumPy – Numerical computations
* Pandas – Data manipulation and analysis
* Matplotlib – Data visualization
* Seaborn – Statistical visualization and heatmaps
* Scikit-learn – Data preprocessing, model training, and evaluation
* Joblib – Model serialization

## **APPROACH**

### **1. Data Preprocessing and Inspection :**
   * Loaded dataset using pandas.read_csv().
   * Checked data types, null values, and dataset dimensions.+
   * Displayed column names, unique values, and overall data summary.

### **2. Correlation and Feature Analysis :**
 * Used DataFrame.corr() to calculate numeric correlations.
 * Plotted:
    * Pair Plots (sns.pairplot) to visualize variable relationships.
    * Heatmaps (sns.heatmap) to identify strong correlations.
    * Triangular Correlation Heatmaps for cleaner interpretation.

### **3. Exploratory Data Visualization :**
   * Attrition Distribution Pie Chart: Visualized overall employee retention vs attrition.
   * Histograms:
     * Age vs Attrition
     * Job Level vs Attrition
     * Years at Company vs Attrition
     * Total Working Years vs Attrition
   * Monthly Income Categorization: Created custom income categories using a Python function and apply() to compare attrition rates.

### **4. Comparative Analysis**
   * Compared retained vs attrited employees using Seaborn’s countplot() and histplot(). 
   * Created:
      * Side-by-side plots for retained vs attrited employees by income category.
      * Single comparison plots grouped by attrition outcome.
   * Analyzed Percent Salary Hike distribution for attrited employees.
   

## **VISUALIZATIONS**

| **Visualization                     | Description **                                                   |
| --------------------------------- | -------------------------------------------------------------- |
| **Pair Plot**                     | Displays relationships between all numerical variables.        |
| **Correlation Heatmap**           | Shows correlations among numeric features.                     |
| **Triangular Heatmap**            | Highlights upper triangle of correlation matrix for clarity.   |
| **Attrition Pie Chart**           | Shows the percentage of retained vs attrited employees.        |
| **Age Distribution Plot**         | Compares age distributions for retained vs attrited employees. |
| **Job Level Distribution**        | Analyzes attrition rate across job levels.                     |
| **Years at Company Plot**         | Shows how tenure affects attrition likelihood.                 |
| **Total Working Years Plot**      | Displays overall experience impact on attrition.               |
| **Monthly Income Category Chart** | Compares income levels for retained and attrited employees.    |



## **RESULTS**

   * Low income, low job level, and fewer working years are strongly linked to higher attrition.
   * Employees with lower salary hikes and shorter tenure tend to leave more often.
   * Younger employees (age group 25–35) exhibit higher attrition probability.
   * Employees with longer service periods generally show stronger retention.

     
## **CONCLUSION**

The Employee Attrition Analysis provides valuable insights into workforce behavior and key attrition drivers.
Findings can help HR professionals and managers:
* Identify high-risk employees early.
* Develop effective retention strategies.
* Design better compensation and career development plans.

**Author**
Ayush Gairola
Data Science Trainee
|(https://www.linkedin.com/in/ayush-gairola1310/) | (https://github.com/ayushgairola13) |
