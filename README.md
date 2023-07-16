# NY-Citibike-bikesharing with Tableau

##  Project Overview:
The project presents an analysis of New York Citi Bike data, using data visualization tools to present to the investors for exploration of the viability of a bike-sharing business in Des Moines. For this analysis, I utilized Pandas to change the "tripduration" column from an integer to a datetime datatype. Using the converted datatype to create a set of visualizations to demonstrate the following:
• Illustrate the length of time that bikes are checked out for all riders and genders

• Illustrate the number of bike trips for all riders and genders for each hour of each day of the week

• Illustrate the number of bike trips for each type of user and gender for each day of the week.

• Finally, the new visualizations are added to the two you created in this module for your final presentation and analysis to pitch to investors.


##  Resources

Data Source: Citi Bike Data, 201908-citibike-tripdata.csv.zip
Software: Python, Anaconda Navigator, Conda, Jupyter Notebook, Tableau Public, Visual Studio Code, CSV Files

##   Results from Tableau Analysis

###  New York Citi Bike data visualizations for August 2019
Change "Trip Duration" to a "Datetime Format" Using Python and Pandas functions, the "Trip Duration" column was converted from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After the convertion of the "tripduration" column to a datetime dataytpe, the DataFrame was exported as a CSV file to use for the trip analysis.

![Image 1 ](https://github.com/jhansolo33/NY-Citibike-bikesharing/assets/119264589/b0cf41b4-74cf-4ac2-a78d-75035984d88e)


####  Length of time that bikes are checked out for all riders

![length of time that bikes are checked out for all riders](https://github.com/jhansolo33/NY-Citibike-bikesharing/assets/119264589/0b0de12a-8661-4c88-93d3-684eb2b1c657)




####  Create the Checkout Times for Users
•Bikes are checked out for ~ 4 to 6 hours.

![image 2](https://github.com/jhansolo33/NY-Citibike-bikesharing/assets/119264589/2344802e-cbf3-4f82-b4d3-53db27843c92)


####  Create the Checkout Times by Gender
• Male users take approximately 3 times more rides than the female users.

![image 4 ](https://github.com/jhansolo33/NY-Citibike-bikesharing/assets/119264589/e8ff754b-2e1e-4e23-8ba7-a1d24cc4ea9a)


####  Trips by Weekday for Each Hour

![image 5](https://github.com/jhansolo33/NY-Citibike-bikesharing/assets/119264589/9a4887e6-38c5-4ef3-bfb3-20e721fbf4f2)


####  Trips by Gender (Weekday per Hour)

• Most weekday rides are around 7:00 AM to 9 AM and 5:00 PM to 7:00 PM.

• Weekend rides are highest from 10:00 AM to 7:00 PM.

• Those rides are mostly taken by male users.

![image 6 ](https://github.com/jhansolo33/NY-Citibike-bikesharing/assets/119264589/47e96e7e-6b7a-4f8e-8379-49802a6527b4)


####  User Trips by Gender by Weekday

![image 7](https://github.com/jhansolo33/NY-Citibike-bikesharing/assets/119264589/97de9a47-6c55-46f8-bdae-a90788c45d15)



####  Top Starting Locations

• There were over 2.3 million rides for the month of August 2019.

• 81% of the users were subscribers. 65% of the users were confirmed males and 25% were confirmed females.

• There is a wide range of the age of the users. Younger users tend to use the service for longer rides.

• Top ride starting locations are in the most touristic and busy areas, as we see here in Manhattan.

![image 8](https://github.com/jhansolo33/NY-Citibike-bikesharing/assets/119264589/0cbc90cc-d3ba-4838-b73c-843f0dbe7bdc)



####  August Peak Hours
• Highest activity hours are from 5:00 PM to 7:00 PM and require the most resources mobilized.

• The activity from 2:00 AM to 5:00 AM is low so this would be the window for bike maintenance.

![image 11](https://github.com/jhansolo33/NY-Citibike-bikesharing/assets/119264589/0a37fdf5-0974-4361-860d-25b6080c0ae1)




####  Bike Utilization

![image 10 ](https://github.com/jhansolo33/NY-Citibike-bikesharing/assets/119264589/85479795-d87f-4acc-921e-d08b74dbb233)



####  Summary
• The data shows high activity of the bike sharing service in New York during the month of August 2019.

• The far majority of the rides were in the very busy Manhattan Island, taken by male users during morning and evening rush hours. This implies that Citi Bike services are used as an alternative to public transportation by commuting workers.

Additional analysis would be beneficial by :

• comparing data for different months to determine trends across the year,

• including weather data to find the correlation between the weather and the rides.
