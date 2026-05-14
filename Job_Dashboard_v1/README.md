# Data Jobs Dashboard with Power BI

<a href="https://app.powerbi.com/view?r=eyJrIjoiN2YzMTdmNTgtMWJmNy00NzlkLTk2ZWEtMGRhZDkzNjFkMjQ1IiwidCI6IjM0NjI3ODc0LWVkM2EtNDk3Yy04ZmI5LTE2Y2U3ZTk3NjRmMSIsImMiOjEwfQ%3D%3D" target="_blank">
  <img src="../Resources/Project_1_a.gif" alt="GIF">
</a>

> <a href="https://app.powerbi.com/view?r=eyJrIjoiN2YzMTdmNTgtMWJmNy00NzlkLTk2ZWEtMGRhZDkzNjFkMjQ1IiwidCI6IjM0NjI3ODc0LWVkM2EtNDk3Yy04ZmI5LTE2Y2U3ZTk3NjRmMSIsImMiOjEwfQ%3D%3D" target="_blank">📊 View the interactive dashboard on the Power BI Service here</a>

## Introduction

This dashboard was built for **Job Seekers, Career Transitioners, and Data Professionals** to solve a common challenge: navigating the scattered and often confusing data job market. By leveraging a real-world dataset of 2024 data science job postings—covering titles, salaries, and global locations—this project provides a centralized, user-friendly interface to easily explore compensation and market trends.

### Dashboard File
You can download the raw project file here to explore the backend: [`Data_Jobs_Dashboard.pbix`](Data_Jobs_Dashboard.pbix).  

## Skills Showcased

This project demonstrates end-to-end data development using key Power BI features. Here is a breakdown of the technical skills applied:

-   **⚙️ Data Transformation (Power Query):** Cleaned, shaped, and prepared raw text data by managing nulls, updating data types, and engineering custom columns.
-   **🧮 Implicit Measures:** Formulated dynamic measures to calculate core KPIs, such as `Median Yearly Salary` and `Job Count`.
-   **📊 Core Visualizations:** Utilized **Column, Bar, Line,** and **Area Charts** to accurately track market trends and compare job volume over time.
-   **🗺️ Geospatial Analysis:** Built interactive **Map Charts** to visualize the global distribution of data roles.
-   **🔢 KPI Indicators & Tables:** Deployed **Cards** for clear top-line metrics and sortable **Tables** for granular, record-level data.
-   **🎨 UI/UX Design:** Designed a clean, accessible layout that uses appropriate chart types to effectively communicate the data's story.
-   **🖱️ Interactive Navigation:** 
    -   **Slicers:** To dynamically filter the entire report by specific Job Titles.
    -   **Buttons & Bookmarks:** To create a smooth, app-like navigation experience.
    -   **Drill-Through:** To connect the high-level summary page directly to contextual, detailed role breakdowns.

---

## Dashboard Overview

*The report is organized into two distinct pages, guiding the user from a broad market summary down to specific role analysis.*

### Page 1: High-Level Market View

![Data Jobs Dashboard Page 1](../images/page_1.png)  

This acts as the mission control for the dataset. It highlights vital KPIs like the total number of job postings, overall median salaries, and the most in-demand job titles, giving users an immediate snapshot of the current market landscape.

### Page 2: Job Title Drill-Through

![Data Jobs Dashboard Page 2](../images/page_2.png)  

This is the targeted deep-dive view. Users can drill through from the main page to isolate specific details for a single job title. It breaks down salary ranges, remote work (WFH) availability, top hiring platforms, and pinpoints exact job locations on a global map.

---

## Conclusion

This project highlights how Power BI can be used to turn messy, real-world job posting data into an actionable career tool. By allowing users to slice, filter, and drill through the market data, it empowers them to make more informed decisions about their professional paths.