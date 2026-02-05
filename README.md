# HR Analytics Dashboard 📊

## 📌 Problem Statement
HR departments often struggle to make sense of complex, raw employee data. The core challenge lies in transforming large volumes of information into an easily digestible and interactive format. Without effective visualization, identifying critical trends—such as high attrition rates, demographic imbalances, or employee satisfaction issues—becomes difficult, limiting data-driven decision-making.

---

## 🎯 Goal / Purpose
The primary goal of this project is to build a **dynamic and interactive HR Analytics Dashboard** that visualizes key workforce metrics.  
The dashboard enables HR managers to:

- Monitor employee attrition and demographics
- Identify workforce trends across gender, education, job roles, and age groups
- Support data-driven retention strategies
- Improve overall workforce planning

---

## 📊 Key Visuals Used

### 🔹 KPI Cards
High-level metrics providing a quick snapshot of the workforce:
- **Total Employees:** 1470  
- **Active Employees:** 1233  
- **Attrition Rate:** 16.12%  
- **Average Age:** 37  

### 🔹 Marital Status (Pie Chart)
Displays employee distribution across:
- Single
- Married
- Divorced  
Helps analyze correlation between marital status and attrition.

### 🔹 Department-wise Attrition (Pie Chart)
Visualizes attrition distribution across:
- HR
- R&D
- Sales  

### 🔹 Attrition by Job Role (Column Chart)
Compares attrition counts across roles such as:
- Laboratory Technicians
- Sales Executives
- Research Scientists
- Managers

### 🔹 Education by Attrition (Horizontal Bar Chart)
Highlights attrition trends based on education level:
- Bachelor’s Degree
- Master’s Degree
- Doctorate
- Diploma

### 🔹 Attrition by Age Group (Column Chart)
Shows attrition segmented by age brackets:
- 18–24
- 25–34
- 35–44
- 45–54
- 55+

### 🔹 Job Satisfaction Rating (Gauge Chart)
Displays the average employee job satisfaction score in a visually intuitive gauge format.

---

## 💡 Business Impact & Insights

- **Identify Attrition Hotspots:**  
  Quickly pinpoints departments and job roles with high turnover for targeted interventions.

- **Demographic Analysis:**  
  Reveals how age and gender impact employee retention, supporting diversity and inclusion initiatives.

- **Education Trends:**  
  Identifies whether employees from specific educational backgrounds are more likely to leave, influencing recruitment strategies.

- **Real-Time Filtering:**  
  Interactive slicers allow instant filtering by Department, Education, and Gender, enabling customized insights for different stakeholders.

---

## 🛠 Techniques & Tools Used

### 🔹 Microsoft Excel
Used as the end-to-end platform for data cleaning, analysis, and visualization.

### 🔹 Pivot Tables
- Aggregated raw HR data
- Created summary tables and frequency distributions
- Served as the backbone for all visualizations

### 🔹 Advanced Excel Formulas
- `IFERROR()` for handling missing or invalid data
- Absolute references (`$`) to preserve formula consistency

### 🔹 Interactive Slicers
- Enabled dynamic filtering across all dashboard visuals
- Allowed quick drill-down into specific segments

### 🔹 Report Connections
- Connected slicers to multiple pivot tables
- Ensured real-time dashboard updates upon filtering

### 🔹 Data Extraction Techniques
- Used precise cell referencing from Pivot Tables
- Enabled creation of advanced visuals like the Gauge Chart

### 🔹 Custom Visual Design
- Gradient fills and custom color palettes
- Removed default gridlines for a clean, professional layout

---

## 📸 Dashboard Preview
> *(Add a screenshot of your dashboard here)*  
> You can upload an image and reference it like this:
```markdown
![HR Analytics Dashboard](dashboard_screenshot.png)

