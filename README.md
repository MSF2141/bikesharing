# bikesharing

## Project Overview
Create a set of visualizations to:
•	Show the length of time that bikes are checked out for all riders and genders
•	Show the number of bike trips for all riders and genders for each hour of each day of the week
•	Show the number of bike trips for each type of user and gender for each day of the week
Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

## Objectives
This new assignment consists of two technical analysis deliverables and a written report to present your results. You will submit the following:
•	Deliverable 1: Change Trip Duration to a Datetime Format
•	Deliverable 2: Create Visualizations uisng Tableau for the Trip Analysis that show:
- How long bikes are checked out for all riders and genders.
- How many trips are taken by the hour for each day of the week, for all riders and genders.
- A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.
•	Deliverable 3: Create a Story and Report for the Final Presentation

## Analysis
- 1.)
Using Python and Pandas in Jupiter Notebook, specifically with the use of to_datetime() funtion, I have converted the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00) and exported the DataFrame as a CSV file to use for the trip analysis in Deliverable 2. See the code here: [NYC_CitiBike_Challenge_starter_code](https://github.com/MSF2141/bikesharing/blob/a4b05fb1059db9886dbfb590f724947eb0e43999/NYC_CitiBike_Challenge_starter_code.ipynb).
