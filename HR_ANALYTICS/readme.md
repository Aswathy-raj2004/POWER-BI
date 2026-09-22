# 📊 HR Analytics Dashboard – Power BI

An interactive **HR Analytics Dashboard built using Microsoft Power BI** to analyze employee demographics, attrition, job satisfaction, education, age groups, and gender-based workforce trends.

The dashboard provides an overview of employee performance and attrition patterns, helping identify key workforce insights through interactive visualizations and KPIs.

---

## 🖥️ Dashboard Preview

<img width="1158" height="650" alt="HR_Analytics" src="https://github.com/user-attachments/assets/92d3f281-11d7-471e-b1e3-ae639b24710f" />


---

## 🎯 Project Objective

The objective of this project is to analyze HR data and build an interactive Power BI dashboard that provides insights into:

- Overall employee count
- Employee attrition
- Attrition rate
- Active employees
- Average employee age
- Department-wise attrition
- Employee distribution by age group and gender
- Job satisfaction by job role
- Attrition by education level
- Attrition rate by gender across different age groups

---

## 📌 Key KPIs

The dashboard includes the following key performance indicators:

| KPI | Description |
|---|---|
| **Overall Employees** | Total number of employees |
| **Attrition** | Number of employees who left the organization |
| **Attrition Rate** | Percentage of employees who left |
| **Active Employees** | Current employees in the organization |
| **Average Age** | Average age of employees |

---

## 📈 Dashboard Visualizations

### 1. Department-wise Attrition
A pie chart showing the distribution of employee attrition across different departments.

### 2. Number of Employees by Age
A stacked column chart showing employee distribution across different age groups, separated by gender.

### 3. Job Satisfaction Rating
A matrix showing job satisfaction ratings across different job roles.

### 4. Attrition by Education
A bar chart displaying employee attrition based on education level.

### 5. Attrition Rate by Gender and Age Group
Donut charts showing the distribution of attrition by gender across different age groups.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Data Visualization**
- **Data Cleaning & Transformation**
- **Data Modeling**

---

## 🧹 Data Preparation

The dataset was prepared using **Power Query** before creating the dashboard.

Key data preparation steps included:

- Removing unnecessary columns
- Handling missing/null values
- Correcting data types
- Creating age groups
- Creating calculated fields
- Transforming data for visualization
- Preparing fields required for DAX calculations

---

## 🧮 DAX Measures

Some of the key measures used in the dashboard include:

### Total Employees

```DAX
Overall Employees = COUNTROWS(Employees)
