# Data Analysis and Visualization Project

## Introduction
This project involves analyzing hotel reservation data and visualizing key performance indicators (KPIs) using Google BigQuery and Looker Studio. The assignment is divided into two parts:

1. Data Visualization in Looker Studio: Create a dashboard to display KPIs and perform analysis based on the hotel reservation data for February 2024.
2. Data Extraction and Transformation using Python: Extract and format data from a JSON file, then upload it to BigQuery.
Tasks

## Assignment 1: Data Studio & BigQuery
Objective: Create a data visualization dashboard in Looker Studio that connects to BigQuery. The dashboard should answer the following questions:

- What is the Occupancy rate, Average Daily Rate (ADR), and Revenue Per Available Room (RevPAR) for February 2024?
- Which Travel Agency and Country should be focused on for marketing, segmented by hotel?
- What is the anticipated date for reservations creation for each day in February 2024?

## Steps:

1. Data Preparation:

- Import and clean data from Google Sheets containing reservation details for February 2024.
- Define the total number of rooms available for each hotel.

2. Write SQL Queries in BigQuery:

- Calculate the number of rooms sold per day using arrival and departure dates.
- Compute KPIs: Occupancy Rate, ADR, and RevPAR.
- Analyze reservations by Travel Agency and Country to identify marketing focus areas.
- Predict reservation anticipation using the difference between arrival and creation dates.
- Dashboard Creation:

3. Build a dashboard in Looker Studio to visualize the KPIs, marketing insights, and reservation anticipation.
Add filters for date and hotel.

## Dashboard Output:

- KPIs: Occupancy Rate, ADR, RevPAR.
- Marketing Insights: Reservations by Travel Agency and Country.
- Reservation Anticipation: Predicted reservation creation dates.

## Assignment 2: Python
Objective: Extract data from a JSON file and create a properly formatted table in BigQuery.

## Steps:

1. Data Extraction:

- Use Python to parse the JSON file and extract relevant columns.
- Convert the extracted data into a structured DataFrame.

2. Table Creation in BigQuery:

- Create a new table in BigQuery with the following columns: Created Date, Completion Date, Demanded by, Category, Priority, Status, Name of the ticket, Description, Project ID

3. Code Implementation:

- Write Python code to parse the JSON file, clean the data, and upload it to BigQuery.
- Data Parsing and Transformation: Python scripts to parse JSON and clean data.
- BigQuery Table Creation: SQL commands to create and upload data to BigQuery.

## Conclusion
This project demonstrates the ability to analyze and visualize complex datasets using modern tools such as BigQuery and Looker Studio. It also showcases proficiency in data extraction and transformation using Python. The final deliverables include a fully functional dashboard and a well-organized BigQuery table, ready for in-depth analysis and reporting.

