# Global Data Job Market Analysis & Salary Insights
An end-to-end Power BI project visualizing over 350,000 data-related job postings to identify hiring trends, salary benchmarks, and educational requirements across the globe.

## 📊 Dashboard Overview
This project consists of a multi-page interactive report designed to provide actionable insights for data professionals and recruiters.

### **Report 1: Market Landscape & Geography**
* **Total Job Volume:** Tracking 352K+ active job postings.
* **Global Distribution:** Geospatial heatmap identifying hiring hubs in North America, Europe, and Asia.
* **Role Demand:** Comparative analysis of demand for Data Engineers, Analysts, Scientists, and ML Engineers.

### **Report 2: Deep Dive - Salaries & Qualifications**
* **Salary Benchmarking:** Median yearly salary comparisons across major regions (UK, US, France, India).
* **Educational Barriers:** Analysis of "No Degree" mentions across different roles to identify accessibility in the tech market.
* **Seniority Impact:** Visualizing the premium paid for "Senior" vs. standard roles.

### **Report 3: Trend Analytics & Timeline Velocity (2024)**
*Focuses on time-series analysis, job volume fluctuations, and dual-axis compensation tracking.*
* **Hiring Trajectory & Forecasting:** Modeled a linear trend line over monthly 2024 job counts, identifying a macro market contraction toward the end of Q3 with a subsequent Q4 recovery.
* **Composition Breakdown over Time:** Utilized area charts and 100% stacked area/bar structures to monitor how the proportional share of distinct data roles shifted month-to-month.
* **Dual-Axis Pay Structure:** Developed a combination combo chart (Bar + Line) mapping Median Yearly Salary alongside Median Hourly Rates to contrast the baseline compensation dynamics between specific job titles (e.g., Senior Data Scientist vs. Data Analyst).

### **Report 4: Advanced Correlation & Workspace Dynamics**
*Focus: Statistical distributions, outlier tracking, and work-culture splits.*
* **Multi-Variable Scatter Analysis:** Modeled `Median Yearly Salary` against `Median Hourly Salary` across specific job titles, plotting a linear regression trend line to identify roles that pay a premium relative to hourly expectations (e.g., Senior Data Engineer outliers).
* **Workplace Flexibility Ratios:** Contrasted standard vs. donut charts to track the exact portion of job postings explicitly offering Work-From-Home (WFH) options (showing a 42.45% baseline adoption rate).
* **Employment Type Densities:** Leveraged a Treemap visual to map job types, proving that Full-Time contracts represent a dominant 90.37% majority of the global market share.
  
## 🚀 Key Features

* **Multi-Variable Correlation Modeling:** Developed an advanced Scatter Plot tracking the relationship between `Median Yearly Salary` and `Median Hourly Salary` across roles, featuring a linear regression trend line to easily spot high-paying outliers (e.g., Senior Data Engineers).
* **Workplace Flexibility Benchmarking:** Engineered a dual-pie/donut chart composition to monitor remote work trends, proving a clear 42.45% baseline adoption rate for Work-From-Home (WFH) positions.
* **Contract Type Density Mapping:** Utilized a nested Treemap visualization to map global employment structures, visually highlighting that Full-Time roles command a dominant 90.37% majority of the market share.
* **Advanced Time-Series Analytics:** Implemented a monthly historical velocity timeline across 2024 using stacked area charts to watch how individual job composition shares fluctuated alongside macro market trend lines.
* **Interactive Data Exploration:** Integrated dynamic, high-level KPI cards and custom multi-select filter panes, allowing end users to isolate target data roles instantly across multiple dimensions.

## 🛠️ Technical Stack
* **Power BI:** Dashboard design and interactive reporting.
* **Power Query:** Data transformation, handling nulls in degree mentions, and currency normalization.
* **DAX:** Custom measures for median salary calculations and job count aggregations.
* **Dataset:** Analyzed a comprehensive dataset containing 17+ columns of job metadata (Title, Location, Salary, Skills, Degree Requirements).

## 📂 Repository Structure
* `Data_Job_Market_Analysis.pbix`: The full multi-page Power BI workbook.
* `/Images/`: High-resolution screenshots of both report pages.
* `README.md`: Project documentation.

## 💡 How to View
1.  Download the `.pbix` file.
2.  Open using **Power BI Desktop**.
3.  Navigate between the tabs at the bottom to switch between the **Overview** and **Qualification Analysis** pages.
