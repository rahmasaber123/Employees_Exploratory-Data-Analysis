# Employees Data Analysis 

##  Project Overview
This project analyzes employee data from a multinational company (MNC) to uncover insights into workforce distribution, salaries, attrition trends, and performance.  
Using **Python (Pandas, Matplotlib, Seaborn, NumPy)**, the analysis highlights HR patterns that can help improve decision-making in recruitment, retention, and compensation strategies.

---

## Tech Stack
- **Python** 
- **Pandas & NumPy** → Data cleaning & manipulation  
- **Matplotlib & Seaborn** → Data visualization  
- **Jupyter Notebook** → Interactive analysis  

---

## 📂 Dataset
- Source: `C:\Users\HP\Downloads\Employees_Data.csv`  
- Contains employee-related fields such as:
  - `Department`
  - `Job Title`
  - `Location`
  - `Salary (INR)`
  - `Experience`
  - `Hire Date`
  - `Performance Rating`
  - `Status (Active/Resigned/Terminated)`
  - `Work Mode (Remote/Onsite)`

---

##  Analysis Workflow
1. **Data Cleaning**
   - Removed unwanted columns  
   - Converted `Hire Date` to datetime  
   - Handled missing and inconsistent data  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of employee status (active, resigned, terminated)  
   - Work mode breakdown (remote vs onsite)  
   - Employees per department & job title  
   - Salary distributions across departments & roles  
   - Experience and salary relationships  
   - Performance rating analysis  

3. **Business Insights**
   - Departments with the highest average salary  
   - Job titles with the highest compensation  
   - Attrition (resigned & terminated employees) per department  
   - Country-wise employee concentration  
   - Salary trends over years of experience  
   - Correlation between salary & performance rating  
   - Remote vs onsite salary comparison  
   - Top 10 employees by salary per department  
   - Departments with highest attrition rates  

---

## Visual Insights
Some of the key insights are visualized below (charts generated in the notebook):

## Hiring Over The Years 

  ![Work Status](https://github.com/rahmasaber123/Employees_Exploratory-Data-Analysis/blob/main/Hiring_Over_Years.png?raw=true)

## Resigned VS Terminated per department 

  ![Average Salary Department](https://github.com/rahmasaber123/Employees_Exploratory-Data-Analysis/blob/main/Resigned_Terminated.png?raw=true)

## Work status distribution  

  ![Job Title Salary](https://github.com/rahmasaber123/Employees_Exploratory-Data-Analysis/blob/main/work_status.png?raw=true)


---
##  Results & Findings

Tech and Data-related departments show higher average salaries.

Some job titles stand out with significantly higher pay.

Employee attrition rates vary widely across departments.

Performance ratings have limited correlation with salary.

Remote vs onsite work shows no significant salary difference.

---
##  Future Improvements

Build predictive models for attrition analysis.

Deploy interactive dashboards with Plotly/Dash or Power BI.

Add automated salary prediction models.

---
##  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/rahmasaber123/Employees_Exploratory-Data-Analysis.git
# Author

Developed by [Rahma Saber Abbas ]
Aspiring Data Analyst | Python | SQL | Visualization | Machine Learning
