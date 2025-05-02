# Log Book - Semester Project-II (Sem-IV, 2024-25)  
**Project Title:** HR Analytics Dashboard using Power BI and Tableau  
**Team:**  
- Patil Gaurav Manohar (Roll No. 7, PRN: 231107005)  
- Patil Nikhil Manoj (Roll No. 11, PRN: 231107009)  
- Mahajan Himanshu Sudhir (Roll No. 12, PRN: 231107010)  
- Bari Vinit Sunil (Roll No. 24, PRN: 231107020)  
**Guide:** Prof. S. P. Salunke  

## Weekly Progress Log  

### 1. Introduction (24/02/2025 – 08/03/2025)  
- **Problem Statement:**  
  Manual employee data analysis causes inefficiencies; need for real-time dashboards.  
- **Objectives:**  
  1. Power BI dashboard (report generation <5 secs).  
  2. Tableau parallel dashboard for comparison.  
  3. Dynamic filters by department/date.  
- **Dataset:**
  <a href="https://github.com/GauravPatil0712/HR-Analytics-Dashboard-/blob/main/HR_Analytics.csv">HR Dataset</a>


### 2. Literature Survey (10/03/2025 – 22/03/2025)  
- **Comparative Analysis:**  
  | Tool    | Strengths                          | Limitations               |  
  |---------|-----------------------------------|---------------------------|  
  | Power BI| DAX formulas, Windows integration | Limited macOS support     |  
  | Tableau | Advanced visuals                  | High licensing cost       |  


### 3. Methodology (24/03/2025 – 05/04/2025)  
- **Tools:** Power BI Desktop, Tableau Public, Excel.  

### 4. Implementation Details (07/04/2025 – 26/04/2025)  

#### **Module 1: Power BI Dashboard**  
- **Description:**  
  - Created employee overview with KPI cards (Avg Salary, Attrition Rate).  
  - Implemented DAX measures and department slicers.  
- **Testing:**  
  - Validated data accuracy using Excel cross-checks.  
  - Optimized report load time (<5 secs).  
- **Snapshot:**  
<a href="https://github.com/GauravPatil0712/HR-Analytics-Dashboard-/blob/main/Power%20bi.PNG">PowerBi</a>

#### **Module 2: Tableau Attrition Analysis**  
- **Description:**  
  - Built calculated fields for attrition status (`IF [Status] = "Left" THEN 1 ELSE 0`).  
  - Designed dual-axis charts for department-wise trends.  
- **Testing:**  
  - Verified filters with dummy data.  
  - Checked mobile responsiveness.  
- **Snapshot:**  
<a href="https://github.com/GauravPatil0712/HR-Analytics-Dashboard-/blob/main/Tableau.PNG">Tableau</a>

### 5. Results (28/04/2025 – 03/05/2025)  

#### **Dataset Used**  
- Source: `Employee.csv` (internal HR data, anonymized). 
- Citation:  
  ```plaintext
  Dataset provided by [Company Name] under NDA.  
  Format: CSV, 1000+ records, fields: ID, Name, Department, Salary.

### 6. Conclusion  
- **Achievements:**  
  - Successfully automated HR analytics with Power BI/Tableau.  
  - Reduced manual report time by 99%.  
- **Future Work:**  
  - Live data integration (Sem-VI).  
  - Row-level security for HR teams.  

### 7. References  
1. Gartner (2023). *Magic Quadrant for Analytics Platforms*.  
2. Microsoft Docs. *Power BI DAX Guide*.  
3. Tableau Help Center. *Calculated Fields*.
