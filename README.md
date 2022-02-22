# PortfolioProject3
To store files related to the Company Financials dashboard project in Tableau

Project Idea :  Came from my wife who is a regional Finance leader who loves to do all her automation in Excel. She was working on a tool to gather regional and local sales revenue and profit data for monthly review. I thought there must be an easier and more effeicient way to do this in SQL or Tableau.

Resources used:  YouTube tutorial from https://www.youtube.com/playlist?list=PLeo1K3hjS3usDI9XeUgjNZs6VnE0meBrL

Tools used : EXCEL, SQL, Tableau, Python, Visual Studio Code

Data Source : In the form of a MySQL dump file was provided in the YouTube link.

Analysis Steps:
  ASK  - Problem description and AIMS grid (Purpose, Stakeholders, End Result, Success Criteria)
  PREPARE - Data collection and organization (Data source cloned from Github - https://github.com/codebasics/DataAnalysisProjects)
          - Used a Python script to convert the MYSQL dump file into a csv file and then imported into MS SQL. This was a bit challenging.
          - Python code is also stored in this Github repository
          - 5 Tables cleaned up
  PROCESS - Data cleaning and model in Tableau
          - Star Schema created in Tableau with relationships between the tables
  ANALYZE - Create some Calculated fields in Tableau and various views to gain insights
  SHARE   - Pulled together all the views into a couple of interactive Tableau dashboards
          - Company Revenue, Sales and Profits by month and year
          - Company wide vs regional sales numbers
          - Top 5 Customers and Products
          - Revenue vs Profit margins
          - Retail vs Online sales
          
          
Final Dashboard stored here : 
https://prod-useast-a.online.tableau.com/#/site/menonstableauprojects/views/2022_02_21_Revenue_Sales_Dashboard_ver1/Dashboard_Revenue_Profit?:iid=2
