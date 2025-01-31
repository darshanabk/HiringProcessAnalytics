# Hiring Process Analytics | [View Live DashBoard ](https://public.tableau.com/app/profile/darshana.b8538/viz/HiringProcessAnalytics_17383579109830/HiringProcessAnalytics)  

## Project Overview

This project focuses on analyzing the hiring process to gain insights into the company's hiring trends, salary distribution, and employee composition by gender, department, and position. The analysis involved data cleaning, handling missing values, addressing outliers, and visualizing key metrics using **Microsoft Excel and Tableau**.

## Approach

1. **Data Cleaning**  
   - Replaced missing values in the `Event_Name` and `Post Name` columns to maintain data integrity.

2. **Outlier Handling**  
   - Adjusted extreme outliers in the `Offered Salary` column using median values to avoid skewed results.

3. **Key Metrics Analysis**  
   - Analyzed hiring trends based on gender, department, and position.  
   - Explored salary distribution by creating salary intervals and comparing salary ranges for hired and rejected candidates.

4. **KPI Analysis & Visualization**  
   - Used **Tableau** for dynamic KPI dashboards.  
   - Created **Excel-based** pivot tables and charts for additional insights.

## Tech Stack Used

- **Microsoft Excel (2022)**
  - Data cleaning and preparation
  - Creating pivot tables and charts
  - Performing statistical analysis and handling outliers
  - Calculating averages, medians, and salary class intervals

- **Tableau**
  - Built an interactive **KPI Dashboard** with the following metrics:
    - **Total Hires**  
    - **Total Rejections & Rejection Rate**  
    - **Hiring Rate by Department**  
    - **Top 5 Posts with the Highest Hires**  
    - **Gender Distribution of Hired Candidates**  
    - **Salary Distribution**  
    - **Monthly Hires Trend**  
    - **Average Salary Offered**  
    - **Total Salary Offered**  

## Data Summary

- Missing values in `Event_Name` and `Post Name` were replaced for data completeness.
- Outliers in `Offered Salary` were adjusted using median values to ensure accurate insights.

## Key Insights

1. **Gender Distribution**  
   - 57% of candidates who attended interviews were male, 37% female, and 6% did not reveal their gender.  
   - 55% of hired candidates were male, 40% female, and 6% unspecified.

2. **Salary Trends**  
   - Most candidates attended interviews for salary ranges between **₹40,001 - ₹50,000**.  
   - Outliers in high salary ranges (₹200,000 - ₹400,000) were adjusted using median values.

3. **Department and Position Insights**  
   - The **Operations Department** had the highest number of hires, while **Human Resources** had the least.  
   - The most frequently hired position was **C9**, while the least hired was **N6**.  

4. **Salary Distribution**  
   - Created class intervals to analyze salary distribution across departments and positions.

## Visualizations

- **Excel:**  
  - Pivot tables summarizing hiring and salary trends.  
- **Tableau Dashboards:**  
  - **Hiring KPI Dashboard** (Total Hires, Rejection Rate, Hiring by Department)  
  - **Salary Insights Dashboard** (Salary Distribution, Average Salary, Top 5 Posts)  
  - **Gender & Monthly Hiring Trends** (Hires by Gender, Monthly Hiring Trends)  

## Results

This analysis provides a comprehensive understanding of the company's hiring process. The cleaned and structured data allows for better decision-making in future hiring strategies, ensuring gender balance and optimizing salary distributions.

## Resources

- **Project Dashboard:** [Tableau Public Link](https://public.tableau.com/app/profile/darshana.b8538/viz/HiringProcessAnalytics_17383579109830/HiringProcessAnalytics)
- **Cleaned Dataset:**[RawData](https://github.com/darshanabk/HiringProcessAnalytics/blob/main/DataCleaningAndAnalysis/Cleaned%20Dataset.xlsx)
- **Excel Workbook:** [ExcelAnalysis](https://github.com/darshanabk/HiringProcessAnalytics/blob/main/DataCleaningAndAnalysis/Raw%20Data%20-%20Data%20Cleaning%20and%20Excel%20Analysis%20HPA.xlsx)
