# HR-analytics-Insights-Dashboard

An interactive **Power BI** dashboard that analyses employee attrition and workforce demographics. It helps HR teams see who is leaving, from which departments and roles, and how factors like salary, age, gender, experience and job satisfaction relate to attrition.

---

## 📖 Project Overview
Employee attrition is costly for any organisation. This project turns raw HR data into a single-page, interactive dashboard that lets stakeholders explore attrition patterns, filter by department, and compare the workforce across several dimensions.

## 🎯 Objectives
- Track headline workforce metrics (headcount, attrition count and rate).
- Identify which **departments, job roles, salary slabs, age groups and genders** show the most attrition.
- Understand the link between **job satisfaction** and attrition.
- Analyse how attrition changes with **total years of experience**.

## 🖼️ Dashboard Preview
> Add a screenshot of your dashboard here.

```
![HR Analytics Dashboard](images/dashboard.png)
```

## 📈 KPIs
The dashboard has six KPI cards at the top:

| KPI | Description |
|---|---|
| **Total Employees** | Total number of employee records (by `EmpID`) |
| **Active Employees** | Employees currently active (`EmployeeCount`) |
| **Attrition Count** | Number of employees who left (`AttritionCount`) |
| **Attrition Rate %** | Percentage of employees who left |
| **Avg Age** | Average employee age |
| **Avg Experience** | Average years at the company (`YearsatCompany`) |

## 📊 Visualizations

| Visual | Chart Type | What It Shows |
|---|---|---|
| Attrition by Department | Donut chart | Share of attrition across departments |
| Attrition by Salary Slab | Clustered bar chart | Employee count per salary slab, split by attrition (Yes/No) |
| Attrition by Job Role & Satisfaction | Matrix (pivot table) | Attrition count by job role against job satisfaction levels |
| Age Group Distribution | Column chart | Employee count by age group |
| Attrition by Gender | Pie chart | Attrition split between genders |
| Attrition Trend by Experience | Area chart | Attrition count across total years of experience |
| Department-wise Employee Count | Funnel chart | Employee count per department |
| Department Slicer | Slicer | Filters the whole dashboard by department |

## 🗂️ Data Fields Used
Source table: `HR_Analytics-4`

- `EmpID`, `Age`, `AgeGroup`, `Gender`
- `Department`, `JobRole`
- `SalarySlab`, `JobSatisfaction`
- `YearsatCompany`, `TotalExperience(Years)`
- `Attrition`, `AttritionCount`, `EmployeeCount`, `Attration Rate %`

> **Dataset source:** _Add the source here (e.g. Kaggle / IBM HR Analytics dataset / company data)._

## 🛠️ Tools & Technologies
- **Power BI Desktop** – data modelling, DAX and visualisation
- **Power Query** – data cleaning and transformation _(update if used)_
- **DAX** – calculated columns and measures (e.g. Attrition Rate %)

## 🚀 How to Use
1. Clone this repository:

```
2. Open `HR_analytics_by_Anu.pbix` in **Power BI Desktop** (free to download from Microsoft).
3. Use the **Department slicer** and click on any chart to cross-filter the other visuals.
4. Hover over visuals for tooltips and exact values.

## 💡 Key Insights
> Replace these with your own findings once you've reviewed the dashboard.

- Which department has the highest attrition?
- Which salary slab loses the most employees?
- Does low job satisfaction line up with higher attrition in certain roles?
- At what experience level does attrition peak?
- Is attrition higher in a particular age group or gender?

## 📁 Repository Structure
```
├── HR_analytics_by_Anu.pbix   # Power BI report file
├── images/
│   └── dashboard.png          # Dashboard screenshot
└── README.md                  # Project documentation
``
