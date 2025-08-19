# Employee & Project Data Analysis – Python Capstone  

## 📌 Overview  
This project focuses on **data wrangling, transformation, and analysis** of employee, project, and seniority datasets using **Python (Pandas, NumPy)**.  
The objective was to apply business rules, clean data, and generate insights such as project costs, employee bonuses, designation changes, and eligibility for project leadership.  

---

## ⚙️ Tech Stack  
- **Python 3**  
- **Pandas, NumPy** for data manipulation  
- **Jupyter Notebook** for execution and documentation  

---

## 🗂️ Project Workflow  
### 1. Data Preparation  
- Read multiple CSV files (`Employee_DataFrame.csv`, `Project_DataFrame.csv`, `Seniority_Level_DataFrame.csv`).  
- Split employee names into *First Name* and *Last Name*.  
- Cleaned and saved structured DataFrames.  

### 2. Data Merging  
- Merged employee, project, and seniority datasets using **left joins**.  
- Ensured employees without seniority or projects were retained.  

### 3. Business Rule Implementation  
- **Bonus Allocation:** 5% bonus for employees on *Finished* projects.  
- **Designation Adjustment:** Demotion for failed projects; promotion for eligible employees based on age and level.  
- **Eligibility Rule:** Employees above level 4 lose project leadership eligibility.  
- **Honorifics:** Added *Mr.* / *Mrs.* prefixes based on gender.  

### 4. Analysis & Insights  
- Calculated **total project cost per employee**.  
- Identified employees in cities containing the letter `"o"`.  
- Implemented **running averages** for project costs.  

---

## 📊 Sample Outputs (for evaluation)  
- Final merged DataFrame with applied business logic.  
- Total project cost per employee.  
- Clean display of large numbers using custom float formatting.  

---

## 🚀 How to Run  
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/python-capstone.git
   cd python-capstone
