# -Citi-Bike
Challenge 18: New York Citi Bike Program Analysis

Introduction:
Welcome to the README for the New York Citi Bike Program Analysis project. As the lead analyst for the Citi Bike program, my task was to build a set of data reports to provide insights into the program's utilization. This README provides an overview of the project, including the data processing steps, Tableau visualizations, and deployment methods used.

Project Overview:
The New York Citi Bike program is the largest bike-sharing program in the United States. Since 2013, the program has collected data on bike usage, which is made public on the Citi Bike Data webpage. However, the data lacked sophisticated reporting processes. My task was to generate regular reports for city officials to improve and publicize the program.

Data Processing:
To begin, I collected data from 2019-2023, ensuring that the data size remained within Tableau's 1GB limit. I used Python to extract, clean, and preprocess the data. Here's a summary of the steps taken:

Extracted and cleaned CSV files from zip archives, focusing on relevant columns.
Renamed columns for consistency across files and converted user types to uniform categories.
Split the datetime columns into date and time for analysis.
Calculated trip duration and adjusted for trips spanning multiple days.
Saved the cleaned data to a CSV file for further analysis in Tableau.

Tableau Visualizations:
Using Tableau, I created a series of interactive visualizations to answer key questions about the Citi Bike program. Here are some of the visualizations implemented:

Total Trips per day, month: Bar chart showing the total number of trips per day or month.
Ridership Growth (trip/year): Bar chart illustrating the trend of trips over time, with options for yearly comparisons.
COVID-19 Impact in 2020: Line chart comparing trip counts, duration, and distance between annual subscribers and short-term customers to observe the impact of COVID-19 on bike usage.
Proportions of Users: Pie or stacked bar chart depicting the proportions of short-term customers and annual subscribers over time.
Peak Hours: Heatmap displaying the peak hours of bike usage, with trip duration as the y-axis, trip count as the x-axis, and different years as categories.
Top and Bottom Stations: Bar chart showcasing the top and bottom start and end stations based on trip counts.
Average Trip Duration: Bar chart presenting the average trip duration for different user types across different years.
Average Distance and Duration: Visualization of the average distance traveled and duration of trips across different years.

Deployment:
The dashboards and the story are accessible via the provided link:
https://public.tableau.com/views/Challenge18_17150956910420/CItiBikeReport?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link
Conclusion:
This project aims to provide insights into the utilization of the New York Citi Bike program through data analysis and visualization. The generated reports and dashboards offer valuable information for city officials to improve and publicize the program effectively.

Thank you for your interest in the New York Citi Bike Program Analysis project!