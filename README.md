![Screenshot 2025-06-04 130915](https://github.com/user-attachments/assets/aac3da54-cdde-477a-8ece-f9b5b95e33b3)

# Bike Sales Dashboard (Excel Project)

### This project is my hands-on take on a guided Excel dashboard tutorial by Alex The Analyst, where I worked with real-world data to create an interactive Excel dashboard and gained a solid understanding of Excel’s core features.

### The goal was to explore and visualize bike buying trends using basic to intermediate Excel functionalities.

### Project Overview
  1. Dataset: Provided bike buyers data (1001 rows x 13 columns) including demographics, income, commute distance, and bike purchase info.
  2. Objective: Clean the data and build an interactive dashboard to derive business insights.

### 1. Key Steps
    1. Data Cleaning: Removed 26 duplicate rows using the Remove Duplicates tool.
    2. Used Find & Replace to convert shorthand labels (e.g., 'M' to 'Married', 'F' to 'Female').
    3. Formatted Income column as currency for better readability.

### 2. Feature Engineering
      Created a new Age Bracket column using the IF() formula:
      =IF([@Age]>90, "Invalid", IF([@Age]>=60, "Elder", IF([@Age]>=31, "Mid Age", IF([@Age]<=30,"Young"))))
      This helped segment insights by age groups: Young, Mid Age, and Elder.

### 3. Data Analysis & Visuals
     1. Built pivot tables and created interactive visualizations using:
        Bar charts / Column charts
        Line charts
        3D column graphs
        Pie charts

     2. Added slicers for filtering by:
        Marital Status        
        Region       
        Home Ownership     
        Education     
        Number of Cars

### 4. Dashboard Insights
    The dashboard helps visualize:
        1. Income distribution based on gender and bike purchase status
        2. Age group patterns by region
        3. Commute distance vs bike purchase behavior
        4. Relationship between home ownership and bike/car count
        
    I also added my own chart:
         Pie chart showing bike and car ownership among homeowners — to better understand purchasing power in relation to home ownership.

### What I Learned
    This project was a huge confidence booster in my Excel learning journey. Here's what I gained:

### Excel Skills Improved:
    Data cleaning basics
    Pivot table creation
    Slicers for interactivity
    Chart formatting & design
    IF functions and basic logic
    Visual storytelling with dashboards

### Conceptual Takeaways:
    The importance of clean data before analysis.
    How simple features like slicers and pivot tables can turn raw data into powerful stories.
    How to segment data for targeted insights (like age groups and region-wise breakdowns).
    How to think like an analyst: asking the “why” behind patterns in charts.
### Use Case
    Ideal for anyone starting out with Excel or data visualization. 
    This project simulates how businesses can analyze customer data to understand who is buying, where, and why — using nothing more than Excel.

### Final Thoughts
    This was more than just an Excel assignment — it taught me how to analyze, visualize, and communicate data effectively. 
    I’m now more confident in handling real-world datasets, creating dashboards, and drawing actionable insights — all using the fundamentals of Excel.
