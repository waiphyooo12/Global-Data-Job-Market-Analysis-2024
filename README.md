# Global Data Job Market Analysis & Salary Insights
An end-to-end Power BI project visualizing over 350,000 data-related job postings to identify hiring trends, salary benchmarks, and educational requirements across the globe.

## 📊 Dashboard Overview
This project consists of a multi-page interactive report designed to provide actionable insights for data professionals and recruiters.
<img width="1547" height="866" alt="Screenshot 2026-05-15 at 5 15 39 AM" src="https://github.com/user-attachments/assets/b1d7571c-5398-42ea-bce3-5947a7a450c4" />
<img width="1547" height="866" alt="Screenshot 2026-05-15 at 9 30 44 AM" src="https://github.com/user-attachments/assets/8d48308d-1053-4209-8e62-478d7a4aedbb" />

### **Page 1: Market Landscape & Geography**
* **Total Job Volume:** Tracking 352K+ active job postings.
* **Global Distribution:** Geospatial heatmap identifying hiring hubs in North America, Europe, and Asia.
* **Role Demand:** Comparative analysis of demand for Data Engineers, Analysts, Scientists, and ML Engineers.

### **Page 2: Deep Dive - Salaries & Qualifications**
* **Salary Benchmarking:** Median yearly salary comparisons across major regions (UK, US, France, India).
* **Educational Barriers:** Analysis of "No Degree" mentions across different roles to identify accessibility in the tech market.
* **Seniority Impact:** Visualizing the premium paid for "Senior" vs. standard roles.

### **Page 3: Trend Analytics & Timeline Velocity (2024)**
*Focuses on time-series analysis, job volume fluctuations, and dual-axis compensation tracking.*
* **Hiring Trajectory & Forecasting:** Modeled a linear trend line over monthly 2024 job counts, identifying a macro market contraction toward the end of Q3 with a subsequent Q4 recovery.
* **Composition Breakdown over Time:** Utilized area charts and 100% stacked area/bar structures to monitor how the proportional share of distinct data roles shifted month-to-month.
* **Dual-Axis Pay Structure:** Developed a combination combo chart (Bar + Line) mapping Median Yearly Salary alongside Median Hourly Rates to contrast the baseline compensation dynamics between specific job titles (e.g., Senior Data Scientist vs. Data Analyst).

## 🚀 Key Features
* **Interactive Slicers:** Full report filtering by job title and location.
* **Dynamic KPIs:** Real-time calculation of average hourly and yearly rates.
* **Data-Driven Visuals:** Utilization of stacked column charts, 100% stacked bar charts, and clustered bar charts to show proportions and rankings.
* **Advanced Time-Series & Trend Analysis:** Implemented monthly historical tracking across 2024 with a built-in linear trend model to forecast market contractions and hiring velocity spikes.
* **Proportional Composition Tracking:** Utilized stacked area charts and 100% stacked visuals to monitor how the market share of specific roles (like Data Analyst vs. Data Engineer) fluctuated dynamically over time.
* **Dual-Axis Pay Structure Evaluation:** Built complex combination charts mapping Median Yearly Salary against Median Hourly Rates simultaneously, allowing stakeholders to immediately contrast flat baseline compensation metrics across different seniority levels.
* **Granular Advanced Filtering:** Integrated complex multi-select filtering layers within the user interface, enabling users to isolate target categories (e.g., exclusively filtering titles containing "data") across all analytical pages dynamically.

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
