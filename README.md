# bikesharing

## Project Overview
Create a set of visualizations to show i) the length of time that bikes are checked out for all riders and genders, ii) the number of bike trips for all riders and genders for each hour of each day of the week, and iii) the number of bike trips for each type of user and gender for each day of the week.

## Objectives
1.) Deliverable: Change Trip Duration to a Datetime Format

2.) Deliverable: Create Visualizations uisng Tableau for the Trip Analysis that show:
- How long bikes are checked out for all riders and genders.
- How many trips are taken by the hour for each day of the week, for all riders and genders.
- A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

3.) Deliverable: Create a Story in Tableau

## Analysis
1.) Using Python and Pandas in Jupyter Notebook v6.4.12, specifically with the use of to_datetime() funtion, I have converted the "tripduration" column from an integer to a "Date and Time" format to get the time in hours, minutes, and seconds (00:00:00) and exported the DataFrame as a CSV file to use for the trip analysis in Deliverable 2. See the code here: [NYC_CitiBike_Challenge_starter_code](https://github.com/MSF2141/bikesharing/blob/a4b05fb1059db9886dbfb590f724947eb0e43999/NYC_CitiBike_Challenge_starter_code.ipynb). This approach is more straightforward than changing the format in Tableau.

2.) How long bikes are checked out for all riders and genders:
![Checkout%20times%20for%20users](https://github.com/MSF2141/bikesharing/blob/de00414825b74fc6389c34f3c4e2a1a7907342b1/Checkout%20times%20for%20users.png)
![Checkout%20times%20by%20gender](https://github.com/MSF2141/bikesharing/blob/2c082b935b8ca7b8454ae77fb5e6b7336ee5174a/Checkout%20times%20by%20gender.png)

How many trips are taken by the hour for each day of the week, for all riders and genders:
![Trips%20by%20weekday%20for%20each%20hour](https://github.com/MSF2141/bikesharing/blob/0c0167e9ba98bcb934c97000629b9bfbb24d7011/Trips%20by%20weekday%20for%20each%20hour.png) ![Trips%20by%20gender%20for%20each%20hour%20of%20weekday](https://github.com/MSF2141/bikesharing/blob/eda1d0082519fc4d8b7d303a6ebd8f9cb786d566/Trips%20by%20gender%20for%20each%20hour%20of%20weekday.png)

A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.
![User%20trips%20by%20gender](https://github.com/MSF2141/bikesharing/blob/c477fc6573863fb4439739a5b8897709728485d6/User%20trips%20by%20gender.png)

3.) Visualizations were combined into a story using a Tableau and published here:
[NYCCitibikeanalysis?publish=yes](https://public.tableau.com/app/profile/msf2141/viz/NYCCitibikeanalysis_16753621665680/NYCCitibikeanalysis?publish=yes).


## Additional analysis:
Top ending locations:
![Top%20ending%20locations](https://github.com/MSF2141/bikesharing/blob/feb29a2b2a27ee0fcfa1c34b2b1227c2281e0dfb/Top%20ending%20locations.png)

