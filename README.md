ANT Trucks Fleet Risk Analytics and Management System

Project Overview
This project presents a comprehensive Big Data and Business Intelligence solution designed to optimize fleet management operations for ANT Trucks. The objective is to analyze fleet operational data to improve safety performance, reduce operational risk, enhance decision-making, and support strategic fleet optimization using advanced analytics and machine learning techniques.
The solution integrates distributed data processing, relational data modeling, interactive dashboarding, and predictive modeling using both Python and R.
________________________________________
Objective
The primary objectives of this project are:
•	Analyze fleet safety events and operational metrics
•	Identify high-risk drivers, cities, and truck models
•	Detect seasonality patterns in event occurrences
•	Evaluate correlations between operational parameters
•	Develop predictive models for risk factor estimation
•	Enable data-driven decision-making for fleet optimization
________________________________________
System Workflow
The project follows a structured data pipeline:
1.	Data ingestion and download
2.	File transfer into Hadoop Distributed File System (HDFS)
3.	Table creation and structured loading
4.	Risk factor population using Apache PIG
5.	Data import into Power BI
6.	Dashboard development and visualization
7.	Regression modeling using Python within Power BI
8.	Advanced modeling and validation using R-Studio
This workflow ensures scalable data processing, structured analytics, and executive-level reporting.
________________________________________
Data Modeling
A relational data model was developed in Power BI integrating multiple datasets, including:
•	Driver information
•	Event logs
•	Truck mileage data
•	Fuel consumption data
•	Velocity metrics
•	Risk factor calculations
The model enables multi-dimensional analysis across:
•	City
•	Truck Model
•	Event Type
•	Driver ID
•	Monthly time dimension
________________________________________
Dashboard Overview
The Power BI dashboard provides interactive analytical capabilities with key performance indicators and drill-down insights.
Key Metrics
•	Total Drivers: 99
•	Total Events: 457
•	Total Miles: 64 million
•	Average Risk Factor: 7.13
Core Analytical Views
•	Events Count versus Risk Factor correlation
•	Average Gasoline versus Average Mileage relationship
•	Top Models by Event Counts
•	Model-wise Risk Distribution
•	Geographic Event Distribution
•	Driver Idle Time Analysis
•	Seasonal Trend Analysis
•	Machine Learning Model Performance Comparison
________________________________________
Key Findings
Correlation Analysis
A strong positive relationship was identified between event frequency and risk factor scores. Additionally, fuel consumption demonstrates a measurable relationship with average mileage, supporting operational efficiency optimization.
________________________________________
Geographic Risk Distribution
Santa Rosa recorded the highest number of event occurrences (53) with elevated risk factor values. Lane departure and unsafe following distance were identified as the most common event types.
This indicates the need for targeted city-level safety interventions.
________________________________________
Seasonal Trends
Event occurrences exhibit consistent seasonal patterns, with peak values observed in:
•	January
•	May
•	October
October recorded the highest number of events. These insights support proactive operational planning during high-risk periods.
________________________________________
Truck Model Evaluation
Models recommended based on lower average risk factors:
•	Navistar
•	Volvo
•	Kenworth
•	Western Star
Models requiring operational review due to higher risk factors:
•	Oshkosh
•	Crane
•	Hino
•	Peterbilt
These findings support strategic procurement and fleet optimization decisions.
________________________________________
Driver Idle Time and Risk Factor
Analysis indicates a relationship between higher idle time and increased risk factor scores. Drivers with lower idle times demonstrate improved safety metrics.
This supports policy-level optimization for idle time reduction and safety performance improvement.
________________________________________
Machine Learning Models
Multiple regression models were developed to predict fleet risk factors.
Models Implemented
•	Linear Regression
•	Polynomial Regression (Degree 4)
•	Multi-linear Regression
•	Random Forest
•	Correlation Heatmap
Python Implementation (Power BI Script Visual)
Best performing model:
Random Forest
•	R-squared: 1.00
•	RMSE: 0.00
________________________________________
R-Studio Implementation
Random Forest Model Results:
•	R-squared: 0.881
•	RMSE: 1.833
Variable Importance Ranking
1.	Average Mileage
2.	Total Miles
3.	Gas
4.	Average Velocity
These variables significantly influence risk factor prediction.
________________________________________
Challenges
•	Implementing regression models within Power BI using Python script visuals
•	Identifying correlations among multiple operational parameters
•	Configuring ODBC connectivity between Hadoop and Power BI
•	Ensuring consistency between Python and R model outputs
________________________________________
Conclusion
This project demonstrates how big data analytics and predictive modeling can significantly enhance fleet management by:
•	Enabling targeted safety interventions
•	Supporting data-driven procurement decisions
•	Optimizing driver performance
•	Improving fuel efficiency
•	Identifying seasonal risk patterns
•	Developing predictive risk estimation models
The integrated approach combines data engineering, business intelligence, and machine learning to deliver actionable operational insights.
________________________________________
Technologies Used
•	Hadoop (HDFS)
•	Apache PIG
•	Power BI Desktop
•	Python (Pandas, Scikit-learn, Matplotlib)
•	R-Studio
•	ODBC Connectivity
•	Relational Data Modeling
________________________________________
Repository Contents
•	TruckRiskAnalysis.pdf – Project documentation and analytical summary
•	TruckRiskAnalysisDashboard.pdf – Dashboard visual report
•	TruckRiskDashboard.pbix – Interactive Power BI dashboard file
_________________________________________________________________________________________________________________________________________________________________________________________________________________________
Author:
Nikita Bhole
Data Analyst | BI Developer

