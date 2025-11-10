# HR Analytics Dashboard (Excel)

## Overview  
An interactive **HR Analytics Dashboard** built in **Microsoft Excel** to analyze and visualize key workforce metrics — including **performance, attendance, overtime, and salary trends** — for data-driven HR decision-making.  

The dashboard transforms raw employee data into actionable insights that help identify **departmental inefficiencies**, **burnout risks**, and **compensation–performance gaps** across the organization.  

---

## Dataset  
The dataset contains **100 employee records** with key HR variables such as:  

- Department  
- Gender  
- Education Level  
- Promotion Status  
- Attendance %  
- Monthly Salary  
- Performance Rating  
- Overtime Hours  
- Age  

Data was cleaned and standardized before visualization to ensure accuracy and consistency.

---

## Methodology  

### 1. Data Cleaning  
Performed in Excel using built-in functions and conditional formatting:  
- Removed duplicates and missing values.  
- Standardized categorical variables (department, gender, education).  
- Converted salary, attendance, and overtime to proper numeric formats.  
- Added calculated fields for KPIs.  

### 2. Data Analysis  
Created **pivot tables** to summarize key metrics:  
- Average Salary by Department  
- Attendance % by Department  
- Overtime vs Performance Rating  
- Department Efficiency Heatmap  
- Gender Distribution  

### 3. Dashboard & Visualization  
Designed a fully interactive dashboard using slicers, KPIs, and multiple chart types:  

#### Pivot Tables  
- Employee Count by Department  
- Department Efficiency (Attendance, Performance, Overtime)  
- Average Attendance by Department  
- Salary–Attendance Correlation  
- Gender Distribution  

#### Pivot Charts  
- Column Chart: Employee Count  
- Heatmap: Department Efficiency  
- Bar Chart: Average Attendance  
- Area Chart: Salary vs Attendance  
- Pie Chart: Gender Diversity  

####  Advanced Charts  
- **Bubble Chart – Department Efficiency Overview**  
  - Avg Salary (X-axis), Avg Performance Rating (Y-axis), Bubble size (Employee Count).  
  - Highlights efficiency gaps where high pay doesn’t correlate with high performance.  
- **Scatter Plot – Overtime vs Performance Rating**  
  - Shows weak correlation (R² ≈ 0.01), indicating overtime doesn’t necessarily improve output.  

---

## Key Insights  

### 1. Pay is not equal to Performance in IT  
- **IT** has the **highest salary (~$81,561)** but **lowest performance rating (2.65)**.  
- Indicates poor ROI on compensation and possible **skill or training inefficiencies**.  

### 2. Marketing Burnout Risk  
- **Marketing** has the **lowest attendance (80.8%)** but **highest overtime (16.9 hrs)**.  
- Suggests uneven workload and risk of burnout — needs workload redistribution.  

### 3. Sales Retention Vulnerability  
- **Sales** shows **best attendance (89%)** but only **mid-range salary (~$71,225)**.  
- High engagement but potential attrition risk due to under-compensation.  

### 4. HR Excellence  
- **HR** has the **largest team (27 employees)** and **high performance (3.04)**.  
- HR’s practices (onboarding, training) can be **scaled** to improve other departments.  

### 5. Overtime Inefficiency  
- Weak correlation (**R² ≈ 0.01**) between overtime and performance.  
- Indicates **more hours ≠ more output** — time to move toward **outcome-based KPIs**.  

---

## Business Impact  
- Identified **low ROI in IT** — opportunity to reallocate budget or improve training.  
- Detected **burnout trends in Marketing**, enabling proactive workload management.  
- Highlighted **Sales retention risks** for high performers.  
- Enabled HR to **benchmark and scale best practices** organization-wide.  

---

## Tools & Techniques  

| Category | Tools / Methods |

| Data Cleaning | Excel Functions (IF, AVERAGEIF, TRIM, CLEAN, VALUE) |
| Data Analysis | Pivot Tables, KPIs, Conditional Formatting |
| Visualization | Pivot Charts, Heatmaps, Bubble & Scatter Charts |
| Design | Interactive Dashboard with Slicers & Dynamic KPIs |

---

## Learnings  
- Strengthened ability to connect HR metrics to business outcomes.  
- Enhanced storytelling through **data visualization** and **insight writing**.  
- Practiced Excel BI techniques (pivot tables, slicers, chart automation).  

---

## How to Use  
1. Download **HR_Analytics_Data.xlsx** from this repository.  
2. Open in Microsoft Excel (desktop version recommended).  
3. Use slicers (Gender, Education, Promotion) to explore interactive insights.  
4. Navigate through the chart sheets for detailed department analysis.  

---

*If you found this project insightful, consider giving it a star!*
