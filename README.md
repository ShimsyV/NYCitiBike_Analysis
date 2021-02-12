# NYCitiBike_Analysis

As the new lead analyst for the New York Citi Bike Program, I am  responsible for overseeing the largest bike sharing program in the United States. In my new role, I will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the Citi Bike Data webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so my first task on the job is to build a set of data reports to provide the answers.

### Data Used

The data I used for the analysis is the 2017 data from January to December from [here](https://s3.amazonaws.com/tripdata/index.html) . (Please note : I chose this data because when trying to use the other years data, I was not getting the months to display in the csv sheet.) Since the data was too big, I was unable to upload it into git hub. 

### Data Limitations & Cleaning

* There seems to be holes in the data for birth year, user type, gender. 

* Some data under trip duration was less than 90 seconds. This was removed since those records would have been due to potential false starts or users trying to re-dock a bike to ensure it's secure. 

* Also removed any record that had over 24hrs of trip duration. This error must have occured due to improper docking. 

* Some of the columns in the sheets were not named the same, so they were renamed. 

* Changed the gender column to note 0:unknown, 1:Male, 2: Female

* Calculated the age from the given birth year

* Removed any data which had age over 100 years. 

## Analysis/ Summary

Click [here](https://public.tableau.com/profile/shimsy#!/vizhome/CitiBike_NY/Story1) for the story board on tableau. 

![img](https://github.com/ShimsyV/NYCitiBike_Analysis/blob/main/images/trip_analysis.JPG)

* Dec-Mar doesnt seem to have as many users as the rest of the months, but not a significant decrease as well. It must be due to the weather.

* 20-40 year olds seem to be the most common users for the bikes. This could be mainly used for commute or chores.

* Average trip duration was about 9 minitues. This is likely due to the use of bikes for short commutes to and from transit hubs like the train, subway or bus stations. 

![img](https://github.com/ShimsyV/NYCitiBike_Analysis/blob/main/images/ageVsGender.JPG)

* There were more male users to female users. 

![img](https://github.com/ShimsyV/NYCitiBike_Analysis/blob/main/images/peek_hours.JPG)

* The busiest peek hours used were 7am-9am and 5pm-6pm. This could be due to the commute for office.

![img](https://github.com/ShimsyV/NYCitiBike_Analysis/blob/main/images/popular_stations.JPG)

* The 10 most popular start and end stations are close to the transit hubs or tourist destinations

![img](https://github.com/ShimsyV/NYCitiBike_Analysis/blob/main/images/top_bike.JPG)

* The most frequently used bikes will need to be regularly insepected, serviced or repaired. 












