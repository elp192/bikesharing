## Overview of the Analysis
In this project [New York Citi (NYC) Bike data (201908-citibike-tripdata.csv.zip)](https://s3.amazonaws.com/tripdata/index.html) is used to determine the bike-sharing business in New York City. We want to analyze this dataset to investigate whether the investment in a similar business for other cities (e.g., Des Mones) is worth it.
For doing this project, the following resources are utilized:
- Programming language: Python (version 3.8.8)- code is written in Jupyter Notebook.
- Dependency: Pandas library (version 1.3.0) 
- Visualization tool: Tableau Public 2021.3

## Results
In this section, the visualizations created by Tableau are demonstrated.

Figure 1 shows time duration that riders check out the bikes. As can be seen, during the first 5 minutes, most bikes (about 140k) are checked out.
<p img align="center" width="100%">
 <img width="500" alt="checkout_times_by_users" src="https://user-images.githubusercontent.com/85843401/134982895-7047ee0c-66ee-4022-bbca-70392568ad65.png">
 <figcaption>Figure 1: Checkout times by users. </figcaption></figure>
</p> 

Figure 2 shows the time duration that bikes are checked out by different gender. As can be seen, for all gender, most bikes are checked out during the first five minutes. Also, most bikes (about 110k) are checked out by males, which is approximately 3.5 times more than bikes that females check out.
<p img align="center" width="100%">
  <img width="500" alt="checkout_times_by_gender" src="https://user-images.githubusercontent.com/85843401/134982974-99eb8611-02c0-4591-ad9e-cf9dfc88b09b.png">
  <figcaption>Figure 2: Checkout times by users and gender. </figcaption></figure>
</p>  

Figure 3 (heatmap) shows bike trips for each hour and weekday. In this figure, the color represents the number of bikes. As can be seen, most riders take the trip at the weekend between 10 AM to 7 PM. From Monday to Friday, the peaking hours for riding are 6 AM to 8 AM and 5 PM to 7 PM.
<p img align="center" width="100%">
  <img width="500" alt="trips_by_weekday_per_hour" src="https://user-images.githubusercontent.com/85843401/134983008-347981a5-ba0e-4073-bbd7-c883dcb1ca1d.png">
  <figcaption>Figure 3: Trips by weekday per hours.</figcaption></figure>
</p> 

Figure 4 (heatmap) shows bike trips for each hour and weekday by gender. The peak times for bike trips are similar to Figure 3 for all gender. Also, most trips are taken by males.
<p img align="center" width="100%">
<img width="500" alt="trips_by_gender_per_hour" src="https://user-images.githubusercontent.com/85843401/134984337-d213d650-ffc8-404b-9d2f-1cd52f13145d.png">
  <figcaption>Figure 4: Trips by gender (Weekday per hour).</figcaption></figure>
</p> 

Figure 5 shows the number of trips by user type, weekday, and gender. It can be seen that male subscribers take most trips during the weekday. The highest number of trips for them are on Thursdays and Fridays. 

 <p img align="center" width="100%">
 <img width="500" alt="user_trips_by_gender_by_weekday" src="https://user-images.githubusercontent.com/85843401/134984304-a14aa8e0-9e3a-4807-b76e-b0f80a82a579.png">
  <figcaption>Figure 5: User trips by gender by weekday. </figcaption></figure>
</p> 

Figure 6 shows the bike stations are in the city center. Also, start and stop locations have similar distributions, meaning riders return the bikes to the locations they check out.
<p img align="center" width="100%">
 <img width="400" alt="top_starting_locations" src="https://user-images.githubusercontent.com/85843401/134984758-1a561183-6cc6-40d6-92e7-bcb351e5b344.png">
 <img width="400" alt="top_ending_location" src="https://user-images.githubusercontent.com/85843401/134984768-e573def7-4194-4a16-a4d9-8344154c5329.png"> 
  <figcaption>Figure 6: Top starting locations and top stoping locations. </figcaption></figure>
</p> 

[Link to Tableau Dashboard](https://public.tableau.com/app/profile/elnaz.pouranbarani/viz/Bikesharingproject/Story1)<br>

## Summary
Summary of the observations are as follows:<br>
- Males' preference in using the bikesharing service is significantly higher than females. So, it is important to investigate why females are less reluctant to use bikesharing services for commuting.<br>
- The bikesharing stations are located in the city center; it is worth to study that whether there is any demand to drop the bikes to other parts of the city or not.<br>

Additional visualizations can be created for future analysis:<br>
- Visualization of the number of riders by gender for each month of the year:  Information about demands for using bikesharing services in different months of the year helps the investors to have a better decision for investing.<br>
- Visualization of the most and less popular starting and ending locations on weekdays and weekends: This information helps the managers to change the hours of operation for each station based on the demands.
