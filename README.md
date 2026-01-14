# Student Alcohol Consumption Analysis 🇵🇹

## Project Overview
This project analyzes alcohol consumption patterns among Portuguese secondary school students, focusing on how social, demographic, and academic factors influence alcohol usage and academic performance.  
This is the final project of a Data Analyst training program.

The goal of the project is to transform raw educational data into actionable insights using data analysis and visualization techniques.

---

## Objectives
- Analyze alcohol consumption patterns among students  
- Identify key factors influencing alcohol consumption  
- Explore the relationship between alcohol consumption and academic performance  
- Create clear visualizations and KPIs to support insights  

---

## Dataset
- **Source:** Kaggle – Student Alcohol Consumption  
- **Datasets used:**  
  - `student-mat.csv` (Mathematics)  
  - `student-por.csv` (Portuguese)  
- **Data content:** Academic grades, demographic, family, school, and social data  
- **Final dataset size:** 672 rows (after merging both datasets)  
- **Total variables:** 33  

---

## Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **Power BI:** Data modeling, KPIs, and dashboard visualization  

---

## Data Preparation
The following steps were performed during data preparation:
- Merged the Mathematics and Portuguese datasets into a single dataset  
- Created a **Subject** column to identify the course (Math or Portuguese)  
- Checked for missing values (no null values found)  
- Converted boolean variables (`yes/no`) into numeric format (1/0)  
- Created an **Average Alcohol Consumption** variable:  


- Categorized alcohol consumption into **Low, Medium, and High** levels  

---

## Analysis & Methodology
The analysis focused on:
- Alcohol consumption on weekdays vs weekends  
- Consumption patterns by **gender and age**  
- Relationship between **average alcohol consumption and final grade (G3)**  
- Impact of **social factors** such as `goout` and `freetime`  
- Relationship between alcohol consumption and **school absences**

---

## Key Insights
- Alcohol consumption is **higher on weekends** compared to weekdays  
- **Male students** consistently show higher average alcohol consumption  
- Higher alcohol consumption is associated with **lower academic performance**  
- Students with **more absences** tend to show higher consumption and lower grades  
- **Social activity level (`goout`)** is the factor most strongly associated with alcohol consumption  
- Family-related factors (such as parents’ education) show **less influence** compared to social factors  

---

## Dashboard Preview
The Power BI dashboard was developed locally.  
Due to account limitations, the dashboard cannot be shared publicly; however, a visual preview is provided below.

![Dashboard Preview](dashboard/dashboard_overview.png)

---

## 📽 Presentation
A project presentation summarizing the analysis, methodology, and key insights.

📄 [View Presentation (PDF)](presentation/Student_Alcohol_Consumption_Presentation.pdf)

---

## Repository Structure
├── data/

├── notebook/

│ └── Student_Alcohol_Consumption.ipynb

├── dashboard/

│ └── dashboard_overview.png

└── README.md


## What I Learned
- Data cleaning and dataset integration  
- Feature engineering and KPI creation  
- Exploratory data analysis (EDA)  
- Dashboard development and visual storytelling  
- Translating analytical findings into clear business insights  

---

## Next Steps
- Add more advanced statistical analysis  
- Improve dashboard interactivity  
- Compare results with students from other countries or datasets  

---

## Author
**Luís Machado**  
Junior Data Analyst  

**Tools:** SQL | Excel | Power BI | Python  
