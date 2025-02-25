# 🏢 HR Analytics Dashboard - Tableau Project

## 📌 Introduction
This **HR Analytics Dashboard** is designed for HR managers to analyze **workforce demographics, salary trends, and employee records**. The dashboard provides both a **summary view** for high-level insights and a **detailed employee record view** for in-depth analysis.

## 🎯 Dashboard Objectives
- **Analyze workforce distribution** by department, gender, age, and education.
- **Track hiring and termination trends** over time.
- **Compare salaries** based on department, education, and gender.
- **Explore employee performance ratings** and their correlation with educational background.
- **Interactive filters** for in-depth analysis.

## 📊 Summary View
### **1️⃣ Overview**
✔ **Total Hired, Active, and Terminated Employees**  
✔ **Hiring & Termination Trends (Yearly Breakdown)**  
✔ **Employees by Department & Job Titles**  
✔ **HQ vs. Branches Employee Distribution**  
✔ **Employee Distribution by State & City**  

### **2️⃣ Workforce Demographics**
✔ **Gender Ratio** – Analyze the male-to-female employee ratio.  
✔ **Age Distribution** – Breakdown of employees across different age groups.  
✔ **Education Levels** – Percentage of employees by highest education achieved.  
✔ **Education vs. Performance** – Relationship between education and performance ratings.  

### **3️⃣ Salary & Income Analysis**
✔ **Salary Comparison by Education & Gender** – Identify pay gaps or trends.  
✔ **Age vs. Salary** – Track salary growth across different age groups in each department.  

## 🗂 Employee Records View
✔ **List of all employees** with Name, Department, Job Title, Gender, Age, Education, Salary, and Performance Rating.  
✔ **Filters available** for department, gender, education, and location.  

---

## 📂 Dataset Details
The dataset was **generated using Python (Faker library)** to simulate **real-world HR data**. It includes:
- **Demographics:** Gender, Age, Education
- **Job Details:** Department, Job Title, Hire & Termination Dates
- **Salary Information:** Base Salary, Adjusted Salary (based on education & age)
- **Performance Ratings**
- **Overtime Status**

🔗 **Dataset:** `HumanResources.csv`  
🔗 **Python Script for Data Generation:** `generate_HR_data.py`  

---

## 🖌️ Mockups & Dashboard Design (Draw.io)
Before building the dashboard in **Tableau**, **mockups** were created using **Draw.io ([diagrams.net](https://app.diagrams.net/))**. These mockups helped in **structuring the layout, aligning KPIs, and designing an intuitive user experience**.

### **📝 Why Use Draw.io for Mockups?**
✔ **Plan dashboard layout** before implementation.  
✔ **Ensure clear data visualization** by pre-defining key components.  
✔ **Organize sections effectively (Summary, Demographics, Salary, Employee Records).**  
✔ **Improve dashboard usability** by iterating designs before final development.  

### **📌 Mockup Preview**
Below is an early wireframe of the **HR Dashboard**, designed in **Draw.io** before being built in Tableau.

![HR Dashboard Mockup](mockup_hr_dashboard.png)

📂 **Mockup File** – The editable Draw.io file is included in the repository under `mockups/HR_Dashboard_Mockup.drawio` for further modifications.

---

## 📊 Dashboard Preview
### **Summary View**
![HR Dashboard Overview](dashboard_overview.png)

### **Employee Records View**
![HR Dashboard Details](dashboard_records.png)

---

## 🎨 Design & Interactivity
- **Year Selection** – Analyze different time periods.
- **Drill-down Filters** – Filter by department, gender, education, location.
- **Dynamic Visualizations** – Interactive bar charts and graphs.

---

## 🛠️ Technologies Used
- **Tableau Public** – Data visualization and dashboard creation  
- **Python (Faker, Pandas, NumPy)** – Synthetic data generation  
- **Excel/CSV** – Data storage  
- **GitHub** – Project hosting  
- **Draw.io (Diagrams.net)** – Mockup & dashboard wireframe design  

---

## 🚀 How to Use This Project
### **1️⃣ Access the Dashboard**
🔗 **[View the Live Tableau Dashboard](https://public.tableau.com/your-dashboard-link)**  
