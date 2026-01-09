# 📊 HR Analytics & Attrition Dashboard (Power BI)

## Table of Contents
- Project Overview  
- Data Source  
- Tools Used  
- Data Preparation  
- Key KPIs  
- Insights  
- Recommendations  

---

## Project Overview

The HR Leadership Team was seeking a data-driven solution to understand **employee attrition, engagement, and workforce health** in order to improve retention and optimize HR strategies.

This project analyzes employee data to identify:
- Why employees are leaving  
- Which departments and roles are most affected  
- How engagement, salary, and work conditions influence attrition  

An **interactive, multi-page Power BI dashboard** was developed to help HR managers, leadership, and business partners make informed workforce decisions.

---

## Data Source

The dataset consists of three main components:

### 1. HRIS (Employee Master Data)
Contains employee-level information such as:
- Department, Job Role, Office  
- Age, Gender, Marital Status  
- Salary, Tenure, Performance  
- Attrition status  

### 2. Engagement Survey
Includes employee feedback on:
- Job Satisfaction  
- Work Life Balance  
- Environment Satisfaction  
- Job Involvement  

### 3. Geo Data
Contains geographical information:
- City  
- State  
- Country  
- Population  

These datasets were modeled together to enable **demographic, engagement, and location-based analysis**.

---

## Tools Used

- **Power BI Desktop** – Data modeling, DAX, and dashboard development  
- **Power Query** – Data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – Creating KPIs and advanced calculations  
- **Excel** – Raw data source  

---

## Data Preparation

The project followed a professional BI workflow:

1. **Data Cleaning**
   - Removed missing and inconsistent values  
   - Standardized column names and data types  
   - Created derived fields such as Age Groups and Attrition flags  

2. **Data Modeling**
   - Designed a **star schema** with:
     - `Fact_Employee` as the main fact table  
     - `Engagement Survey` and `Geo Data` as dimension tables  
   - Created relationships using Employee ID and City  

3. **DAX Measures**
   - Built KPIs for Attrition, Salary, Engagement, Tenure, and Overtime  
   - Used explicit measures instead of implicit calculations  

4. **Dashboard Design**
   - Developed a **3-page interactive dashboard**:
     - Home (Executive Overview)  
     - Attrition Analysis  
     - Employee Insights  

---

## Key KPIs

Some of the important KPIs used in this project include:

- Total Employees  
- Active Employees  
- Attrition Count  
- Attrition Rate (%)  
- Average Salary  
- Average Job Satisfaction  
- Average Work Life Balance  
- Overtime Attrition Rate  
- Average Years at Company  

These KPIs drive all visuals and interactions across the dashboard.

---

## Insights

### 1. Workforce Overview
- The organization has a large active workforce, but a noticeable percentage of employees have exited.  
- Attrition varies significantly across departments and job roles, indicating **role-specific risks**.  

### 2. Attrition Patterns
- Certain departments and job roles experience much higher attrition than others.  
- Employees with **lower tenure** are more likely to leave.  
- Overtime workers show a **higher attrition rate**, indicating potential burnout.  

### 3. Engagement & Satisfaction
- Employees with **lower job satisfaction and poor work-life balance** are more likely to churn.  
- Departments with lower engagement scores also show higher attrition.  

### 4. Compensation & Performance
- Salary levels vary across departments and roles.  
- Some high-attrition roles also have **lower average salaries**, suggesting compensation may be a factor.  

### 5. Location Analysis
- Employee distribution varies by city and country.  
- Certain locations show higher churn, pointing to possible local operational issues.  

---

## Recommendations

Based on the analysis, the following actions are recommended:

- Improve retention in **high-risk departments and job roles** by reviewing workload, compensation, and engagement levels.  
- Reduce **burnout** by monitoring overtime employees and balancing workloads.  
- Increase **engagement initiatives** (training, career development, recognition) for teams with low satisfaction scores.  
- Focus on **early-tenure employees** by strengthening onboarding, mentoring, and support programs.  
- Use **geo-based insights** to identify and address location-specific workforce challenges.  

By acting on these insights, the company can improve employee satisfaction, reduce attrition, and build a more stable and productive workforce.
