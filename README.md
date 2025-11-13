# **EMPLOYEE ATTRITION PREDICTION**

## **OVERVIEW**
This project aims to analyze and predict employee attrition using data machine learning. Through exploratory data analysis (EDA), feature correlation, and model building, the goal is to understand the key factors that influence whether an employee is likely to leave an organization.

## **OBJECTIVES**

* To explore and visualize employee data effectively.
* To understand key factors influencing employee attrition.
* To analyze trends in income, job level, age, and experience that impact attrition.

## **DATASET DESCRIPTION**

URL: https://github.com/IBM/employee-attrition-aif360/blob/master/data/emp_attrition.csv

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

### 1.**Data Preprocessing:**
   * Loaded data using Pandas.
   * Checked for missing values and data types.
   * Reviewed unique values and data summaries.
 
### 2. **Correlation Analysis:**
   * Calculated correlations between numeric features.
   * Plotted pair plots and heatmaps to find relationships.
   * Used a triangular heatmap for a cleaner view.

### 3. **Data Visualization:**
   * Created pie charts to show retained vs. attrited employees.
   * Plotted histograms for:
     * Age vs. Attrition
     * Job Level vs. Attrition
     * Years at Company vs. Attrition
     * Total Working Years vs. Attrition  
  * Grouped employees into income categories to compare attrition rates.

### 4. **Comparative Analysis:**
   * Compared retained and attrited employees by income, job level, and salary hike.
   * Used Seaborn’s countplots and histplots for visual comparison.


## **RESULTS**

   * Low income, low job level, and fewer working years are strongly linked to higher attrition.
   * Employees with lower salary hikes and shorter tenure tend to leave more often.
   * Younger employees (age group 25–35) exhibit higher attrition probability.
   * Employees with longer service periods generally show stronger retention.


## **VISUALISATION :**

| **Visualization**      | **Description**                               |
| ---------------------- | --------------------------------------------- |
| Pair Plot              | Shows relationships between numeric variables |
| Correlation Heatmap    | Displays feature correlations                 |
| Triangular Heatmap     | Cleaner version of correlation heatmap        |
| Attrition Pie Chart    | Percentage of retained vs. left employees     |
| Age & Job Level Charts | Attrition trends by age and job level         |
| Income Category Chart  | Comparison of attrition across income levels  |

     
## **CONCLUSION**

The Employee Attrition Analysis provides valuable insights into workforce behavior and key attrition drivers.
Findings can help HR professionals and managers:
* Identify high-risk employees early.
* Develop effective retention strategies.
* Design better compensation and career development plans.

**Author :**
Ayush Gairola
| Data Science Trainee
| (https://www.linkedin.com/in/ayush-gairola1310/) | (https://github.com/ayushgairola13) |
