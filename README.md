# CWRUBootcamp_M14_11172022_Bike_Sharing_Hoynacke
## Project Overview 
Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

Show the length of time that bikes are checked out for all riders and genders
Show the number of bike trips for all riders and genders for each hour of each day of the week
Show the number of bike trips for each type of user and gender for each day of the week.
Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

## Project Requirements 
What You're Creating
This new assignment consists of two technical analysis deliverables and a written report to present your results. You will submit the following:

Deliverable 1: Change Trip Duration to a Datetime Format
Deliverable 2: Create Visualizations for the Trip Analysis
Deliverable 3: Create a Story and Report for the Final Presentation

## Deliverable 1 
### The data in the "tripduration" column is converted to a datetime datatype and has the correct time format 

Below are details and screen shots of part 1 of deliverable 1. 

<img width="1102" alt="Screen Shot 2022-11-17 at 2 05 40 PM" src="https://user-images.githubusercontent.com/111096384/202536208-f8f9f897-f930-4eea-b2c8-04c0cad0f94a.png">

<img width="1093" alt="Screen Shot 2022-11-17 at 2 07 54 PM" src="https://user-images.githubusercontent.com/111096384/202536330-ce2ca7dd-fb95-4b09-934e-8df96e770c5b.png">

<img width="1099" alt="Screen Shot 2022-11-17 at 2 08 24 PM" src="https://user-images.githubusercontent.com/111096384/202536438-186f70da-632c-4450-adc3-e90946814439.png">

<img width="1087" alt="Screen Shot 2022-11-17 at 2 08 54 PM" src="https://user-images.githubusercontent.com/111096384/202536593-b4594824-9734-4a15-8b85-aec82e954e97.png">

### The DataFrame is exported as a new file without the index column 

Exporting to a new file was completed by using the following line of code: 

<img width="1082" alt="Screen Shot 2022-11-17 at 2 10 14 PM" src="https://user-images.githubusercontent.com/111096384/202536828-09b38b1d-731e-4817-813f-7cd406db0afa.png">

## Deliverable 2 
### Below you will find the requirements for Deliverable 2 and screen shots of the final results built in Tableau: 

### Check Out by Duration for Users
There is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour 

<img width="1380" alt="Screen Shot 2022-11-17 at 2 55 31 PM" src="https://user-images.githubusercontent.com/111096384/202546215-d793f369-fdd5-4afe-977f-2c5900d3edb9.png">

### Check Out by Duration for each Gender 
There is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender 

<img width="1166" alt="Screen Shot 2022-11-17 at 3 09 43 PM" src="https://user-images.githubusercontent.com/111096384/202549130-40cdf125-3a2a-47e2-999e-d40a0ed45326.png">

### Trips by Weekday for Each Hour 
A heatmap is created showing the number of bike trips for each hour of each day of the week 

<img width="1379" alt="Screen Shot 2022-11-17 at 3 17 35 PM" src="https://user-images.githubusercontent.com/111096384/202551063-0c1a5366-c88e-428d-9489-6f9ef6c695d8.png">

### Trips by Gender (Weekday per Hour)
A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender

<img width="999" alt="Screen Shot 2022-11-17 at 3 24 57 PM" src="https://user-images.githubusercontent.com/111096384/202552461-639dfd14-9ad5-4077-840d-52bdab16ef8f.png">

### User Trips by Gender by Weekday 
A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender

<img width="1171" alt="Screen Shot 2022-11-17 at 3 27 45 PM" src="https://user-images.githubusercontent.com/111096384/202552966-21664d57-9b19-4451-95f2-107e9fa663eb.png">

## Deliverable 3 - Analysis

### Link to final dashboard can be found here:
https://public.tableau.com/app/profile/alexa.hoynacke2376/viz/Bike_Sharing_16687177743180/Story1?publish=yes

### Summary of Results and Suggestions:

The city of Des Moines is the capital and most populous city in Iowa. This metropolitan area has an estimated population of 212,000, and has lots of business and e-commerce engagement. This is why it would be a great idea to move forward with the next phase. In addition to the visualizations already delivered two additional visualizations I would like to see for future analysis are:

Business Partners - Local Businesses: Analyze the businesses along the routes to see if we could offer discounted rates to their employees. 

Female Engagement - We need to look further into female engagement so visualizations that show promotions tailored to women or look into offer specials that would increase revenue per hour by Gender (focusing on women) and weekday. 


