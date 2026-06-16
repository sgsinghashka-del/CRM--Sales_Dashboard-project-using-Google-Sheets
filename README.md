## 🔗 Live Dashboard (Google Sheets)
👉 View the live CRM dashboard here:  https://docs.google.com/spreadsheets/d/148SLImRvdIjrBIzUM_VLuuZS-PvLJ_ZDuJYlYlzAGcI/edit?usp=sharing


🎯 **Project Overview & Objectives**
This project was developed entirely within Google Sheets following the structured Maven Analytics data challenge. The core focus was to explore a corporate sales pipeline dataset, perform data quality assurance (QA), and transform raw transactional records into an interactive executive dashboard to track quarterly performance and sales agent metrics.

🛠️ **Step-by-Step Implementation**

🔹 Objective 1: Data Preparation & Quality Assurance (ETL)
Data Exploration & QA: Profiled the sales_pipeline.csv dataset to analyze total won opportunities, identify products sold, determine the analysis time horizon, and check for missing or anomalous values.
Data Joining & Modeling: Opened sales_teams.csv and used advanced lookup formulas (XLOOKUP / VLOOKUP) to dynamically map and bring each sales agent's respective Manager and Regional Office into the main sales pipeline table.

🔹 Objective 2: Data Exploration with Pivot Tables
Quarterly Trend Analysis: Structured dynamic Pivot Tables to isolate and calculate total opportunities won by quarter.
Conversion Metrics: Built a specialized view showing the precise breakdown percentage of Won vs. Lost opportunities on a quarterly basis.
Performance Benchmarking: Generated a ranking pivot table tracking quarterly wins per sales agent, sorted in descending order to spotlight top performers.
Dynamic Formatting: Restructured the layout to place quarters as dynamic columns, sorted chronologically with the most recent quarter appearing first for stakeholder convenience.

🔹 **Objective 3: Dynamic Dashboard & UI Design**
KPI Scorecards: Implemented a Scorecard chart visual displaying opportunities won in the most recent quarter (2017-Q4) compared directly against the previous quarter (2017-Q3) to show growth metrics.
Funnel Visualization: Visualized the win/loss distribution percentage for the latest quarter using a clean Pie Chart.
Leaderboard Performance: Deployed a horizontal Bar Chart visualizing opportunities won by individual sales agents during 2017-Q4.
Interactive Controls (Slicers): Embedded interactive Slicers for Regional Office and Manager, turning a static spreadsheet into a fully dynamic reporting tool.


🧰 **Tools & Formulas Used**
Platform: Google Sheets
Advanced Formulas: XLOOKUP, Logical Operators (IF/IFS), Aggregate Functions (SUMIFS, COUNTIFS).
Features: Dynamic Pivot Tables, Scorecards, Custom Bar & Pie Charts, Dashboard Slicers, and Data Sorting/Filtering.
