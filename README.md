# Dash-application
Airline Distance Group Dashboard
📌 Overview
This is a simple Dash web application that visualizes the proportion of flights based on distance groups (250-mile intervals).
The dashboard uses the Airline Reporting Carrier On-Time Performance dataset and displays the results in a Pie Chart.
Example:
If a flight covers 500 miles, it falls under Distance Group 2 (250 miles + 250 miles).

Dataset Information
Source: Airline Data CSV
Key Columns Used:
Flights → Number of flights
DistanceGroup → Distance interval group (250 miles per group)

Application Layout
The dashboard contains:
Title → Airline Dashboard
Description → Explains what the chart shows
Pie Chart → Displays the percentage of flights by distance group

Technologies Used
Python
Pandas → Data processing
Plotly Express → Chart creation
Dash → Web app framework
