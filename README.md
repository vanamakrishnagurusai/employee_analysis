# 🧑‍💼 Employee Performance Analysis with Python

This project performs data cleaning, feature engineering, analysis, and visualization on an employee dataset using **Pandas**, **Matplotlib**, and **Seaborn**. The final results are exported to an Excel file with multiple sheets and saved as visual charts.

---

## 📂 Dataset

The dataset (`employee_performance.csv`) includes the following columns:

- `EmployeeID`
- `Name`
- `Gender`
- `Department`
- `Salary`
- `JoinDate`
- `PerformanceRating`

---

## ✅ Tasks Performed

### 1. Data Cleaning
- Convert `JoinDate` to datetime format (`dd-mm-yyyy`)
- Ensure `Salary` and `PerformanceRating` are numeric
- Check and handle missing values

### 2. Feature Engineering
- Create a new column: `Tenure` = `2025 - Year(JoinDate)`
- Create a new column: `SalaryCategory`
  - Salary < 50,000 → `Low`
  - 50,000 ≤ Salary ≤ 90,000 → `Medium`
  - Salary > 90,000 → `High`

### 3. Aggregated Analysis
- **Average Salary by Department**
- **Gender Count by Department**
- **Average Performance Rating by Department**
- **List of Low Performers** (Performance Rating ≤ 2)

### 4. Visualization
- 📊 Bar Chart: Average Salary by Department
- 📊 Bar Chart: Average Performance Rating by Department
- 🥧 Pie Chart: Gender Distribution
- 🥧 Pie Chart: Salary Category Distribution

---

## 📦 Output

- `employee_analysis.xlsx`: Cleaned and aggregated data in multiple Excel sheets
- `avg_salary_by_dept.png`: Bar chart
- `avg_rating_by_dept.png`: Bar chart
- `gender_distribution.png`: Pie chart
- `salary_category_distribution.png`: Pie chart

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/employee-performance-analysis.git
   cd employee-performance-analysis
