# Bikesharing

## Overview of Analysis
### Tableau will assist the data professional and Kate in creating effective visualizations from the Citi Bike data which can be used to help answer important questions for their bike sharing program in Des Moines. The tools data visualization features will help bring the data together and present it in a way that accurately represents the findings. With Tableau, they will be able to create compelling visualizations that reduce personal bias and help their audience understand the insights that the data is revealing.

## Results
### We perform specified code using Python and Pandas functions to convert the "tripduration" column from an integer to a datetime datatype and export the resulting DataFrame as a CSV file. We created a DataFrame using the provided csv file and check the datatypes of each column in the DataFrame. Then we use the to_datetime() function to convert the "tripduration" column to a datetime datatype which allows us to calculate the time in hours, minutes, and seconds. Then we checked the datatypes of the DataFrame to confirm that the "tripduration" column was converted correctly and export the DataFrame as a new CSV file to perform our analysis visualizations.
![D1-1](https://user-images.githubusercontent.com/118647523/227394804-71eb754b-4ddc-4d15-ad19-6d0ed9122993.png)

### We use Tableau to create visualizations that show how long bikes are checked out, how many trips are taken by hour for each day of the week, and what days users are more likely to check out a bike by user type.
![D2-1](https://user-images.githubusercontent.com/118647523/227396076-133f6265-2a79-4647-81f4-f303c071ba5b.png)

### To perform the visualization as seen below we slightly modify checkout times for users worksheet to display a line chart with checkout times split by gender in multiple colors.
![D2-2](https://user-images.githubusercontent.com/118647523/227397832-235b6da5-5e59-45d6-9938-1d332d854663.png)

### The trips by weekday for each hour visualization displays the number of bike trips taken by weekday and hour of the day as a heatmap. To create this visualization the start time column was added to the rows and filtered by hour while the stop time column was added to the columns and filtered by weekdays. The number of records was added to the marks field as a color, creating a heatmap and finally formatting the y-axis to show the 12-hour timeline.
![D2-3](https://user-images.githubusercontent.com/118647523/227399163-73d5ce94-2e39-4bb4-9369-50c96aa0b88e.png)

### To perform the visualization as seen below we slightly modify the trips by weekday for each hour worksheet to display a heat map showcasing trips specified by gender throughout the weekdays along with the hour associated during the time of day.
![D2-4](https://user-images.githubusercontent.com/118647523/227399967-98ee3ff5-2b94-42da-8bb3-50c0a9045813.png)

 


https://public.tableau.com/views/Bikesharing_Challenge_16796003468870/BikeSharingSTORY?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link
 
