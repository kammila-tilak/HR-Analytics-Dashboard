# HR Analytics Dashboard

This repository contains an **HR Analytics Dashboard** developed using **Power BI** to analyze employee data. The dashboard offers insights into workforce demographics, attrition trends, job satisfaction, and average salary statistics. It serves as a valuable tool for HR teams to make data-driven decisions and improve employee retention strategies.

---

## Project Overview  
The HR Analytics Dashboard aims to:  
- Understand the overall employee distribution and demographics.  
- Analyze attrition trends by years at the company and education field.  
- Evaluate job satisfaction across various job roles.  
- Assess average salary, years at the company, and age distribution.  

---

## Dataset Details  
The dataset includes the following fields:  
- **Employee Demographics:** Gender, Age, Education Field, Department  
- **Work-Related Information:** Job Role, Years at Company, Salary, Business Travel  
- **Attrition and Satisfaction:** Attrition status, Job satisfaction, Work-life balance  

---

## Dashboard Features  
### **KPIs:**  
- **Total Employees:** 1,470  
- **Attrition Count:** 237 employees  
- **Attrition Percentage:** 16.12%  
- **Average Salary:** 6.50K  
- **Average Years at Company:** 7 years  
- **Average Age:** 36.92 years  

### **Visualizations:**  
- **Gender Distribution:** Number of male (882) and female (588) employees.  
- **Attrition Analysis:**  
  - **By Years at Company:** Line chart analyzing attrition trends over time.  
  - **By Education Field:** Donut chart showing attrition rates by educational backgrounds.  
  - **By Age Group:** Bar chart categorizing attrition by age groups (18-25, 26-35, etc.).  
- **Job Satisfaction:** Stacked bar chart displaying satisfaction levels across various job roles.  

---

## Technologies Used  
- **Power BI:** For data visualization and interactive dashboard creation.  
- **DAX (Data Analysis Expressions):** For creating calculated measures and extracting meaningful insights.
- **EXCEL:** Used for initial data cleaning, preprocessing, and organizing the dataset before importing it into Power BI. It helped in removing duplicates, handling missing values, and performing basic statistical analysis. 

---

## DAX Calculations  
- **Attrition Percentage:**  
```DAX
Attrition Percentage = DIVIDE([Attrition Count], [Total Employees], 0)
```
- **Average Salary:** 
```
Avg Salary = AVERAGE(EmployeeData[Salary])
```
---

## Key Insights  
- **Attrition Analysis:** High attrition observed among employees with **0-5 years** of experience.  
- **Education Field:** Life Sciences and Medical fields have higher attrition rates.  
- **Job Satisfaction:** Varies significantly across job roles, with **Research Scientists** showing higher satisfaction.  
- **Average Salary and Tenure:** Potential correlation between **higher salaries** and **longer tenure**.  

---

## Future Enhancements  
- Implement **predictive analytics** to identify potential attrition risks.  
- Analyze correlations between **job satisfaction** and **work-life balance**.  
- Incorporate additional metrics like **performance ratings** and **absenteeism**.  

---

## How to Use  
1. **Clone the repository:**  
```bash
git clone https://github.com/kammila-tilak/hr-analytics-dashboard.git
```
---

 
## Light Theme  
![image-alt](https://github.com/kammila-tilak/HR-Analytics-Dashboard/blob/9b910d37bd52fa743e70bb90937e6f34be8422bc/Light%20Theme.png)

## Dark Theme  
![image-alt](https://github.com/kammila-tilak/HR-Analytics-Dashboard/blob/9b910d37bd52fa743e70bb90937e6f34be8422bc/Dark%20Theme.png)

---

## Contact  
For any queries or suggestions, feel free to reach out:  
- **Email:** [kammilatilak@gmail.com](mailto:kammilatilak@gmail.com)  
- **LinkedIn:** [Tilak Kammila](https://www.linkedin.com/in/tilak-kammila)  
