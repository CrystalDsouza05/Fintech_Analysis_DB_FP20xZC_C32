# 💳 FinTech Analytics Dashboard - FP20 Analytics Challenge 32 x ZoomCharts Mini Challenge

## 📊 Overview
This dashboard was created for **FP20 Analytics Challenge 32**, which focuses on analyzing a **FinTech Project Management Dataset** from a company developing innovative payment solutions across Europe. The goal is to uncover insights that improve **project delivery efficiency, resource allocation, cost control, and performance monitoring** across multiple fintech products such as digital wallets, tap-to-pay systems, and online payment APIs.

### [Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiZmU0OGE0NzctYWM2NS00YzQ0LWE0YmMtOTYzZWY1NDU4Zjc2IiwidCI6IjQ2NTRiNmYxLTBlNDctNDU3OS1hOGExLTAyZmU5ZDk0M2M3YiIsImMiOjl9)

This project uses **Power BI** to transform complex operational data into an interactive and intuitive analytical experience. It provides clear visibility into planned versus actual performance, task execution, employee productivity, efficiencies, and overall project health.

## 🧰 Tools and Technologies
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Microsoft Excel (Data preparation)
- PowerPoint (Dashboard design planning)

## 📂 Dataset
The dataset includes structured information about:
- Projects across fintech product development  
- Tasks with statuses, timelines, and priorities  
- Employees and Departments  
- Countries and Locations  
- Risk levels, budgets, and hours  
- Planned vs actual metrics  

It represents the complete lifecycle of fintech projects from planning to execution, allowing comprehensive analysis of performance, timelines, and resource utilization.

---

## 📄 Dashboard Structure

# Page 1. Planned vs Actuals: Budget and Hours Overview
**Purpose:**  
To compare planned versus actual performance across budget (EUR) and effort (hours), providing a high-level portfolio view for financial and operational monitoring.

🔍 **Key Visuals**
- **KPIs (8 Cards):** Actual Budget, Planned Budget, Usage Percentage (EUR), Actual Hours, Planned Hours, Variance metrics.  
  **Shows:** Financial and effort alignment across projects.
- **Total Projects by Status (Donut Chart):** In Progress, Completed, Delayed, Not Started.  
  **Shows:** Portfolio workload and bottlenecks.
- **Total Projects by Risk Level (Donut Chart):** Low, Medium, High.  
  **Shows:** Overall risk exposure.
- **EUR Performance by Department (Bar Chart):** Planned vs actual budget, drillable through Departments → Countries → Products → Project ID.  
  **Shows:** Cost efficiency by segment.
- **Planned and Actual Budget Over Time (Area Chart):** Monthly trend.  
  **Shows:** Spending pace and deviations.
- **Hours Performance by Department (Bar Chart):** Planned vs actual hours with drilldown hierarchy.  
  **Shows:** Resource utilization patterns.
- **Planned and Actual Hours Over Time (Area Chart):** Monthly trend.  
  **Shows:** Effort consumption rate and schedule adherence.

---

# Page 2. Project and Tasks Performance
**Purpose:**  
A detailed view for operational monitoring of project-level and task-level performance with hierarchical drilldowns.

🔍 **Key Visuals**
- **Selected Items Indicator:** Displays current filter selections such as Country, Head, Employee, Task, etc.  
  **Shows:** Filter context for better interpretation.
- **Filter Panel (Slicers):** Country, Head of Department, Employee ID, Task Status, Project Status.  
  **Shows:** Quick access to isolate teams, individuals, or statuses.
- **Project and Tasks Snapshot (Table):** Central visual with hierarchical drilldown.  
  **Key Columns:**  
  - Department Name / Project ID  
  - Task Status / Priority  
  - Planned Start and End Date  
  - Duration (Days)  
  - Project Status  
  - Planned Hours  
  - Risk Level  
  - Completion Percentage  
  **Shows:** Detailed task execution and schedule health.

---

# Page 3. Employee Performance
**Purpose:**  
To analyze workforce efficiency, cost, and utilization across departments, tasks, and experience levels.

🔍 **Key Visuals**
- **Performance KPIs (4 Cards):** Total Employees, Average Actual Hours, Employee Efficiency, Average Hourly Rate.  
  **Shows:** Overall workforce performance.
- **Selected Items Indicator:** Highlights filter context (Heads, Departments, Tasks, Employees, Experience Levels, Countries, Cities).
- **Filter Panel:** Head of Department, Task Name and Stage.
- **Employee Performance Table:**  
  Includes Labour Cost, Hourly Rate, Efficiency, Planned Hours, Actual Hours.  
  **Shows:** Granular efficiency and cost insights.
- **Efficiency by Experience Level (Donut Chart):**  
  **Shows:** Productivity comparison between Junior, Mid, and Senior levels.
- **Total Employees by Country (Bar Chart):**  
  **Shows:** Workforce distribution across regions.

---

## 🧮 DAX Measures
A wide range of calculated measures were built, including:

### **Core Metrics**
- Total Projects  
- Total Tasks  
- Total Employees  
- Actual Budget  
- Planned Budget  
- Budget Variance  
- Actual Hours  
- Planned Hours  
- Hours Variance  
- Completion Percentage  

### **Usage Calculations**
- Usage % EUR  
- Usage % Hours  

### **Employee Metrics**
- Employee Actual Hours  
- Employee Planned Hours  
- Hourly Rate  
- Labour Cost  
- Employee Efficiency  
- Average Hourly Rate  

### **HTML-Based Indicators (for dynamic labels)**
- Selected Items Cards  
- Multi-Selection Cards  
- Timeline Error Messages  
- Visual Hierarchy Selection  

All DAX formulas are included in the repository for reference and reuse in similar analytical projects.

---

## ⚙️ Features
- Interactive visuals for drilldown across departments, countries, products, and projects.  
- Dynamic HTML-based cards for clean context indicators.  
- A complete breakdown of project, task, and employee performance.  
- Cross-filtering for deep-dive exploration.  
- Clean dashboard design with organized navigation.

---

## 🚀 How to Use
1. Download the `.pbix` file from this repository.  
2. Open it in **Power BI Desktop**.  
3. Explore the pages and interact with filters, tables, and visuals.  
4. Use drilldowns to analyze performance at project, task, or employee level.

---

## 🏆 Challenge Details
**Organizer:** FP20 Analytics  
**Challenge:** Challenge 32  
**Theme:** FinTech Project Management Analytics  

---

## 📸 Dashboard Images
Page 1:

<img width="1280" height="720" alt="Slide1" src="https://github.com/user-attachments/assets/d6941cb7-1bd6-4ba4-9b4b-40d48e30bc08" /> 

Page 2:  

<img width="1280" height="720" alt="Slide2" src="https://github.com/user-attachments/assets/4add144e-b1d6-4a3a-8499-a792192a8bf1" />

Page 3:  

<img width="1280" height="720" alt="Slide3" src="https://github.com/user-attachments/assets/410ba028-6716-466e-a741-03acbd206c3a" />

---

## ZoomCharts Submission

Changed the Theme and added ZoomCarts Visuals. 

<img width="2008" height="1129" alt="image" src="https://github.com/user-attachments/assets/7508512e-7c3d-4106-bd0c-9268743cd0a1" />

<img width="2008" height="1129" alt="image" src="https://github.com/user-attachments/assets/1ec12cc1-d1bd-4c15-8e54-4107b8393af4" />

<img width="2008" height="1129" alt="image" src="https://github.com/user-attachments/assets/eb65e5fa-8763-4592-95fc-330c84d8f561" />


---

## 🗂️ Data Model
<img width="1280" height="720" alt="Slide4" src="https://github.com/user-attachments/assets/581aebab-85eb-49cb-b395-aa033c2d997a" />

