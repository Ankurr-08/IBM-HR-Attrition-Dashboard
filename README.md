# IBM HR Analytics – Employee Attrition Analysis  
A complete Data Analytics project covering **data cleaning, exploratory data analysis (EDA), and interactive dashboard building** using the IBM HR Attrition dataset (1470 employees).

---

## 📌 Project Overview
Employee attrition is a critical HR metric that affects hiring costs, productivity, and organizational stability.  
This project analyzes employee attrition patterns using:

- Data Cleaning (Pandas)
- Exploratory Data Analysis (EDA)
- Tableau Dashboard
- Actionable Insights & Recommendations

---

## 📂 Dataset Information
**Dataset name:** IBM HR Analytics Employee Attrition & Performance  
**Total employees:** 1470  
**Target variable:** `Attrition` (Yes / No)

Dataset includes:
- Employee demographics  
- Job role, department  
- Salary & compensation  
- Performance & work-life balance  
- Tenure & job satisfaction  
- Overtime & work environment  

---

# 🧹 1. Data Cleaning (Python)
Performed comprehensive cleaning to ensure dataset quality.

### ✔ Steps Performed
- Removed duplicate rows  
- Checked & handled missing values (none found in this dataset)  
- Standardized column names  
- Converted categorical variables to consistent formatting  
- Verified numerical columns  
- Outlier detection for:
  - Monthly Income
  - Years at Company  
- Created new derived fields:
  - Income Band
  - Age Group
  - Tenure Group
- Validated dataset integrity

All cleaning was done using **Pandas + Numpy**.

---

# 📊 2. Exploratory Data Analysis (EDA)
EDA performed to understand patterns behind employee attrition.

### ✔ Univariate Analysis
- Distribution of Age, Monthly Income, Tenure
- Overall Attrition Rate
- Job Satisfaction distributions

### ✔ Bivariate Analysis
- Attrition vs Job Role  
- Attrition vs Department  
- Attrition vs Gender  
- Attrition vs Overtime  
- Attrition vs Age Group  
- Attrition vs Monthly Income  

### ✔ Multivariate Analysis
- Heatmap: Attrition % by Job Role  
- Boxplot: Monthly Income vs Job Role  
- Work-life balance vs Attrition  
- Satisfaction metrics vs Attrition  

---

# 📈 3. Tableau Dashboard
A full interactive dashboard was created that includes:

### ⭐ KPI Cards
- Total Employees  
- Attrition Count  
- Attrition Rate (%)  
- Avg Monthly Income  
- Avg Tenure  

### ⭐ Visuals
- Grouped bar: Attrition by Job Role  
- Stacked bar: Attrition by Department  
- Bar chart: Attrition by Age Group  
- Donut chart: Attrition by Gender  
- Bar chart: Attrition by Overtime  
- Bar chart: Work-Life Balance vs Attrition  
- Heatmap: Attrition Rate by Job Role  
- Boxplot: Income by Job Role  
- Filters for dynamic interaction  

Dashboard helps HR identify **high-risk roles, salary patterns, workload issues**, and **key drivers of attrition**.

---

# 🔍 4. Key Insights

### 🔹 High-Risk Job Roles  
Sales Representatives, Laboratory Technicians, and Sales Executives show the **highest attrition**.

### 🔹 Department-Level Risk  
Sales department has the **highest turnover**, indicating heavy workload/targets.

### 🔹 Workload Impact  
Employees who work **overtime** are significantly more likely to leave.

### 🔹 Age Factor  
Younger employees (26–35) show higher attrition compared to older groups.

### 🔹 Compensation Impact  
Lower monthly income correlates with higher attrition levels.

### 🔹 Work-Life Balance  
Poor work-life balance (ratings 1–2) strongly increases attrition.

---

# 🎯 5. Recommendations

- Improve work-life balance policies (review overtime practices)  
- Increase focus on early-career employees (26–35 age group)  
- Review compensation for low-income roles  
- Provide development opportunities for high-attrition job roles  
- Strengthen engagement programs in Sales department  
- Improve managerial support and job satisfaction efforts  

---

# 🛠 6. Tools & Technologies

### ✔ Python  
- pandas  
- numpy  
- matplotlib  
- seaborn  

### ✔ Tableau  
- KPI Cards  
- Interactive Filters  
- Heatmaps  
- Donut Charts  
- Bar Charts  
- Boxplots  

### ✔ Version Control  
- Git  
- GitHub  

---

# 📁 7. Project Structure

