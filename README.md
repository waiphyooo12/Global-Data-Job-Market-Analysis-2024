# Global-Data-Job-Market-Analysis-2024

An interactive Power BI dashboard designed to analyze global data science job market trends. This project visualizes job availability, salary distributions, and geographical hiring hotspots across various technical roles.

## 📊 Dashboard Preview
<img width="1547" height="866" alt="Screenshot 2026-05-15 at 5 15 39 AM" src="https://github.com/user-attachments/assets/b1d7571c-5398-42ea-bce3-5947a7a450c4" />

## 🎯 Project Overview
This dashboard was created to help aspiring data professionals understand the current hiring landscape. By aggregating global job data, it provides a macro-view of which roles are in high demand and what the associated financial rewards are across different regions.

### **Key Questions Addressed:**
* **Market Volume:** Which roles (Data Engineer, Analyst, Scientist) have the highest number of active openings?
* **Geographic Distribution:** Where are the primary hiring hubs located globally?
* **Compensation:** What is the average yearly and hourly salary for specific data career paths?

## 🚀 Key Features & Functionality
* **Dynamic Filtering:** Users can slice the entire dashboard by Job Title (e.g., Data Analyst, Data Engineer, Machine Learning Engineer) using the interactive filter pane.
* **Global Heatmap:** A geospatial visualization showing job density across North America, Europe, Africa, and Asia.
* **KPI Tracking:** High-level metrics for total Job Count, Average Annual Salary, and Average Hourly Rate.
* **Trend Analysis:** Bar charts comparing the volume of top jobs to identify market leaders.

## 🛠️ Tools & Technologies Used
* **Power BI Desktop:** Used for data modeling and report design.
* **Power Query:** Leveraged for data cleaning, type conversion, and handling currency formatting.
* **DAX (Data Analysis Expressions):** Created custom measures for:
    * `Average of salary_year_avg`
    * `Total Job Count`
* **Geospatial Mapping:** Integrated Microsoft Bing maps for location-based insights.

## 📂 Repository Structure
* `Data-Job-Dashboard.pbix`: The source Power BI file.
* `/Data/`: (Optional) The raw dataset used for the analysis.
* `/Images/`: Screenshots and GIFs of the dashboard for quick viewing.

## 💡 How to Use
1.  Download the `.pbix` file from this repository.
2.  Open it using [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3.  Use the **Filters** pane on the right to interact with the data and see specific role insights.
